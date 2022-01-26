<script lang="ts" context="module">
	console.log('path2 __layout.svelte context=module runs');
	export function load() {
		console.log('path2 __layout.svelte context=module load() runs');
		return {};
	}
</script>

<slot />
