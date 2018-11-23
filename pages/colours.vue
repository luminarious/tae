<template lang="pug">
main
	h1 Colours
	section.colours
		- let a = [1,2,3,4,5,6,7,8]
		each i in a
			.tile(class='fill-A' + i) A#{i}
		each i in a
			.tile(class='text-A' + i) A#{i}
		each i in a
			.tile(class='fill-B' + i) B#{i}
		each i in a
			.tile(class='text-B' + i) B#{i}
</template>
<style lang="stylus" scoped>
@import '../assets/styles/_variables.styl'
.colours
	display: grid
	grid-template-columns: repeat(8, 6rem)
	grid-auto-rows: 6rem
	grid-gap: space.s
</style>

