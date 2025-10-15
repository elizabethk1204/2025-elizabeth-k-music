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
	<a href="/start">Start Practice Session</a>
	<a href="/graph">Data and Graph</a>
	<a href="enlargedOnePast">Single Past Session</a>
	<a href="inSession">In Session</a>
	<a href="endSession">End Session</a>
</nav>

{@render children?.()}

<style>
	nav {
		display: flex;
		flex-direction: row;
		flex-wrap: wrap;
		height: 10vh;
		width: 100vw;
		background-color: lightcoral;
		margin: 0px;
		padding: 0px;

		object-position: bottom;
		background-attachment: fixed;
		background-position: bottom;

		align-items: center;
		justify-items: center;
		justify-content: left;
	}

	nav a {
		font-size: 18px;
		font-weight: bold;
		color: lightpink;
		text-align: left;
		align-items: right;
		justify-items: right;
		margin: 5px;
	}
</style>
