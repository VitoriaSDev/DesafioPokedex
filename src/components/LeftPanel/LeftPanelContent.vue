<template>
	<div class="content">
		<List />
	</div>
</template>

<script>
	import List from '@/components/List/List.vue';

	export default {
		name: 'LeftPanelContent',
		components: {
			List,
		},
	};
</script>

<style lang="scss" scoped>
	.content {
		width: 100%;

		@media (min-width: 768px) {
			margin-top: 50px;
		}
	}
</style>
