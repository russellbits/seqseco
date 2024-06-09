<!-- +page.svelte -->
<script>
	import Menu from '$lib/components/Menu.svelte'
	import Notice from '$lib/components/Notice.svelte'
	import TimerControls from '$lib/components/TimerControls.svelte'
	import Timer from '$lib/components/Timer.svelte'
	import TimerInput from '$lib/components/TimerInput.svelte'
	import InfoDialog from '$lib/components/InfoDialog.svelte'
	import SettingsDialog from '$lib/components/SettingsDialog.svelte'
</script>

<div id="app">
	<Notice />
	<InfoDialog />
	<SettingsDialog />

	<Menu />

	<TimerControls />

	<main>
		<Timer />
		<TimerInput />
	</main>
</div>
