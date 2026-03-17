<script>
import { words } from "$lib/words";

let wordsQueue = [];
let currentWord = $state("");
let correctAnswer = $state("");
let options = $state([]);

let correctSelected = $state(null);
let wrongSelected = $state(null);

function shuffle(arr) {
  return [...arr].sort(() => Math.random() - 0.5);
}

function generateOptions(word) {
  const other = words
    .filter(w => w.word !== word.word)
    .map(w => w.translation);

  const wrong = shuffle(other).slice(0, 3);

  return shuffle([word.translation, ...wrong]);
}

function resetQueue() {
  wordsQueue = shuffle([...words]);
}

function nextWord() {
  correctSelected = null;
  wrongSelected = null;

  if (wordsQueue.length === 0) {
    resetQueue();
  }

  const word = wordsQueue.shift();

  currentWord = word.word;
  correctAnswer = word.translation;
  options = generateOptions(word);
}

function choose(option) {
  if (option === correctAnswer) {
    correctSelected = option;
    setTimeout(() => {
      nextWord();
    }, 2000);
  } else {
    wrongSelected = option;
    setTimeout(() => {
      wrongSelected = null;
    }, 800);
  }
}

resetQueue();
nextWord();
</script>

<div class="container">

  <div class="ornament top">✦</div>

  <div class="card">
    <h1 class="word">{currentWord}</h1>
    <div class="divider"><span></span><span class="diamond">◆</span><span></span></div>
  </div>

  <div class="options">
    {#each options as option (option)}
    <button
      onclick={() => choose(option)}
      class:correct={correctSelected === option}
      class:wrong={wrongSelected === option}
    >
      {option}
    </button>
    {/each}
  </div>

  <div class="ornament bottom">✦</div>

</div>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,600;1,300;1,400&family=Cormorant+SC:wght@300;400&display=swap');

  :global(body) {
    background-color: #0a0a0a;
    margin: 0;
    min-height: 100vh;
  }

  .container {
    max-width: 480px;
    margin: 0 auto;
    padding: 60px 40px;
    text-align: center;
    display: flex;
    flex-direction: column;
    align-items: center;
    min-height: 100vh;
    justify-content: center;
    gap: 0;
  }

  .ornament {
    color: #555;
    font-size: 10px;
    letter-spacing: 8px;
    opacity: 0.6;
    user-select: none;
  }

  .ornament.top { margin-bottom: 32px; }
  .ornament.bottom { margin-top: 32px; }

  .card {
    width: 100%;
    border: 1px solid #2a2a2a;
    border-top: 1px solid #444;
    padding: 36px 40px 32px;
    background: #0f0f0f;
    position: relative;
  }

  /* Угловые орнаменты карточки */
  .card::before,
  .card::after {
    content: '';
    position: absolute;
    width: 12px;
    height: 12px;
    border-color: #666;
    border-style: solid;
  }
  .card::before {
    top: -1px; left: -1px;
    border-width: 1px 0 0 1px;
  }
  .card::after {
    top: -1px; right: -1px;
    border-width: 1px 1px 0 0;
  }

  .word {
    font-family: 'Cormorant Garamond', serif;
    font-size: clamp(2.2rem, 6vw, 3.2rem);
    font-weight: 300;
    font-style: italic;
    color: #f0ece4;
    margin: 0 0 24px;
    letter-spacing: 0.04em;
    line-height: 1.1;
  }

  .divider {
    display: flex;
    align-items: center;
    gap: 10px;
    opacity: 0.3;
  }

  .divider span:not(.diamond) {
    flex: 1;
    height: 1px;
    background: #666;
  }

  .diamond {
    font-size: 6px;
    color: #888;
  }

  .options {
    width: 100%;
    display: flex;
    flex-direction: column;
    gap: 0;
    border: 1px solid #2a2a2a;
    border-top: none;
  }

  button {
    display: block;
    width: 100%;
    padding: 16px 24px;
    font-family: 'Cormorant Garamond', serif;
    font-size: 1.9rem;
    font-weight: 400;
    letter-spacing: 0.06em;
    border: none;
    border-top: 1px solid #1e1e1e;
    background: #0a0a0a;
    color: #b0a898;
    cursor: pointer;
    transition: background 0.25s, color 0.25s, letter-spacing 0.25s;
    position: relative;
  }

  button:hover:not(.correct):not(.wrong) {
    background: #161616;
    color: #e8e0d4;
    letter-spacing: 0.1em;
  }

  button:active {
    transform: none;
  }

  .correct {
    background: #0f0f0f !important;
    color: #c8c0a0 !important;
    letter-spacing: 0.12em;
  }

  .correct::after {
    content: '✓';
    position: absolute;
    right: 20px;
    top: 50%;
    transform: translateY(-50%);
    font-size: 0.9rem;
    opacity: 0.7;
  }

  .wrong {
    background: #110808 !important;
    color: #7a4040 !important;
    letter-spacing: 0.02em;
  }
</style>