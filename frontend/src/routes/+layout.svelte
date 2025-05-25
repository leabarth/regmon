<script lang="ts">
	import '../app.css';
	import Layout from '$lib/Layout.svelte';
	import Navbar from '$lib/Navbar.svelte';

	let { children } = $props();
</script>

<Navbar />

<Layout>
	{@render children()}
</Layout>
