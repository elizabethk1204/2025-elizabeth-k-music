<script>
	import { onMount } from 'svelte';

	let sessions = $state(undefined);

	onMount(() => {
		let s = localStorage.getItem('sessions');

		if (s !== null) {
		}
	});
</script>

<div class="background">
	<div class="menu">
		<div class="ICON"></div>
		<div class="subtext">welcome</div>
	</div>

	<br />
	<br />
	<div class="title">past sessions</div>
	<div class="session">
		<div class="date">
			Date
			<div class="variable">XX:XX</div>
		</div>
		<div class="goal">
			Goal
			<div class="variable">goal</div>
		</div>
		<div class="time">
			Time
			<div class="variable">XX:XX</div>
		</div>
		<div class="note">
			Notes
			<div class="variable">notes</div>
		</div>
		<div class="recordings">
			Recordings
			<div class="variable">recordings</div>
		</div>
	</div>
</div>

<div class="menu">
	<div class="ICON"></div>
	<div class="subtext">start new practice session</div>
</div>

<style>
	.title {
		font-size: 36px;
		font-weight: bold;
		color: white;
		text-align: center;
		margin: 0px;
		padding: 0px;
	}

	.session {
		height: 100px;
		width: 600px;
		background-color: blanchedalmond;
		border-bottom: 5px solid lightcoral;
		margin: 30px;
		display: flex;
		flex-wrap: wrap;
		flex-direction: row;
		align-content: space-evenly;
	}

	.variable {
		background-color: lemonchiffon;
		height: 50px;
		width: 50px;
		font-size: 24px;
		font-style: italic;
		color: lightcoral;
		align-items: center;
		justify-items: center;
		justify-content: center;
		text-align: center;
	}
	.date {
		background-color: white;
		border: 1px solid lightcoral;
		height: 200px;
		width: 148px;
		color: lightcoral;
		align-items: center;
		justify-items: center;
		justify-content: center;
		text-align: center;
	}
	.goal {
		background-color: white;
		border: 1px solid lightcoral;
		height: 200px;
		width: 298px;
		color: lightcoral;
		align-items: center;
		justify-items: center;
		justify-content: center;
		text-align: center;
	}
	.note {
		background-color: white;
		border: 1px solid lightcoral;
		height: 230px;
		width: 600px;
		color: lightcoral;
		align-items: center;
		justify-items: center;
		justify-content: center;
		text-align: center;
	}
	.recordings {
		background-color: white;
		border: 1px solid lightcoral;
		border-bottom: 5px solid lightcoral;
		height: 100px;
		width: 600px;
		color: lightcoral;
		align-items: center;
		justify-items: center;
		justify-content: center;
		text-align: center;
	}
	.time {
		background-color: white;
		border: 1px solid lightcoral;
		height: 200px;
		width: 148px;
		color: lightcoral;
		align-items: center;
		justify-items: center;
		justify-content: center;
		text-align: center;
	}

	.subtext {
		font-size: 24px;
		font-weight: bold;
		color: lightpink;
		text-align: left;
		align-items: right;
		justify-items: right;
		margin: 5px;
	}
	.ICON {
		height: 20px;
		width: 20px;

		background-color: white;
		background-attachment: fixed;
		background-position: bottom;
		margin: 10px;
		padding: 5px;
	}

	.content {
		display: flex;
		flex-direction: row;
		text-align: center;
		align-items: center;
		justify-items: center;
		justify-content: center;
		margin-top: 0px;

		height: 100vh;
		width: 100vw;
	}

	.menu {
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

	.smalltext {
		font-size: 24px;
		font-weight: bold;
		color: white;
		text-align: center;
		margin: 5px;
	}

	.bodytext {
		font-size: 16px;
		color: white;
		text-align: center;
		margin: 5px;
		margin-left: 100px;
		margin-right: 100px;
	}

	body {
		margin: 0;
		padding: 0;
	}
	.background {
		background-color: lightpink;
		height: 130vh;
		width: 100vw;

		background-size: cover;
		background-position: center;
		background-attachment: fixed;

		margin: 0px;
		padding: 0px;
	}
</style>
