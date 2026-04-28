<script>
	import favicon from '$lib/assets/favicon.svg';
	import { Header, Navigation, Footer, } from '$lib';
	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>

<Header />

<header>
	<Navigation />
</header>

<Footer />

{@render children()}

<style>


	/* piedra-latin-400-normal 
@font-face {
  font-family: 'Piedra';
  font-style: normal;
  font-display: swap;
  font-weight: 400;
  src: url($lib/font/piedra-latin-400-normal.ttf), format(true)
} */
</style>
