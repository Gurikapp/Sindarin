<script>
    let value = $state('');
</script>

<div class="wrapper">
    <span class="mirror">{value}</span>
    <input bind:value class="input" size="1" />
</div>

<style>
    .wrapper {
        display: inline-grid;
        min-width: 20px;
    }

    .mirror {
        grid-area: 1 / 1;
        visibility: hidden;
        white-space: pre;

        font-family: 'Cormorant Garamond', serif;
        font-size: 1.5rem;
        font-weight: 300;
        font-style: italic;
        letter-spacing: 0.06em;
    }

    .input {
        grid-area: 1 / 1;

        font-family: 'Cormorant Garamond', serif;
        font-size: 1.5rem;
        font-weight: 300;
        font-style: italic;
        letter-spacing: 0.06em;

        color: #f0ece4;
        background: #0a0a0a;

        border: 1px solid #2a2a2a;
        border-top: 1px solid #444;

        outline: none;
        text-align: center;
    }
</style>