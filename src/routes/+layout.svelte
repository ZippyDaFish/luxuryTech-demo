<script lang="ts">
	import './layout.css';
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();
</script>

<svelte:head><link rel="icon" href={favicon} /></svelte:head>

<header class="absolute top-0 right-0 w-full p-8 flex justify-end items-center">

  <!-- Right boxes container -->
  <div class="relative flex group w-48 h-12">

    <!-- Box 1 -->
    <div class="w-12 h-12 rounded-lg absolute top-0 right-0
                bg-[linear-gradient(0deg,var(--color-accent)_0%,var(--color-accent)_60%,var(--color-accent-light)_100%)]
                shadow-md
                transition-all duration-500 transform
                group-hover:-translate-x-0"></div>

    <!-- Box 2 -->
    <div class="w-12 h-12 rounded-lg absolute top-0 right-0
                bg-[linear-gradient(0deg,var(--color-accent)_0%,var(--color-accent)_60%,var(--color-accent-light)_100%)]
                shadow-md
                transition-all duration-500 transform
                group-hover:-translate-x-14"></div>

    <!-- Box 3 -->
    <div class="w-12 h-12 rounded-lg absolute top-0 right-0
                bg-[linear-gradient(0deg,var(--color-accent)_0%,var(--color-accent)_60%,var(--color-accent-light)_100%)]
                shadow-md
                transition-all duration-500 transform
                group-hover:-translate-x-28"></div>

    <!-- Box 4 -->
    <div class="w-12 h-12 rounded-lg absolute top-0 right-0
                bg-[linear-gradient(0deg,var(--color-accent)_0%,var(--color-accent)_60%,var(--color-accent-light)_100%)]
                shadow-md
                transition-all duration-500 transform
                group-hover:-translate-x-42"></div>

  </div>
</header>

{@render children()}