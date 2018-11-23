<template lang="pug">
main
	h1 Typography
	h2 Scale
	p.type-d3 Display 3
	p.type-d2 Display 2 is almost exactly fifty characters long.
	p.type-d1 Display 1 is almost exactly fifty characters long.
	p.type-h1 Heading 1 is almost exactly fifty characters long. This end makes it at 75. Here is an extra sentence to show line height.
	p.type-h2 Heading 2 is almost exactly fifty characters long. This end makes it at 75. Here is an extra sentence to show line height.
	p.type-h3 Heading 3 is almost exactly fifty characters long. This end makes it at 75. Here is an extra sentence to show line height.
	p.type-s1 Subheading 1 is almost exactly fifty characters long. This end makes it at 75. Here is an extra sentence to show line height.
	p.type-s2 Subheading 2 is almost exactly fifty characters long. This end makes it at 75. Here is an extra sentence to show line height.
	p.type-b1 Body 1 is almost exactly fifty characters long. This end makes it at 75. Here is an extra sentence to show line height.
	p.type-b2 Body 2 is almost exactly fifty characters long. This end makes it at 75. Here is an extra sentence to show line height.
	p.type-small Small is almost exactly fifty characters long. This end makes it at 75. Here is an extra sentence to show line height.
	p.type-caption Caption is almost exactly fifty characters long. This end makes it at 75. Here is an extra sentence to show line height.
	p.type-button Button
	p.type-overline Overline
	
	h2 Utilities
	p.text-left(title=".text-left") Left-aligned
	p.text-center(title=".text-center") Center-aligned
	p.text-right Right-aligned

	p.case-none Regular case
	p.case-upper Uppercase
	p.case-lower Lowercase
	p.case-title Title case
	
	p.letter-upper uppercase first letter
	p.letter-lower Lowercase first letter

	h2 Language support
	table
		thead
			tr
				th Language
				th Code
				th Example
		tbody
			tr
				td(colspan="2") Western European (default)
				td Happy birthday 😄
			tr(lang="et-EE")
				td Estonian
				td et-EE
				td Palju õnne sünnipäevaks!
			tr(lang="lt-LT")
				td Lithuanian
				td lt-LT
				td Sveikinu gimtadienio proga
			tr(lang="lv-LV")
				td Latvian (Lettish)
				td lv-LV
				td Daudz laimes dzimšanas dienā!
			tr(lang="ru-RU")
				td Russian
				td ru-RU
				td С днём рожде́ния!
</template>
<style lang="stylus" scoped>
p
	margin-bottom: 4vh
	max-width: 30em
p[class^="type-"]
	opacity: 0.6
</style>

