<script>
	import Header from '../components/Header/index.svelte';
	import Footer from '../components/Footer/index.svelte';
	import '../app.css';
</script>

<Header />

<main>
	<slot />
</main>

<Footer />

<style>
	main {
		flex: 1;
		display: flex;
		flex-direction: column;
		padding: 1rem;
		width: 100%;
		max-width: 1024px;
		margin: 0 auto;
		margin-top: 55px;
		box-sizing: border-box;
	}

	@media (min-width: 480px) {
		main {
			margin-top: 70px;
		}
	}
</style>
