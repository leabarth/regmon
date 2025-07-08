<div class="flex flex-col gap-4">
	<div class="card card-border bg-base-100 md:max-w-2/3 w-full min-w-56 border-2 border-gray-300">
		<div class="card-body">
			<h2 class="card-title">Benutzerkonto</h2>
			<fieldset class="fieldset">
				<legend class="fieldset-legend">Benutzername</legend>
				<input type="text" class="input" placeholder="Benutzername" />
			</fieldset>
			<fieldset class="fieldset">
				<legend class="fieldset-legend">Passwort</legend>
				<input type="text" class="input" placeholder="Passwort" />
                <p class="label break-words whitespace-normal">
                    Lassen Sie dieses Feld leer, wenn Sie das Passwort nicht ändern wollen.
                </p>
			</fieldset>
			<fieldset class="fieldset">
				<legend class="fieldset-legend">Passwort bestätigen</legend>
				<input type="text" class="input" placeholder="Passwort bestätigen" />
			</fieldset>
			<fieldset class="fieldset">
				<legend class="fieldset-legend">Ihre Email</legend>
				<input type="text" class="input" placeholder="Ihre Email" />
			</fieldset>
			<fieldset class="fieldset">
				<legend class="fieldset-legend">Vorname</legend>
				<input type="text" class="input" placeholder="Vorname" />
			</fieldset>
			<fieldset class="fieldset">
				<legend class="fieldset-legend">Nachname</legend>
				<input type="text" class="input" placeholder="Nachname" />
			</fieldset>
			<fieldset class="fieldset">
				<legend class="fieldset-legend">Sportart</legend>
				<input type="text" class="input" placeholder="Sportart" />
			</fieldset>
			<fieldset class="fieldset">
				<legend class="fieldset-legend">Körperhöhe</legend>
				<input
					type="number"
					class="input validator"
					placeholder="Körperhöhe"
					min="100"
					max="250"
					title="Muss zwischen 100 und 250 liegen."
				/>
			</fieldset>
			<fieldset class="fieldset">
				<legend class="fieldset-legend">Geschlecht</legend>
				<select class="select">
					<option disabled selected>Geschlecht</option>
					<option>Männlich</option>
					<option>Weiblich</option>
					<option>Divers</option>
				</select>
			</fieldset>
			<fieldset class="fieldset">
				<legend class="fieldset-legend">Geburtsdatum</legend>
				<input type="date" class="input" />
			</fieldset>
			<fieldset class="fieldset">
				<legend class="fieldset-legend">Mobiltelefon</legend>
				<input type="text" class="input" placeholder="Mobiltelefon" />
			</fieldset>
			<div class="card-actions justify-end">
				<button class="btn btn-outline btn-sm border-2 border-[#003F66] text-[#003F66]"
					>Speichern</button
				>
			</div>
		</div>
	</div>

	<div class="self-start">
		<button class="btn btn-sm border-2 border-[#003F66] bg-[#003F66] text-white shadow-none"
			>Abmelden</button
		>
	</div>
</div>
