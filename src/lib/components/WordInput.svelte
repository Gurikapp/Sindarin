<script lang="ts">
    let el: HTMLSpanElement | null = $state(null);
    let isEmpty = $state(true);

    function onInput() {
        isEmpty = (el?.innerText.trim() ?? '') === '';
    }

    function onKeydown(e: KeyboardEvent) {
        if (e.key === 'Enter') e.preventDefault();
    }
</script>

<span
    bind:this={el}
    contenteditable="true"
    role="textbox"
    tabindex="0"
    aria-label="введите слово"
    class="word-input"
    class:empty={isEmpty}
    oninput={onInput}
    onkeydown={onKeydown}
></span>

<style>
    .word-input {
        display: inline;
        min-width: 60px;
        padding: 0 4px;

        font-family: 'Cormorant Garamond', serif;
        font-size: 1.5rem;
        font-weight: 300;
        font-style: italic;
        letter-spacing: 0.06em;
        color: #f0ece4;

        border-bottom: 1px solid #444;
        border-top: 1px solid #2a2a2a;
        outline: none;

        /* Позволяет переносить вместе с текстом */
        word-break: break-word;
        white-space: normal;
    }

    /* Placeholder через псевдоэлемент */
    .word-input.empty::before {
        content: '___';
        color: #444;
        pointer-events: none;
    }

    .word-input:focus {
        border-bottom-color: #888;
        background: rgba(255, 255, 255, 0.03);
    }
</style>