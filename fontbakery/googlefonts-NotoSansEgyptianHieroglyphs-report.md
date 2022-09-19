## Fontbakery report

Fontbakery version: 0.8.10

<details><summary><b>[7] NotoSansEgyptianHieroglyphs-Regular.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Egyptian Hieroglyphs' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* u13004 (U+13004): L<<228.0,789.0>--<339.0,614.0>>/L<<339.0,614.0>--<256.0,813.0>> = 9.746066721350674

	* u1300F (U+1300F): B<<637.5,644.0>-<661.0,606.0>-<681.0,563.0>>/B<<681.0,563.0>-<677.0,571.0>-<674.5,581.0>> = 1.6211459136531066

	* u1302A (U+1302A): B<<538.5,21.0>-<571.0,22.0>-<601.0,24.0>>/L<<601.0,24.0>--<538.0,24.0>> = 3.8140748342903783

	* u1302A (U+1302A): L<<395.0,24.0>--<364.0,24.0>>/B<<364.0,24.0>-<388.0,22.0>-<415.0,21.0>> = 4.763641690726143

	* u1302B (U+1302B): B<<592.5,21.0>-<625.0,22.0>-<655.0,24.0>>/L<<655.0,24.0>--<592.0,24.0>> = 3.8140748342903783

	* u1302B (U+1302B): L<<449.0,24.0>--<418.0,24.0>>/B<<418.0,24.0>-<442.0,22.0>-<469.0,21.0>> = 4.763641690726143

	* u1302C (U+1302C): B<<619.5,274.0>-<619.0,290.0>-<613.0,309.0>>/B<<613.0,309.0>-<615.0,281.0>-<608.5,261.5>> = 13.439951593747935

	* u1302C (U+1302C): B<<632.5,364.0>-<642.0,341.0>-<645.0,317.0>>/B<<645.0,317.0>-<648.0,341.0>-<657.5,364.0>> = 14.25003269780357

	* u1302C (U+1302C): L<<1023.0,148.0>--<1016.0,340.0>>/B<<1016.0,340.0>-<1016.0,338.0>-<1014.0,338.0>> = 2.0879838327232854

	* u13030 (U+13030): L<<358.0,442.0>--<357.0,441.0>>/B<<357.0,441.0>-<372.0,453.0>-<391.0,453.0>> = 6.340191745909908 

	* And 244 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* U1336F (U+1336F): L<<327.0,409.0>--<325.0,756.0>>

	* U1336F (U+1336F): L<<344.0,756.0>--<347.0,409.0>>

	* u1301F (U+1301F): L<<678.0,588.0>--<552.0,589.0>>

	* u1303B (U+1303B): L<<169.0,105.0>--<170.0,337.0>>

	* u1303B (U+1303B): L<<191.0,329.0>--<189.0,99.0>>

	* u1303B (U+1303B): L<<735.0,408.0>--<734.0,551.0>>

	* u1303C (U+1303C): L<<179.0,105.0>--<180.0,337.0>>

	* u1303C (U+1303C): L<<200.0,329.0>--<198.0,99.0>>

	* u1303C (U+1303C): L<<341.0,558.0>--<471.0,559.0>>

	* u13056 (U+13056): L<<169.0,105.0>--<170.0,337.0>> 

	* And 44 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 0 | 7 | 112 | 7 | 101 | 0 |
| 0% | 0% | 3% | 49% | 3% | 44% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
