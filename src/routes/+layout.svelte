<script lang="ts">
	import "./layout.css";

	let { children } = $props();
</script>

<svelte:head>
	<title>Open Vaporphase</title>
</svelte:head>
{@render children()}
