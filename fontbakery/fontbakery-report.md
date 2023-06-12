## Fontbakery report

Fontbakery version: 0.8.8

<details><summary><b>[9] BricolageGrotesque-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Space and non-breaking space have the same width? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/hmtx.html#com.google.fonts/check/whitespace_widths">com.google.fonts/check/whitespace_widths</a>)</summary><div>


* 🔥 **FAIL** Space and non-breaking space have differing width: The space glyph named space is 246 font units wide, non-breaking space named (uni00A0) is 245 font units wide, and both should be positive and the same. GlyphsApp has "Sidebearing arithmetic" (https://glyphsapp.com/tutorials/spacing) which allows you to set the non-breaking space width to always equal the space width. [code: different-widths]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'ATLR' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Bricolage Grotesque Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: at	Contours detected: 3	Expected: 2
	- Glyph name: brokenbar	Contours detected: 1	Expected: 2
	- Glyph name: copyright	Contours detected: 2	Expected: 3
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: Uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2
	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2
	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2 
	- And 24 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:
	* exclam (U+0021): X=65.0,Y=661.0 (should be at cap-height 660?)
	* exclam (U+0021): X=158.0,Y=661.0 (should be at cap-height 660?)
	* dollar (U+0024): X=323.0,Y=659.0 (should be at cap-height 660?)
	* percent (U+0025): X=784.5,Y=1.5 (should be at baseline 0?)
	* ampersand (U+0026): X=608.0,Y=1.0 (should be at baseline 0?)
	* four (U+0034): X=319.0,Y=661.0 (should be at cap-height 660?)
	* four (U+0034): X=447.0,Y=661.0 (should be at cap-height 660?)
	* asciicircum (U+005E): X=211.0,Y=661.0 (should be at cap-height 660?)
	* asciicircum (U+005E): X=307.0,Y=661.0 (should be at cap-height 660?)
	* g (U+0067): X=281.0,Y=515.0 (should be at x-height 514?) and 65 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:
	* G (U+0047): L<<610.0,320.0>--<610.0,225.0>> -> L<<610.0,225.0>--<611.0,0.0>>
	* Gbreve (U+011E): L<<610.0,320.0>--<610.0,225.0>> -> L<<610.0,225.0>--<611.0,0.0>>
	* Gdotaccent (U+0120): L<<610.0,320.0>--<610.0,225.0>> -> L<<610.0,225.0>--<611.0,0.0>>
	* b (U+0062): L<<71.0,0.0>--<71.0,252.0>> -> L<<71.0,252.0>--<71.0,688.0>>
	* d (U+0064): L<<505.0,688.0>--<504.0,249.0>> -> L<<504.0,249.0>--<505.0,0.0>>
	* dcaron (U+010F): L<<505.0,688.0>--<504.0,249.0>> -> L<<504.0,249.0>--<505.0,0.0>>
	* dcroat (U+0111): L<<505.0,584.0>--<504.0,249.0>> -> L<<504.0,249.0>--<505.0,0.0>>
	* dong (U+20AB): L<<505.0,584.0>--<504.0,249.0>> -> L<<504.0,249.0>--<505.0,0.0>>
	* eng (U+014B): L<<71.0,0.0>--<71.0,290.0>> -> L<<71.0,290.0>--<71.0,514.0>>
	* h (U+0068): L<<71.0,0.0>--<71.0,274.0>> -> L<<71.0,274.0>--<71.0,688.0>> and 36 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * Eng (U+014A): L<<147.0,575.0>--<151.0,0.0>>
 * Eng (U+014A): L<<545.0,92.0>--<541.0,660.0>>
 * G (U+0047): L<<610.0,225.0>--<611.0,0.0>>
 * Gbreve (U+011E): L<<610.0,225.0>--<611.0,0.0>>
 * Gdotaccent (U+0120): L<<610.0,225.0>--<611.0,0.0>>
 * M (U+004D): L<<147.0,586.0>--<150.0,0.0>>
 * M (U+004D): L<<686.0,0.0>--<690.0,585.0>>
 * N (U+004E): L<<147.0,575.0>--<151.0,0.0>>
 * N (U+004E): L<<545.0,92.0>--<541.0,660.0>>
 * Nacute (U+0143): L<<147.0,575.0>--<151.0,0.0>> and 27 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[10] BricolageGrotesque-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Space and non-breaking space have the same width? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/hmtx.html#com.google.fonts/check/whitespace_widths">com.google.fonts/check/whitespace_widths</a>)</summary><div>


* 🔥 **FAIL** Space and non-breaking space have differing width: The space glyph named space is 228 font units wide, non-breaking space named (uni00A0) is 227 font units wide, and both should be positive and the same. GlyphsApp has "Sidebearing arithmetic" (https://glyphsapp.com/tutorials/spacing) which allows you to set the non-breaking space width to always equal the space width. [code: different-widths]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'ATLR' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Bricolage Grotesque SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: at	Contours detected: 3	Expected: 2
	- Glyph name: brokenbar	Contours detected: 1	Expected: 2
	- Glyph name: copyright	Contours detected: 2	Expected: 3
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: Uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2
	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2
	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2 
	- And 24 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:
	* dollar (U+0024): X=258.0,Y=2.0 (should be at baseline 0?)
	* dollar (U+0024): X=258.0,Y=659.0 (should be at cap-height 660?)
	* dollar (U+0024): X=344.0,Y=659.0 (should be at cap-height 660?)
	* dollar (U+0024): X=343.0,Y=1.0 (should be at baseline 0?)
	* three (U+0033): X=54.0,Y=661.0 (should be at cap-height 660?)
	* three (U+0033): X=511.0,Y=661.0 (should be at cap-height 660?)
	* four (U+0034): X=273.0,Y=661.0 (should be at cap-height 660?)
	* four (U+0034): X=488.0,Y=661.0 (should be at cap-height 660?)
	* seven (U+0037): X=20.0,Y=661.0 (should be at cap-height 660?)
	* seven (U+0037): X=474.0,Y=661.0 (should be at cap-height 660?) and 54 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:
	* G (U+0047): L<<639.0,334.0>--<639.0,220.0>> -> L<<639.0,220.0>--<639.0,0.0>>
	* Gbreve (U+011E): L<<639.0,334.0>--<639.0,220.0>> -> L<<639.0,220.0>--<639.0,0.0>>
	* Gdotaccent (U+0120): L<<639.0,334.0>--<639.0,220.0>> -> L<<639.0,220.0>--<639.0,0.0>>
	* b (U+0062): L<<60.0,0.0>--<60.0,241.0>> -> L<<60.0,241.0>--<60.0,703.0>>
	* d (U+0064): L<<544.0,703.0>--<544.0,239.0>> -> L<<544.0,239.0>--<544.0,0.0>>
	* dcaron (U+010F): L<<544.0,703.0>--<544.0,239.0>> -> L<<544.0,239.0>--<544.0,0.0>>
	* dcroat (U+0111): L<<544.0,588.0>--<544.0,239.0>> -> L<<544.0,239.0>--<544.0,0.0>>
	* dong (U+20AB): L<<544.0,588.0>--<544.0,239.0>> -> L<<544.0,239.0>--<544.0,0.0>>
	* eng (U+014B): L<<60.0,0.0>--<60.0,303.0>> -> L<<60.0,303.0>--<60.0,522.0>>
	* h (U+0068): L<<60.0,0.0>--<60.0,299.0>> -> L<<60.0,299.0>--<60.0,703.0>> and 36 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:
	* Ohorn (U+01A0): L<<531.0,621.0>--<529.0,622.0>>/B<<529.0,622.0>-<587.0,580.0>-<619.5,506.0>> = 9.344671902099657
	* Uogonek (U+0172): B<<571.0,76.0>-<517.0,8.0>-<413.0,-9.0>>/L<<413.0,-9.0>--<413.0,-9.0>> = 9.283552805261326
	* uni1EDA (U+1EDA): L<<531.0,621.0>--<529.0,622.0>>/B<<529.0,622.0>-<587.0,580.0>-<619.5,506.0>> = 9.344671902099657
	* uni1EDC (U+1EDC): L<<531.0,621.0>--<529.0,622.0>>/B<<529.0,622.0>-<587.0,580.0>-<619.5,506.0>> = 9.344671902099657
	* uni1EDE (U+1EDE): L<<531.0,621.0>--<529.0,622.0>>/B<<529.0,622.0>-<587.0,580.0>-<619.5,506.0>> = 9.344671902099657
	* uni1EE0 (U+1EE0): L<<531.0,621.0>--<529.0,622.0>>/B<<529.0,622.0>-<587.0,580.0>-<619.5,506.0>> = 9.344671902099657 and uni1EE2 (U+1EE2): L<<531.0,621.0>--<529.0,622.0>>/B<<529.0,622.0>-<587.0,580.0>-<619.5,506.0>> = 9.344671902099657 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * lira (U+20A4): L<<479.0,287.0>--<362.0,286.0>>
 * oe (U+0153): L<<565.0,313.0>--<794.0,314.0>>
 * q (U+0071): L<<543.0,282.0>--<544.0,-158.0>>
 * q (U+0071): L<<544.0,522.0>--<543.0,282.0>>
 * seven (U+0037): L<<357.0,557.0>--<20.0,555.0>>
 * sterling (U+00A3): L<<487.0,317.0>--<348.0,316.0>>
 * three (U+0033): L<<376.0,557.0>--<54.0,556.0>>
 * u (U+0075): L<<525.0,228.0>--<526.0,0.0>>
 * uacute (U+00FA): L<<525.0,228.0>--<526.0,0.0>>
 * ubreve (U+016D): L<<525.0,228.0>--<526.0,0.0>> and 16 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[8] BricolageGrotesque48pt-SemiBold.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'ATLR' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Bricolage Grotesque 48pt SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: at	Contours detected: 3	Expected: 2
	- Glyph name: brokenbar	Contours detected: 1	Expected: 2
	- Glyph name: copyright	Contours detected: 2	Expected: 3
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: Uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2
	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2
	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2 
	- And 24 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:
	* dollar (U+0024): X=237.0,Y=659.0 (should be at cap-height 660?)
	* dollar (U+0024): X=329.0,Y=2.0 (should be at baseline 0?)
	* three (U+0033): X=47.0,Y=661.0 (should be at cap-height 660?)
	* three (U+0033): X=505.0,Y=661.0 (should be at cap-height 660?)
	* four (U+0034): X=267.0,Y=661.0 (should be at cap-height 660?)
	* four (U+0034): X=476.0,Y=661.0 (should be at cap-height 660?)
	* five (U+0035): X=74.0,Y=661.0 (should be at cap-height 660?)
	* five (U+0035): X=498.0,Y=661.0 (should be at cap-height 660?)
	* seven (U+0037): X=13.0,Y=661.0 (should be at cap-height 660?)
	* seven (U+0037): X=465.0,Y=661.0 (should be at cap-height 660?) and 59 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:
	* G (U+0047): L<<609.0,330.0>--<609.0,216.0>> -> L<<609.0,216.0>--<610.0,0.0>>
	* Gbreve (U+011E): L<<609.0,330.0>--<609.0,216.0>> -> L<<609.0,216.0>--<610.0,0.0>>
	* Gdotaccent (U+0120): L<<609.0,330.0>--<609.0,216.0>> -> L<<609.0,216.0>--<610.0,0.0>>
	* b (U+0062): L<<41.0,0.0>--<41.0,211.0>> -> L<<41.0,211.0>--<41.0,690.0>>
	* d (U+0064): L<<520.0,690.0>--<519.0,207.0>> -> L<<519.0,207.0>--<520.0,0.0>>
	* dcaron (U+010F): L<<520.0,690.0>--<519.0,207.0>> -> L<<519.0,207.0>--<520.0,0.0>>
	* dcroat (U+0111): L<<520.0,564.0>--<519.0,207.0>> -> L<<519.0,207.0>--<520.0,0.0>>
	* dong (U+20AB): L<<520.0,564.0>--<519.0,207.0>> -> L<<519.0,207.0>--<520.0,0.0>>
	* eng (U+014B): L<<41.0,0.0>--<41.0,272.0>> -> L<<41.0,272.0>--<41.0,522.0>>
	* h (U+0068): L<<41.0,0.0>--<41.0,252.0>> -> L<<41.0,252.0>--<41.0,690.0>> and 36 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * G (U+0047): L<<609.0,216.0>--<610.0,0.0>>
 * Gbreve (U+011E): L<<609.0,216.0>--<610.0,0.0>>
 * Gdotaccent (U+0120): L<<609.0,216.0>--<610.0,0.0>>
 * d (U+0064): L<<519.0,207.0>--<520.0,0.0>>
 * d (U+0064): L<<520.0,690.0>--<519.0,207.0>>
 * dcaron (U+010F): L<<519.0,207.0>--<520.0,0.0>>
 * dcaron (U+010F): L<<520.0,690.0>--<519.0,207.0>>
 * dcroat (U+0111): L<<519.0,207.0>--<520.0,0.0>>
 * dcroat (U+0111): L<<520.0,564.0>--<519.0,207.0>>
 * dong (U+20AB): L<<519.0,207.0>--<520.0,0.0>> and 11 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[10] BricolageGrotesque10pt-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Space and non-breaking space have the same width? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/hmtx.html#com.google.fonts/check/whitespace_widths">com.google.fonts/check/whitespace_widths</a>)</summary><div>


* 🔥 **FAIL** Space and non-breaking space have differing width: The space glyph named space is 247 font units wide, non-breaking space named (uni00A0) is 246 font units wide, and both should be positive and the same. GlyphsApp has "Sidebearing arithmetic" (https://glyphsapp.com/tutorials/spacing) which allows you to set the non-breaking space width to always equal the space width. [code: different-widths]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'ATLR' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Bricolage Grotesque 10pt Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: at	Contours detected: 3	Expected: 2
	- Glyph name: brokenbar	Contours detected: 1	Expected: 2
	- Glyph name: copyright	Contours detected: 2	Expected: 3
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: Uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2
	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2
	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2 
	- And 24 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:
	* exclam (U+0021): X=69.0,Y=661.0 (should be at cap-height 660?)
	* exclam (U+0021): X=198.0,Y=661.0 (should be at cap-height 660?)
	* dollar (U+0024): X=274.0,Y=1.0 (should be at baseline 0?)
	* three (U+0033): X=59.0,Y=661.0 (should be at cap-height 660?)
	* three (U+0033): X=506.0,Y=661.0 (should be at cap-height 660?)
	* four (U+0034): X=291.0,Y=661.0 (should be at cap-height 660?)
	* four (U+0034): X=481.0,Y=661.0 (should be at cap-height 660?)
	* seven (U+0037): X=26.0,Y=661.0 (should be at cap-height 660?)
	* seven (U+0037): X=468.0,Y=661.0 (should be at cap-height 660?)
	* question (U+003F): X=100.0,Y=659.0 (should be at cap-height 660?) and 43 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:
	* uni00B5 (U+00B5): L<<536.0,520.0>--<536.0,215.0>> -> L<<536.0,215.0>--<538.0,0.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:
	* Uogonek (U+0172): B<<586.5,73.5>-<530.0,7.0>-<425.0,-9.0>>/L<<425.0,-9.0>--<425.0,-9.0>> = 8.664135433108044 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * ae (U+00E6): L<<862.0,242.0>--<502.0,239.0>>
 * e (U+0065): L<<156.0,307.0>--<423.0,309.0>>
 * e (U+0065): L<<524.0,242.0>--<152.0,239.0>>
 * eacute (U+00E9): L<<156.0,307.0>--<423.0,309.0>>
 * eacute (U+00E9): L<<524.0,242.0>--<152.0,239.0>>
 * ecaron (U+011B): L<<156.0,307.0>--<423.0,309.0>>
 * ecaron (U+011B): L<<524.0,242.0>--<152.0,239.0>>
 * ecircumflex (U+00EA): L<<156.0,307.0>--<423.0,309.0>>
 * ecircumflex (U+00EA): L<<524.0,242.0>--<152.0,239.0>>
 * edieresis (U+00EB): L<<156.0,307.0>--<423.0,309.0>> and 28 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[8] BricolageGrotesque10ptCondensed-ExtraBold.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'ATLR' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Bricolage Grotesque 10pt Condensed ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: at	Contours detected: 3	Expected: 2
	- Glyph name: brokenbar	Contours detected: 1	Expected: 2
	- Glyph name: copyright	Contours detected: 2	Expected: 3
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: Uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2
	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2
	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2 
	- And 24 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:
	* dollar (U+0024): X=200.0,Y=1.0 (should be at baseline 0?)
	* dollar (U+0024): X=198.0,Y=661.0 (should be at cap-height 660?)
	* dollar (U+0024): X=277.0,Y=661.0 (should be at cap-height 660?)
	* dollar (U+0024): X=276.0,Y=-1.0 (should be at baseline 0?)
	* four (U+0034): X=164.0,Y=661.0 (should be at cap-height 660?)
	* four (U+0034): X=410.0,Y=661.0 (should be at cap-height 660?)
	* question (U+003F): X=74.5,Y=661.0 (should be at cap-height 660?)
	* Q (U+0051): X=50.0,Y=-2.0 (should be at baseline 0?)
	* Q (U+0051): X=153.0,Y=-1.0 (should be at baseline 0?)
	* g (U+0067): X=131.0,Y=-1.0 (should be at baseline 0?) and 86 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:
	* trademark (U+2122): L<<410.0,328.0>--<367.0,544.0>>/L<<367.0,544.0>--<367.0,328.0>> = 11.258912202988107 and trademark (U+2122): L<<544.0,328.0>--<544.0,544.0>>/L<<544.0,544.0>--<501.0,328.0>> = 11.258912202988107 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * G (U+0047): L<<400.0,0.0>--<401.0,192.0>>
 * Gbreve (U+011E): L<<400.0,0.0>--<401.0,192.0>>
 * Gdotaccent (U+0120): L<<400.0,0.0>--<401.0,192.0>>
 * two (U+0032): L<<181.0,122.0>--<429.0,124.0>>
 * uni0122 (U+0122): L<<400.0,0.0>--<401.0,192.0>>
 * uni20B2 (U+20B2): L<<375.0,5.0>--<376.0,193.0>> and uni20BA (U+20BA): L<<403.0,265.0>--<565.0,266.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[8] BricolageGrotesque10pt-ExtraLight.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'ATLR' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Bricolage Grotesque 10pt ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: at	Contours detected: 3	Expected: 2
	- Glyph name: brokenbar	Contours detected: 1	Expected: 2
	- Glyph name: copyright	Contours detected: 2	Expected: 3
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: Uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2
	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2
	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2 
	- And 24 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:
	* exclam (U+0021): X=78.0,Y=661.0 (should be at cap-height 660?)
	* exclam (U+0021): X=154.0,Y=661.0 (should be at cap-height 660?)
	* dollar (U+0024): X=282.0,Y=-1.0 (should be at baseline 0?)
	* dollar (U+0024): X=282.0,Y=662.0 (should be at cap-height 660?)
	* dollar (U+0024): X=324.0,Y=661.0 (should be at cap-height 660?)
	* dollar (U+0024): X=324.0,Y=-1.0 (should be at baseline 0?)
	* four (U+0034): X=335.0,Y=661.0 (should be at cap-height 660?)
	* four (U+0034): X=435.0,Y=661.0 (should be at cap-height 660?)
	* g (U+0067): X=297.0,Y=513.0 (should be at x-height 512?)
	* g (U+0067): X=525.0,Y=513.0 (should be at x-height 512?) and 61 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:
	* uni00B5 (U+00B5): L<<120.0,65.0>--<137.0,-110.0>> -> L<<137.0,-110.0>--<137.0,-159.0>> and uni00B5 (U+00B5): L<<479.0,512.0>--<479.0,216.0>> -> L<<479.0,216.0>--<482.0,0.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * Eng (U+014A): L<<146.0,593.0>--<151.0,0.0>>
 * Eng (U+014A): L<<560.0,74.0>--<555.0,660.0>>
 * M (U+004D): L<<148.0,604.0>--<152.0,0.0>>
 * M (U+004D): L<<715.0,0.0>--<720.0,603.0>>
 * N (U+004E): L<<146.0,593.0>--<151.0,0.0>>
 * N (U+004E): L<<560.0,74.0>--<555.0,660.0>>
 * Nacute (U+0143): L<<146.0,593.0>--<151.0,0.0>>
 * Nacute (U+0143): L<<560.0,74.0>--<555.0,660.0>>
 * Ncaron (U+0147): L<<146.0,593.0>--<151.0,0.0>>
 * Ncaron (U+0147): L<<560.0,74.0>--<555.0,660.0>> and 37 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[8] BricolageGrotesque10ptCondensed-SemiBold.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'ATLR' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Bricolage Grotesque 10pt Condensed SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: at	Contours detected: 3	Expected: 2
	- Glyph name: brokenbar	Contours detected: 1	Expected: 2
	- Glyph name: copyright	Contours detected: 2	Expected: 3
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: Uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2
	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2
	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2 
	- And 24 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:
	* G (U+0047): L<<458.0,326.0>--<458.0,228.0>> -> L<<458.0,228.0>--<458.0,0.0>>
	* Gbreve (U+011E): L<<458.0,326.0>--<458.0,228.0>> -> L<<458.0,228.0>--<458.0,0.0>>
	* Gdotaccent (U+0120): L<<458.0,326.0>--<458.0,228.0>> -> L<<458.0,228.0>--<458.0,0.0>>
	* uni0122 (U+0122): L<<458.0,326.0>--<458.0,228.0>> -> L<<458.0,228.0>--<458.0,0.0>> and uni20B2 (U+20B2): L<<430.0,324.0>--<430.0,228.0>> -> L<<430.0,228.0>--<431.0,5.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:
	* trademark (U+2122): L<<388.0,328.0>--<340.0,565.0>>/L<<340.0,565.0>--<340.0,328.0>> = 11.449337988500027 and trademark (U+2122): L<<518.0,328.0>--<518.0,565.0>>/L<<518.0,565.0>--<468.0,328.0>> = 11.913023668400745 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * d (U+0064): L<<328.0,0.0>--<327.0,133.0>>
 * dcaron (U+010F): L<<328.0,0.0>--<327.0,133.0>>
 * dcroat (U+0111): L<<328.0,0.0>--<327.0,133.0>>
 * dong (U+20AB): L<<328.0,0.0>--<327.0,133.0>>
 * three (U+0033): L<<253.0,560.0>--<33.0,559.0>>
 * threeeighths (U+215C): L<<167.0,624.0>--<26.0,623.0>>
 * threequarters (U+00BE): L<<167.0,624.0>--<26.0,623.0>>
 * two (U+0032): L<<154.0,99.0>--<399.0,100.0>>
 * u (U+0075): L<<316.0,0.0>--<317.0,146.0>>
 * uacute (U+00FA): L<<316.0,0.0>--<317.0,146.0>> and 23 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[8] BricolageGrotesque10ptCondensed-Light.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'ATLR' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Bricolage Grotesque 10pt Condensed Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: at	Contours detected: 3	Expected: 2
	- Glyph name: brokenbar	Contours detected: 1	Expected: 2
	- Glyph name: copyright	Contours detected: 2	Expected: 3
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: Uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2
	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2
	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2 
	- And 24 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:
	* G (U+0047): L<<412.0,313.0>--<412.0,232.0>> -> L<<412.0,232.0>--<412.0,0.0>>
	* Gbreve (U+011E): L<<412.0,313.0>--<412.0,232.0>> -> L<<412.0,232.0>--<412.0,0.0>>
	* Gdotaccent (U+0120): L<<412.0,313.0>--<412.0,232.0>> -> L<<412.0,232.0>--<412.0,0.0>>
	* OE (U+0152): L<<341.0,660.0>--<410.0,660.0>> -> L<<410.0,660.0>--<410.0,660.0>>
	* OE (U+0152): L<<410.0,660.0>--<410.0,660.0>> -> L<<410.0,660.0>--<618.0,660.0>>
	* uni0122 (U+0122): L<<412.0,313.0>--<412.0,232.0>> -> L<<412.0,232.0>--<412.0,0.0>> and uni20B2 (U+20B2): L<<382.0,311.0>--<382.0,232.0>> -> L<<382.0,232.0>--<383.0,5.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:
	* trademark (U+2122): L<<356.0,328.0>--<299.0,596.0>>/L<<299.0,596.0>--<299.0,328.0>> = 12.007126587838695 and trademark (U+2122): L<<478.0,328.0>--<478.0,596.0>>/L<<478.0,596.0>--<419.0,328.0>> = 12.415575090732794 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * Uogonek (U+0172): L<<144.0,660.0>--<143.0,177.0>>
 * uni1EEA (U+1EEA): L<<144.0,660.0>--<143.0,177.0>>
 * uni20B2 (U+20B2): L<<382.0,232.0>--<383.0,5.0>> and uni20BC (U+20BC): L<<282.0,486.0>--<283.0,0.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[8] BricolageGrotesque48ptCondensed-ExtraBold.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'ATLR' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Bricolage Grotesque 48pt Condensed ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: at	Contours detected: 3	Expected: 2
	- Glyph name: brokenbar	Contours detected: 1	Expected: 2
	- Glyph name: copyright	Contours detected: 2	Expected: 3
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: Uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2
	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2
	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2 
	- And 24 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:
	* ampersand (U+0026): X=71.5,Y=1.5 (should be at baseline 0?)
	* ampersand (U+0026): X=506.0,Y=-1.0 (should be at baseline 0?)
	* four (U+0034): X=144.0,Y=661.0 (should be at cap-height 660?)
	* four (U+0034): X=387.0,Y=661.0 (should be at cap-height 660?)
	* question (U+003F): X=63.5,Y=659.0 (should be at cap-height 660?)
	* Q (U+0051): X=25.0,Y=-2.0 (should be at baseline 0?)
	* g (U+0067): X=136.0,Y=-0.5 (should be at baseline 0?)
	* r (U+0072): X=278.0,Y=530.0 (should be at x-height 528?)
	* r (U+0072): X=285.0,Y=530.0 (should be at x-height 528?)
	* r (U+0072): X=292.0,Y=529.0 (should be at x-height 528?) and 41 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:
	* oslash (U+00F8): B<<170.0,252.0>-<170.0,234.0>-<170.0,220.0>>/L<<170.0,220.0>--<220.0,416.0>> = 14.311041262606418
	* trademark (U+2122): L<<398.0,328.0>--<359.0,536.0>>/L<<359.0,536.0>--<359.0,328.0>> = 10.61965527615514 and trademark (U+2122): L<<528.0,328.0>--<528.0,536.0>>/L<<528.0,536.0>--<491.0,328.0>> = 10.086531684653783 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * minute (U+2032): L<<5.0,402.0>--<6.0,660.0>>
 * second (U+2033): L<<159.0,402.0>--<160.0,660.0>> and second (U+2033): L<<5.0,402.0>--<6.0,660.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[9] BricolageGrotesque48ptCondensed-SemiBold.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'ATLR' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Bricolage Grotesque 48pt Condensed SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: at	Contours detected: 3	Expected: 2
	- Glyph name: brokenbar	Contours detected: 1	Expected: 2
	- Glyph name: copyright	Contours detected: 2	Expected: 3
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: Uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2
	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2
	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2 
	- And 24 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:
	* ampersand (U+0026): X=465.0,Y=-1.0 (should be at baseline 0?)
	* four (U+0034): X=154.0,Y=661.0 (should be at cap-height 660?)
	* four (U+0034): X=348.0,Y=661.0 (should be at cap-height 660?)
	* a (U+0061): X=125.0,Y=530.0 (should be at x-height 528?)
	* f (U+0066): X=231.0,Y=529.0 (should be at x-height 528?)
	* h (U+0068): X=143.5,Y=529.5 (should be at x-height 528?)
	* r (U+0072): X=262.0,Y=530.0 (should be at x-height 528?)
	* braceleft (U+007B): X=257.0,Y=2.0 (should be at baseline 0?)
	* braceright (U+007D): X=6.0,Y=2.0 (should be at baseline 0?)
	* section (U+00A7): X=223.0,Y=-1.0 (should be at baseline 0?) and 31 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:
	* G (U+0047): L<<371.0,332.0>--<371.0,232.0>> -> L<<371.0,232.0>--<372.0,0.0>>
	* Gbreve (U+011E): L<<371.0,332.0>--<371.0,232.0>> -> L<<371.0,232.0>--<372.0,0.0>>
	* Gdotaccent (U+0120): L<<371.0,332.0>--<371.0,232.0>> -> L<<371.0,232.0>--<372.0,0.0>>
	* b (U+0062): L<<24.0,0.0>--<26.0,251.0>> -> L<<26.0,251.0>--<26.0,680.0>>
	* d (U+0064): L<<352.0,680.0>--<351.0,250.0>> -> L<<351.0,250.0>--<352.0,0.0>>
	* dcaron (U+010F): L<<352.0,680.0>--<351.0,250.0>> -> L<<351.0,250.0>--<352.0,0.0>>
	* dcroat (U+0111): L<<351.0,564.0>--<351.0,250.0>> -> L<<351.0,250.0>--<352.0,0.0>>
	* dong (U+20AB): L<<351.0,564.0>--<351.0,250.0>> -> L<<351.0,250.0>--<352.0,0.0>>
	* eng (U+014B): L<<25.0,0.0>--<25.0,302.0>> -> L<<25.0,302.0>--<24.0,528.0>>
	* h (U+0068): L<<25.0,0.0>--<25.0,289.0>> -> L<<25.0,289.0>--<24.0,680.0>> and 36 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:
	* trademark (U+2122): L<<340.0,328.0>--<303.0,559.0>>/L<<303.0,559.0>--<303.0,328.0>> = 9.09995035978375 and trademark (U+2122): L<<455.0,328.0>--<455.0,559.0>>/L<<455.0,559.0>--<419.0,328.0>> = 8.857958763628323 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * G (U+0047): L<<371.0,232.0>--<372.0,0.0>>
 * Gbreve (U+011E): L<<371.0,232.0>--<372.0,0.0>>
 * Gdotaccent (U+0120): L<<371.0,232.0>--<372.0,0.0>>
 * b (U+0062): L<<24.0,0.0>--<26.0,251.0>>
 * d (U+0064): L<<351.0,250.0>--<352.0,0.0>>
 * d (U+0064): L<<352.0,680.0>--<351.0,250.0>>
 * dcaron (U+010F): L<<351.0,250.0>--<352.0,0.0>>
 * dcaron (U+010F): L<<352.0,680.0>--<351.0,250.0>>
 * dcroat (U+0111): L<<351.0,250.0>--<352.0,0.0>>
 * dong (U+20AB): L<<351.0,250.0>--<352.0,0.0>> and 47 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[11] BricolageGrotesque10ptCondensed-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check name table: FONT_FAMILY_NAME entries. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/familyname">com.google.fonts/check/name/familyname</a>)</summary><div>


* 🔥 **FAIL** Entry [FONT_FAMILY_NAME(1):WINDOWS(3)] on the "name" table: Expected "Bricolage Grotesque 10pt Condensed" but got "Bricolage Grotesque 10pt Condensed Bricolage Grotesque 10pt Condensed Regular". [code: mismatch]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: TYPOGRAPHIC_FAMILY_NAME entries. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/typographicfamilyname">com.google.fonts/check/name/typographicfamilyname</a>)</summary><div>


* 🔥 **FAIL** Font style is "Bold" and, for that reason, it is not expected to have a [TYPOGRAPHIC_FAMILY_NAME(16):WINDOWS(3)] entry! [code: ribbi]
</div></details><details><summary>🔥 <b>FAIL:</b> Does full font name begin with the font family name? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/name.html#com.google.fonts/check/name/match_familyname_fullfont">com.google.fonts/check/name/match_familyname_fullfont</a>)</summary><div>


* 🔥 **FAIL** On the 'name' table, the full font name (NameID 4 - FULL_FONT_NAME: 'Bricolage Grotesque 10pt Condensed Bricolage Grotesque 10pt Condensed Regular') does not begin with font family name (NameID 1 - FONT_FAMILY_NAME: 'Bricolage Grotesque 10pt Condensed Bold') [code: does-not]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'ATLR' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Bricolage Grotesque 10pt Condensed Bricolage Grotesque 10pt Condensed Regular' / SUBFAMILY_NAME = 'Bold'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: at	Contours detected: 3	Expected: 2
	- Glyph name: brokenbar	Contours detected: 1	Expected: 2
	- Glyph name: copyright	Contours detected: 2	Expected: 3
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: Uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2
	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2
	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2 
	- And 24 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:
	* G (U+0047): L<<474.0,331.0>--<474.0,226.0>> -> L<<474.0,226.0>--<474.0,0.0>>
	* Gbreve (U+011E): L<<474.0,331.0>--<474.0,226.0>> -> L<<474.0,226.0>--<474.0,0.0>>
	* Gdotaccent (U+0120): L<<474.0,331.0>--<474.0,226.0>> -> L<<474.0,226.0>--<474.0,0.0>>
	* uni0122 (U+0122): L<<474.0,331.0>--<474.0,226.0>> -> L<<474.0,226.0>--<474.0,0.0>> and uni20B2 (U+20B2): L<<446.0,329.0>--<446.0,227.0>> -> L<<446.0,227.0>--<446.0,5.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:
	* trademark (U+2122): L<<399.0,328.0>--<353.0,554.0>>/L<<353.0,554.0>--<353.0,328.0>> = 11.504815326258814 and trademark (U+2122): L<<531.0,328.0>--<531.0,554.0>>/L<<531.0,554.0>--<485.0,328.0>> = 11.504815326258814 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * lira (U+20A4): L<<49.0,316.0>--<189.0,315.0>>
 * two (U+0032): L<<168.0,111.0>--<414.0,112.0>> and uni00B5 (U+00B5): L<<330.0,0.0>--<329.0,152.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[8] BricolageGrotesque-ExtraBold.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'ATLR' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Bricolage Grotesque ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: at	Contours detected: 3	Expected: 2
	- Glyph name: brokenbar	Contours detected: 1	Expected: 2
	- Glyph name: copyright	Contours detected: 2	Expected: 3
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: Uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2
	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2
	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2 
	- And 24 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:
	* dollar (U+0024): X=250.0,Y=658.0 (should be at cap-height 660?)
	* dollar (U+0024): X=358.0,Y=658.0 (should be at cap-height 660?)
	* dollar (U+0024): X=357.0,Y=2.0 (should be at baseline 0?)
	* percent (U+0025): X=361.0,Y=658.0 (should be at cap-height 660?)
	* percent (U+0025): X=614.5,Y=-1.5 (should be at baseline 0?)
	* ampersand (U+0026): X=99.0,Y=2.0 (should be at baseline 0?)
	* three (U+0033): X=51.0,Y=661.0 (should be at cap-height 660?)
	* three (U+0033): X=527.0,Y=661.0 (should be at cap-height 660?)
	* four (U+0034): X=242.0,Y=661.0 (should be at cap-height 660?)
	* four (U+0034): X=516.0,Y=661.0 (should be at cap-height 660?) and 69 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:
	* uni20BF (U+20BF): L<<361.0,7.0>--<356.0,7.0>> -> L<<356.0,7.0>--<252.0,7.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * G (U+0047): L<<548.0,0.0>--<547.0,170.0>>
 * Gbreve (U+011E): L<<548.0,0.0>--<547.0,170.0>>
 * Gdotaccent (U+0120): L<<548.0,0.0>--<547.0,170.0>>
 * d (U+0064): L<<435.0,0.0>--<434.0,159.0>>
 * dcaron (U+010F): L<<435.0,0.0>--<434.0,159.0>>
 * dcroat (U+0111): L<<435.0,0.0>--<434.0,159.0>>
 * dong (U+20AB): L<<435.0,0.0>--<434.0,159.0>>
 * eng (U+014B): L<<185.0,528.0>--<186.0,352.0>>
 * m (U+006D): L<<183.0,528.0>--<184.0,352.0>>
 * n (U+006E): L<<185.0,528.0>--<186.0,352.0>> and 8 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[7] BricolageGrotesque10pt-ExtraBold.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'ATLR' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Bricolage Grotesque 10pt ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: at	Contours detected: 3	Expected: 2
	- Glyph name: brokenbar	Contours detected: 1	Expected: 2
	- Glyph name: copyright	Contours detected: 2	Expected: 3
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: Uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2
	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2
	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2 
	- And 24 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:
	* dollar (U+0024): X=264.0,Y=658.0 (should be at cap-height 660?)
	* dollar (U+0024): X=366.0,Y=659.0 (should be at cap-height 660?)
	* dollar (U+0024): X=365.0,Y=2.0 (should be at baseline 0?)
	* percent (U+0025): X=362.5,Y=658.0 (should be at cap-height 660?)
	* percent (U+0025): X=629.5,Y=-1.5 (should be at baseline 0?)
	* ampersand (U+0026): X=100.5,Y=2.0 (should be at baseline 0?)
	* three (U+0033): X=55.0,Y=661.0 (should be at cap-height 660?)
	* three (U+0033): X=531.0,Y=661.0 (should be at cap-height 660?)
	* four (U+0034): X=246.0,Y=661.0 (should be at cap-height 660?)
	* four (U+0034): X=526.0,Y=661.0 (should be at cap-height 660?) and 60 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * ae (U+00E6): L<<903.0,232.0>--<549.0,229.0>>
 * e (U+0065): L<<552.0,232.0>--<187.0,229.0>>
 * eacute (U+00E9): L<<552.0,232.0>--<187.0,229.0>>
 * ecaron (U+011B): L<<552.0,232.0>--<187.0,229.0>>
 * ecircumflex (U+00EA): L<<552.0,232.0>--<187.0,229.0>>
 * edieresis (U+00EB): L<<552.0,232.0>--<187.0,229.0>>
 * edotaccent (U+0117): L<<552.0,232.0>--<187.0,229.0>>
 * egrave (U+00E8): L<<552.0,232.0>--<187.0,229.0>>
 * emacron (U+0113): L<<552.0,232.0>--<187.0,229.0>>
 * eogonek (U+0119): L<<552.0,232.0>--<187.0,229.0>> and 10 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[11] BricolageGrotesque10pt-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check name table: FONT_FAMILY_NAME entries. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/familyname">com.google.fonts/check/name/familyname</a>)</summary><div>


* 🔥 **FAIL** Entry [FONT_FAMILY_NAME(1):WINDOWS(3)] on the "name" table: Expected "Bricolage Grotesque 10pt" but got "Bricolage Grotesque 10pt Bricolage Grotesque 10pt Regular". [code: mismatch]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: TYPOGRAPHIC_FAMILY_NAME entries. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/typographicfamilyname">com.google.fonts/check/name/typographicfamilyname</a>)</summary><div>


* 🔥 **FAIL** Font style is "Bold" and, for that reason, it is not expected to have a [TYPOGRAPHIC_FAMILY_NAME(16):WINDOWS(3)] entry! [code: ribbi]
</div></details><details><summary>🔥 <b>FAIL:</b> Does full font name begin with the font family name? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/name.html#com.google.fonts/check/name/match_familyname_fullfont">com.google.fonts/check/name/match_familyname_fullfont</a>)</summary><div>


* 🔥 **FAIL** On the 'name' table, the full font name (NameID 4 - FULL_FONT_NAME: 'Bricolage Grotesque 10pt Bricolage Grotesque 10pt Regular') does not begin with font family name (NameID 1 - FONT_FAMILY_NAME: 'Bricolage Grotesque 10pt Bold') [code: does-not]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'ATLR' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Bricolage Grotesque 10pt Bricolage Grotesque 10pt Regular' / SUBFAMILY_NAME = 'Bold'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: at	Contours detected: 3	Expected: 2
	- Glyph name: brokenbar	Contours detected: 1	Expected: 2
	- Glyph name: copyright	Contours detected: 2	Expected: 3
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: Uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2
	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2
	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2 
	- And 24 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:
	* dollar (U+0024): X=267.0,Y=659.0 (should be at cap-height 660?)
	* dollar (U+0024): X=359.0,Y=659.0 (should be at cap-height 660?)
	* dollar (U+0024): X=358.0,Y=1.0 (should be at baseline 0?)
	* three (U+0033): X=56.0,Y=661.0 (should be at cap-height 660?)
	* three (U+0033): X=522.0,Y=661.0 (should be at cap-height 660?)
	* four (U+0034): X=261.0,Y=661.0 (should be at cap-height 660?)
	* four (U+0034): X=511.0,Y=661.0 (should be at cap-height 660?)
	* seven (U+0037): X=22.0,Y=661.0 (should be at cap-height 660?)
	* seven (U+0037): X=490.0,Y=661.0 (should be at cap-height 660?)
	* j (U+006A): X=70.0,Y=-2.0 (should be at baseline 0?) and 42 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:
	* uni00B5 (U+00B5): L<<574.0,525.0>--<574.0,214.0>> -> L<<574.0,214.0>--<575.0,0.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * ae (U+00E6): L<<889.0,235.0>--<533.0,233.0>>
 * b (U+0062): L<<187.0,152.0>--<186.0,0.0>>
 * e (U+0065): L<<180.0,311.0>--<411.0,313.0>>
 * e (U+0065): L<<543.0,235.0>--<175.0,233.0>>
 * eacute (U+00E9): L<<180.0,311.0>--<411.0,313.0>>
 * eacute (U+00E9): L<<543.0,235.0>--<175.0,233.0>>
 * ecaron (U+011B): L<<180.0,311.0>--<411.0,313.0>>
 * ecaron (U+011B): L<<543.0,235.0>--<175.0,233.0>>
 * ecircumflex (U+00EA): L<<180.0,311.0>--<411.0,313.0>>
 * ecircumflex (U+00EA): L<<543.0,235.0>--<175.0,233.0>> and 38 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[8] BricolageGrotesque10ptCondensed-ExtraLight.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'ATLR' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Bricolage Grotesque 10pt Condensed ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: at	Contours detected: 3	Expected: 2
	- Glyph name: brokenbar	Contours detected: 1	Expected: 2
	- Glyph name: copyright	Contours detected: 2	Expected: 3
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: Uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2
	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2
	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2 
	- And 24 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:
	* G (U+0047): L<<396.0,308.0>--<396.0,233.0>> -> L<<396.0,233.0>--<397.0,0.0>>
	* Gbreve (U+011E): L<<396.0,308.0>--<396.0,233.0>> -> L<<396.0,233.0>--<397.0,0.0>>
	* Gdotaccent (U+0120): L<<396.0,308.0>--<396.0,233.0>> -> L<<396.0,233.0>--<397.0,0.0>>
	* uni0122 (U+0122): L<<396.0,308.0>--<396.0,233.0>> -> L<<396.0,233.0>--<397.0,0.0>> and uni20B2 (U+20B2): L<<366.0,307.0>--<366.0,233.0>> -> L<<366.0,233.0>--<367.0,5.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:
	* trademark (U+2122): L<<345.0,328.0>--<285.0,606.0>>/L<<285.0,606.0>--<285.0,328.0>> = 12.17918105252412 and trademark (U+2122): L<<465.0,328.0>--<465.0,606.0>>/L<<465.0,606.0>--<403.0,328.0>> = 12.572445004227527 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * Eng (U+014A): L<<128.0,608.0>--<133.0,0.0>>
 * Eng (U+014A): L<<393.0,52.0>--<388.0,660.0>>
 * G (U+0047): L<<396.0,233.0>--<397.0,0.0>>
 * Gbreve (U+011E): L<<396.0,233.0>--<397.0,0.0>>
 * Gdotaccent (U+0120): L<<396.0,233.0>--<397.0,0.0>>
 * M (U+004D): L<<129.0,609.0>--<134.0,0.0>>
 * M (U+004D): L<<527.0,0.0>--<532.0,608.0>>
 * N (U+004E): L<<128.0,608.0>--<133.0,0.0>>
 * N (U+004E): L<<393.0,52.0>--<388.0,660.0>>
 * Nacute (U+0143): L<<128.0,608.0>--<133.0,0.0>> and 13 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[9] BricolageGrotesque48ptCondensed-Medium.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'ATLR' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Bricolage Grotesque 48pt Condensed Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: at	Contours detected: 3	Expected: 2
	- Glyph name: brokenbar	Contours detected: 1	Expected: 2
	- Glyph name: copyright	Contours detected: 2	Expected: 3
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: Uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2
	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2
	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2 
	- And 24 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:
	* percent (U+0025): X=75.0,Y=661.0 (should be at cap-height 660?)
	* ampersand (U+0026): X=445.0,Y=-0.5 (should be at baseline 0?)
	* four (U+0034): X=159.0,Y=661.0 (should be at cap-height 660?)
	* four (U+0034): X=329.0,Y=661.0 (should be at cap-height 660?)
	* Q (U+0051): X=144.0,Y=2.0 (should be at baseline 0?)
	* bracketleft (U+005B): X=133.0,Y=1.0 (should be at baseline 0?)
	* bracketleft (U+005B): X=239.0,Y=1.0 (should be at baseline 0?)
	* bracketright (U+005D): X=0.0,Y=1.0 (should be at baseline 0?)
	* bracketright (U+005D): X=107.0,Y=1.0 (should be at baseline 0?)
	* a (U+0061): X=118.5,Y=530.0 (should be at x-height 528?) and 44 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:
	* G (U+0047): L<<351.0,330.0>--<351.0,236.0>> -> L<<351.0,236.0>--<352.0,0.0>>
	* Gbreve (U+011E): L<<351.0,330.0>--<351.0,236.0>> -> L<<351.0,236.0>--<352.0,0.0>>
	* Gdotaccent (U+0120): L<<351.0,330.0>--<351.0,236.0>> -> L<<351.0,236.0>--<352.0,0.0>>
	* b (U+0062): L<<27.0,0.0>--<29.0,253.0>> -> L<<29.0,253.0>--<29.0,680.0>>
	* d (U+0064): L<<329.0,680.0>--<328.0,251.0>> -> L<<328.0,251.0>--<329.0,0.0>>
	* dcaron (U+010F): L<<329.0,680.0>--<328.0,251.0>> -> L<<328.0,251.0>--<329.0,0.0>>
	* dcroat (U+0111): L<<329.0,565.0>--<328.0,251.0>> -> L<<328.0,251.0>--<329.0,0.0>>
	* dong (U+20AB): L<<329.0,565.0>--<328.0,251.0>> -> L<<328.0,251.0>--<329.0,0.0>>
	* eng (U+014B): L<<29.0,0.0>--<29.0,292.0>> -> L<<29.0,292.0>--<27.0,528.0>>
	* h (U+0068): L<<29.0,0.0>--<29.0,281.0>> -> L<<29.0,281.0>--<27.0,680.0>> and 36 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:
	* trademark (U+2122): L<<312.0,328.0>--<276.0,571.0>>/L<<276.0,571.0>--<276.0,328.0>> = 8.426969021480636 and trademark (U+2122): L<<419.0,328.0>--<419.0,571.0>>/L<<419.0,571.0>--<383.0,328.0>> = 8.426969021480636 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * G (U+0047): L<<351.0,236.0>--<352.0,0.0>>
 * Gbreve (U+011E): L<<351.0,236.0>--<352.0,0.0>>
 * Gdotaccent (U+0120): L<<351.0,236.0>--<352.0,0.0>>
 * b (U+0062): L<<27.0,0.0>--<29.0,253.0>>
 * d (U+0064): L<<328.0,251.0>--<329.0,0.0>>
 * d (U+0064): L<<329.0,680.0>--<328.0,251.0>>
 * dcaron (U+010F): L<<328.0,251.0>--<329.0,0.0>>
 * dcaron (U+010F): L<<329.0,680.0>--<328.0,251.0>>
 * dcroat (U+0111): L<<328.0,251.0>--<329.0,0.0>>
 * dcroat (U+0111): L<<329.0,565.0>--<328.0,251.0>> and 48 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[6] BricolageGrotesque48pt-ExtraBold.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'ATLR' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Bricolage Grotesque 48pt ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: at	Contours detected: 3	Expected: 2
	- Glyph name: brokenbar	Contours detected: 1	Expected: 2
	- Glyph name: copyright	Contours detected: 2	Expected: 3
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: Uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2
	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2
	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2 
	- And 24 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * lira (U+20A4): L<<310.0,402.0>--<485.0,403.0>>
 * lira (U+20A4): L<<363.0,322.0>--<485.0,323.0>>
 * lira (U+20A4): L<<485.0,356.0>--<342.0,355.0>> and two (U+0032): L<<216.0,133.0>--<530.0,135.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[11] BricolageGrotesque48pt-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check name table: FONT_FAMILY_NAME entries. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/familyname">com.google.fonts/check/name/familyname</a>)</summary><div>


* 🔥 **FAIL** Entry [FONT_FAMILY_NAME(1):WINDOWS(3)] on the "name" table: Expected "Bricolage Grotesque 48pt" but got "Bricolage Grotesque 48pt Bricolage Grotesque 48pt Regular". [code: mismatch]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: TYPOGRAPHIC_FAMILY_NAME entries. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/typographicfamilyname">com.google.fonts/check/name/typographicfamilyname</a>)</summary><div>


* 🔥 **FAIL** Font style is "Bold" and, for that reason, it is not expected to have a [TYPOGRAPHIC_FAMILY_NAME(16):WINDOWS(3)] entry! [code: ribbi]
</div></details><details><summary>🔥 <b>FAIL:</b> Does full font name begin with the font family name? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/name.html#com.google.fonts/check/name/match_familyname_fullfont">com.google.fonts/check/name/match_familyname_fullfont</a>)</summary><div>


* 🔥 **FAIL** On the 'name' table, the full font name (NameID 4 - FULL_FONT_NAME: 'Bricolage Grotesque 48pt Bricolage Grotesque 48pt Regular') does not begin with font family name (NameID 1 - FONT_FAMILY_NAME: 'Bricolage Grotesque 48pt Bold') [code: does-not]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'ATLR' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Bricolage Grotesque 48pt Bricolage Grotesque 48pt Regular' / SUBFAMILY_NAME = 'Bold'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: at	Contours detected: 3	Expected: 2
	- Glyph name: brokenbar	Contours detected: 1	Expected: 2
	- Glyph name: copyright	Contours detected: 2	Expected: 3
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: Uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2
	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2
	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2 
	- And 24 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:
	* dollar (U+0024): X=231.0,Y=658.0 (should be at cap-height 660?)
	* dollar (U+0024): X=336.0,Y=2.0 (should be at baseline 0?)
	* three (U+0033): X=46.0,Y=661.0 (should be at cap-height 660?)
	* three (U+0033): X=513.0,Y=661.0 (should be at cap-height 660?)
	* four (U+0034): X=251.0,Y=661.0 (should be at cap-height 660?)
	* four (U+0034): X=487.0,Y=661.0 (should be at cap-height 660?)
	* five (U+0035): X=71.0,Y=661.0 (should be at cap-height 660?)
	* five (U+0035): X=505.0,Y=661.0 (should be at cap-height 660?)
	* seven (U+0037): X=12.0,Y=661.0 (should be at cap-height 660?)
	* seven (U+0037): X=476.0,Y=661.0 (should be at cap-height 660?) and 51 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:
	* G (U+0047): L<<614.0,333.0>--<614.0,214.0>> -> L<<614.0,214.0>--<614.0,0.0>>
	* Gbreve (U+011E): L<<614.0,333.0>--<614.0,214.0>> -> L<<614.0,214.0>--<614.0,0.0>>
	* Gdotaccent (U+0120): L<<614.0,333.0>--<614.0,214.0>> -> L<<614.0,214.0>--<614.0,0.0>>
	* b (U+0062): L<<38.0,0.0>--<39.0,199.0>> -> L<<39.0,199.0>--<38.0,695.0>>
	* d (U+0064): L<<530.0,695.0>--<530.0,196.0>> -> L<<530.0,196.0>--<530.0,0.0>>
	* dcaron (U+010F): L<<530.0,695.0>--<530.0,196.0>> -> L<<530.0,196.0>--<530.0,0.0>>
	* dcroat (U+0111): L<<530.0,564.0>--<530.0,196.0>> -> L<<530.0,196.0>--<530.0,0.0>>
	* dong (U+20AB): L<<530.0,564.0>--<530.0,196.0>> -> L<<530.0,196.0>--<530.0,0.0>>
	* eng (U+014B): L<<39.0,0.0>--<39.0,286.0>> -> L<<39.0,286.0>--<38.0,525.0>>
	* h (U+0068): L<<39.0,0.0>--<39.0,266.0>> -> L<<39.0,266.0>--<38.0,695.0>> and 36 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * b (U+0062): L<<38.0,0.0>--<39.0,199.0>>
 * b (U+0062): L<<39.0,199.0>--<38.0,695.0>>
 * eng (U+014B): L<<39.0,286.0>--<38.0,525.0>>
 * four (U+0034): L<<16.0,125.0>--<15.0,263.0>>
 * h (U+0068): L<<39.0,266.0>--<38.0,695.0>>
 * lira (U+20A4): L<<293.0,405.0>--<473.0,406.0>>
 * lira (U+20A4): L<<346.0,325.0>--<473.0,326.0>>
 * lira (U+20A4): L<<473.0,359.0>--<324.0,358.0>>
 * m (U+006D): L<<39.0,277.0>--<38.0,525.0>>
 * n (U+006E): L<<39.0,286.0>--<38.0,525.0>> and 14 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[9] BricolageGrotesque48ptCondensed-Regular.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'ATLR' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Bricolage Grotesque 48pt Condensed' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: at	Contours detected: 3	Expected: 2
	- Glyph name: brokenbar	Contours detected: 1	Expected: 2
	- Glyph name: copyright	Contours detected: 2	Expected: 3
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: Uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2
	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2
	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2 
	- And 24 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:
	* dollar (U+0024): X=139.0,Y=-2.0 (should be at baseline 0?)
	* dollar (U+0024): X=193.0,Y=-2.0 (should be at baseline 0?)
	* ampersand (U+0026): X=424.5,Y=-0.5 (should be at baseline 0?)
	* four (U+0034): X=164.0,Y=661.0 (should be at cap-height 660?)
	* four (U+0034): X=309.0,Y=661.0 (should be at cap-height 660?)
	* Q (U+0051): X=136.5,Y=0.5 (should be at baseline 0?)
	* a (U+0061): X=112.0,Y=529.0 (should be at x-height 528?)
	* h (U+0068): X=117.0,Y=526.0 (should be at x-height 528?)
	* t (U+0074): X=200.0,Y=1.0 (should be at baseline 0?)
	* copyright (U+00A9): X=282.0,Y=1.0 (should be at baseline 0?) and 81 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:
	* G (U+0047): L<<330.0,327.0>--<330.0,239.0>> -> L<<330.0,239.0>--<331.0,0.0>>
	* Gbreve (U+011E): L<<330.0,327.0>--<330.0,239.0>> -> L<<330.0,239.0>--<331.0,0.0>>
	* Gdotaccent (U+0120): L<<330.0,327.0>--<330.0,239.0>> -> L<<330.0,239.0>--<331.0,0.0>>
	* b (U+0062): L<<30.0,0.0>--<32.0,254.0>> -> L<<32.0,254.0>--<32.0,680.0>>
	* d (U+0064): L<<306.0,680.0>--<305.0,251.0>> -> L<<305.0,251.0>--<306.0,0.0>>
	* dcaron (U+010F): L<<306.0,680.0>--<305.0,251.0>> -> L<<305.0,251.0>--<306.0,0.0>>
	* dcroat (U+0111): L<<306.0,566.0>--<305.0,251.0>> -> L<<305.0,251.0>--<306.0,0.0>>
	* dong (U+20AB): L<<306.0,566.0>--<305.0,251.0>> -> L<<305.0,251.0>--<306.0,0.0>>
	* eng (U+014B): L<<32.0,0.0>--<32.0,281.0>> -> L<<32.0,281.0>--<30.0,528.0>>
	* h (U+0068): L<<32.0,0.0>--<32.0,273.0>> -> L<<32.0,273.0>--<30.0,680.0>> and 36 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:
	* trademark (U+2122): L<<283.0,328.0>--<248.0,583.0>>/L<<248.0,583.0>--<248.0,328.0>> = 7.815293546766871 and trademark (U+2122): L<<382.0,328.0>--<382.0,583.0>>/L<<382.0,583.0>--<347.0,328.0>> = 7.815293546766871 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * G (U+0047): L<<330.0,239.0>--<331.0,0.0>>
 * Gbreve (U+011E): L<<330.0,239.0>--<331.0,0.0>>
 * Gdotaccent (U+0120): L<<330.0,239.0>--<331.0,0.0>>
 * b (U+0062): L<<30.0,0.0>--<32.0,254.0>>
 * d (U+0064): L<<305.0,251.0>--<306.0,0.0>>
 * d (U+0064): L<<306.0,680.0>--<305.0,251.0>>
 * dcaron (U+010F): L<<305.0,251.0>--<306.0,0.0>>
 * dcaron (U+010F): L<<306.0,680.0>--<305.0,251.0>>
 * dcroat (U+0111): L<<305.0,251.0>--<306.0,0.0>>
 * dcroat (U+0111): L<<306.0,566.0>--<305.0,251.0>> and 47 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[8] BricolageGrotesque-ExtraLight.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'ATLR' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Bricolage Grotesque ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: at	Contours detected: 3	Expected: 2
	- Glyph name: brokenbar	Contours detected: 1	Expected: 2
	- Glyph name: copyright	Contours detected: 2	Expected: 3
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: Uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2
	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2
	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2 
	- And 24 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:
	* exclam (U+0021): X=67.0,Y=661.0 (should be at cap-height 660?)
	* exclam (U+0021): X=143.0,Y=661.0 (should be at cap-height 660?)
	* dollar (U+0024): X=274.0,Y=661.0 (should be at cap-height 660?)
	* ampersand (U+0026): X=607.0,Y=2.0 (should be at baseline 0?)
	* four (U+0034): X=335.0,Y=661.0 (should be at cap-height 660?)
	* four (U+0034): X=434.0,Y=661.0 (should be at cap-height 660?)
	* asciicircum (U+005E): X=218.0,Y=662.0 (should be at cap-height 660?)
	* asciicircum (U+005E): X=290.0,Y=662.0 (should be at cap-height 660?)
	* g (U+0067): X=281.0,Y=512.0 (should be at x-height 511?)
	* g (U+0067): X=519.0,Y=512.0 (should be at x-height 511?) and 29 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:
	* G (U+0047): L<<600.0,315.0>--<600.0,226.0>> -> L<<600.0,226.0>--<601.0,0.0>>
	* Gbreve (U+011E): L<<600.0,315.0>--<600.0,226.0>> -> L<<600.0,226.0>--<601.0,0.0>>
	* Gdotaccent (U+0120): L<<600.0,315.0>--<600.0,226.0>> -> L<<600.0,226.0>--<601.0,0.0>>
	* b (U+0062): L<<74.0,0.0>--<75.0,256.0>> -> L<<75.0,256.0>--<74.0,683.0>>
	* d (U+0064): L<<492.0,683.0>--<491.0,252.0>> -> L<<491.0,252.0>--<492.0,0.0>>
	* dcaron (U+010F): L<<492.0,683.0>--<491.0,252.0>> -> L<<491.0,252.0>--<492.0,0.0>>
	* dcroat (U+0111): L<<492.0,582.0>--<491.0,252.0>> -> L<<491.0,252.0>--<492.0,0.0>>
	* dong (U+20AB): L<<492.0,582.0>--<491.0,252.0>> -> L<<491.0,252.0>--<492.0,0.0>>
	* eng (U+014B): L<<75.0,0.0>--<75.0,286.0>> -> L<<75.0,286.0>--<74.0,511.0>>
	* h (U+0068): L<<75.0,0.0>--<75.0,266.0>> -> L<<75.0,266.0>--<74.0,683.0>> and 36 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * Eng (U+014A): L<<135.0,597.0>--<138.0,0.0>>
 * Eng (U+014A): L<<545.0,67.0>--<541.0,660.0>>
 * G (U+0047): L<<600.0,226.0>--<601.0,0.0>>
 * Gbreve (U+011E): L<<600.0,226.0>--<601.0,0.0>>
 * Gdotaccent (U+0120): L<<600.0,226.0>--<601.0,0.0>>
 * M (U+004D): L<<136.0,604.0>--<138.0,0.0>>
 * M (U+004D): L<<684.0,0.0>--<687.0,603.0>>
 * N (U+004E): L<<135.0,597.0>--<138.0,0.0>>
 * N (U+004E): L<<545.0,67.0>--<541.0,660.0>>
 * Nacute (U+0143): L<<135.0,597.0>--<138.0,0.0>> and 46 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[9] BricolageGrotesque10ptCondensed-Regular.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'ATLR' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Bricolage Grotesque 10pt Condensed' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: at	Contours detected: 3	Expected: 2
	- Glyph name: brokenbar	Contours detected: 1	Expected: 2
	- Glyph name: copyright	Contours detected: 2	Expected: 3
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: Uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2
	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2
	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2 
	- And 24 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:
	* dollar (U+0024): X=195.0,Y=2.0 (should be at baseline 0?)
	* dollar (U+0024): X=194.0,Y=661.0 (should be at cap-height 660?)
	* dollar (U+0024): X=249.0,Y=662.0 (should be at cap-height 660?)
	* four (U+0034): X=193.0,Y=661.0 (should be at cap-height 660?)
	* four (U+0034): X=340.0,Y=661.0 (should be at cap-height 660?)
	* j (U+006A): X=76.0,Y=1.0 (should be at baseline 0?)
	* p (U+0070): X=63.0,Y=527.0 (should be at x-height 528?)
	* p (U+0070): X=137.0,Y=527.0 (should be at x-height 528?)
	* q (U+0071): X=309.0,Y=527.0 (should be at x-height 528?)
	* q (U+0071): X=383.0,Y=527.0 (should be at x-height 528?) and 85 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:
	* G (U+0047): L<<427.0,317.0>--<427.0,230.0>> -> L<<427.0,230.0>--<428.0,0.0>>
	* Gbreve (U+011E): L<<427.0,317.0>--<427.0,230.0>> -> L<<427.0,230.0>--<428.0,0.0>>
	* Gdotaccent (U+0120): L<<427.0,317.0>--<427.0,230.0>> -> L<<427.0,230.0>--<428.0,0.0>>
	* uni0122 (U+0122): L<<427.0,317.0>--<427.0,230.0>> -> L<<427.0,230.0>--<428.0,0.0>>
	* uni20B2 (U+20B2): L<<398.0,316.0>--<398.0,231.0>> -> L<<398.0,231.0>--<399.0,5.0>> and yen (U+00A5): L<<35.0,211.0>--<180.0,211.0>> -> L<<180.0,211.0>--<180.0,211.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:
	* trademark (U+2122): L<<367.0,328.0>--<312.0,585.0>>/L<<312.0,585.0>--<312.0,328.0>> = 12.079530986614987 and trademark (U+2122): L<<491.0,328.0>--<491.0,585.0>>/L<<491.0,585.0>--<436.0,328.0>> = 12.079530986614987 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * G (U+0047): L<<427.0,230.0>--<428.0,0.0>>
 * Gbreve (U+011E): L<<427.0,230.0>--<428.0,0.0>>
 * Gdotaccent (U+0120): L<<427.0,230.0>--<428.0,0.0>>
 * three (U+0033): L<<252.0,584.0>--<38.0,583.0>>
 * threeeighths (U+215C): L<<166.0,640.0>--<31.0,639.0>>
 * threequarters (U+00BE): L<<166.0,640.0>--<31.0,639.0>>
 * two (U+0032): L<<128.0,76.0>--<368.0,77.0>>
 * uni00B3 (U+00B3): L<<166.0,610.0>--<31.0,609.0>>
 * uni0122 (U+0122): L<<427.0,230.0>--<428.0,0.0>>
 * uni2083 (U+2083): L<<166.0,130.0>--<31.0,129.0>> and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[8] BricolageGrotesque10ptCondensed-Medium.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'ATLR' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Bricolage Grotesque 10pt Condensed Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: at	Contours detected: 3	Expected: 2
	- Glyph name: brokenbar	Contours detected: 1	Expected: 2
	- Glyph name: copyright	Contours detected: 2	Expected: 3
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: Uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2
	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2
	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2 
	- And 24 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:
	* G (U+0047): L<<443.0,322.0>--<443.0,229.0>> -> L<<443.0,229.0>--<443.0,0.0>>
	* Gbreve (U+011E): L<<443.0,322.0>--<443.0,229.0>> -> L<<443.0,229.0>--<443.0,0.0>>
	* Gdotaccent (U+0120): L<<443.0,322.0>--<443.0,229.0>> -> L<<443.0,229.0>--<443.0,0.0>>
	* uni0122 (U+0122): L<<443.0,322.0>--<443.0,229.0>> -> L<<443.0,229.0>--<443.0,0.0>> and uni20B2 (U+20B2): L<<414.0,320.0>--<414.0,229.0>> -> L<<414.0,229.0>--<415.0,5.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:
	* trademark (U+2122): L<<378.0,328.0>--<326.0,575.0>>/L<<326.0,575.0>--<326.0,328.0>> = 11.888658039627968 and trademark (U+2122): L<<505.0,328.0>--<505.0,575.0>>/L<<505.0,575.0>--<452.0,328.0>> = 12.110597767654415 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * d (U+0064): L<<320.0,0.0>--<321.0,129.0>>
 * dcaron (U+010F): L<<320.0,0.0>--<321.0,129.0>>
 * dcroat (U+0111): L<<320.0,0.0>--<321.0,129.0>>
 * dong (U+20AB): L<<320.0,0.0>--<321.0,129.0>>
 * r (U+0072): L<<147.0,528.0>--<146.0,351.0>>
 * racute (U+0155): L<<147.0,528.0>--<146.0,351.0>>
 * rcaron (U+0159): L<<147.0,528.0>--<146.0,351.0>>
 * three (U+0033): L<<253.0,572.0>--<36.0,571.0>>
 * threeeighths (U+215C): L<<167.0,632.0>--<29.0,631.0>>
 * threequarters (U+00BE): L<<167.0,632.0>--<29.0,631.0>> and 8 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[8] BricolageGrotesque48pt-ExtraLight.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'ATLR' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Bricolage Grotesque 48pt ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: at	Contours detected: 3	Expected: 2
	- Glyph name: brokenbar	Contours detected: 1	Expected: 2
	- Glyph name: copyright	Contours detected: 2	Expected: 3
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: Uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2
	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2
	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2 
	- And 24 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:
	* dollar (U+0024): X=260.0,Y=1.0 (should be at baseline 0?)
	* dollar (U+0024): X=260.0,Y=659.0 (should be at cap-height 660?)
	* dollar (U+0024): X=302.0,Y=658.0 (should be at cap-height 660?)
	* dollar (U+0024): X=301.0,Y=1.0 (should be at baseline 0?)
	* ampersand (U+0026): X=562.5,Y=2.0 (should be at baseline 0?)
	* four (U+0034): X=334.0,Y=661.0 (should be at cap-height 660?)
	* four (U+0034): X=431.0,Y=661.0 (should be at cap-height 660?)
	* question (U+003F): X=100.5,Y=658.5 (should be at cap-height 660?)
	* k (U+006B): X=379.0,Y=512.0 (should be at x-height 510?)
	* k (U+006B): X=438.0,Y=512.0 (should be at x-height 510?) and 46 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:
	* G (U+0047): L<<589.0,319.0>--<589.0,224.0>> -> L<<589.0,224.0>--<591.0,0.0>>
	* Gbreve (U+011E): L<<589.0,319.0>--<589.0,224.0>> -> L<<589.0,224.0>--<591.0,0.0>>
	* Gdotaccent (U+0120): L<<589.0,319.0>--<589.0,224.0>> -> L<<589.0,224.0>--<591.0,0.0>>
	* b (U+0062): L<<50.0,0.0>--<52.0,262.0>> -> L<<52.0,262.0>--<50.0,670.0>>
	* d (U+0064): L<<480.0,670.0>--<477.0,248.0>> -> L<<477.0,248.0>--<481.0,0.0>>
	* dcaron (U+010F): L<<480.0,670.0>--<477.0,248.0>> -> L<<477.0,248.0>--<481.0,0.0>>
	* dcroat (U+0111): L<<479.0,564.0>--<477.0,248.0>> -> L<<477.0,248.0>--<481.0,0.0>>
	* dong (U+20AB): L<<479.0,564.0>--<477.0,248.0>> -> L<<477.0,248.0>--<481.0,0.0>>
	* eng (U+014B): L<<52.0,0.0>--<52.0,218.0>> -> L<<52.0,218.0>--<50.0,510.0>>
	* h (U+0068): L<<52.0,0.0>--<52.0,199.0>> -> L<<52.0,199.0>--<50.0,670.0>> and 37 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * b (U+0062): L<<50.0,0.0>--<52.0,262.0>>
 * b (U+0062): L<<52.0,262.0>--<50.0,670.0>>
 * d (U+0064): L<<480.0,670.0>--<477.0,248.0>>
 * dcaron (U+010F): L<<480.0,670.0>--<477.0,248.0>>
 * dcroat (U+0111): L<<479.0,564.0>--<477.0,248.0>>
 * dong (U+20AB): L<<479.0,564.0>--<477.0,248.0>>
 * eng (U+014B): L<<52.0,218.0>--<50.0,510.0>>
 * h (U+0068): L<<52.0,199.0>--<50.0,670.0>>
 * hbar (U+0127): L<<56.0,199.0>--<54.0,564.0>>
 * lira (U+20A4): L<<75.0,332.0>--<193.0,333.0>> and 35 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[8] BricolageGrotesque48ptCondensed-Light.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'ATLR' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Bricolage Grotesque 48pt Condensed Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: at	Contours detected: 3	Expected: 2
	- Glyph name: brokenbar	Contours detected: 1	Expected: 2
	- Glyph name: copyright	Contours detected: 2	Expected: 3
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: Uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2
	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2
	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2 
	- And 24 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:
	* G (U+0047): L<<309.0,325.0>--<309.0,243.0>> -> L<<309.0,243.0>--<311.0,0.0>>
	* Gbreve (U+011E): L<<309.0,325.0>--<309.0,243.0>> -> L<<309.0,243.0>--<311.0,0.0>>
	* Gdotaccent (U+0120): L<<309.0,325.0>--<309.0,243.0>> -> L<<309.0,243.0>--<311.0,0.0>>
	* b (U+0062): L<<32.0,0.0>--<36.0,255.0>> -> L<<36.0,255.0>--<36.0,680.0>>
	* d (U+0064): L<<284.0,680.0>--<282.0,252.0>> -> L<<282.0,252.0>--<284.0,0.0>>
	* dcaron (U+010F): L<<284.0,680.0>--<282.0,252.0>> -> L<<282.0,252.0>--<284.0,0.0>>
	* dcroat (U+0111): L<<283.0,568.0>--<282.0,252.0>> -> L<<282.0,252.0>--<284.0,0.0>>
	* dong (U+20AB): L<<283.0,568.0>--<282.0,252.0>> -> L<<282.0,252.0>--<284.0,0.0>>
	* eng (U+014B): L<<35.0,0.0>--<35.0,271.0>> -> L<<35.0,271.0>--<32.0,528.0>>
	* h (U+0068): L<<35.0,0.0>--<35.0,266.0>> -> L<<35.0,266.0>--<32.0,680.0>> and 37 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:
	* trademark (U+2122): L<<251.0,656.0>--<285.0,397.0>>/L<<285.0,397.0>--<313.0,656.0>> = 13.648864603177843
	* trademark (U+2122): L<<254.0,328.0>--<220.0,594.0>>/L<<220.0,594.0>--<220.0,328.0>> = 7.284023654416849 and trademark (U+2122): L<<346.0,328.0>--<346.0,594.0>>/L<<346.0,594.0>--<311.0,328.0>> = 7.495857639729836 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * G (U+0047): L<<309.0,243.0>--<311.0,0.0>>
 * Gbreve (U+011E): L<<309.0,243.0>--<311.0,0.0>>
 * Gdotaccent (U+0120): L<<309.0,243.0>--<311.0,0.0>>
 * d (U+0064): L<<282.0,252.0>--<284.0,0.0>>
 * d (U+0064): L<<284.0,680.0>--<282.0,252.0>>
 * dcaron (U+010F): L<<282.0,252.0>--<284.0,0.0>>
 * dcaron (U+010F): L<<284.0,680.0>--<282.0,252.0>>
 * dcroat (U+0111): L<<282.0,252.0>--<284.0,0.0>>
 * dcroat (U+0111): L<<283.0,568.0>--<282.0,252.0>>
 * dong (U+20AB): L<<282.0,252.0>--<284.0,0.0>> and 13 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[8] BricolageGrotesque10pt-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Space and non-breaking space have the same width? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/hmtx.html#com.google.fonts/check/whitespace_widths">com.google.fonts/check/whitespace_widths</a>)</summary><div>


* 🔥 **FAIL** Space and non-breaking space have differing width: The space glyph named space is 263 font units wide, non-breaking space named (uni00A0) is 262 font units wide, and both should be positive and the same. GlyphsApp has "Sidebearing arithmetic" (https://glyphsapp.com/tutorials/spacing) which allows you to set the non-breaking space width to always equal the space width. [code: different-widths]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'ATLR' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Bricolage Grotesque 10pt Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: at	Contours detected: 3	Expected: 2
	- Glyph name: brokenbar	Contours detected: 1	Expected: 2
	- Glyph name: copyright	Contours detected: 2	Expected: 3
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: Uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2
	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2
	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2 
	- And 24 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:
	* uni00B5 (U+00B5): L<<498.0,515.0>--<498.0,216.0>> -> L<<498.0,216.0>--<501.0,0.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * M (U+004D): L<<158.0,586.0>--<163.0,0.0>>
 * Uogonek (U+0172): L<<161.0,660.0>--<160.0,251.0>>
 * ae (U+00E6): L<<474.0,302.0>--<763.0,304.0>>
 * ae (U+00E6): L<<834.0,249.0>--<471.0,246.0>>
 * e (U+0065): L<<505.0,249.0>--<129.0,246.0>>
 * eacute (U+00E9): L<<505.0,249.0>--<129.0,246.0>>
 * ecaron (U+011B): L<<505.0,249.0>--<129.0,246.0>>
 * ecircumflex (U+00EA): L<<505.0,249.0>--<129.0,246.0>>
 * edieresis (U+00EB): L<<505.0,249.0>--<129.0,246.0>>
 * edotaccent (U+0117): L<<505.0,249.0>--<129.0,246.0>> and 17 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[8] BricolageGrotesque48pt-Light.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'ATLR' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Bricolage Grotesque 48pt Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: at	Contours detected: 3	Expected: 2
	- Glyph name: brokenbar	Contours detected: 1	Expected: 2
	- Glyph name: copyright	Contours detected: 2	Expected: 3
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: Uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2
	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2
	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2 
	- And 24 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:
	* dollar (U+0024): X=254.0,Y=1.0 (should be at baseline 0?)
	* dollar (U+0024): X=254.0,Y=659.0 (should be at cap-height 660?)
	* dollar (U+0024): X=309.0,Y=658.0 (should be at cap-height 660?)
	* dollar (U+0024): X=308.0,Y=1.0 (should be at baseline 0?)
	* percent (U+0025): X=771.5,Y=1.5 (should be at baseline 0?)
	* ampersand (U+0026): X=567.0,Y=0.5 (should be at baseline 0?)
	* four (U+0034): X=317.0,Y=661.0 (should be at cap-height 660?)
	* four (U+0034): X=442.0,Y=661.0 (should be at cap-height 660?)
	* k (U+006B): X=372.0,Y=515.0 (should be at x-height 513?)
	* k (U+006B): X=452.0,Y=515.0 (should be at x-height 513?) and 43 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:
	* G (U+0047): L<<594.0,322.0>--<594.0,222.0>> -> L<<594.0,222.0>--<596.0,0.0>>
	* Gbreve (U+011E): L<<594.0,322.0>--<594.0,222.0>> -> L<<594.0,222.0>--<596.0,0.0>>
	* Gdotaccent (U+0120): L<<594.0,322.0>--<594.0,222.0>> -> L<<594.0,222.0>--<596.0,0.0>>
	* b (U+0062): L<<48.0,0.0>--<49.0,249.0>> -> L<<49.0,249.0>--<48.0,675.0>>
	* d (U+0064): L<<490.0,675.0>--<488.0,238.0>> -> L<<488.0,238.0>--<491.0,0.0>>
	* dcaron (U+010F): L<<490.0,675.0>--<488.0,238.0>> -> L<<488.0,238.0>--<491.0,0.0>>
	* dcroat (U+0111): L<<489.0,564.0>--<488.0,238.0>> -> L<<488.0,238.0>--<491.0,0.0>>
	* dong (U+20AB): L<<489.0,564.0>--<488.0,238.0>> -> L<<488.0,238.0>--<491.0,0.0>>
	* eng (U+014B): L<<49.0,0.0>--<49.0,232.0>> -> L<<49.0,232.0>--<48.0,513.0>>
	* h (U+0068): L<<49.0,0.0>--<49.0,212.0>> -> L<<49.0,212.0>--<48.0,675.0>> and 37 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * Uogonek (U+0172): L<<127.0,660.0>--<126.0,258.0>>
 * b (U+0062): L<<48.0,0.0>--<49.0,249.0>>
 * b (U+0062): L<<49.0,249.0>--<48.0,675.0>>
 * d (U+0064): L<<490.0,675.0>--<488.0,238.0>>
 * dcaron (U+010F): L<<490.0,675.0>--<488.0,238.0>>
 * dcroat (U+0111): L<<489.0,564.0>--<488.0,238.0>>
 * dong (U+20AB): L<<489.0,564.0>--<488.0,238.0>>
 * eng (U+014B): L<<49.0,232.0>--<48.0,513.0>>
 * h (U+0068): L<<49.0,212.0>--<48.0,675.0>>
 * hbar (U+0127): L<<54.0,212.0>--<53.0,564.0>> and 41 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[12] BricolageGrotesque48ptCondensed-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check name table: FONT_FAMILY_NAME entries. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/familyname">com.google.fonts/check/name/familyname</a>)</summary><div>


* 🔥 **FAIL** Entry [FONT_FAMILY_NAME(1):WINDOWS(3)] on the "name" table: Expected "Bricolage Grotesque 48pt Condensed" but got "Bricolage Grotesque 48pt Condensed Bricolage Grotesque 48pt Condensed Regular". [code: mismatch]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: TYPOGRAPHIC_FAMILY_NAME entries. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/typographicfamilyname">com.google.fonts/check/name/typographicfamilyname</a>)</summary><div>


* 🔥 **FAIL** Font style is "Bold" and, for that reason, it is not expected to have a [TYPOGRAPHIC_FAMILY_NAME(16):WINDOWS(3)] entry! [code: ribbi]
</div></details><details><summary>🔥 <b>FAIL:</b> Does full font name begin with the font family name? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/name.html#com.google.fonts/check/name/match_familyname_fullfont">com.google.fonts/check/name/match_familyname_fullfont</a>)</summary><div>


* 🔥 **FAIL** On the 'name' table, the full font name (NameID 4 - FULL_FONT_NAME: 'Bricolage Grotesque 48pt Condensed Bricolage Grotesque 48pt Condensed Regular') does not begin with font family name (NameID 1 - FONT_FAMILY_NAME: 'Bricolage Grotesque 48pt Condensed Bold') [code: does-not]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'ATLR' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Bricolage Grotesque 48pt Condensed Bricolage Grotesque 48pt Condensed Regular' / SUBFAMILY_NAME = 'Bold'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: at	Contours detected: 3	Expected: 2
	- Glyph name: brokenbar	Contours detected: 1	Expected: 2
	- Glyph name: copyright	Contours detected: 2	Expected: 3
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: Uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2
	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2
	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2 
	- And 24 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:
	* ampersand (U+0026): X=485.5,Y=-1.0 (should be at baseline 0?)
	* four (U+0034): X=149.0,Y=661.0 (should be at cap-height 660?)
	* four (U+0034): X=368.0,Y=661.0 (should be at cap-height 660?)
	* r (U+0072): X=277.0,Y=530.0 (should be at x-height 528?)
	* t (U+0074): X=57.5,Y=529.0 (should be at x-height 528?)
	* section (U+00A7): X=363.0,Y=-1.0 (should be at baseline 0?)
	* germandbls (U+00DF): X=218.0,Y=-0.5 (should be at baseline 0?)
	* atilde (U+00E3): X=246.5,Y=658.5 (should be at cap-height 660?)
	* eth (U+00F0): X=249.0,Y=-2.0 (should be at baseline 0?)
	* ntilde (U+00F1): X=249.5,Y=658.5 (should be at cap-height 660?) and 37 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:
	* G (U+0047): L<<392.0,335.0>--<392.0,229.0>> -> L<<392.0,229.0>--<393.0,0.0>>
	* Gbreve (U+011E): L<<392.0,335.0>--<392.0,229.0>> -> L<<392.0,229.0>--<393.0,0.0>>
	* Gdotaccent (U+0120): L<<392.0,335.0>--<392.0,229.0>> -> L<<392.0,229.0>--<393.0,0.0>>
	* b (U+0062): L<<22.0,0.0>--<22.0,250.0>> -> L<<22.0,250.0>--<22.0,680.0>>
	* d (U+0064): L<<374.0,680.0>--<374.0,249.0>> -> L<<374.0,249.0>--<374.0,0.0>>
	* dcaron (U+010F): L<<374.0,680.0>--<374.0,249.0>> -> L<<374.0,249.0>--<374.0,0.0>>
	* dcroat (U+0111): L<<374.0,562.0>--<374.0,249.0>> -> L<<374.0,249.0>--<374.0,0.0>>
	* dong (U+20AB): L<<374.0,562.0>--<374.0,249.0>> -> L<<374.0,249.0>--<374.0,0.0>>
	* eng (U+014B): L<<22.0,0.0>--<22.0,313.0>> -> L<<22.0,313.0>--<22.0,528.0>>
	* h (U+0068): L<<22.0,0.0>--<22.0,296.0>> -> L<<22.0,296.0>--<22.0,680.0>> and 36 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:
	* trademark (U+2122): L<<369.0,328.0>--<331.0,548.0>>/L<<331.0,548.0>--<331.0,328.0>> = 9.799848668867625 and trademark (U+2122): L<<492.0,328.0>--<492.0,548.0>>/L<<492.0,548.0>--<455.0,328.0>> = 9.546766921403826 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * G (U+0047): L<<303.0,0.0>--<304.0,192.0>>
 * G (U+0047): L<<392.0,229.0>--<393.0,0.0>>
 * Gbreve (U+011E): L<<303.0,0.0>--<304.0,192.0>>
 * Gbreve (U+011E): L<<392.0,229.0>--<393.0,0.0>>
 * Gdotaccent (U+0120): L<<303.0,0.0>--<304.0,192.0>>
 * Gdotaccent (U+0120): L<<392.0,229.0>--<393.0,0.0>>
 * q (U+0071): L<<374.0,276.0>--<375.0,-130.0>>
 * q (U+0071): L<<375.0,528.0>--<374.0,276.0>>
 * uni00B5 (U+00B5): L<<377.0,236.0>--<378.0,0.0>>
 * uni0122 (U+0122): L<<303.0,0.0>--<304.0,192.0>>
 * uni0122 (U+0122): L<<392.0,229.0>--<393.0,0.0>> and uni20B2 (U+20B2): L<<285.0,5.0>--<286.0,193.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[7] BricolageGrotesque-Bold.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'ATLR' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: at	Contours detected: 3	Expected: 2
	- Glyph name: brokenbar	Contours detected: 1	Expected: 2
	- Glyph name: copyright	Contours detected: 2	Expected: 3
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: Uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2
	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2
	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2 
	- And 24 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:
	* dollar (U+0024): X=254.0,Y=659.0 (should be at cap-height 660?)
	* dollar (U+0024): X=351.0,Y=658.0 (should be at cap-height 660?)
	* dollar (U+0024): X=350.0,Y=2.0 (should be at baseline 0?)
	* three (U+0033): X=52.0,Y=661.0 (should be at cap-height 660?)
	* three (U+0033): X=519.0,Y=661.0 (should be at cap-height 660?)
	* four (U+0034): X=257.0,Y=661.0 (should be at cap-height 660?)
	* four (U+0034): X=502.0,Y=661.0 (should be at cap-height 660?)
	* seven (U+0037): X=18.0,Y=661.0 (should be at cap-height 660?)
	* seven (U+0037): X=485.0,Y=661.0 (should be at cap-height 660?)
	* g (U+0067): X=434.0,Y=2.0 (should be at baseline 0?) and 82 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:
	* G (U+0047): L<<649.0,339.0>--<649.0,219.0>> -> L<<649.0,219.0>--<649.0,0.0>>
	* Gbreve (U+011E): L<<649.0,339.0>--<649.0,219.0>> -> L<<649.0,219.0>--<649.0,0.0>>
	* Gdotaccent (U+0120): L<<649.0,339.0>--<649.0,219.0>> -> L<<649.0,219.0>--<649.0,0.0>>
	* b (U+0062): L<<57.0,0.0>--<57.0,237.0>> -> L<<57.0,237.0>--<57.0,708.0>>
	* d (U+0064): L<<557.0,708.0>--<557.0,236.0>> -> L<<557.0,236.0>--<557.0,0.0>>
	* dcaron (U+010F): L<<557.0,708.0>--<557.0,236.0>> -> L<<557.0,236.0>--<557.0,0.0>>
	* dcroat (U+0111): L<<557.0,589.0>--<557.0,236.0>> -> L<<557.0,236.0>--<557.0,0.0>>
	* dong (U+20AB): L<<557.0,589.0>--<557.0,236.0>> -> L<<557.0,236.0>--<557.0,0.0>>
	* eng (U+014B): L<<57.0,0.0>--<57.0,307.0>> -> L<<57.0,307.0>--<57.0,525.0>>
	* h (U+0068): L<<57.0,0.0>--<57.0,307.0>> -> L<<57.0,307.0>--<57.0,708.0>> and 36 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * d (U+0064): L<<435.0,0.0>--<436.0,157.0>>
 * dcaron (U+010F): L<<435.0,0.0>--<436.0,157.0>>
 * dcroat (U+0111): L<<435.0,0.0>--<436.0,157.0>>
 * dong (U+20AB): L<<435.0,0.0>--<436.0,157.0>>
 * e (U+0065): L<<527.0,238.0>--<171.0,235.0>>
 * eacute (U+00E9): L<<527.0,238.0>--<171.0,235.0>>
 * ecaron (U+011B): L<<527.0,238.0>--<171.0,235.0>>
 * ecircumflex (U+00EA): L<<527.0,238.0>--<171.0,235.0>>
 * edieresis (U+00EB): L<<527.0,238.0>--<171.0,235.0>>
 * edotaccent (U+0117): L<<527.0,238.0>--<171.0,235.0>> and 26 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[8] BricolageGrotesque10pt-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Space and non-breaking space have the same width? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/hmtx.html#com.google.fonts/check/whitespace_widths">com.google.fonts/check/whitespace_widths</a>)</summary><div>


* 🔥 **FAIL** Space and non-breaking space have differing width: The space glyph named space is 255 font units wide, non-breaking space named (uni00A0) is 254 font units wide, and both should be positive and the same. GlyphsApp has "Sidebearing arithmetic" (https://glyphsapp.com/tutorials/spacing) which allows you to set the non-breaking space width to always equal the space width. [code: different-widths]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'ATLR' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Bricolage Grotesque 10pt' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: at	Contours detected: 3	Expected: 2
	- Glyph name: brokenbar	Contours detected: 1	Expected: 2
	- Glyph name: copyright	Contours detected: 2	Expected: 3
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: Uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2
	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2
	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2 
	- And 24 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:
	* uni00B5 (U+00B5): L<<517.0,517.0>--<517.0,215.0>> -> L<<517.0,215.0>--<519.0,0.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * ae (U+00E6): L<<490.0,304.0>--<762.0,306.0>>
 * ae (U+00E6): L<<848.0,245.0>--<486.0,243.0>>
 * e (U+0065): L<<144.0,305.0>--<429.0,307.0>>
 * e (U+0065): L<<515.0,245.0>--<140.0,243.0>>
 * eacute (U+00E9): L<<144.0,305.0>--<429.0,307.0>>
 * eacute (U+00E9): L<<515.0,245.0>--<140.0,243.0>>
 * ecaron (U+011B): L<<144.0,305.0>--<429.0,307.0>>
 * ecaron (U+011B): L<<515.0,245.0>--<140.0,243.0>>
 * ecircumflex (U+00EA): L<<144.0,305.0>--<429.0,307.0>>
 * ecircumflex (U+00EA): L<<515.0,245.0>--<140.0,243.0>> and 31 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[8] BricolageGrotesque10pt-SemiBold.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'ATLR' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Bricolage Grotesque 10pt SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: at	Contours detected: 3	Expected: 2
	- Glyph name: brokenbar	Contours detected: 1	Expected: 2
	- Glyph name: copyright	Contours detected: 2	Expected: 3
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: Uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2
	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2
	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2 
	- And 24 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:
	* dollar (U+0024): X=271.0,Y=2.0 (should be at baseline 0?)
	* dollar (U+0024): X=352.0,Y=659.0 (should be at cap-height 660?)
	* dollar (U+0024): X=351.0,Y=1.0 (should be at baseline 0?)
	* three (U+0033): X=57.0,Y=661.0 (should be at cap-height 660?)
	* three (U+0033): X=514.0,Y=661.0 (should be at cap-height 660?)
	* four (U+0034): X=276.0,Y=661.0 (should be at cap-height 660?)
	* four (U+0034): X=496.0,Y=661.0 (should be at cap-height 660?)
	* seven (U+0037): X=24.0,Y=661.0 (should be at cap-height 660?)
	* seven (U+0037): X=479.0,Y=661.0 (should be at cap-height 660?)
	* question (U+003F): X=103.5,Y=661.0 (should be at cap-height 660?) and 33 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:
	* uni00B5 (U+00B5): L<<555.0,523.0>--<555.0,214.0>> -> L<<555.0,214.0>--<556.0,0.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * ae (U+00E6): L<<522.0,309.0>--<761.0,311.0>>
 * ae (U+00E6): L<<875.0,239.0>--<517.0,236.0>>
 * b (U+0062): L<<177.0,147.0>--<178.0,0.0>>
 * e (U+0065): L<<168.0,309.0>--<417.0,311.0>>
 * e (U+0065): L<<533.0,239.0>--<163.0,236.0>>
 * eacute (U+00E9): L<<168.0,309.0>--<417.0,311.0>>
 * eacute (U+00E9): L<<533.0,239.0>--<163.0,236.0>>
 * ecaron (U+011B): L<<168.0,309.0>--<417.0,311.0>>
 * ecaron (U+011B): L<<533.0,239.0>--<163.0,236.0>>
 * ecircumflex (U+00EA): L<<168.0,309.0>--<417.0,311.0>> and 33 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[8] BricolageGrotesque48pt-Medium.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'ATLR' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Bricolage Grotesque 48pt Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: at	Contours detected: 3	Expected: 2
	- Glyph name: brokenbar	Contours detected: 1	Expected: 2
	- Glyph name: copyright	Contours detected: 2	Expected: 3
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: Uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2
	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2
	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2 
	- And 24 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:
	* dollar (U+0024): X=243.0,Y=659.0 (should be at cap-height 660?)
	* dollar (U+0024): X=322.0,Y=2.0 (should be at baseline 0?)
	* three (U+0033): X=49.0,Y=661.0 (should be at cap-height 660?)
	* three (U+0033): X=497.0,Y=661.0 (should be at cap-height 660?)
	* four (U+0034): X=284.0,Y=661.0 (should be at cap-height 660?)
	* four (U+0034): X=465.0,Y=661.0 (should be at cap-height 660?)
	* five (U+0035): X=77.0,Y=661.0 (should be at cap-height 660?)
	* five (U+0035): X=491.0,Y=661.0 (should be at cap-height 660?)
	* seven (U+0037): X=13.0,Y=661.0 (should be at cap-height 660?)
	* seven (U+0037): X=454.0,Y=661.0 (should be at cap-height 660?) and 63 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:
	* G (U+0047): L<<604.0,328.0>--<604.0,218.0>> -> L<<604.0,218.0>--<605.0,0.0>>
	* Gbreve (U+011E): L<<604.0,328.0>--<604.0,218.0>> -> L<<604.0,218.0>--<605.0,0.0>>
	* Gdotaccent (U+0120): L<<604.0,328.0>--<604.0,218.0>> -> L<<604.0,218.0>--<605.0,0.0>>
	* b (U+0062): L<<43.0,0.0>--<44.0,224.0>> -> L<<44.0,224.0>--<43.0,685.0>>
	* d (U+0064): L<<510.0,685.0>--<509.0,217.0>> -> L<<509.0,217.0>--<511.0,0.0>>
	* dcaron (U+010F): L<<510.0,685.0>--<509.0,217.0>> -> L<<509.0,217.0>--<511.0,0.0>>
	* dcroat (U+0111): L<<510.0,564.0>--<509.0,217.0>> -> L<<509.0,217.0>--<511.0,0.0>>
	* dong (U+20AB): L<<510.0,564.0>--<509.0,217.0>> -> L<<509.0,217.0>--<511.0,0.0>>
	* eng (U+014B): L<<44.0,0.0>--<44.0,259.0>> -> L<<44.0,259.0>--<43.0,519.0>>
	* h (U+0068): L<<44.0,0.0>--<44.0,239.0>> -> L<<44.0,239.0>--<43.0,685.0>> and 36 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * G (U+0047): L<<604.0,218.0>--<605.0,0.0>>
 * Gbreve (U+011E): L<<604.0,218.0>--<605.0,0.0>>
 * Gdotaccent (U+0120): L<<604.0,218.0>--<605.0,0.0>>
 * b (U+0062): L<<43.0,0.0>--<44.0,224.0>>
 * b (U+0062): L<<44.0,224.0>--<43.0,685.0>>
 * d (U+0064): L<<510.0,685.0>--<509.0,217.0>>
 * dcaron (U+010F): L<<510.0,685.0>--<509.0,217.0>>
 * dcroat (U+0111): L<<510.0,564.0>--<509.0,217.0>>
 * dong (U+20AB): L<<510.0,564.0>--<509.0,217.0>>
 * eng (U+014B): L<<44.0,259.0>--<43.0,519.0>> and 45 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[9] BricolageGrotesque48ptCondensed-ExtraLight.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'ATLR' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Bricolage Grotesque 48pt Condensed ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: at	Contours detected: 3	Expected: 2
	- Glyph name: brokenbar	Contours detected: 1	Expected: 2
	- Glyph name: copyright	Contours detected: 2	Expected: 3
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: Uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2
	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2
	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2 
	- And 24 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:
	* dollar (U+0024): X=128.0,Y=1.0 (should be at baseline 0?)
	* dollar (U+0024): X=127.0,Y=658.0 (should be at cap-height 660?)
	* dollar (U+0024): X=169.0,Y=658.0 (should be at cap-height 660?)
	* dollar (U+0024): X=168.0,Y=1.0 (should be at baseline 0?)
	* ampersand (U+0026): X=384.0,Y=-0.5 (should be at baseline 0?)
	* four (U+0034): X=174.0,Y=661.0 (should be at cap-height 660?)
	* four (U+0034): X=270.0,Y=661.0 (should be at cap-height 660?)
	* Q (U+0051): X=120.0,Y=-2.0 (should be at baseline 0?)
	* a (U+0061): X=62.5,Y=2.0 (should be at baseline 0?)
	* t (U+0074): X=175.0,Y=1.0 (should be at baseline 0?) and 74 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:
	* G (U+0047): L<<288.0,322.0>--<288.0,246.0>> -> L<<288.0,246.0>--<290.0,0.0>>
	* Gbreve (U+011E): L<<288.0,322.0>--<288.0,246.0>> -> L<<288.0,246.0>--<290.0,0.0>>
	* Gdotaccent (U+0120): L<<288.0,322.0>--<288.0,246.0>> -> L<<288.0,246.0>--<290.0,0.0>>
	* b (U+0062): L<<35.0,0.0>--<39.0,256.0>> -> L<<39.0,256.0>--<39.0,680.0>>
	* d (U+0064): L<<261.0,680.0>--<259.0,253.0>> -> L<<259.0,253.0>--<261.0,0.0>>
	* dcaron (U+010F): L<<261.0,680.0>--<259.0,253.0>> -> L<<259.0,253.0>--<261.0,0.0>>
	* dcroat (U+0111): L<<260.0,569.0>--<259.0,253.0>> -> L<<259.0,253.0>--<261.0,0.0>>
	* dong (U+20AB): L<<260.0,569.0>--<259.0,253.0>> -> L<<259.0,253.0>--<261.0,0.0>>
	* eng (U+014B): L<<38.0,0.0>--<38.0,260.0>> -> L<<38.0,260.0>--<35.0,528.0>>
	* h (U+0068): L<<38.0,0.0>--<38.0,258.0>> -> L<<38.0,258.0>--<35.0,680.0>> and 37 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:
	* Uogonek (U+0172): L<<178.0,-11.0>--<186.0,-9.0>>/B<<186.0,-9.0>-<180.0,-10.0>-<175.5,-10.0>> = 4.573921259900818
	* trademark (U+2122): L<<219.0,656.0>--<252.0,382.0>>/L<<252.0,382.0>--<281.0,656.0>> = 12.909168285065485
	* trademark (U+2122): L<<225.0,328.0>--<192.0,606.0>>/L<<192.0,606.0>--<192.0,328.0>> = 6.769619527623964 and trademark (U+2122): L<<309.0,328.0>--<309.0,606.0>>/L<<309.0,606.0>--<275.0,328.0>> = 6.972769286026432 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * G (U+0047): L<<288.0,246.0>--<290.0,0.0>>
 * Gbreve (U+011E): L<<288.0,246.0>--<290.0,0.0>>
 * Gdotaccent (U+0120): L<<288.0,246.0>--<290.0,0.0>>
 * d (U+0064): L<<259.0,253.0>--<261.0,0.0>>
 * d (U+0064): L<<261.0,680.0>--<259.0,253.0>>
 * dcaron (U+010F): L<<259.0,253.0>--<261.0,0.0>>
 * dcaron (U+010F): L<<261.0,680.0>--<259.0,253.0>>
 * dcroat (U+0111): L<<259.0,253.0>--<261.0,0.0>>
 * dcroat (U+0111): L<<260.0,569.0>--<259.0,253.0>>
 * dong (U+20AB): L<<259.0,253.0>--<261.0,0.0>> and 7 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[8] BricolageGrotesque-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Space and non-breaking space have the same width? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/hmtx.html#com.google.fonts/check/whitespace_widths">com.google.fonts/check/whitespace_widths</a>)</summary><div>


* 🔥 **FAIL** Space and non-breaking space have differing width: The space glyph named space is 240 font units wide, non-breaking space named (uni00A0) is 239 font units wide, and both should be positive and the same. GlyphsApp has "Sidebearing arithmetic" (https://glyphsapp.com/tutorials/spacing) which allows you to set the non-breaking space width to always equal the space width. [code: different-widths]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'ATLR' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: at	Contours detected: 3	Expected: 2
	- Glyph name: brokenbar	Contours detected: 1	Expected: 2
	- Glyph name: copyright	Contours detected: 2	Expected: 3
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: Uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2
	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2
	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2 
	- And 24 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:
	* G (U+0047): L<<620.0,324.0>--<620.0,223.0>> -> L<<620.0,223.0>--<620.0,0.0>>
	* Gbreve (U+011E): L<<620.0,324.0>--<620.0,223.0>> -> L<<620.0,223.0>--<620.0,0.0>>
	* Gdotaccent (U+0120): L<<620.0,324.0>--<620.0,223.0>> -> L<<620.0,223.0>--<620.0,0.0>>
	* b (U+0062): L<<67.0,0.0>--<68.0,248.0>> -> L<<68.0,248.0>--<67.0,693.0>>
	* d (U+0064): L<<518.0,693.0>--<517.0,245.0>> -> L<<517.0,245.0>--<518.0,0.0>>
	* dcaron (U+010F): L<<518.0,693.0>--<517.0,245.0>> -> L<<517.0,245.0>--<518.0,0.0>>
	* dcroat (U+0111): L<<518.0,585.0>--<517.0,245.0>> -> L<<517.0,245.0>--<518.0,0.0>>
	* dong (U+20AB): L<<518.0,585.0>--<517.0,245.0>> -> L<<517.0,245.0>--<518.0,0.0>>
	* eng (U+014B): L<<68.0,0.0>--<68.0,294.0>> -> L<<68.0,294.0>--<67.0,517.0>>
	* h (U+0068): L<<68.0,0.0>--<68.0,283.0>> -> L<<68.0,283.0>--<67.0,693.0>> and 36 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:
	* Uogonek (U+0172): B<<555.5,73.0>-<501.0,7.0>-<403.0,-9.0>>/L<<403.0,-9.0>--<403.0,-9.0>> = 9.272601777200284 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * Eng (U+014A): L<<160.0,553.0>--<164.0,0.0>>
 * Eng (U+014A): L<<545.0,117.0>--<541.0,660.0>>
 * M (U+004D): L<<158.0,568.0>--<162.0,0.0>>
 * M (U+004D): L<<688.0,0.0>--<692.0,567.0>>
 * N (U+004E): L<<160.0,553.0>--<164.0,0.0>>
 * N (U+004E): L<<545.0,117.0>--<541.0,660.0>>
 * Nacute (U+0143): L<<160.0,553.0>--<164.0,0.0>>
 * Nacute (U+0143): L<<545.0,117.0>--<541.0,660.0>>
 * Ncaron (U+0147): L<<160.0,553.0>--<164.0,0.0>>
 * Ncaron (U+0147): L<<545.0,117.0>--<541.0,660.0>> and 42 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[10] BricolageGrotesque-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Space and non-breaking space have the same width? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/hmtx.html#com.google.fonts/check/whitespace_widths">com.google.fonts/check/whitespace_widths</a>)</summary><div>


* 🔥 **FAIL** Space and non-breaking space have differing width: The space glyph named space is 234 font units wide, non-breaking space named (uni00A0) is 233 font units wide, and both should be positive and the same. GlyphsApp has "Sidebearing arithmetic" (https://glyphsapp.com/tutorials/spacing) which allows you to set the non-breaking space width to always equal the space width. [code: different-widths]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'ATLR' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Bricolage Grotesque Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: at	Contours detected: 3	Expected: 2
	- Glyph name: brokenbar	Contours detected: 1	Expected: 2
	- Glyph name: copyright	Contours detected: 2	Expected: 3
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: Uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2
	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2
	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2 
	- And 24 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:
	* dollar (U+0024): X=262.0,Y=2.0 (should be at baseline 0?)
	* dollar (U+0024): X=337.0,Y=659.0 (should be at cap-height 660?)
	* dollar (U+0024): X=336.0,Y=1.0 (should be at baseline 0?)
	* ampersand (U+0026): X=609.0,Y=-1.5 (should be at baseline 0?)
	* three (U+0033): X=55.0,Y=661.0 (should be at cap-height 660?)
	* three (U+0033): X=502.0,Y=661.0 (should be at cap-height 660?)
	* four (U+0034): X=288.0,Y=661.0 (should be at cap-height 660?)
	* four (U+0034): X=475.0,Y=661.0 (should be at cap-height 660?)
	* seven (U+0037): X=21.0,Y=661.0 (should be at cap-height 660?)
	* seven (U+0037): X=462.0,Y=661.0 (should be at cap-height 660?) and 81 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:
	* G (U+0047): L<<629.0,329.0>--<629.0,222.0>> -> L<<629.0,222.0>--<630.0,0.0>>
	* Gbreve (U+011E): L<<629.0,329.0>--<629.0,222.0>> -> L<<629.0,222.0>--<630.0,0.0>>
	* Gdotaccent (U+0120): L<<629.0,329.0>--<629.0,222.0>> -> L<<629.0,222.0>--<630.0,0.0>>
	* b (U+0062): L<<64.0,0.0>--<64.0,245.0>> -> L<<64.0,245.0>--<64.0,698.0>>
	* d (U+0064): L<<531.0,698.0>--<531.0,242.0>> -> L<<531.0,242.0>--<531.0,0.0>>
	* dcaron (U+010F): L<<531.0,698.0>--<531.0,242.0>> -> L<<531.0,242.0>--<531.0,0.0>>
	* dcroat (U+0111): L<<531.0,586.0>--<531.0,242.0>> -> L<<531.0,242.0>--<531.0,0.0>>
	* dong (U+20AB): L<<531.0,586.0>--<531.0,242.0>> -> L<<531.0,242.0>--<531.0,0.0>>
	* eng (U+014B): L<<64.0,0.0>--<64.0,298.0>> -> L<<64.0,298.0>--<64.0,520.0>>
	* h (U+0068): L<<64.0,0.0>--<64.0,291.0>> -> L<<64.0,291.0>--<64.0,698.0>> and 36 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:
	* Uogonek (U+0172): B<<563.5,74.0>-<509.0,7.0>-<408.0,-9.0>>/L<<408.0,-9.0>--<408.0,-9.0>> = 9.001755122561303 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * Eng (U+014A): L<<173.0,531.0>--<177.0,0.0>>
 * G (U+0047): L<<629.0,222.0>--<630.0,0.0>>
 * Gbreve (U+011E): L<<629.0,222.0>--<630.0,0.0>>
 * Gdotaccent (U+0120): L<<629.0,222.0>--<630.0,0.0>>
 * N (U+004E): L<<173.0,531.0>--<177.0,0.0>>
 * Nacute (U+0143): L<<173.0,531.0>--<177.0,0.0>>
 * Ncaron (U+0147): L<<173.0,531.0>--<177.0,0.0>>
 * Ntilde (U+00D1): L<<173.0,531.0>--<177.0,0.0>>
 * lira (U+20A4): L<<469.0,290.0>--<348.0,289.0>>
 * oe (U+0153): L<<554.0,311.0>--<803.0,313.0>> and 30 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[8] BricolageGrotesque48pt-Regular.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'ATLR' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Bricolage Grotesque 48pt' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: at	Contours detected: 3	Expected: 2
	- Glyph name: brokenbar	Contours detected: 1	Expected: 2
	- Glyph name: copyright	Contours detected: 2	Expected: 3
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: uogonek	Contours detected: 2	Expected: 1
	- Glyph name: Uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2
	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2
	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2 
	- And 24 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:
	* dollar (U+0024): X=248.0,Y=2.0 (should be at baseline 0?)
	* dollar (U+0024): X=248.0,Y=659.0 (should be at cap-height 660?)
	* dollar (U+0024): X=315.0,Y=1.0 (should be at baseline 0?)
	* percent (U+0025): X=116.5,Y=661.0 (should be at cap-height 660?)
	* percent (U+0025): X=303.0,Y=659.5 (should be at cap-height 660?)
	* ampersand (U+0026): X=571.5,Y=-0.5 (should be at baseline 0?)
	* four (U+0034): X=301.0,Y=661.0 (should be at cap-height 660?)
	* four (U+0034): X=453.0,Y=661.0 (should be at cap-height 660?)
	* question (U+003F): X=98.5,Y=660.5 (should be at cap-height 660?)
	* a (U+0061): X=102.0,Y=1.5 (should be at baseline 0?) and 67 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:
	* G (U+0047): L<<599.0,325.0>--<599.0,220.0>> -> L<<599.0,220.0>--<600.0,0.0>>
	* Gbreve (U+011E): L<<599.0,325.0>--<599.0,220.0>> -> L<<599.0,220.0>--<600.0,0.0>>
	* Gdotaccent (U+0120): L<<599.0,325.0>--<599.0,220.0>> -> L<<599.0,220.0>--<600.0,0.0>>
	* b (U+0062): L<<45.0,0.0>--<47.0,237.0>> -> L<<47.0,237.0>--<45.0,680.0>>
	* d (U+0064): L<<500.0,680.0>--<498.0,227.0>> -> L<<498.0,227.0>--<501.0,0.0>>
	* dcaron (U+010F): L<<500.0,680.0>--<498.0,227.0>> -> L<<498.0,227.0>--<501.0,0.0>>
	* dcroat (U+0111): L<<499.0,564.0>--<498.0,227.0>> -> L<<498.0,227.0>--<501.0,0.0>>
	* dong (U+20AB): L<<499.0,564.0>--<498.0,227.0>> -> L<<498.0,227.0>--<501.0,0.0>>
	* eng (U+014B): L<<47.0,0.0>--<47.0,245.0>> -> L<<47.0,245.0>--<45.0,516.0>>
	* h (U+0068): L<<47.0,0.0>--<47.0,226.0>> -> L<<47.0,226.0>--<45.0,680.0>> and 37 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * G (U+0047): L<<599.0,220.0>--<600.0,0.0>>
 * Gbreve (U+011E): L<<599.0,220.0>--<600.0,0.0>>
 * Gdotaccent (U+0120): L<<599.0,220.0>--<600.0,0.0>>
 * b (U+0062): L<<45.0,0.0>--<47.0,237.0>>
 * b (U+0062): L<<47.0,237.0>--<45.0,680.0>>
 * d (U+0064): L<<500.0,680.0>--<498.0,227.0>>
 * dcaron (U+010F): L<<500.0,680.0>--<498.0,227.0>>
 * dcroat (U+0111): L<<499.0,564.0>--<498.0,227.0>>
 * dong (U+20AB): L<<499.0,564.0>--<498.0,227.0>>
 * eng (U+014B): L<<47.0,245.0>--<45.0,516.0>> and 42 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 19 | 282 | 3713 | 233 | 3084 | 0 |
| 0% | 0% | 4% | 51% | 3% | 42% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
