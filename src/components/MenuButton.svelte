<script>
let open = $state(false);
</script>

<div class="menu">

  <button class="menu-button" onclick={() => open = !open} aria-label="Меню">
    <span class="star">✦</span>
  </button>

  {#if open}
  <div class="dropdown">
    <a href="/" onclick={() => open = false}>Тренировка</a>
    <a href="/phonetics" onclick={() => open = false}>Фонетика</a>
  </div>
  {/if}

</div>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Cormorant+SC:wght@300;400&display=swap');

  .menu {
    position: fixed;
    top: 20px;
    right: 20px;
    z-index: 100;
  }

  @keyframes shimmer {
    0%, 100% { opacity: 0.35; transform: scale(1) rotate(0deg); }
    50%       { opacity: 0.9;  transform: scale(1.15) rotate(45deg); }
  }

  .menu-button {
    width: 36px;
    height: 36px;
    background: none;
    border: none;
    cursor: pointer;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 0;
  }

  .star {
    font-size: 25px;
    color: #c8c0a0;
    animation: shimmer 3.5s ease-in-out infinite;
    display: block;
    line-height: 1;
    transition: color 0.25s;
  }

  .menu-button:hover .star {
    color: #f0ece4;
    animation-duration: 1s;
  }

  .dropdown {
    position: absolute;
    top: calc(100% + 8px);
    right: 0;
    background: #0a0a0a;
    border: 1px solid #2a2a2a;
    border-top: 1px solid #3a3a3a;
    min-width: 140px;
    display: flex;
    flex-direction: column;
  }

  a {
    font-family: 'Cormorant SC', serif;
    font-size: 19px;
    letter-spacing: 3px;
    font-weight: 300;
    padding: 14px 20px;
    text-decoration: none;
    color: #8a8888;
    transition: color 0.2s, background 0.2s, letter-spacing 0.2s;
    border-bottom: 1px solid #1a1a1a;
  }

  a:last-child {
    border-bottom: none;
  }

  a:hover {
    background: #111;
    color: #c8c0a0;
    letter-spacing: 4px;
  }
</style>