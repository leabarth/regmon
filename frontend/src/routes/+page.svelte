<script>
	import logoSmall from '$lib/assets/regmon-logo-sm.png';
	import FormModal from '$lib/FormModal.svelte';
	/**
	 * @type {import("svelte").SvelteComponent<{ modalId: any; showModal?: (() => void) | undefined; }, { [evt: string]: CustomEvent<any>; }, {}> & { $$bindings?: string | undefined; } & { showModal: () => void; }}
	 */
	let modalRef;
	function openModal() {
		modalRef?.showModal();
	}
</script>

<!-- <div class="flex flex-col items-center justify-center h-screen gap-4">
  <div class="flex flex-col items-center justify-center gap-4">
    <img alt="REGmon logo" class="h-16" src={logoSmall} />
    <h1 class="text-3xl font-bold">Willkommen bei REGmon</h1>
  </div>

  <div class="flex flex-col items-center justify-center gap-4">
    <p class="text-lg">Hier kannst du deine Regenerationsdaten erfassen und analysieren.</p>
  </div> -->
<div class="flex flex-col gap-4">
	<div class="card card-border bg-base-100 md:max-w-2/3 w-full min-w-56 border-2 border-gray-300">
		<div class="card-body">
			<h2 class="card-title">
				<img alt="REGmon logo" class="h-6" src={logoSmall} /> Erfasse Regenerationsdaten
			</h2>
			<p>Eine Übersicht deiner erfassten Daten kannst du im Kalender einsehen.</p>
			<div class="card-actions justify-end">
				<button
					class="btn btn-sm border-2 border-[#003F66] bg-[#003F66] text-white shadow-none"
					on:click={openModal}>+ Daten eintragen</button
				>
				<FormModal modalId="my_modal_1" bind:this={modalRef} />
			</div>
		</div>
	</div>

	<div class="flex flex-col gap-4 sm:flex-row">
		<div class="card card-border bg-base-100 w-full min-w-56 border-2 border-gray-300">
			<div class="card-body">
				<h2 class="card-title">Füge Grafiken zur Ergebnisdarstellung hinzu</h2>
				<div class="card-actions justify-end">
					<a
						class="btn btn-sm border-2 border-[#003F66] bg-[#003F66] text-white shadow-none"
						href="/results">Zum Editor</a
					>
				</div>
			</div>
		</div>
		<div class="card card-border bg-base-100 w-full min-w-56 border-2 border-gray-300">
			<div class="card-body">
				<h2 class="card-title">Chart placeholder</h2>
				<div class="card-actions justify-end">
					<a
						class="btn btn-sm border-2 border-[#003F66] bg-[#003F66] text-white shadow-none"
						href="/results">Zum Editor</a
					>
				</div>
			</div>
		</div>
	</div>
</div>
