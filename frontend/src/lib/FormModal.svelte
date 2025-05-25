<script>
	export let modalId;
	/**
	 * @type {HTMLDialogElement}
	 */
	let dialogRef;
	// Methode, um das Modal von außen zu öffnen
	export function showModal() {
		dialogRef?.showModal();
	}
</script>

<dialog id={modalId} class="modal" bind:this={dialogRef}>
	<div class="modal-box">
		<h3 class="text-lg font-bold">Formulare</h3>
		<p class="py-4"><a href="/forms/1">Formular 1</a></p>
		<p class="py-4"><a href="/forms/2">Formular 2</a></p>
		<p class="py-4"><a href="/forms/3">Formular 3</a></p>
		<div class="modal-action">
			<form method="dialog">
				<!-- if there is a button in form, it will close the modal -->
				<button class="btn">Close</button>
			</form>
		</div>
	</div>
</dialog>
