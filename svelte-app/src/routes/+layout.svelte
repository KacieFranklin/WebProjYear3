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
