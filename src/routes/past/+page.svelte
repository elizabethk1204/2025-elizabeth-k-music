<div class="background">
	<br />
	<br />
	<br />
	<div class="title">past sessions</div>
	<div class="bodytext">
		here is a log of your past practice sessions! come here to check on your progress, set up future
		goals, and for it to serve as documentation of your hard work.
	</div>
	<div class="graphbutton">graph and data</div>
	<div class="content">
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
		</div>
		<br />
		<br />
		<div class="session">
			<div class="date">
				Date
				<div class="variable"></div>
			</div>
			<div class="goal">
				Goal
				<div class="variable"></div>
			</div>
			<div class="time">
				Time
				<div class="variable"></div>
			</div>
		</div>
		<br />
		<br />
		<div class="session">
			<div class="date">
				Date
				<div class="variable"></div>
			</div>
			<div class="goal">
				Goal
				<div class="variable"></div>
			</div>
			<div class="time">
				Time
				<div class="variable"></div>
			</div>
		</div>
		<br />
		<br />
	</div>
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
		margin: -10px;
		display: flex;
		flex-wrap: wrap;
		flex-direction: row;
		align-content: space-evenly;
	}
	.graphbutton {
		height: 50px;
		width: 120px;
		font-size: 20px;
		font-style: italic;
		background: lemonchiffon;
		object-position: center;
		margin: 10px;
		text-align: center;
		color: lightcoral;
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
		height: 100px;
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
		height: 100px;
		width: 298px;
		color: lightcoral;
		align-items: center;
		justify-items: center;
		justify-content: center;
		text-align: center;
	}
	.time {
		background-color: white;
		border: 1px solid lightcoral;
		height: 100px;
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
		flex-direction: column;
		text-align: center;
		align-items: center;
		justify-items: center;
		justify-content: center;
		margin-top: -20px;

		height: 70vh;
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
		height: 100vh;
		width: 100vw;

		background-size: cover;
		background-position: center;
		background-attachment: fixed;

		margin: 0px;
		padding: 0px;
	}
</style>
