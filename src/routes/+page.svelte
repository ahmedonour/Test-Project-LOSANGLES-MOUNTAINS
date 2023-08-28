<script>
	import Herosection from '../Component/herosection.svelte';
	import Nav from '../Component/nav.svelte';
</script>

<svelte:head>
	<title>Los Angles Mountains</title>
	<link
		href="https://api.fontshare.com/v2/css?f[]=general-sans@200,500,300,600,400,700&display=swap"
		rel="stylesheet"
	/>
</svelte:head>
<main>
	<Nav />
	<Herosection />
</main>

<style>
	main {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
	}
</style>
