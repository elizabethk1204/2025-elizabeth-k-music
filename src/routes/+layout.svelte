<script>
	import '../app.css';
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>

<nav>
	<a href="/">Home</a>
	<a href="/welcome">Welcome</a>
	<a href="/past">Past Sessions</a>
</nav>
{@render children?.()}

<style>
	nav {
		background: gray;
		color: white;
		padding: 10px;
	}
	nav a {
		color: white;
	}
</style>
