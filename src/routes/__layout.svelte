<script lang="ts" context="module">
	console.log('/ __layout.svelte context=module runs');
	export function load() {
		console.log('/ __layout.svelte context=module load() runs');
		return {};
	}
</script>

<div>
	<a href="/" sveltekit:prefetch>Home</a>
	<a href="/path1" sveltekit:prefetch>Path1</a>
	<a href="/path2" sveltekit:prefetch>Path2</a>
</div>
<slot />
