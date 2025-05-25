<script>
	import { onMount } from 'svelte';
	import { page } from '$app/state';
	const formId = page.params.formId;
</script>

<h1>Details von Formular {formId}</h1>
