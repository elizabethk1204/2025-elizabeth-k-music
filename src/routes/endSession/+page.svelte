<div class="background">
	<br />
	<br />
	<br />
	<div class="title">practice session ended.</div>
	<div class="bodytext"></div>
	<br />
	<div class="smalltext">goal for today:</div>
	<div class="bodytext">the actual goal, typed out so you remember</div>
	<br />
	<div class="content">
		<div class="smalltext">notes</div>
		<textarea placeholder="notes, observations, analysis for tomorrow's musician?'"></textarea>
		<br />
		<br />
		<div class="smalltext">practice session length:</div>
		<div class="timer">
			<div class="title">0:00</div>
		</div>
	</div>
</div>

<nav>
	<a href="/past">past practice sessions</a>
</nav>

<style>
	.title {
		font-size: 36px;
		font-weight: bold;
		color: white;
		text-align: center;
		margin: 0px;
		padding: 0px;
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

	.content {
		display: flex;
		flex-direction: column;
		text-align: center;
		align-items: center;
		justify-items: center;
		justify-content: center;
		margin-top: -20px;

		height: 70vh;
		width: 100vw;
	}

	.timer {
		height: 70px;
		width: 200px;
		align-items: center;
		justify-items: center;
		text-align: center;
		margin: 20px;
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

	body {
		margin: 0;
		padding: 0;
	}
	.background {
		background-color: lightpink;
		height: 110vh;
		width: 100vw;

		background-size: cover;
		background-position: center;
		background-attachment: fixed;

		margin: 0px;
		padding: 0px;
	}

	.start {
		align-items: center;
		justify-items: center;
		height: 200px;
		width: 200px;
		background-color: white;
		border: 5px solid lightcoral;
		background-position: center;
		border-radius: 100px;
		justify-content: center;
		margin: 20px;
		display: flex;
		flex-wrap: wrap;
	}

	.play {
		height: 60px;
		width: 60px;
		background-color: lightcoral;
		text-align: center;
		text-wrap: wrap;
		object-position: center;
		align-items: center;
		justify-items: center;
		justify-content: center;
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
	.heart {
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
