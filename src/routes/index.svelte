<script context="module">
	export async function load({ page }) {
		await import('../lib/' + 'test' + '.svelte'); // does not work

		return {
			props: {}
		};
	}
</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
