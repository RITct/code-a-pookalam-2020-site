<script>
	import Nav from '../components/Nav.svelte';

	export let segment;
</script>

<style>
	main {
		max-width: 75em;
		background-color: white;
		padding: 2em;
		margin: 0 auto;
		box-sizing: border-box;
		background-color: inherit;
	}
	@media only screen and (max-width: 720px) {
		main{
			max-width: unset;
			width: 100%;
			padding:0;
		}
	}
</style>

<Nav {segment}/>

<main>
	<slot></slot>
</main>