<script lang="ts" context="module">
	console.log('path1 index.svelte context=module runs');
	export function load() {
		console.log('path1 index.svelte context=module load() runs');
		return {};
	}
</script>

<div>Path1</div>
