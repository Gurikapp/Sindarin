<script>
	import AudioPlayer from '$lib/components/AudioPlayer.svelte';
	import LessonTextField from '$lib/components/LessonTextField.svelte';
</script>

<div class="container">
	<div class="ornament">✦</div>
	<!-- <AudioPlayer src="/audio/Edhellen_Urok1_Upr1.mp3" />
	<LessonTextField></LessonTextField> -->
	<a href="/urok1" class="urokN textM">Урок 1</a>
	<a href="/urok2" class="urokN textM">Урок 2</a>
	<a href="/urok3" class="urokN textM">Урок 3</a>
	<a href="/urok4" class="urokN textM">Урок 4</a>
	<a href="/urok5" class="urokN textM">Урок 5</a>
	<a href="/urok6" class="urokN textM">Урок 6</a>
	<a href="/urok7" class="urokN textM">Урок 7</a>
	<a href="/urok8" class="urokN textM">Урок 8</a>
	<div class="ornament">✦</div>
</div>

<style lang="scss">
	@import '$lib/styles/uchebnikMain.scss';
</style>
