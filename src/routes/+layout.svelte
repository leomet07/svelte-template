<script lang="ts">
	import "../globals.css";
	import Navbar from "../components/Navbar.svelte";
</script>

<svelte:head>
	<title>My SvelteKit App</title>
</svelte:head>

<div class="app">
	<Navbar />
	<slot />
</div>
