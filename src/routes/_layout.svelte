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
		background-color: #E8A93F;
	}
</style>

<Nav {segment}/>

<main>
	<slot></slot>
</main>