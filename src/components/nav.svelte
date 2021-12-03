<svelte:head>
	<script src="https://kit.fontawesome.com/08b656cb6e.js" crossorigin="anonymous"></script>
</svelte:head>

<nav class="">
	<div class="_container text-white p-8">
		<div class="_top-nav">
			<a class="_title text-4xl m-1 mb-8 font-bold uppercase" href="#home">J0rdan <br /> L0well</a>

			<div class="_pages">
				<a class="text-3xl font-light m-6 text-white text-opacity-60 uppercase" href="#about"
					>Ab0ut</a
				>
				<a class="text-3xl m-6 font-light text-white text-opacity-60 uppercase" href="#projects"
					>Pr0jects</a
				>
				<a class="text-3xl m-6 font-light text-white text-opacity-60 uppercase" href="#contact"
					>C0ntact</a
				>
			</div>
		</div>
		<div class="_bottom_nav text-white">
			<a class="uppercase m-12 text-4xl font-bold" href="/blog">_Bl0g_</a>
			<div class="_socials ">
				<!-- TODO: Add links -->
				<a class="text-3xl m-1" href="/"><span class="fab fa-twitter" /></a>
				<a class="text-3xl m-1" href="/"><span class="fab fa-github" /></a>
				<a class="text-3xl m-1" href="/"><span class="fab fa-linkedin" /></a>
				<a class="text-3xl m-1" href="/"><span class="fab fa-dribbble" /></a>
				<a class="text-3xl m-1" href="/"><span class="fab fa-behance" /></a>
			</div>
		</div>
	</div>
</nav>

<style>
	._container {
		background-color: #3a3a3a;
		width: 12vw;
		height: 100vh;

		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: space-between;
	}

	._top-nav {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: space-between;
	}

	._pages {
		display: flex;
		flex-direction: column;
		align-items: flex-start;
		justify-content: space-between;
	}

	._pages a {
		letter-spacing: 0.2rem;
	}

	._bottom_nav {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: space-between;
	}

	._title {
		letter-spacing: 0.5rem;
		line-height: 3rem;
	}
</style>
