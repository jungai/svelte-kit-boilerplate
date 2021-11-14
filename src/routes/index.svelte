<script context="module" lang="ts">
	export const prerender = true;
	// export const ssr = false; // -> make it into `spa`
	// export const hydrate = false; // -> dont required js
</script>

<script lang="ts">
	console.log('hello index page');
</script>

<svelte:head>
	<title>Index Page</title>
</svelte:head>

<div class="grid place-content-center h-screen">
	<p class="text-[tomato] capitalize text-2xl">hello svelte kit</p>
</div>
