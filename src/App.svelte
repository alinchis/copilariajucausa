<script>
	// export let name;
</script>

<main>
	<div class="bg-cover bg-center background-image">
		<div class="under-construction-banner">
			<img src="../images/copilaria-jucausa_logo-10-7_adj.png" alt="Our Logo" class="logo">
			<h1>Under Construction</h1>
		</div>
	</div>

	
</main>

<style>
	main {
		height: 100vh;
		width: 100%;
		text-align: center;
		max-width: 240px;
		padding: 0;
		margin: 0 auto;
	}

	h1 {
		color: #ffffff;
		font-size: 4em;
		font-weight: 300;
		padding: 0 0 0.5em 0;
		margin: 0 auto;
	}

	.background-image {
		display: flex;
		flex-direction: column;
		justify-content: center;
		background-image: url('/images/background-image.jpg');
		background-size: cover;
		background-position: center;
		height: 100vh;
	}

	.under-construction-banner {
		width: 100%;
		background-color: rgba(0, 0, 0, 0.7); /* Semi-transparent black */
		color: white;
		text-align: center;
		z-index: 1000; /* Ensure it's above other elements */
	}


	@media (min-width: 320px) and (orientation: portrait) {
		main {
			max-width: none;
		}

		h1 {
			font-size: 2em;
		}

		.under-construction-banner .logo {
			max-width: 15em;
			margin: 1em;
		}
	}

	@media (min-width: 320px) and (orientation: landscape) {
		main {
			max-width: none;
		}

		h1 {
			font-size: 2em;
		}

		.under-construction-banner {
			height: 100vh;
		}

		.under-construction-banner .logo {
			max-width: 10em;
			margin: 0.5em;
		}
	}

	@media (min-width: 480px) and (orientation: portrait) {
		main {
			max-width: none;
		}

		h1 {
			font-size: 3em;
		}

		.under-construction-banner .logo {
			max-width: 15em;
			margin: 1em;
		}
	}

	@media (min-width: 480px) and (orientation: landscape) {
		main {
			max-width: none;
		}

		h1 {
			font-size: 3em;
		}

		.background-image {
			display: flex;
			flex-direction: row;
			height: 100vh;
		}

		.under-construction-banner {
			height: 100hv;
			padding: 0;
			margin: 0;
		}

		.under-construction-banner .logo {
			max-width: 10em;
			margin: 2em;
		}
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}

		h1 {
			font-size: 6vh;
			padding: 0 0 0.5em 0;
		}

		.background-image {
			display: flex;
			flex-direction: column;
			height: 100vh;
		}

		.under-construction-banner {
			height: 60vh;
		}

		.under-construction-banner .logo {
			max-width: 30vh;
			margin: 10vh 5vh 0 5vh;
		}
	}

	@media (min-width: 1240px) {
		main {
			max-width: none;
		}

		h1 {
			font-size: 10vh;
			padding: 0 0 0.5em 0;
		}

		.background-image {
			display: flex;
			flex-direction: column;
			height: 100vh;
		}

		.under-construction-banner {
			height: 60vh;
		}

		.under-construction-banner .logo {
			max-width: 30vh;
			margin: 10vh 5vh 0 5vh;
		}
	}
</style>