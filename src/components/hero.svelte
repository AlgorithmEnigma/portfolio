<script>
	import Nav from '../components/nav.svelte';
</script>

<section class="_first-section" id="home">
	<img src="../static/images/nasa-moon.jpg" alt="" />
	<Nav />
	<div class="_hero-container">
		<h1 class="text-9xl font-black uppercase">Hi, I'm Jordan</h1>
		<p class="text-5xl capitalize mt-6">Aspiring.. No Inspiring UX/UI Engineer</p>
	</div>
</section>

<style>
	._first-section {
		display: flex;
		background-color: #3a3a3a;
		z-index: -2;
		opacity: 0.99;
	}

	._first-section img {
		position: absolute;
		z-index: -1;
		height: 100vh;
		width: 90vw;
		opacity: 0.2;
		left: 12vw;
	}

	._hero-container {
		margin: 15rem;
		color: white;
	}
</style>
