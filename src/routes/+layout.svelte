<script>
	import Header from './Header.svelte';
	import "../app.css";
	import { goto } from '$app/navigation';
 	import { session } from '$app/stores';
</script>

<div class="app">
	<main>
		<slot />

	<footer>
		<p>visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to learn SvelteKit</p>
	</footer>
</div>

