<script lang="ts">

// получаем props через runes
const { src } = $props<{ src: string }>();

let audio: HTMLAudioElement | null = null;
let isPlaying = $state(false);

function toggle() {
  if (!audio) return;

  if (isPlaying) {
    audio.pause();
    isPlaying = false;
  } else {
    audio.play();
    isPlaying = true;
  }
}

function onEnded() {
  isPlaying = false;
}

</script>

<button class="player" class:playing={isPlaying} onclick={toggle}>
  <span class="icon">{#if isPlaying}❚❚{:else}▶{/if}</span>
</button>

<audio bind:this={audio} src={src} onended={onEnded}></audio>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,600;1,300;1,400&display=swap');

  .player {
    width: 25px;
    height: 25px;
    background: #0f0f0f;
    border: 1px solid #2a2a2a;
    border-top-color: #444;
    color: #b0a898;
    font-size: 14px;
    cursor: pointer;
    transition: background 0.25s, color 0.25s, border-color 0.25s;
  }

  /* Угловые орнаменты — как у .card */
  .player::before,
  .player::after {
    content: '';
    position: absolute;
    width: 8px;
    height: 8px;
    border-color: #666;
    border-style: solid;
    pointer-events: none;
  }
  .player::before {
    top: -1px; left: -1px;
    border-width: 1px 0 0 1px;
  }
  .player::after {
    top: -1px; right: -1px;
    border-width: 1px 1px 0 0;
  }

  .player:hover:not(.playing) {
    background: #161616;
    color: #e8e0d4;
    border-color: #555;
  }

  .player.playing {
    background: #0f0f0f;
    color: #c8c0a0;
    border-color: #555;
  }

  .icon {
    font-size: 13px;
    line-height: 1;
    user-select: none;
  }
</style>