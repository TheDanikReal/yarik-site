<svelte:head>
	<title>Home</title>
	<meta name="description" content="Yarik AI home" />
</svelte:head>

<section>
	<h1>
		<span class="welcome">
			Welcome to <strong> Yarik AI </strong> <br />
		</span>

		A free and open source AI powered Discord bot<br />
	</h1>
</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;
	}

	h1 {
		font-family: 'Fira Mono', monospace;
		width: 100%;
	}

	.welcome {
		position: relative;
		width: 100%;
		height: 0;
		padding: 0 0 calc(100% * 495 / 2048) 0;
		font-size: clamp(2.5rem, 10vw, 8rem);
		align-content: center;
	}
</style>
