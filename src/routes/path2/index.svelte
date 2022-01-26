<script lang="ts" context="module">
	console.log('path2 index.svelte context=module runs');
	export function load() {
		console.log('path2 index.svelte context=module load() runs');
		return {};
	}
</script>

<div>Path2</div>
