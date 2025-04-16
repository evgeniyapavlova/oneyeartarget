<script>
	import { onMount } from 'svelte';
	import { getURLParameters } from '$lib/utils/getAffParams';
	import { searchString } from '$lib/stores/affs';
	import '$lib/styles/styles.scss';

	onMount(() => {
		$searchString = getURLParameters();
	});
</script>

<div class="app">
	<slot />
</div>

<style>
	.app {
		display: flex;
		flex-direction: column;
		min-height: 100vh;
		padding: 40px 0;
	}
</style>
