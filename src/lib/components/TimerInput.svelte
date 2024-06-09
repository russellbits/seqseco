<!--Timer input -->
<div id="timerInput">
	<form action="#" method="POST">
		<div class="form-row">
			<input
				type="number"
				pattern="[0-9]*"
				inputmode="decimal"
				name="hours10"
				id="hours10"
				min="0"
				max="6"
				class="no-arrows"
				onkeypress="return isNumberKey(event)"
			/>
			<input
				type="number"
				pattern="[0-9]*"
				inputmode="decimal"
				name="hours1"
				id="hours1"
				min="0"
				max="9"
				class="no-arrows"
				onkeypress="return isNumberKey(event)"
			/>
			:
			<input
				type="number"
				pattern="[0-6]*"
				inputmode="decimal"
				name="minutes10"
				id="minutes10"
				min="0"
				max="6"
				class="no-arrows"
				onkeypress="return isNumberKey(event)"
			/>
			<input
				type="number"
				pattern="[0-9]*"
				inputmode="decimal"
				name="minutes1"
				id="minutes1"
				min="0"
				max="9"
				class="no-arrows"
				onkeypress="return isNumberKey(event)"
			/>
			:
			<input
				type="number"
				pattern="[0-6]*"
				inputmode="decimal"
				name="seconds10"
				id="seconds10"
				min="0"
				max="6"
				class="no-arrows"
				onkeypress="return isNumberKey(event)"
			/>
			<input
				type="number"
				pattern="[0-9]*"
				inputmode="decimal"
				name="seconds1"
				id="seconds1"
				min="0"
				max="9"
				class="no-arrows"
				onkeypress="return isNumberKey(event)"
			/>
			<img
				id="addTimerBtn"
				src="images/button-add-timer-inactive.png"
				onclick="generateTimer()"
				width="42"
				height="76"
				alt="Add timer, inactive"
			/>
		</div>
	</form>
</div>
