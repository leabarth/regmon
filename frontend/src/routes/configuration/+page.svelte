<nav
	class="fixed right-8 top-32 z-10 hidden flex-col gap-2 rounded-none bg-white/80 p-2 text-sm font-medium text-gray-400 shadow-none md:flex"
>
	<a href="#formulare" class="hover:underline">Formulare</a>
	<a href="#gruppe" class="hover:underline">Gruppe</a>
	<a href="#datenmanagement" class="hover:underline">Datenmanagement</a>
</nav>

<div class="flex flex-col gap-4">
	<div id="formulare" class="flex scroll-mt-24 flex-col gap-2">
		<h2 class="font-bold">Formulare</h2>
		<div class="card card-border bg-base-100 md:max-w-2/3 w-full min-w-56 border-2 border-gray-300">
			<div class="card-body">
				<h2 class="card-title">Meine Formularauswahl</h2>
				<p class="py-4"><a href="/forms/1">Formular 1</a></p>
				<p class="py-4"><a href="/forms/2">Formular 2</a></p>
				<p class="py-4"><a href="/forms/3">Formular 3</a></p>
				<div class="card-actions justify-end">
					<button class="btn btn-outline btn-sm border-2 border-[#003F66] text-[#003F66]"
						>Hinzufügen</button
					>
					<button class="btn btn-outline btn-sm border-2 border-[#003F66] text-[#003F66]"
						>Löschen</button
					>
				</div>
			</div>
		</div>
	</div>

	<div id="gruppe" class="flex scroll-mt-24 flex-col gap-2">
		<h2 class="font-bold">Gruppe</h2>
		<div class="self-start">
			<button class="btn btn-sm border-2 border-[#003F66] bg-[#003F66] text-white shadow-none"
				>Gruppe verlassen</button
			>
		</div>
	</div>

	<div id="datenmanagement" class="flex scroll-mt-24 flex-col gap-2">
		<h2 class="font-bold">Datenmanagement</h2>
		<div class="self-start">
			<button class="btn btn-sm border-2 border-[#003F66] bg-[#003F66] text-white shadow-none"
				>Datenabfrage (Export)</button
			>
		</div>
	</div>
</div>
