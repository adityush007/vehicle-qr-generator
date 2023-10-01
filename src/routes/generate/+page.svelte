<script>
</script>

<!-- <div class="container">
	<img src={url} alt="" />
	<input type="text" bind:value={link} />
	<button on:click={() => qr()}> make qr</button>
</div> -->

<div class="container">
	<h3>Enter the details of vehicle</h3>
	<form method="POST" action="?/create">
		<div class="grid">
			<label for="registration-number">
				Registration number
				<input
					type="text"
					name="registration-number"
					placeholder="Registration number of vehicle"
				/>
			</label>
			<label for="color">
				Color of vehicle
				<input type="text" name="color" placeholder="Color of vehicle" />
			</label>
		</div>
		<div class="grid">
			<label for="owner">
				Owner's name
				<input type="text" name="owner" placeholder="Owner's Name" />
			</label>
			<label for="make">
				Maker of vehicle
				<input type="text" name="make" placeholder="Maker of vehicle" />
			</label>
		</div>
		<div class="grid">
			<label for="model">
				Model of vehicle
				<input type="text" name="model" placeholder="Model of vehicle" />
			</label>
			<label for="vehicle-class">
				Class of vehicle
				<select name="vehicle-class" id="vehicle-class">
					<option value="MCWOG">Motorcycle without gears (Scooters and Mopeds)</option>
					<option value="MCWG">Motorcycle with gears </option>
					<option value="LMV">Light Motor Vehicle (Cars and SUVs)</option>
				</select>
			</label>
		</div>
		<div class="grid">
			<label for="date"
				>Registration Date
				<input type="date" id="date" name="reg-date" />
			</label>
			<label for="date"
				>Registration validity
				<input type="date" id="date" name="valid-end-date" />
			</label>
		</div>
		<!-- <div class="grid">
			<label for="date"
				>Date
				<input type="date" id="date" name="date" />
			</label>
		</div>
		<label for="chassis-number">
			Chassis Number
			<input type="text" name="chassis-number" placeholder="Chassis number of vehicle" />
		</label> -->
		<button type="submit">Submit</button>
	</form>
</div>

<style>
	/* img {
		width: 300px;
	} */
</style>
