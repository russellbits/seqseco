<!-- +page.svelte -->
<script>
	import Menu from '$lib/components/Menu.svelte'
	import Notice from '$lib/components/Notice.svelte'
	import TimerControls from '$lib/components/TimerControls.svelte'
	import Timer from '$lib/components/Timer.svelte'
	import TimerInput from '$lib/components/TimerInput.svelte'
</script>

<div id="app">
	<Notice />

	<Menu />

	<TimerControls />

	<main>
		<Timer />
		<TimerInput />
	</main>
</div>
