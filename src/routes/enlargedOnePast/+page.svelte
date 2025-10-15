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
</style>
