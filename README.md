Sassy Ink
=========

A quick and dirty attempt to make a Sass version of [Ink](http://zurb.com/ink). 

Only container width, number of columns, and gutter width are variable. There is much left to be done.

I tried to follow [Foundation](http://foundation.zurb.com/)'s structure and keep the generated CSS as close to the original as possible. Compare the Saas generated `ink.css` with the original, `ink-original.css`. Differences include:

* white space
* significant digits (8.333333% vs 8.33333%)
* rounding (16.666666% vs 16.66667%)
* Sass conversion of six-digit hexadecimal colors to color names (#FFFFFF vs white)

Credit
======

* [ZURB](http://www.zurb.com) (obvious)
* [René Meye](https://github.com/renemeye)'s [pull request #61](https://github.com/zurb/ink/pull/61). (less obvious)

Ink
===

Ink is a responsive email framework, used to make HTML emails look great on any client or device.  It includes a 12-column grid, as well as some simple UI elements for rapid prototyping.

Homepage:      http://zurb.com/ink<br />
Documentation: http://zurb.com/ink/docs.php<br />
Download:      http://zurb.com/ink/download.php

Ink is MIT-licensed and absolutely free to use.

ZURB
====

Ink was made by [ZURB](http://www.zurb.com), a product design company in Campbell, CA.

Diff
====
diff -w ink-original.css ink.css

	288c287
	<   width: 8.333333%;
	---
	>   width: 8.33333%;
	293c292
	<   width: 16.666666%;
	---
	>   width: 16.66667%;
	303c302
	<   width: 33.333333%;
	---
	>   width: 33.33333%;
	308c307
	<   width: 41.666666%;
	---
	>   width: 41.66667%;
	318c317
	<   width: 58.333333%;
	---
	>   width: 58.33333%;
	323c322
	<   width: 66.666666%;
	---
	>   width: 66.66667%;
	333c332
	<   width: 83.333333%;
	---
	>   width: 83.33333%;
	338c337
	<   width: 91.666666%;
	---
	>   width: 91.66667%;
	622c621
	<   color: #ffffff;
	---
	>   color: white;
	650c649
	<   color: #ffffff;
	---
	>   color: white;
	815c814
	<     width: 8.333333% !important;
	---
	>     width: 8.33333% !important;
	820c819
	<     width: 16.666666% !important;
	---
	>     width: 16.66667% !important;
	830c829
	<     width: 33.333333% !important;
	---
	>     width: 33.33333% !important;
	835c834
	<     width: 41.666666% !important;
	---
	>     width: 41.66667% !important;
	845c844
	<     width: 58.333333% !important;
	---
	>     width: 58.33333% !important;
	850c849
	<     width: 66.666666% !important;
	---
	>     width: 66.66667% !important;
	860c859
	<     width: 83.333333% !important;
	---
	>     width: 83.33333% !important;
	865c864
	<     width: 91.666666% !important;
	---
	>     width: 91.66667% !important;
	873,883c872
	<   table[class="body"] td.offset-by-one,
	<   table[class="body"] td.offset-by-two,
	<   table[class="body"] td.offset-by-three,
	<   table[class="body"] td.offset-by-four,
	<   table[class="body"] td.offset-by-five,
	<   table[class="body"] td.offset-by-six,
	<   table[class="body"] td.offset-by-seven,
	<   table[class="body"] td.offset-by-eight,
	<   table[class="body"] td.offset-by-nine,
	<   table[class="body"] td.offset-by-ten,
	<   table[class="body"] td.offset-by-eleven {
	---
	>   table[class="body"] td.offset-by-one, table[class="body"] td.offset-by-two, table[class="body"] td.offset-by-three, table[class="body"] td.offset-by-four, table[class="body"] td.offset-by-five, table[class="body"] td.offset-by-six, table[class="body"] td.offset-by-seven, table[class="body"] td.offset-by-eight, table[class="body"] td.offset-by-nine, table[class="body"] td.offset-by-ten, table[class="body"] td.offset-by-eleven {
