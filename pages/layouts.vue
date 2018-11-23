<template lang="pug">
main
	h1 Two types of layouts
	h2 Sidebar
	.grid-app.fill-B3
		.grid-bar.fill-B1 Sidebar
		.grid-txt Content

	h2 Top bar
	.grid-app.fill-B3
		.grid-top.fill-B1 Top
		.grid-txt Content
</template>
<script>
import LayoutTop from '~/layouts/top.vue'
import LayoutSide from '~/layouts/default.vue'

export default {
	components: {
		LayoutTop,
		LayoutSide
	}
}
</script>
<style lang="stylus" scoped>
.grid-app
	grid-column: 1/8
	height: 20rem
.grid-bar
.grid-top
	padding: 1rem
</style>

