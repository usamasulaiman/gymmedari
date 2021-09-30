<script>
	import Header from './Components/Header.svelte'
	import SearchBar from './Components/SearchBar.svelte'
	import QuestionsList from './Components/QuestionsList.svelte'
</script>

<main>
	<Header />
	<SearchBar />
	<QuestionsList />
</main>

<style>
	:global(body) {
		background: floralwhite;
	}
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	@media (min-width: 640px) {
		main {
			max-width: 1200px;
		}
	}
</style>