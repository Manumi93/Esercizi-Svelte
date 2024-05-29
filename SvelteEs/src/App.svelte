<script>
	
	import Header from './components/header.svelte';
	import Main from './components/main.svelte';
	import Footer from './components/footer.svelte';

	// export let name;
	
	// import Home from "./components/Home.svelte";
	
</script>

<main>
	<!-- <h1>Hello {name}!</h1> -->
	<Header></Header>
	<Main></Main>
	<!-- <Home></Home> -->
	<Footer></Footer>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>