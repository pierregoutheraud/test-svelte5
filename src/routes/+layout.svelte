<script lang="ts">
	import { onMount } from 'svelte';
	import { myStore } from '../stores/test';

	onMount(() => {
		$myStore = 1;
	});
</script>

<slot />
