<script>
	import FormModal from '$lib/FormModal.svelte';
	/**
	 * @type {import("svelte").SvelteComponent<{ modalId: any; showModal?: (() => void) | undefined; }, { [evt: string]: CustomEvent<any>; }, {}> & { $$bindings?: string | undefined; } & { showModal: () => void; }}
	 */
	let modalRef;
	function openModal() {
		modalRef?.showModal();
	}
</script>

<div class="card card-border bg-base-100 w-full min-w-56 border-2 border-gray-300">
	<div class="card-body">
		<h2 class="card-title">Kalender</h2>
		<fieldset class="fieldset">
			<legend class="fieldset-legend">Gruppe</legend>
			<select class="select">
				<option disabled selected>Wähle eine Gruppe</option>
				<option>Group 1</option>
				<option>Group 2</option>
				<option>Group 3</option>
			</select>
		</fieldset>
		<p>Kalender placeholder</p>
		<div class="card-actions justify-end">
			<button
				class="btn btn-sm border-2 border-[#003F66] bg-[#003F66] text-white shadow-none"
				on:click={openModal}>+ Daten eintragen</button
			>
			<FormModal modalId="my_modal_1" bind:this={modalRef} />
		</div>
	</div>
</div>
