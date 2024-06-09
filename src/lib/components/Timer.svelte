<!--
				Timer template
				Will be initially hidden via CSS.
				-->
<div id="template" class="timer">
	<div class="leftColumn">
		<div>
			<span class="hours">00</span>:<span class="minutes">00</span>:<span class="seconds">00</span
			><span class="tenthSeconds"><small>.00</small></span>
		</div>
		<div class="timerName">Timer Name</div>
	</div>
	<div class="rightColumn">
		<img
			src="images/button-remove-timer.png"
			width="42"
			height="76"
			alt="Remove Timer Button"
			onClick="deleteTimer()"
		/>
	</div>
</div>
