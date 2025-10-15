<div class="background">
	<br />
	<br />
	<br />
	<div class="smalltext">hello, welcome to [name of app]</div>
	<div class="title">why do <em>you</em> have a passion for music?</div>
	<div class="content">
		<textarea placeholder="type here, or record by pressing the button next to this text box."
		></textarea>
		<div class="record">
			<div class="startrecording"></div>
		</div>
	</div>
	<div class="bodytext">
		your answer can be changed after this step, so don't worry. at any time you wish, you can look
		back at your passion to be reminded again of your love for music. simply click on the heart icon
		next to the welcome menu.
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

	.content {
		display: flex;
		flex-direction: row;
		text-align: center;
		align-items: center;
		justify-items: center;
		justify-content: center;
		margin-top: -20px;

		height: 70vh;
		width: 100vw;
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

	.body {
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

	.record {
		align-items: center;
		justify-items: center;
		height: 100px;
		width: 100px;
		background-color: white;
		border: 5px solid lightcoral;
		background-position: center;
		border-radius: 100px;
		justify-content: center;
		margin: 20px;
		display: flex;
		flex-wrap: wrap;
	}

	.startrecording {
		height: 40px;
		width: 40px;
		background-color: lightcoral;
		text-align: center;
		text-wrap: wrap;
		object-position: center;
		align-items: center;
		justify-items: center;
		justify-content: center;
	}
</style>
