<script lang="ts">
	import './layout.css';
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();
</script>

<svelte:head><link rel="icon" href={favicon} /></svelte:head>

<header class="absolute top-0 left-0 w-full p-8 flex justify-between">
	<div>
		<div class="w-12 h-12 border rounded-lg"></div>
	</div>
	<div class="flex gap-8">
		<div class="w-12 h-12 border rounded-lg"></div>
		<div class="w-12 h-12 border rounded-lg"></div>
		<div class="w-12 h-12 border rounded-lg"></div>
		<div class="w-12 h-12 border rounded-lg"></div>
	</div>
</header>

{@render children()}

<footer class="w-full min-h-[15vh] bg-[var(--color-surface)]">

</footer>