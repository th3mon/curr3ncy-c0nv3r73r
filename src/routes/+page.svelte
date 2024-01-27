<h1>Currency Converter</h1>

<form action="" class="form">
	<div class="form__cash-in">
		<div class="form-control">
			<select name="in" id="cash-in-combobox">
				<option value="PLN" class="form__option-item">PLN</option>
				<option value="EUR" class="form__option-item">EUR</option>
				<option value="USD" class="form__option-item">USD</option>
				<option value="GBP" class="form__option-item">GBP</option>
			</select>
		</div>

		<div class="form-control">
			<label for="cash-in-value">Amount</label>
			<input type="number" id="cash-in-value" step="0.01" />
		</div>
	</div>
	<div class="form__cash-out">
		<div class="form-control">
			<select name="out" id="cash-out-combobox" class="">
				<option value="PLN" class="form__option-item">PLN</option>
				<option value="EUR" class="form__option-item">EUR</option>
				<option value="USD" class="form__option-item">USD</option>
				<option value="GBP" class="form__option-item">GBP</option>
			</select>
		</div>

		<div class="form-control">
			<label for="cash-out-value">Amount</label>
			<input type="number" id="cash-out-value" step="0.01" />
		</div>
	</div>
</form>
