<script lang="ts">
	let value = $state('');
	let textarea: HTMLTextAreaElement | null = null;

	function resize() {
		if (!textarea) return;
		textarea.style.height = 'auto';
		textarea.style.height = textarea.scrollHeight + 'px';
	}
</script>

<textarea bind:this={textarea} bind:value oninput={resize} rows="1" class="input"></textarea>

<style>
	.input {
		display: block;
		width: 100%;
		max-width: 480px;

		resize: none;
		overflow: hidden;
		box-sizing: border-box;

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
	}
</style>
