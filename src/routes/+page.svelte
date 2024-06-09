<!-- +page.svelte -->
<script>
	import Menu from '$lib/components/Menu.svelte'
	import Notice from '$lib/components/Notice.svelte'
	import TimerControls from '$lib/components/TimerControls.svelte'
</script>

<div id="app">
	<Notice />

	<Menu />

	<TimerControls />

	<h1>Sequence Timer</h1>

	<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a>Hello?</p>
</div>
