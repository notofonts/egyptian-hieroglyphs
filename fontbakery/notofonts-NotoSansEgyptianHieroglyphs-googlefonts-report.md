## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[11] NotoSansEgyptianHieroglyphs-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nl_Latn (Dutch)</td>
<td align="left">Shaper didn't attach acutecomb to J</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0237</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check for presence of an ARTICLE.en_us.html file <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.description.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>This is a Noto font but it lacks an ARTICLE.en_us.html file.</p>
 [code: missing-article]



* 🔥 **FAIL** <p>This is a Noto font but it lacks a DESCRIPTION.en_us.html file.</p>
 [code: missing-description]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check mark characters are in GDEF mark glyph class. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following mark characters could be in the GDEF mark glyph class:
acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C), uni0326 (U+0326), uni0327 (U+0327) and uni0328 (U+0328)</p>
 [code: mark-chars]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSansEgyptianHieroglyphs/googlefonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, coptic, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, malayalam, syriac, todhri, math, old-permic, tifinagh, canadian-aboriginal, hebrew, duployan, coptic</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: tagbanwa, tai-le, pahawh-hmong, siddham, javanese, kayah-li, bengali, thai, sundanese, lepcha, chakma, dogra, gujarati, kharoshthi, saurashtra, bhaiksuki, new-tai-lue, khojki, malayalam, sinhala, tamil, psalter-pahlavi, tai-tham, mandaic, thaana, hebrew, syloti-nagri, takri, tibetan, duployan, syriac, buginese, meetei-mayek, mongolian, tagalog, tai-viet, tirhuta, gurmukhi, telugu, khmer, hanifi-rohingya, kannada, manichaean, brahmi, modi, hatran, balinese, limbu, batak, avestan, myanmar, buhid, rejang, devanagari, arabic, mahajani, oriya, lao, kaithi, hanunoo, grantha, khudawadi, newa, sogdian, sharada, yi, zanabazar-square, warang-citi, nko, masaram-gondi, gunjala-gondi, tifinagh, phags-pa, cham</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: tagbanwa, tai-le, pahawh-hmong, siddham, javanese, kayah-li, bengali, thai, sundanese, lepcha, chakma, dogra, gujarati, kharoshthi, saurashtra, bhaiksuki, new-tai-lue, khojki, malayalam, sinhala, tamil, psalter-pahlavi, tai-tham, mandaic, thaana, hebrew, syloti-nagri, takri, tibetan, duployan, syriac, buginese, meetei-mayek, mongolian, tagalog, tai-viet, tirhuta, gurmukhi, telugu, khmer, hanifi-rohingya, kannada, manichaean, brahmi, modi, limbu, balinese, myanmar, batak, avestan, rejang, buhid, devanagari, old-hungarian, arabic, mahajani, oriya, lao, kaithi, hanunoo, grantha, khudawadi, newa, sogdian, sharada, yi, zanabazar-square, warang-citi, nko, masaram-gondi, gunjala-gondi, tifinagh, phags-pa, cham</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: thai, bhaiksuki, bassa-vah, khojki, marchen, sinhala, caucasian-albanian, takri, syriac, tagalog, tai-viet, khmer, old-permic, hanifi-rohingya, kannada, modi, brahmi, rejang, myanmar, devanagari, oriya, canadian-aboriginal, masaram-gondi, gunjala-gondi, elbasan, phags-pa, cham, kayah-li, bengali, sundanese, gujarati, malayalam, tamil, miao, hebrew, syloti-nagri, tibetan, duployan, meetei-mayek, armenian, gurmukhi, manichaean, buhid, tagbanwa, tai-le, pahawh-hmong, symbols, chakma, dogra, saurashtra, new-tai-lue, music, tai-tham, thaana, telugu, sogdian, limbu, balinese, batak, mahajani, lao, kaithi, newa, khudawadi, yi, nko, coptic, siddham, javanese, lepcha, kharoshthi, wancho, adlam, psalter-pahlavi, mandaic, buginese, mongolian, tirhuta, math, osage, ahom, mende-kikakui, hanunoo, grantha, sharada, zanabazar-square, soyombo, warang-citi, tifinagh</li>
<li>U+13000 EGYPTIAN HIEROGLYPH A001: try adding egyptian-hieroglyphs</li>
<li>U+13001 EGYPTIAN HIEROGLYPH A002: try adding egyptian-hieroglyphs</li>
<li>U+13002 EGYPTIAN HIEROGLYPH A003: try adding egyptian-hieroglyphs</li>
<li>U+13003 EGYPTIAN HIEROGLYPH A004: try adding egyptian-hieroglyphs</li>
<li>U+13004 EGYPTIAN HIEROGLYPH A005: try adding egyptian-hieroglyphs</li>
<li>U+13005 EGYPTIAN HIEROGLYPH A005A: try adding egyptian-hieroglyphs</li>
<li>U+13006 EGYPTIAN HIEROGLYPH A006: try adding egyptian-hieroglyphs</li>
<li>U+13007 EGYPTIAN HIEROGLYPH A006A: try adding egyptian-hieroglyphs</li>
<li>U+13008 EGYPTIAN HIEROGLYPH A006B: try adding egyptian-hieroglyphs</li>
<li>U+13009 EGYPTIAN HIEROGLYPH A007: try adding egyptian-hieroglyphs</li>
<li>U+1300A EGYPTIAN HIEROGLYPH A008: try adding egyptian-hieroglyphs</li>
<li>U+1300B EGYPTIAN HIEROGLYPH A009: try adding egyptian-hieroglyphs</li>
<li>U+1300C EGYPTIAN HIEROGLYPH A010: try adding egyptian-hieroglyphs</li>
<li>U+1300D EGYPTIAN HIEROGLYPH A011: try adding egyptian-hieroglyphs</li>
<li>U+1300E EGYPTIAN HIEROGLYPH A012: try adding egyptian-hieroglyphs</li>
<li>U+1300F EGYPTIAN HIEROGLYPH A013: try adding egyptian-hieroglyphs</li>
<li>U+13010 EGYPTIAN HIEROGLYPH A014: try adding egyptian-hieroglyphs</li>
<li>U+13011 EGYPTIAN HIEROGLYPH A014A: try adding egyptian-hieroglyphs</li>
<li>U+13012 EGYPTIAN HIEROGLYPH A015: try adding egyptian-hieroglyphs</li>
<li>U+13013 EGYPTIAN HIEROGLYPH A016: try adding egyptian-hieroglyphs</li>
<li>U+13014 EGYPTIAN HIEROGLYPH A017: try adding egyptian-hieroglyphs</li>
<li>U+13015 EGYPTIAN HIEROGLYPH A017A: try adding egyptian-hieroglyphs</li>
<li>U+13016 EGYPTIAN HIEROGLYPH A018: try adding egyptian-hieroglyphs</li>
<li>U+13017 EGYPTIAN HIEROGLYPH A019: try adding egyptian-hieroglyphs</li>
<li>U+13018 EGYPTIAN HIEROGLYPH A020: try adding egyptian-hieroglyphs</li>
<li>U+13019 EGYPTIAN HIEROGLYPH A021: try adding egyptian-hieroglyphs</li>
<li>U+1301A EGYPTIAN HIEROGLYPH A022: try adding egyptian-hieroglyphs</li>
<li>U+1301B EGYPTIAN HIEROGLYPH A023: try adding egyptian-hieroglyphs</li>
<li>U+1301C EGYPTIAN HIEROGLYPH A024: try adding egyptian-hieroglyphs</li>
<li>U+1301D EGYPTIAN HIEROGLYPH A025: try adding egyptian-hieroglyphs</li>
<li>U+1301E EGYPTIAN HIEROGLYPH A026: try adding egyptian-hieroglyphs</li>
<li>U+1301F EGYPTIAN HIEROGLYPH A027: try adding egyptian-hieroglyphs</li>
<li>U+13020 EGYPTIAN HIEROGLYPH A028: try adding egyptian-hieroglyphs</li>
<li>U+13021 EGYPTIAN HIEROGLYPH A029: try adding egyptian-hieroglyphs</li>
<li>U+13022 EGYPTIAN HIEROGLYPH A030: try adding egyptian-hieroglyphs</li>
<li>U+13023 EGYPTIAN HIEROGLYPH A031: try adding egyptian-hieroglyphs</li>
<li>U+13024 EGYPTIAN HIEROGLYPH A032: try adding egyptian-hieroglyphs</li>
<li>U+13025 EGYPTIAN HIEROGLYPH A032A: try adding egyptian-hieroglyphs</li>
<li>U+13026 EGYPTIAN HIEROGLYPH A033: try adding egyptian-hieroglyphs</li>
<li>U+13027 EGYPTIAN HIEROGLYPH A034: try adding egyptian-hieroglyphs</li>
<li>U+13028 EGYPTIAN HIEROGLYPH A035: try adding egyptian-hieroglyphs</li>
<li>U+13029 EGYPTIAN HIEROGLYPH A036: try adding egyptian-hieroglyphs</li>
<li>U+1302A EGYPTIAN HIEROGLYPH A037: try adding egyptian-hieroglyphs</li>
<li>U+1302B EGYPTIAN HIEROGLYPH A038: try adding egyptian-hieroglyphs</li>
<li>U+1302C EGYPTIAN HIEROGLYPH A039: try adding egyptian-hieroglyphs</li>
<li>U+1302D EGYPTIAN HIEROGLYPH A040: try adding egyptian-hieroglyphs</li>
<li>U+1302E EGYPTIAN HIEROGLYPH A040A: try adding egyptian-hieroglyphs</li>
<li>U+1302F EGYPTIAN HIEROGLYPH A041: try adding egyptian-hieroglyphs</li>
<li>U+13030 EGYPTIAN HIEROGLYPH A042: try adding egyptian-hieroglyphs</li>
<li>U+13031 EGYPTIAN HIEROGLYPH A042A: try adding egyptian-hieroglyphs</li>
<li>U+13032 EGYPTIAN HIEROGLYPH A043: try adding egyptian-hieroglyphs</li>
<li>U+13033 EGYPTIAN HIEROGLYPH A043A: try adding egyptian-hieroglyphs</li>
<li>U+13034 EGYPTIAN HIEROGLYPH A044: try adding egyptian-hieroglyphs</li>
<li>U+13035 EGYPTIAN HIEROGLYPH A045: try adding egyptian-hieroglyphs</li>
<li>U+13036 EGYPTIAN HIEROGLYPH A045A: try adding egyptian-hieroglyphs</li>
<li>U+13037 EGYPTIAN HIEROGLYPH A046: try adding egyptian-hieroglyphs</li>
<li>U+13038 EGYPTIAN HIEROGLYPH A047: try adding egyptian-hieroglyphs</li>
<li>U+13039 EGYPTIAN HIEROGLYPH A048: try adding egyptian-hieroglyphs</li>
<li>U+1303A EGYPTIAN HIEROGLYPH A049: try adding egyptian-hieroglyphs</li>
<li>U+1303B EGYPTIAN HIEROGLYPH A050: try adding egyptian-hieroglyphs</li>
<li>U+1303C EGYPTIAN HIEROGLYPH A051: try adding egyptian-hieroglyphs</li>
<li>U+1303D EGYPTIAN HIEROGLYPH A052: try adding egyptian-hieroglyphs</li>
<li>U+1303E EGYPTIAN HIEROGLYPH A053: try adding egyptian-hieroglyphs</li>
<li>U+1303F EGYPTIAN HIEROGLYPH A054: try adding egyptian-hieroglyphs</li>
<li>U+13040 EGYPTIAN HIEROGLYPH A055: try adding egyptian-hieroglyphs</li>
<li>U+13041 EGYPTIAN HIEROGLYPH A056: try adding egyptian-hieroglyphs</li>
<li>U+13042 EGYPTIAN HIEROGLYPH A057: try adding egyptian-hieroglyphs</li>
<li>U+13043 EGYPTIAN HIEROGLYPH A058: try adding egyptian-hieroglyphs</li>
<li>U+13044 EGYPTIAN HIEROGLYPH A059: try adding egyptian-hieroglyphs</li>
<li>U+13045 EGYPTIAN HIEROGLYPH A060: try adding egyptian-hieroglyphs</li>
<li>U+13046 EGYPTIAN HIEROGLYPH A061: try adding egyptian-hieroglyphs</li>
<li>U+13047 EGYPTIAN HIEROGLYPH A062: try adding egyptian-hieroglyphs</li>
<li>U+13048 EGYPTIAN HIEROGLYPH A063: try adding egyptian-hieroglyphs</li>
<li>U+13049 EGYPTIAN HIEROGLYPH A064: try adding egyptian-hieroglyphs</li>
<li>U+1304A EGYPTIAN HIEROGLYPH A065: try adding egyptian-hieroglyphs</li>
<li>U+1304B EGYPTIAN HIEROGLYPH A066: try adding egyptian-hieroglyphs</li>
<li>U+1304C EGYPTIAN HIEROGLYPH A067: try adding egyptian-hieroglyphs</li>
<li>U+1304D EGYPTIAN HIEROGLYPH A068: try adding egyptian-hieroglyphs</li>
<li>U+1304E EGYPTIAN HIEROGLYPH A069: try adding egyptian-hieroglyphs</li>
<li>U+1304F EGYPTIAN HIEROGLYPH A070: try adding egyptian-hieroglyphs</li>
<li>U+13050 EGYPTIAN HIEROGLYPH B001: try adding egyptian-hieroglyphs</li>
<li>U+13051 EGYPTIAN HIEROGLYPH B002: try adding egyptian-hieroglyphs</li>
<li>U+13052 EGYPTIAN HIEROGLYPH B003: try adding egyptian-hieroglyphs</li>
<li>U+13053 EGYPTIAN HIEROGLYPH B004: try adding egyptian-hieroglyphs</li>
<li>U+13054 EGYPTIAN HIEROGLYPH B005: try adding egyptian-hieroglyphs</li>
<li>U+13055 EGYPTIAN HIEROGLYPH B005A: try adding egyptian-hieroglyphs</li>
<li>U+13056 EGYPTIAN HIEROGLYPH B006: try adding egyptian-hieroglyphs</li>
<li>U+13057 EGYPTIAN HIEROGLYPH B007: try adding egyptian-hieroglyphs</li>
<li>U+13058 EGYPTIAN HIEROGLYPH B008: try adding egyptian-hieroglyphs</li>
<li>U+13059 EGYPTIAN HIEROGLYPH B009: try adding egyptian-hieroglyphs</li>
<li>U+1305A EGYPTIAN HIEROGLYPH C001: try adding egyptian-hieroglyphs</li>
<li>U+1305B EGYPTIAN HIEROGLYPH C002: try adding egyptian-hieroglyphs</li>
<li>U+1305C EGYPTIAN HIEROGLYPH C002A: try adding egyptian-hieroglyphs</li>
<li>U+1305D EGYPTIAN HIEROGLYPH C002B: try adding egyptian-hieroglyphs</li>
<li>U+1305E EGYPTIAN HIEROGLYPH C002C: try adding egyptian-hieroglyphs</li>
<li>U+1305F EGYPTIAN HIEROGLYPH C003: try adding egyptian-hieroglyphs</li>
<li>U+13060 EGYPTIAN HIEROGLYPH C004: try adding egyptian-hieroglyphs</li>
<li>U+13061 EGYPTIAN HIEROGLYPH C005: try adding egyptian-hieroglyphs</li>
<li>U+13062 EGYPTIAN HIEROGLYPH C006: try adding egyptian-hieroglyphs</li>
<li>U+13063 EGYPTIAN HIEROGLYPH C007: try adding egyptian-hieroglyphs</li>
<li>U+13064 EGYPTIAN HIEROGLYPH C008: try adding egyptian-hieroglyphs</li>
<li>U+13065 EGYPTIAN HIEROGLYPH C009: try adding egyptian-hieroglyphs</li>
<li>U+13066 EGYPTIAN HIEROGLYPH C010: try adding egyptian-hieroglyphs</li>
<li>U+13067 EGYPTIAN HIEROGLYPH C010A: try adding egyptian-hieroglyphs</li>
<li>U+13068 EGYPTIAN HIEROGLYPH C011: try adding egyptian-hieroglyphs</li>
<li>U+13069 EGYPTIAN HIEROGLYPH C012: try adding egyptian-hieroglyphs</li>
<li>U+1306A EGYPTIAN HIEROGLYPH C013: try adding egyptian-hieroglyphs</li>
<li>U+1306B EGYPTIAN HIEROGLYPH C014: try adding egyptian-hieroglyphs</li>
<li>U+1306C EGYPTIAN HIEROGLYPH C015: try adding egyptian-hieroglyphs</li>
<li>U+1306D EGYPTIAN HIEROGLYPH C016: try adding egyptian-hieroglyphs</li>
<li>U+1306E EGYPTIAN HIEROGLYPH C017: try adding egyptian-hieroglyphs</li>
<li>U+1306F EGYPTIAN HIEROGLYPH C018: try adding egyptian-hieroglyphs</li>
<li>U+13070 EGYPTIAN HIEROGLYPH C019: try adding egyptian-hieroglyphs</li>
<li>U+13071 EGYPTIAN HIEROGLYPH C020: try adding egyptian-hieroglyphs</li>
<li>U+13072 EGYPTIAN HIEROGLYPH C021: try adding egyptian-hieroglyphs</li>
<li>U+13073 EGYPTIAN HIEROGLYPH C022: try adding egyptian-hieroglyphs</li>
<li>U+13074 EGYPTIAN HIEROGLYPH C023: try adding egyptian-hieroglyphs</li>
<li>U+13075 EGYPTIAN HIEROGLYPH C024: try adding egyptian-hieroglyphs</li>
<li>U+13076 EGYPTIAN HIEROGLYPH D001: try adding egyptian-hieroglyphs</li>
<li>U+13077 EGYPTIAN HIEROGLYPH D002: try adding egyptian-hieroglyphs</li>
<li>U+13078 EGYPTIAN HIEROGLYPH D003: try adding egyptian-hieroglyphs</li>
<li>U+13079 EGYPTIAN HIEROGLYPH D004: try adding egyptian-hieroglyphs</li>
<li>U+1307A EGYPTIAN HIEROGLYPH D005: try adding egyptian-hieroglyphs</li>
<li>U+1307B EGYPTIAN HIEROGLYPH D006: try adding egyptian-hieroglyphs</li>
<li>U+1307C EGYPTIAN HIEROGLYPH D007: try adding egyptian-hieroglyphs</li>
<li>U+1307D EGYPTIAN HIEROGLYPH D008: try adding egyptian-hieroglyphs</li>
<li>U+1307E EGYPTIAN HIEROGLYPH D008A: try adding egyptian-hieroglyphs</li>
<li>U+1307F EGYPTIAN HIEROGLYPH D009: try adding egyptian-hieroglyphs</li>
<li>U+13080 EGYPTIAN HIEROGLYPH D010: try adding egyptian-hieroglyphs</li>
<li>U+13081 EGYPTIAN HIEROGLYPH D011: try adding egyptian-hieroglyphs</li>
<li>U+13082 EGYPTIAN HIEROGLYPH D012: try adding egyptian-hieroglyphs</li>
<li>U+13083 EGYPTIAN HIEROGLYPH D013: try adding egyptian-hieroglyphs</li>
<li>U+13084 EGYPTIAN HIEROGLYPH D014: try adding egyptian-hieroglyphs</li>
<li>U+13085 EGYPTIAN HIEROGLYPH D015: try adding egyptian-hieroglyphs</li>
<li>U+13086 EGYPTIAN HIEROGLYPH D016: try adding egyptian-hieroglyphs</li>
<li>U+13087 EGYPTIAN HIEROGLYPH D017: try adding egyptian-hieroglyphs</li>
<li>U+13088 EGYPTIAN HIEROGLYPH D018: try adding egyptian-hieroglyphs</li>
<li>U+13089 EGYPTIAN HIEROGLYPH D019: try adding egyptian-hieroglyphs</li>
<li>U+1308A EGYPTIAN HIEROGLYPH D020: try adding egyptian-hieroglyphs</li>
<li>U+1308B EGYPTIAN HIEROGLYPH D021: try adding egyptian-hieroglyphs</li>
<li>U+1308C EGYPTIAN HIEROGLYPH D022: try adding egyptian-hieroglyphs</li>
<li>U+1308D EGYPTIAN HIEROGLYPH D023: try adding egyptian-hieroglyphs</li>
<li>U+1308E EGYPTIAN HIEROGLYPH D024: try adding egyptian-hieroglyphs</li>
<li>U+1308F EGYPTIAN HIEROGLYPH D025: try adding egyptian-hieroglyphs</li>
<li>U+13090 EGYPTIAN HIEROGLYPH D026: try adding egyptian-hieroglyphs</li>
<li>U+13091 EGYPTIAN HIEROGLYPH D027: try adding egyptian-hieroglyphs</li>
<li>U+13092 EGYPTIAN HIEROGLYPH D027A: try adding egyptian-hieroglyphs</li>
<li>U+13093 EGYPTIAN HIEROGLYPH D028: try adding egyptian-hieroglyphs</li>
<li>U+13094 EGYPTIAN HIEROGLYPH D029: try adding egyptian-hieroglyphs</li>
<li>U+13095 EGYPTIAN HIEROGLYPH D030: try adding egyptian-hieroglyphs</li>
<li>U+13096 EGYPTIAN HIEROGLYPH D031: try adding egyptian-hieroglyphs</li>
<li>U+13097 EGYPTIAN HIEROGLYPH D031A: try adding egyptian-hieroglyphs</li>
<li>U+13098 EGYPTIAN HIEROGLYPH D032: try adding egyptian-hieroglyphs</li>
<li>U+13099 EGYPTIAN HIEROGLYPH D033: try adding egyptian-hieroglyphs</li>
<li>U+1309A EGYPTIAN HIEROGLYPH D034: try adding egyptian-hieroglyphs</li>
<li>U+1309B EGYPTIAN HIEROGLYPH D034A: try adding egyptian-hieroglyphs</li>
<li>U+1309C EGYPTIAN HIEROGLYPH D035: try adding egyptian-hieroglyphs</li>
<li>U+1309D EGYPTIAN HIEROGLYPH D036: try adding egyptian-hieroglyphs</li>
<li>U+1309E EGYPTIAN HIEROGLYPH D037: try adding egyptian-hieroglyphs</li>
<li>U+1309F EGYPTIAN HIEROGLYPH D038: try adding egyptian-hieroglyphs</li>
<li>U+130A0 EGYPTIAN HIEROGLYPH D039: try adding egyptian-hieroglyphs</li>
<li>U+130A1 EGYPTIAN HIEROGLYPH D040: try adding egyptian-hieroglyphs</li>
<li>U+130A2 EGYPTIAN HIEROGLYPH D041: try adding egyptian-hieroglyphs</li>
<li>U+130A3 EGYPTIAN HIEROGLYPH D042: try adding egyptian-hieroglyphs</li>
<li>U+130A4 EGYPTIAN HIEROGLYPH D043: try adding egyptian-hieroglyphs</li>
<li>U+130A5 EGYPTIAN HIEROGLYPH D044: try adding egyptian-hieroglyphs</li>
<li>U+130A6 EGYPTIAN HIEROGLYPH D045: try adding egyptian-hieroglyphs</li>
<li>U+130A7 EGYPTIAN HIEROGLYPH D046: try adding egyptian-hieroglyphs</li>
<li>U+130A8 EGYPTIAN HIEROGLYPH D046A: try adding egyptian-hieroglyphs</li>
<li>U+130A9 EGYPTIAN HIEROGLYPH D047: try adding egyptian-hieroglyphs</li>
<li>U+130AA EGYPTIAN HIEROGLYPH D048: try adding egyptian-hieroglyphs</li>
<li>U+130AB EGYPTIAN HIEROGLYPH D048A: try adding egyptian-hieroglyphs</li>
<li>U+130AC EGYPTIAN HIEROGLYPH D049: try adding egyptian-hieroglyphs</li>
<li>U+130AD EGYPTIAN HIEROGLYPH D050: try adding egyptian-hieroglyphs</li>
<li>U+130AE EGYPTIAN HIEROGLYPH D050A: try adding egyptian-hieroglyphs</li>
<li>U+130AF EGYPTIAN HIEROGLYPH D050B: try adding egyptian-hieroglyphs</li>
<li>U+130B0 EGYPTIAN HIEROGLYPH D050C: try adding egyptian-hieroglyphs</li>
<li>U+130B1 EGYPTIAN HIEROGLYPH D050D: try adding egyptian-hieroglyphs</li>
<li>U+130B2 EGYPTIAN HIEROGLYPH D050E: try adding egyptian-hieroglyphs</li>
<li>U+130B3 EGYPTIAN HIEROGLYPH D050F: try adding egyptian-hieroglyphs</li>
<li>U+130B4 EGYPTIAN HIEROGLYPH D050G: try adding egyptian-hieroglyphs</li>
<li>U+130B5 EGYPTIAN HIEROGLYPH D050H: try adding egyptian-hieroglyphs</li>
<li>U+130B6 EGYPTIAN HIEROGLYPH D050I: try adding egyptian-hieroglyphs</li>
<li>U+130B7 EGYPTIAN HIEROGLYPH D051: try adding egyptian-hieroglyphs</li>
<li>U+130B8 EGYPTIAN HIEROGLYPH D052: try adding egyptian-hieroglyphs</li>
<li>U+130B9 EGYPTIAN HIEROGLYPH D052A: try adding egyptian-hieroglyphs</li>
<li>U+130BA EGYPTIAN HIEROGLYPH D053: try adding egyptian-hieroglyphs</li>
<li>U+130BB EGYPTIAN HIEROGLYPH D054: try adding egyptian-hieroglyphs</li>
<li>U+130BC EGYPTIAN HIEROGLYPH D054A: try adding egyptian-hieroglyphs</li>
<li>U+130BD EGYPTIAN HIEROGLYPH D055: try adding egyptian-hieroglyphs</li>
<li>U+130BE EGYPTIAN HIEROGLYPH D056: try adding egyptian-hieroglyphs</li>
<li>U+130BF EGYPTIAN HIEROGLYPH D057: try adding egyptian-hieroglyphs</li>
<li>U+130C0 EGYPTIAN HIEROGLYPH D058: try adding egyptian-hieroglyphs</li>
<li>U+130C1 EGYPTIAN HIEROGLYPH D059: try adding egyptian-hieroglyphs</li>
<li>U+130C2 EGYPTIAN HIEROGLYPH D060: try adding egyptian-hieroglyphs</li>
<li>U+130C3 EGYPTIAN HIEROGLYPH D061: try adding egyptian-hieroglyphs</li>
<li>U+130C4 EGYPTIAN HIEROGLYPH D062: try adding egyptian-hieroglyphs</li>
<li>U+130C5 EGYPTIAN HIEROGLYPH D063: try adding egyptian-hieroglyphs</li>
<li>U+130C6 EGYPTIAN HIEROGLYPH D064: try adding egyptian-hieroglyphs</li>
<li>U+130C7 EGYPTIAN HIEROGLYPH D065: try adding egyptian-hieroglyphs</li>
<li>U+130C8 EGYPTIAN HIEROGLYPH D066: try adding egyptian-hieroglyphs</li>
<li>U+130C9 EGYPTIAN HIEROGLYPH D067: try adding egyptian-hieroglyphs</li>
<li>U+130CA EGYPTIAN HIEROGLYPH D067A: try adding egyptian-hieroglyphs</li>
<li>U+130CB EGYPTIAN HIEROGLYPH D067B: try adding egyptian-hieroglyphs</li>
<li>U+130CC EGYPTIAN HIEROGLYPH D067C: try adding egyptian-hieroglyphs</li>
<li>U+130CD EGYPTIAN HIEROGLYPH D067D: try adding egyptian-hieroglyphs</li>
<li>U+130CE EGYPTIAN HIEROGLYPH D067E: try adding egyptian-hieroglyphs</li>
<li>U+130CF EGYPTIAN HIEROGLYPH D067F: try adding egyptian-hieroglyphs</li>
<li>U+130D0 EGYPTIAN HIEROGLYPH D067G: try adding egyptian-hieroglyphs</li>
<li>U+130D1 EGYPTIAN HIEROGLYPH D067H: try adding egyptian-hieroglyphs</li>
<li>U+130D2 EGYPTIAN HIEROGLYPH E001: try adding egyptian-hieroglyphs</li>
<li>U+130D3 EGYPTIAN HIEROGLYPH E002: try adding egyptian-hieroglyphs</li>
<li>U+130D4 EGYPTIAN HIEROGLYPH E003: try adding egyptian-hieroglyphs</li>
<li>U+130D5 EGYPTIAN HIEROGLYPH E004: try adding egyptian-hieroglyphs</li>
<li>U+130D6 EGYPTIAN HIEROGLYPH E005: try adding egyptian-hieroglyphs</li>
<li>U+130D7 EGYPTIAN HIEROGLYPH E006: try adding egyptian-hieroglyphs</li>
<li>U+130D8 EGYPTIAN HIEROGLYPH E007: try adding egyptian-hieroglyphs</li>
<li>U+130D9 EGYPTIAN HIEROGLYPH E008: try adding egyptian-hieroglyphs</li>
<li>U+130DA EGYPTIAN HIEROGLYPH E008A: try adding egyptian-hieroglyphs</li>
<li>U+130DB EGYPTIAN HIEROGLYPH E009: try adding egyptian-hieroglyphs</li>
<li>U+130DC EGYPTIAN HIEROGLYPH E009A: try adding egyptian-hieroglyphs</li>
<li>U+130DD EGYPTIAN HIEROGLYPH E010: try adding egyptian-hieroglyphs</li>
<li>U+130DE EGYPTIAN HIEROGLYPH E011: try adding egyptian-hieroglyphs</li>
<li>U+130DF EGYPTIAN HIEROGLYPH E012: try adding egyptian-hieroglyphs</li>
<li>U+130E0 EGYPTIAN HIEROGLYPH E013: try adding egyptian-hieroglyphs</li>
<li>U+130E1 EGYPTIAN HIEROGLYPH E014: try adding egyptian-hieroglyphs</li>
<li>U+130E2 EGYPTIAN HIEROGLYPH E015: try adding egyptian-hieroglyphs</li>
<li>U+130E3 EGYPTIAN HIEROGLYPH E016: try adding egyptian-hieroglyphs</li>
<li>U+130E4 EGYPTIAN HIEROGLYPH E016A: try adding egyptian-hieroglyphs</li>
<li>U+130E5 EGYPTIAN HIEROGLYPH E017: try adding egyptian-hieroglyphs</li>
<li>U+130E6 EGYPTIAN HIEROGLYPH E017A: try adding egyptian-hieroglyphs</li>
<li>U+130E7 EGYPTIAN HIEROGLYPH E018: try adding egyptian-hieroglyphs</li>
<li>U+130E8 EGYPTIAN HIEROGLYPH E019: try adding egyptian-hieroglyphs</li>
<li>U+130E9 EGYPTIAN HIEROGLYPH E020: try adding egyptian-hieroglyphs</li>
<li>U+130EA EGYPTIAN HIEROGLYPH E020A: try adding egyptian-hieroglyphs</li>
<li>U+130EB EGYPTIAN HIEROGLYPH E021: try adding egyptian-hieroglyphs</li>
<li>U+130EC EGYPTIAN HIEROGLYPH E022: try adding egyptian-hieroglyphs</li>
<li>U+130ED EGYPTIAN HIEROGLYPH E023: try adding egyptian-hieroglyphs</li>
<li>U+130EE EGYPTIAN HIEROGLYPH E024: try adding egyptian-hieroglyphs</li>
<li>U+130EF EGYPTIAN HIEROGLYPH E025: try adding egyptian-hieroglyphs</li>
<li>U+130F0 EGYPTIAN HIEROGLYPH E026: try adding egyptian-hieroglyphs</li>
<li>U+130F1 EGYPTIAN HIEROGLYPH E027: try adding egyptian-hieroglyphs</li>
<li>U+130F2 EGYPTIAN HIEROGLYPH E028: try adding egyptian-hieroglyphs</li>
<li>U+130F3 EGYPTIAN HIEROGLYPH E028A: try adding egyptian-hieroglyphs</li>
<li>U+130F4 EGYPTIAN HIEROGLYPH E029: try adding egyptian-hieroglyphs</li>
<li>U+130F5 EGYPTIAN HIEROGLYPH E030: try adding egyptian-hieroglyphs</li>
<li>U+130F6 EGYPTIAN HIEROGLYPH E031: try adding egyptian-hieroglyphs</li>
<li>U+130F7 EGYPTIAN HIEROGLYPH E032: try adding egyptian-hieroglyphs</li>
<li>U+130F8 EGYPTIAN HIEROGLYPH E033: try adding egyptian-hieroglyphs</li>
<li>U+130F9 EGYPTIAN HIEROGLYPH E034: try adding egyptian-hieroglyphs</li>
<li>U+130FA EGYPTIAN HIEROGLYPH E034A: try adding egyptian-hieroglyphs</li>
<li>U+130FB EGYPTIAN HIEROGLYPH E036: try adding egyptian-hieroglyphs</li>
<li>U+130FC EGYPTIAN HIEROGLYPH E037: try adding egyptian-hieroglyphs</li>
<li>U+130FD EGYPTIAN HIEROGLYPH E038: try adding egyptian-hieroglyphs</li>
<li>U+130FE EGYPTIAN HIEROGLYPH F001: try adding egyptian-hieroglyphs</li>
<li>U+130FF EGYPTIAN HIEROGLYPH F001A: try adding egyptian-hieroglyphs</li>
<li>U+13100 EGYPTIAN HIEROGLYPH F002: try adding egyptian-hieroglyphs</li>
<li>U+13101 EGYPTIAN HIEROGLYPH F003: try adding egyptian-hieroglyphs</li>
<li>U+13102 EGYPTIAN HIEROGLYPH F004: try adding egyptian-hieroglyphs</li>
<li>U+13103 EGYPTIAN HIEROGLYPH F005: try adding egyptian-hieroglyphs</li>
<li>U+13104 EGYPTIAN HIEROGLYPH F006: try adding egyptian-hieroglyphs</li>
<li>U+13105 EGYPTIAN HIEROGLYPH F007: try adding egyptian-hieroglyphs</li>
<li>U+13106 EGYPTIAN HIEROGLYPH F008: try adding egyptian-hieroglyphs</li>
<li>U+13107 EGYPTIAN HIEROGLYPH F009: try adding egyptian-hieroglyphs</li>
<li>U+13108 EGYPTIAN HIEROGLYPH F010: try adding egyptian-hieroglyphs</li>
<li>U+13109 EGYPTIAN HIEROGLYPH F011: try adding egyptian-hieroglyphs</li>
<li>U+1310A EGYPTIAN HIEROGLYPH F012: try adding egyptian-hieroglyphs</li>
<li>U+1310B EGYPTIAN HIEROGLYPH F013: try adding egyptian-hieroglyphs</li>
<li>U+1310C EGYPTIAN HIEROGLYPH F013A: try adding egyptian-hieroglyphs</li>
<li>U+1310D EGYPTIAN HIEROGLYPH F014: try adding egyptian-hieroglyphs</li>
<li>U+1310E EGYPTIAN HIEROGLYPH F015: try adding egyptian-hieroglyphs</li>
<li>U+1310F EGYPTIAN HIEROGLYPH F016: try adding egyptian-hieroglyphs</li>
<li>U+13110 EGYPTIAN HIEROGLYPH F017: try adding egyptian-hieroglyphs</li>
<li>U+13111 EGYPTIAN HIEROGLYPH F018: try adding egyptian-hieroglyphs</li>
<li>U+13112 EGYPTIAN HIEROGLYPH F019: try adding egyptian-hieroglyphs</li>
<li>U+13113 EGYPTIAN HIEROGLYPH F020: try adding egyptian-hieroglyphs</li>
<li>U+13114 EGYPTIAN HIEROGLYPH F021: try adding egyptian-hieroglyphs</li>
<li>U+13115 EGYPTIAN HIEROGLYPH F021A: try adding egyptian-hieroglyphs</li>
<li>U+13116 EGYPTIAN HIEROGLYPH F022: try adding egyptian-hieroglyphs</li>
<li>U+13117 EGYPTIAN HIEROGLYPH F023: try adding egyptian-hieroglyphs</li>
<li>U+13118 EGYPTIAN HIEROGLYPH F024: try adding egyptian-hieroglyphs</li>
<li>U+13119 EGYPTIAN HIEROGLYPH F025: try adding egyptian-hieroglyphs</li>
<li>U+1311A EGYPTIAN HIEROGLYPH F026: try adding egyptian-hieroglyphs</li>
<li>U+1311B EGYPTIAN HIEROGLYPH F027: try adding egyptian-hieroglyphs</li>
<li>U+1311C EGYPTIAN HIEROGLYPH F028: try adding egyptian-hieroglyphs</li>
<li>U+1311D EGYPTIAN HIEROGLYPH F029: try adding egyptian-hieroglyphs</li>
<li>U+1311E EGYPTIAN HIEROGLYPH F030: try adding egyptian-hieroglyphs</li>
<li>U+1311F EGYPTIAN HIEROGLYPH F031: try adding egyptian-hieroglyphs</li>
<li>U+13120 EGYPTIAN HIEROGLYPH F031A: try adding egyptian-hieroglyphs</li>
<li>U+13121 EGYPTIAN HIEROGLYPH F032: try adding egyptian-hieroglyphs</li>
<li>U+13122 EGYPTIAN HIEROGLYPH F033: try adding egyptian-hieroglyphs</li>
<li>U+13123 EGYPTIAN HIEROGLYPH F034: try adding egyptian-hieroglyphs</li>
<li>U+13124 EGYPTIAN HIEROGLYPH F035: try adding egyptian-hieroglyphs</li>
<li>U+13125 EGYPTIAN HIEROGLYPH F036: try adding egyptian-hieroglyphs</li>
<li>U+13126 EGYPTIAN HIEROGLYPH F037: try adding egyptian-hieroglyphs</li>
<li>U+13127 EGYPTIAN HIEROGLYPH F037A: try adding egyptian-hieroglyphs</li>
<li>U+13128 EGYPTIAN HIEROGLYPH F038: try adding egyptian-hieroglyphs</li>
<li>U+13129 EGYPTIAN HIEROGLYPH F038A: try adding egyptian-hieroglyphs</li>
<li>U+1312A EGYPTIAN HIEROGLYPH F039: try adding egyptian-hieroglyphs</li>
<li>U+1312B EGYPTIAN HIEROGLYPH F040: try adding egyptian-hieroglyphs</li>
<li>U+1312C EGYPTIAN HIEROGLYPH F041: try adding egyptian-hieroglyphs</li>
<li>U+1312D EGYPTIAN HIEROGLYPH F042: try adding egyptian-hieroglyphs</li>
<li>U+1312E EGYPTIAN HIEROGLYPH F043: try adding egyptian-hieroglyphs</li>
<li>U+1312F EGYPTIAN HIEROGLYPH F044: try adding egyptian-hieroglyphs</li>
<li>U+13130 EGYPTIAN HIEROGLYPH F045: try adding egyptian-hieroglyphs</li>
<li>U+13131 EGYPTIAN HIEROGLYPH F045A: try adding egyptian-hieroglyphs</li>
<li>U+13132 EGYPTIAN HIEROGLYPH F046: try adding egyptian-hieroglyphs</li>
<li>U+13133 EGYPTIAN HIEROGLYPH F046A: try adding egyptian-hieroglyphs</li>
<li>U+13134 EGYPTIAN HIEROGLYPH F047: try adding egyptian-hieroglyphs</li>
<li>U+13135 EGYPTIAN HIEROGLYPH F047A: try adding egyptian-hieroglyphs</li>
<li>U+13136 EGYPTIAN HIEROGLYPH F048: try adding egyptian-hieroglyphs</li>
<li>U+13137 EGYPTIAN HIEROGLYPH F049: try adding egyptian-hieroglyphs</li>
<li>U+13138 EGYPTIAN HIEROGLYPH F050: try adding egyptian-hieroglyphs</li>
<li>U+13139 EGYPTIAN HIEROGLYPH F051: try adding egyptian-hieroglyphs</li>
<li>U+1313A EGYPTIAN HIEROGLYPH F051A: try adding egyptian-hieroglyphs</li>
<li>U+1313B EGYPTIAN HIEROGLYPH F051B: try adding egyptian-hieroglyphs</li>
<li>U+1313C EGYPTIAN HIEROGLYPH F051C: try adding egyptian-hieroglyphs</li>
<li>U+1313D EGYPTIAN HIEROGLYPH F052: try adding egyptian-hieroglyphs</li>
<li>U+1313E EGYPTIAN HIEROGLYPH F053: try adding egyptian-hieroglyphs</li>
<li>U+1313F EGYPTIAN HIEROGLYPH G001: try adding egyptian-hieroglyphs</li>
<li>U+13140 EGYPTIAN HIEROGLYPH G002: try adding egyptian-hieroglyphs</li>
<li>U+13141 EGYPTIAN HIEROGLYPH G003: try adding egyptian-hieroglyphs</li>
<li>U+13142 EGYPTIAN HIEROGLYPH G004: try adding egyptian-hieroglyphs</li>
<li>U+13143 EGYPTIAN HIEROGLYPH G005: try adding egyptian-hieroglyphs</li>
<li>U+13144 EGYPTIAN HIEROGLYPH G006: try adding egyptian-hieroglyphs</li>
<li>U+13145 EGYPTIAN HIEROGLYPH G006A: try adding egyptian-hieroglyphs</li>
<li>U+13146 EGYPTIAN HIEROGLYPH G007: try adding egyptian-hieroglyphs</li>
<li>U+13147 EGYPTIAN HIEROGLYPH G007A: try adding egyptian-hieroglyphs</li>
<li>U+13148 EGYPTIAN HIEROGLYPH G007B: try adding egyptian-hieroglyphs</li>
<li>U+13149 EGYPTIAN HIEROGLYPH G008: try adding egyptian-hieroglyphs</li>
<li>U+1314A EGYPTIAN HIEROGLYPH G009: try adding egyptian-hieroglyphs</li>
<li>U+1314B EGYPTIAN HIEROGLYPH G010: try adding egyptian-hieroglyphs</li>
<li>U+1314C EGYPTIAN HIEROGLYPH G011: try adding egyptian-hieroglyphs</li>
<li>U+1314D EGYPTIAN HIEROGLYPH G011A: try adding egyptian-hieroglyphs</li>
<li>U+1314E EGYPTIAN HIEROGLYPH G012: try adding egyptian-hieroglyphs</li>
<li>U+1314F EGYPTIAN HIEROGLYPH G013: try adding egyptian-hieroglyphs</li>
<li>U+13150 EGYPTIAN HIEROGLYPH G014: try adding egyptian-hieroglyphs</li>
<li>U+13151 EGYPTIAN HIEROGLYPH G015: try adding egyptian-hieroglyphs</li>
<li>U+13152 EGYPTIAN HIEROGLYPH G016: try adding egyptian-hieroglyphs</li>
<li>U+13153 EGYPTIAN HIEROGLYPH G017: try adding egyptian-hieroglyphs</li>
<li>U+13154 EGYPTIAN HIEROGLYPH G018: try adding egyptian-hieroglyphs</li>
<li>U+13155 EGYPTIAN HIEROGLYPH G019: try adding egyptian-hieroglyphs</li>
<li>U+13156 EGYPTIAN HIEROGLYPH G020: try adding egyptian-hieroglyphs</li>
<li>U+13157 EGYPTIAN HIEROGLYPH G020A: try adding egyptian-hieroglyphs</li>
<li>U+13158 EGYPTIAN HIEROGLYPH G021: try adding egyptian-hieroglyphs</li>
<li>U+13159 EGYPTIAN HIEROGLYPH G022: try adding egyptian-hieroglyphs</li>
<li>U+1315A EGYPTIAN HIEROGLYPH G023: try adding egyptian-hieroglyphs</li>
<li>U+1315B EGYPTIAN HIEROGLYPH G024: try adding egyptian-hieroglyphs</li>
<li>U+1315C EGYPTIAN HIEROGLYPH G025: try adding egyptian-hieroglyphs</li>
<li>U+1315D EGYPTIAN HIEROGLYPH G026: try adding egyptian-hieroglyphs</li>
<li>U+1315E EGYPTIAN HIEROGLYPH G026A: try adding egyptian-hieroglyphs</li>
<li>U+1315F EGYPTIAN HIEROGLYPH G027: try adding egyptian-hieroglyphs</li>
<li>U+13160 EGYPTIAN HIEROGLYPH G028: try adding egyptian-hieroglyphs</li>
<li>U+13161 EGYPTIAN HIEROGLYPH G029: try adding egyptian-hieroglyphs</li>
<li>U+13162 EGYPTIAN HIEROGLYPH G030: try adding egyptian-hieroglyphs</li>
<li>U+13163 EGYPTIAN HIEROGLYPH G031: try adding egyptian-hieroglyphs</li>
<li>U+13164 EGYPTIAN HIEROGLYPH G032: try adding egyptian-hieroglyphs</li>
<li>U+13165 EGYPTIAN HIEROGLYPH G033: try adding egyptian-hieroglyphs</li>
<li>U+13166 EGYPTIAN HIEROGLYPH G034: try adding egyptian-hieroglyphs</li>
<li>U+13167 EGYPTIAN HIEROGLYPH G035: try adding egyptian-hieroglyphs</li>
<li>U+13168 EGYPTIAN HIEROGLYPH G036: try adding egyptian-hieroglyphs</li>
<li>U+13169 EGYPTIAN HIEROGLYPH G036A: try adding egyptian-hieroglyphs</li>
<li>U+1316A EGYPTIAN HIEROGLYPH G037: try adding egyptian-hieroglyphs</li>
<li>U+1316B EGYPTIAN HIEROGLYPH G037A: try adding egyptian-hieroglyphs</li>
<li>U+1316C EGYPTIAN HIEROGLYPH G038: try adding egyptian-hieroglyphs</li>
<li>U+1316D EGYPTIAN HIEROGLYPH G039: try adding egyptian-hieroglyphs</li>
<li>U+1316E EGYPTIAN HIEROGLYPH G040: try adding egyptian-hieroglyphs</li>
<li>U+1316F EGYPTIAN HIEROGLYPH G041: try adding egyptian-hieroglyphs</li>
<li>U+13170 EGYPTIAN HIEROGLYPH G042: try adding egyptian-hieroglyphs</li>
<li>U+13171 EGYPTIAN HIEROGLYPH G043: try adding egyptian-hieroglyphs</li>
<li>U+13172 EGYPTIAN HIEROGLYPH G043A: try adding egyptian-hieroglyphs</li>
<li>U+13173 EGYPTIAN HIEROGLYPH G044: try adding egyptian-hieroglyphs</li>
<li>U+13174 EGYPTIAN HIEROGLYPH G045: try adding egyptian-hieroglyphs</li>
<li>U+13175 EGYPTIAN HIEROGLYPH G045A: try adding egyptian-hieroglyphs</li>
<li>U+13176 EGYPTIAN HIEROGLYPH G046: try adding egyptian-hieroglyphs</li>
<li>U+13177 EGYPTIAN HIEROGLYPH G047: try adding egyptian-hieroglyphs</li>
<li>U+13178 EGYPTIAN HIEROGLYPH G048: try adding egyptian-hieroglyphs</li>
<li>U+13179 EGYPTIAN HIEROGLYPH G049: try adding egyptian-hieroglyphs</li>
<li>U+1317A EGYPTIAN HIEROGLYPH G050: try adding egyptian-hieroglyphs</li>
<li>U+1317B EGYPTIAN HIEROGLYPH G051: try adding egyptian-hieroglyphs</li>
<li>U+1317C EGYPTIAN HIEROGLYPH G052: try adding egyptian-hieroglyphs</li>
<li>U+1317D EGYPTIAN HIEROGLYPH G053: try adding egyptian-hieroglyphs</li>
<li>U+1317E EGYPTIAN HIEROGLYPH G054: try adding egyptian-hieroglyphs</li>
<li>U+1317F EGYPTIAN HIEROGLYPH H001: try adding egyptian-hieroglyphs</li>
<li>U+13180 EGYPTIAN HIEROGLYPH H002: try adding egyptian-hieroglyphs</li>
<li>U+13181 EGYPTIAN HIEROGLYPH H003: try adding egyptian-hieroglyphs</li>
<li>U+13182 EGYPTIAN HIEROGLYPH H004: try adding egyptian-hieroglyphs</li>
<li>U+13183 EGYPTIAN HIEROGLYPH H005: try adding egyptian-hieroglyphs</li>
<li>U+13184 EGYPTIAN HIEROGLYPH H006: try adding egyptian-hieroglyphs</li>
<li>U+13185 EGYPTIAN HIEROGLYPH H006A: try adding egyptian-hieroglyphs</li>
<li>U+13186 EGYPTIAN HIEROGLYPH H007: try adding egyptian-hieroglyphs</li>
<li>U+13187 EGYPTIAN HIEROGLYPH H008: try adding egyptian-hieroglyphs</li>
<li>U+13188 EGYPTIAN HIEROGLYPH I001: try adding egyptian-hieroglyphs</li>
<li>U+13189 EGYPTIAN HIEROGLYPH I002: try adding egyptian-hieroglyphs</li>
<li>U+1318A EGYPTIAN HIEROGLYPH I003: try adding egyptian-hieroglyphs</li>
<li>U+1318B EGYPTIAN HIEROGLYPH I004: try adding egyptian-hieroglyphs</li>
<li>U+1318C EGYPTIAN HIEROGLYPH I005: try adding egyptian-hieroglyphs</li>
<li>U+1318D EGYPTIAN HIEROGLYPH I005A: try adding egyptian-hieroglyphs</li>
<li>U+1318E EGYPTIAN HIEROGLYPH I006: try adding egyptian-hieroglyphs</li>
<li>U+1318F EGYPTIAN HIEROGLYPH I007: try adding egyptian-hieroglyphs</li>
<li>U+13190 EGYPTIAN HIEROGLYPH I008: try adding egyptian-hieroglyphs</li>
<li>U+13191 EGYPTIAN HIEROGLYPH I009: try adding egyptian-hieroglyphs</li>
<li>U+13192 EGYPTIAN HIEROGLYPH I009A: try adding egyptian-hieroglyphs</li>
<li>U+13193 EGYPTIAN HIEROGLYPH I010: try adding egyptian-hieroglyphs</li>
<li>U+13194 EGYPTIAN HIEROGLYPH I010A: try adding egyptian-hieroglyphs</li>
<li>U+13195 EGYPTIAN HIEROGLYPH I011: try adding egyptian-hieroglyphs</li>
<li>U+13196 EGYPTIAN HIEROGLYPH I011A: try adding egyptian-hieroglyphs</li>
<li>U+13197 EGYPTIAN HIEROGLYPH I012: try adding egyptian-hieroglyphs</li>
<li>U+13198 EGYPTIAN HIEROGLYPH I013: try adding egyptian-hieroglyphs</li>
<li>U+13199 EGYPTIAN HIEROGLYPH I014: try adding egyptian-hieroglyphs</li>
<li>U+1319A EGYPTIAN HIEROGLYPH I015: try adding egyptian-hieroglyphs</li>
<li>U+1319B EGYPTIAN HIEROGLYPH K001: try adding egyptian-hieroglyphs</li>
<li>U+1319C EGYPTIAN HIEROGLYPH K002: try adding egyptian-hieroglyphs</li>
<li>U+1319D EGYPTIAN HIEROGLYPH K003: try adding egyptian-hieroglyphs</li>
<li>U+1319E EGYPTIAN HIEROGLYPH K004: try adding egyptian-hieroglyphs</li>
<li>U+1319F EGYPTIAN HIEROGLYPH K005: try adding egyptian-hieroglyphs</li>
<li>U+131A0 EGYPTIAN HIEROGLYPH K006: try adding egyptian-hieroglyphs</li>
<li>U+131A1 EGYPTIAN HIEROGLYPH K007: try adding egyptian-hieroglyphs</li>
<li>U+131A2 EGYPTIAN HIEROGLYPH K008: try adding egyptian-hieroglyphs</li>
<li>U+131A3 EGYPTIAN HIEROGLYPH L001: try adding egyptian-hieroglyphs</li>
<li>U+131A4 EGYPTIAN HIEROGLYPH L002: try adding egyptian-hieroglyphs</li>
<li>U+131A5 EGYPTIAN HIEROGLYPH L002A: try adding egyptian-hieroglyphs</li>
<li>U+131A6 EGYPTIAN HIEROGLYPH L003: try adding egyptian-hieroglyphs</li>
<li>U+131A7 EGYPTIAN HIEROGLYPH L004: try adding egyptian-hieroglyphs</li>
<li>U+131A8 EGYPTIAN HIEROGLYPH L005: try adding egyptian-hieroglyphs</li>
<li>U+131A9 EGYPTIAN HIEROGLYPH L006: try adding egyptian-hieroglyphs</li>
<li>U+131AA EGYPTIAN HIEROGLYPH L006A: try adding egyptian-hieroglyphs</li>
<li>U+131AB EGYPTIAN HIEROGLYPH L007: try adding egyptian-hieroglyphs</li>
<li>U+131AC EGYPTIAN HIEROGLYPH L008: try adding egyptian-hieroglyphs</li>
<li>U+131AD EGYPTIAN HIEROGLYPH M001: try adding egyptian-hieroglyphs</li>
<li>U+131AE EGYPTIAN HIEROGLYPH M001A: try adding egyptian-hieroglyphs</li>
<li>U+131AF EGYPTIAN HIEROGLYPH M001B: try adding egyptian-hieroglyphs</li>
<li>U+131B0 EGYPTIAN HIEROGLYPH M002: try adding egyptian-hieroglyphs</li>
<li>U+131B1 EGYPTIAN HIEROGLYPH M003: try adding egyptian-hieroglyphs</li>
<li>U+131B2 EGYPTIAN HIEROGLYPH M003A: try adding egyptian-hieroglyphs</li>
<li>U+131B3 EGYPTIAN HIEROGLYPH M004: try adding egyptian-hieroglyphs</li>
<li>U+131B4 EGYPTIAN HIEROGLYPH M005: try adding egyptian-hieroglyphs</li>
<li>U+131B5 EGYPTIAN HIEROGLYPH M006: try adding egyptian-hieroglyphs</li>
<li>U+131B6 EGYPTIAN HIEROGLYPH M007: try adding egyptian-hieroglyphs</li>
<li>U+131B7 EGYPTIAN HIEROGLYPH M008: try adding egyptian-hieroglyphs</li>
<li>U+131B8 EGYPTIAN HIEROGLYPH M009: try adding egyptian-hieroglyphs</li>
<li>U+131B9 EGYPTIAN HIEROGLYPH M010: try adding egyptian-hieroglyphs</li>
<li>U+131BA EGYPTIAN HIEROGLYPH M010A: try adding egyptian-hieroglyphs</li>
<li>U+131BB EGYPTIAN HIEROGLYPH M011: try adding egyptian-hieroglyphs</li>
<li>U+131BC EGYPTIAN HIEROGLYPH M012: try adding egyptian-hieroglyphs</li>
<li>U+131BD EGYPTIAN HIEROGLYPH M012A: try adding egyptian-hieroglyphs</li>
<li>U+131BE EGYPTIAN HIEROGLYPH M012B: try adding egyptian-hieroglyphs</li>
<li>U+131BF EGYPTIAN HIEROGLYPH M012C: try adding egyptian-hieroglyphs</li>
<li>U+131C0 EGYPTIAN HIEROGLYPH M012D: try adding egyptian-hieroglyphs</li>
<li>U+131C1 EGYPTIAN HIEROGLYPH M012E: try adding egyptian-hieroglyphs</li>
<li>U+131C2 EGYPTIAN HIEROGLYPH M012F: try adding egyptian-hieroglyphs</li>
<li>U+131C3 EGYPTIAN HIEROGLYPH M012G: try adding egyptian-hieroglyphs</li>
<li>U+131C4 EGYPTIAN HIEROGLYPH M012H: try adding egyptian-hieroglyphs</li>
<li>U+131C5 EGYPTIAN HIEROGLYPH M013: try adding egyptian-hieroglyphs</li>
<li>U+131C6 EGYPTIAN HIEROGLYPH M014: try adding egyptian-hieroglyphs</li>
<li>U+131C7 EGYPTIAN HIEROGLYPH M015: try adding egyptian-hieroglyphs</li>
<li>U+131C8 EGYPTIAN HIEROGLYPH M015A: try adding egyptian-hieroglyphs</li>
<li>U+131C9 EGYPTIAN HIEROGLYPH M016: try adding egyptian-hieroglyphs</li>
<li>U+131CA EGYPTIAN HIEROGLYPH M016A: try adding egyptian-hieroglyphs</li>
<li>U+131CB EGYPTIAN HIEROGLYPH M017: try adding egyptian-hieroglyphs</li>
<li>U+131CC EGYPTIAN HIEROGLYPH M017A: try adding egyptian-hieroglyphs</li>
<li>U+131CD EGYPTIAN HIEROGLYPH M018: try adding egyptian-hieroglyphs</li>
<li>U+131CE EGYPTIAN HIEROGLYPH M019: try adding egyptian-hieroglyphs</li>
<li>U+131CF EGYPTIAN HIEROGLYPH M020: try adding egyptian-hieroglyphs</li>
<li>U+131D0 EGYPTIAN HIEROGLYPH M021: try adding egyptian-hieroglyphs</li>
<li>U+131D1 EGYPTIAN HIEROGLYPH M022: try adding egyptian-hieroglyphs</li>
<li>U+131D2 EGYPTIAN HIEROGLYPH M022A: try adding egyptian-hieroglyphs</li>
<li>U+131D3 EGYPTIAN HIEROGLYPH M023: try adding egyptian-hieroglyphs</li>
<li>U+131D4 EGYPTIAN HIEROGLYPH M024: try adding egyptian-hieroglyphs</li>
<li>U+131D5 EGYPTIAN HIEROGLYPH M024A: try adding egyptian-hieroglyphs</li>
<li>U+131D6 EGYPTIAN HIEROGLYPH M025: try adding egyptian-hieroglyphs</li>
<li>U+131D7 EGYPTIAN HIEROGLYPH M026: try adding egyptian-hieroglyphs</li>
<li>U+131D8 EGYPTIAN HIEROGLYPH M027: try adding egyptian-hieroglyphs</li>
<li>U+131D9 EGYPTIAN HIEROGLYPH M028: try adding egyptian-hieroglyphs</li>
<li>U+131DA EGYPTIAN HIEROGLYPH M028A: try adding egyptian-hieroglyphs</li>
<li>U+131DB EGYPTIAN HIEROGLYPH M029: try adding egyptian-hieroglyphs</li>
<li>U+131DC EGYPTIAN HIEROGLYPH M030: try adding egyptian-hieroglyphs</li>
<li>U+131DD EGYPTIAN HIEROGLYPH M031: try adding egyptian-hieroglyphs</li>
<li>U+131DE EGYPTIAN HIEROGLYPH M031A: try adding egyptian-hieroglyphs</li>
<li>U+131DF EGYPTIAN HIEROGLYPH M032: try adding egyptian-hieroglyphs</li>
<li>U+131E0 EGYPTIAN HIEROGLYPH M033: try adding egyptian-hieroglyphs</li>
<li>U+131E1 EGYPTIAN HIEROGLYPH M033A: try adding egyptian-hieroglyphs</li>
<li>U+131E2 EGYPTIAN HIEROGLYPH M033B: try adding egyptian-hieroglyphs</li>
<li>U+131E3 EGYPTIAN HIEROGLYPH M034: try adding egyptian-hieroglyphs</li>
<li>U+131E4 EGYPTIAN HIEROGLYPH M035: try adding egyptian-hieroglyphs</li>
<li>U+131E5 EGYPTIAN HIEROGLYPH M036: try adding egyptian-hieroglyphs</li>
<li>U+131E6 EGYPTIAN HIEROGLYPH M037: try adding egyptian-hieroglyphs</li>
<li>U+131E7 EGYPTIAN HIEROGLYPH M038: try adding egyptian-hieroglyphs</li>
<li>U+131E8 EGYPTIAN HIEROGLYPH M039: try adding egyptian-hieroglyphs</li>
<li>U+131E9 EGYPTIAN HIEROGLYPH M040: try adding egyptian-hieroglyphs</li>
<li>U+131EA EGYPTIAN HIEROGLYPH M040A: try adding egyptian-hieroglyphs</li>
<li>U+131EB EGYPTIAN HIEROGLYPH M041: try adding egyptian-hieroglyphs</li>
<li>U+131EC EGYPTIAN HIEROGLYPH M042: try adding egyptian-hieroglyphs</li>
<li>U+131ED EGYPTIAN HIEROGLYPH M043: try adding egyptian-hieroglyphs</li>
<li>U+131EE EGYPTIAN HIEROGLYPH M044: try adding egyptian-hieroglyphs</li>
<li>U+131EF EGYPTIAN HIEROGLYPH N001: try adding egyptian-hieroglyphs</li>
<li>U+131F0 EGYPTIAN HIEROGLYPH N002: try adding egyptian-hieroglyphs</li>
<li>U+131F1 EGYPTIAN HIEROGLYPH N003: try adding egyptian-hieroglyphs</li>
<li>U+131F2 EGYPTIAN HIEROGLYPH N004: try adding egyptian-hieroglyphs</li>
<li>U+131F3 EGYPTIAN HIEROGLYPH N005: try adding egyptian-hieroglyphs</li>
<li>U+131F4 EGYPTIAN HIEROGLYPH N006: try adding egyptian-hieroglyphs</li>
<li>U+131F5 EGYPTIAN HIEROGLYPH N007: try adding egyptian-hieroglyphs</li>
<li>U+131F6 EGYPTIAN HIEROGLYPH N008: try adding egyptian-hieroglyphs</li>
<li>U+131F7 EGYPTIAN HIEROGLYPH N009: try adding egyptian-hieroglyphs</li>
<li>U+131F8 EGYPTIAN HIEROGLYPH N010: try adding egyptian-hieroglyphs</li>
<li>U+131F9 EGYPTIAN HIEROGLYPH N011: try adding egyptian-hieroglyphs</li>
<li>U+131FA EGYPTIAN HIEROGLYPH N012: try adding egyptian-hieroglyphs</li>
<li>U+131FB EGYPTIAN HIEROGLYPH N013: try adding egyptian-hieroglyphs</li>
<li>U+131FC EGYPTIAN HIEROGLYPH N014: try adding egyptian-hieroglyphs</li>
<li>U+131FD EGYPTIAN HIEROGLYPH N015: try adding egyptian-hieroglyphs</li>
<li>U+131FE EGYPTIAN HIEROGLYPH N016: try adding egyptian-hieroglyphs</li>
<li>U+131FF EGYPTIAN HIEROGLYPH N017: try adding egyptian-hieroglyphs</li>
<li>U+13200 EGYPTIAN HIEROGLYPH N018: try adding egyptian-hieroglyphs</li>
<li>U+13201 EGYPTIAN HIEROGLYPH N018A: try adding egyptian-hieroglyphs</li>
<li>U+13202 EGYPTIAN HIEROGLYPH N018B: try adding egyptian-hieroglyphs</li>
<li>U+13203 EGYPTIAN HIEROGLYPH N019: try adding egyptian-hieroglyphs</li>
<li>U+13204 EGYPTIAN HIEROGLYPH N020: try adding egyptian-hieroglyphs</li>
<li>U+13205 EGYPTIAN HIEROGLYPH N021: try adding egyptian-hieroglyphs</li>
<li>U+13206 EGYPTIAN HIEROGLYPH N022: try adding egyptian-hieroglyphs</li>
<li>U+13207 EGYPTIAN HIEROGLYPH N023: try adding egyptian-hieroglyphs</li>
<li>U+13208 EGYPTIAN HIEROGLYPH N024: try adding egyptian-hieroglyphs</li>
<li>U+13209 EGYPTIAN HIEROGLYPH N025: try adding egyptian-hieroglyphs</li>
<li>U+1320A EGYPTIAN HIEROGLYPH N025A: try adding egyptian-hieroglyphs</li>
<li>U+1320B EGYPTIAN HIEROGLYPH N026: try adding egyptian-hieroglyphs</li>
<li>U+1320C EGYPTIAN HIEROGLYPH N027: try adding egyptian-hieroglyphs</li>
<li>U+1320D EGYPTIAN HIEROGLYPH N028: try adding egyptian-hieroglyphs</li>
<li>U+1320E EGYPTIAN HIEROGLYPH N029: try adding egyptian-hieroglyphs</li>
<li>U+1320F EGYPTIAN HIEROGLYPH N030: try adding egyptian-hieroglyphs</li>
<li>U+13210 EGYPTIAN HIEROGLYPH N031: try adding egyptian-hieroglyphs</li>
<li>U+13211 EGYPTIAN HIEROGLYPH N032: try adding egyptian-hieroglyphs</li>
<li>U+13212 EGYPTIAN HIEROGLYPH N033: try adding egyptian-hieroglyphs</li>
<li>U+13213 EGYPTIAN HIEROGLYPH N033A: try adding egyptian-hieroglyphs</li>
<li>U+13214 EGYPTIAN HIEROGLYPH N034: try adding egyptian-hieroglyphs</li>
<li>U+13215 EGYPTIAN HIEROGLYPH N034A: try adding egyptian-hieroglyphs</li>
<li>U+13216 EGYPTIAN HIEROGLYPH N035: try adding egyptian-hieroglyphs</li>
<li>U+13217 EGYPTIAN HIEROGLYPH N035A: try adding egyptian-hieroglyphs</li>
<li>U+13218 EGYPTIAN HIEROGLYPH N036: try adding egyptian-hieroglyphs</li>
<li>U+13219 EGYPTIAN HIEROGLYPH N037: try adding egyptian-hieroglyphs</li>
<li>U+1321A EGYPTIAN HIEROGLYPH N037A: try adding egyptian-hieroglyphs</li>
<li>U+1321B EGYPTIAN HIEROGLYPH N038: try adding egyptian-hieroglyphs</li>
<li>U+1321C EGYPTIAN HIEROGLYPH N039: try adding egyptian-hieroglyphs</li>
<li>U+1321D EGYPTIAN HIEROGLYPH N040: try adding egyptian-hieroglyphs</li>
<li>U+1321E EGYPTIAN HIEROGLYPH N041: try adding egyptian-hieroglyphs</li>
<li>U+1321F EGYPTIAN HIEROGLYPH N042: try adding egyptian-hieroglyphs</li>
<li>U+13220 EGYPTIAN HIEROGLYPH NL001: try adding egyptian-hieroglyphs</li>
<li>U+13221 EGYPTIAN HIEROGLYPH NL002: try adding egyptian-hieroglyphs</li>
<li>U+13222 EGYPTIAN HIEROGLYPH NL003: try adding egyptian-hieroglyphs</li>
<li>U+13223 EGYPTIAN HIEROGLYPH NL004: try adding egyptian-hieroglyphs</li>
<li>U+13224 EGYPTIAN HIEROGLYPH NL005: try adding egyptian-hieroglyphs</li>
<li>U+13225 EGYPTIAN HIEROGLYPH NL005A: try adding egyptian-hieroglyphs</li>
<li>U+13226 EGYPTIAN HIEROGLYPH NL006: try adding egyptian-hieroglyphs</li>
<li>U+13227 EGYPTIAN HIEROGLYPH NL007: try adding egyptian-hieroglyphs</li>
<li>U+13228 EGYPTIAN HIEROGLYPH NL008: try adding egyptian-hieroglyphs</li>
<li>U+13229 EGYPTIAN HIEROGLYPH NL009: try adding egyptian-hieroglyphs</li>
<li>U+1322A EGYPTIAN HIEROGLYPH NL010: try adding egyptian-hieroglyphs</li>
<li>U+1322B EGYPTIAN HIEROGLYPH NL011: try adding egyptian-hieroglyphs</li>
<li>U+1322C EGYPTIAN HIEROGLYPH NL012: try adding egyptian-hieroglyphs</li>
<li>U+1322D EGYPTIAN HIEROGLYPH NL013: try adding egyptian-hieroglyphs</li>
<li>U+1322E EGYPTIAN HIEROGLYPH NL014: try adding egyptian-hieroglyphs</li>
<li>U+1322F EGYPTIAN HIEROGLYPH NL015: try adding egyptian-hieroglyphs</li>
<li>U+13230 EGYPTIAN HIEROGLYPH NL016: try adding egyptian-hieroglyphs</li>
<li>U+13231 EGYPTIAN HIEROGLYPH NL017: try adding egyptian-hieroglyphs</li>
<li>U+13232 EGYPTIAN HIEROGLYPH NL017A: try adding egyptian-hieroglyphs</li>
<li>U+13233 EGYPTIAN HIEROGLYPH NL018: try adding egyptian-hieroglyphs</li>
<li>U+13234 EGYPTIAN HIEROGLYPH NL019: try adding egyptian-hieroglyphs</li>
<li>U+13235 EGYPTIAN HIEROGLYPH NL020: try adding egyptian-hieroglyphs</li>
<li>U+13236 EGYPTIAN HIEROGLYPH NU001: try adding egyptian-hieroglyphs</li>
<li>U+13237 EGYPTIAN HIEROGLYPH NU002: try adding egyptian-hieroglyphs</li>
<li>U+13238 EGYPTIAN HIEROGLYPH NU003: try adding egyptian-hieroglyphs</li>
<li>U+13239 EGYPTIAN HIEROGLYPH NU004: try adding egyptian-hieroglyphs</li>
<li>U+1323A EGYPTIAN HIEROGLYPH NU005: try adding egyptian-hieroglyphs</li>
<li>U+1323B EGYPTIAN HIEROGLYPH NU006: try adding egyptian-hieroglyphs</li>
<li>U+1323C EGYPTIAN HIEROGLYPH NU007: try adding egyptian-hieroglyphs</li>
<li>U+1323D EGYPTIAN HIEROGLYPH NU008: try adding egyptian-hieroglyphs</li>
<li>U+1323E EGYPTIAN HIEROGLYPH NU009: try adding egyptian-hieroglyphs</li>
<li>U+1323F EGYPTIAN HIEROGLYPH NU010: try adding egyptian-hieroglyphs</li>
<li>U+13240 EGYPTIAN HIEROGLYPH NU010A: try adding egyptian-hieroglyphs</li>
<li>U+13241 EGYPTIAN HIEROGLYPH NU011: try adding egyptian-hieroglyphs</li>
<li>U+13242 EGYPTIAN HIEROGLYPH NU011A: try adding egyptian-hieroglyphs</li>
<li>U+13243 EGYPTIAN HIEROGLYPH NU012: try adding egyptian-hieroglyphs</li>
<li>U+13244 EGYPTIAN HIEROGLYPH NU013: try adding egyptian-hieroglyphs</li>
<li>U+13245 EGYPTIAN HIEROGLYPH NU014: try adding egyptian-hieroglyphs</li>
<li>U+13246 EGYPTIAN HIEROGLYPH NU015: try adding egyptian-hieroglyphs</li>
<li>U+13247 EGYPTIAN HIEROGLYPH NU016: try adding egyptian-hieroglyphs</li>
<li>U+13248 EGYPTIAN HIEROGLYPH NU017: try adding egyptian-hieroglyphs</li>
<li>U+13249 EGYPTIAN HIEROGLYPH NU018: try adding egyptian-hieroglyphs</li>
<li>U+1324A EGYPTIAN HIEROGLYPH NU018A: try adding egyptian-hieroglyphs</li>
<li>U+1324B EGYPTIAN HIEROGLYPH NU019: try adding egyptian-hieroglyphs</li>
<li>U+1324C EGYPTIAN HIEROGLYPH NU020: try adding egyptian-hieroglyphs</li>
<li>U+1324D EGYPTIAN HIEROGLYPH NU021: try adding egyptian-hieroglyphs</li>
<li>U+1324E EGYPTIAN HIEROGLYPH NU022: try adding egyptian-hieroglyphs</li>
<li>U+1324F EGYPTIAN HIEROGLYPH NU022A: try adding egyptian-hieroglyphs</li>
<li>U+13250 EGYPTIAN HIEROGLYPH O001: try adding egyptian-hieroglyphs</li>
<li>U+13251 EGYPTIAN HIEROGLYPH O001A: try adding egyptian-hieroglyphs</li>
<li>U+13252 EGYPTIAN HIEROGLYPH O002: try adding egyptian-hieroglyphs</li>
<li>U+13253 EGYPTIAN HIEROGLYPH O003: try adding egyptian-hieroglyphs</li>
<li>U+13254 EGYPTIAN HIEROGLYPH O004: try adding egyptian-hieroglyphs</li>
<li>U+13255 EGYPTIAN HIEROGLYPH O005: try adding egyptian-hieroglyphs</li>
<li>U+13256 EGYPTIAN HIEROGLYPH O005A: try adding egyptian-hieroglyphs</li>
<li>U+13257 EGYPTIAN HIEROGLYPH O006: try adding egyptian-hieroglyphs</li>
<li>U+13258 EGYPTIAN HIEROGLYPH O006A: try adding egyptian-hieroglyphs</li>
<li>U+13259 EGYPTIAN HIEROGLYPH O006B: try adding egyptian-hieroglyphs</li>
<li>U+1325A EGYPTIAN HIEROGLYPH O006C: try adding egyptian-hieroglyphs</li>
<li>U+1325B EGYPTIAN HIEROGLYPH O006D: try adding egyptian-hieroglyphs</li>
<li>U+1325C EGYPTIAN HIEROGLYPH O006E: try adding egyptian-hieroglyphs</li>
<li>U+1325D EGYPTIAN HIEROGLYPH O006F: try adding egyptian-hieroglyphs</li>
<li>U+1325E EGYPTIAN HIEROGLYPH O007: try adding egyptian-hieroglyphs</li>
<li>U+1325F EGYPTIAN HIEROGLYPH O008: try adding egyptian-hieroglyphs</li>
<li>U+13260 EGYPTIAN HIEROGLYPH O009: try adding egyptian-hieroglyphs</li>
<li>U+13261 EGYPTIAN HIEROGLYPH O010: try adding egyptian-hieroglyphs</li>
<li>U+13262 EGYPTIAN HIEROGLYPH O010A: try adding egyptian-hieroglyphs</li>
<li>U+13263 EGYPTIAN HIEROGLYPH O010B: try adding egyptian-hieroglyphs</li>
<li>U+13264 EGYPTIAN HIEROGLYPH O010C: try adding egyptian-hieroglyphs</li>
<li>U+13265 EGYPTIAN HIEROGLYPH O011: try adding egyptian-hieroglyphs</li>
<li>U+13266 EGYPTIAN HIEROGLYPH O012: try adding egyptian-hieroglyphs</li>
<li>U+13267 EGYPTIAN HIEROGLYPH O013: try adding egyptian-hieroglyphs</li>
<li>U+13268 EGYPTIAN HIEROGLYPH O014: try adding egyptian-hieroglyphs</li>
<li>U+13269 EGYPTIAN HIEROGLYPH O015: try adding egyptian-hieroglyphs</li>
<li>U+1326A EGYPTIAN HIEROGLYPH O016: try adding egyptian-hieroglyphs</li>
<li>U+1326B EGYPTIAN HIEROGLYPH O017: try adding egyptian-hieroglyphs</li>
<li>U+1326C EGYPTIAN HIEROGLYPH O018: try adding egyptian-hieroglyphs</li>
<li>U+1326D EGYPTIAN HIEROGLYPH O019: try adding egyptian-hieroglyphs</li>
<li>U+1326E EGYPTIAN HIEROGLYPH O019A: try adding egyptian-hieroglyphs</li>
<li>U+1326F EGYPTIAN HIEROGLYPH O020: try adding egyptian-hieroglyphs</li>
<li>U+13270 EGYPTIAN HIEROGLYPH O020A: try adding egyptian-hieroglyphs</li>
<li>U+13271 EGYPTIAN HIEROGLYPH O021: try adding egyptian-hieroglyphs</li>
<li>U+13272 EGYPTIAN HIEROGLYPH O022: try adding egyptian-hieroglyphs</li>
<li>U+13273 EGYPTIAN HIEROGLYPH O023: try adding egyptian-hieroglyphs</li>
<li>U+13274 EGYPTIAN HIEROGLYPH O024: try adding egyptian-hieroglyphs</li>
<li>U+13275 EGYPTIAN HIEROGLYPH O024A: try adding egyptian-hieroglyphs</li>
<li>U+13276 EGYPTIAN HIEROGLYPH O025: try adding egyptian-hieroglyphs</li>
<li>U+13277 EGYPTIAN HIEROGLYPH O025A: try adding egyptian-hieroglyphs</li>
<li>U+13278 EGYPTIAN HIEROGLYPH O026: try adding egyptian-hieroglyphs</li>
<li>U+13279 EGYPTIAN HIEROGLYPH O027: try adding egyptian-hieroglyphs</li>
<li>U+1327A EGYPTIAN HIEROGLYPH O028: try adding egyptian-hieroglyphs</li>
<li>U+1327B EGYPTIAN HIEROGLYPH O029: try adding egyptian-hieroglyphs</li>
<li>U+1327C EGYPTIAN HIEROGLYPH O029A: try adding egyptian-hieroglyphs</li>
<li>U+1327D EGYPTIAN HIEROGLYPH O030: try adding egyptian-hieroglyphs</li>
<li>U+1327E EGYPTIAN HIEROGLYPH O030A: try adding egyptian-hieroglyphs</li>
<li>U+1327F EGYPTIAN HIEROGLYPH O031: try adding egyptian-hieroglyphs</li>
<li>U+13280 EGYPTIAN HIEROGLYPH O032: try adding egyptian-hieroglyphs</li>
<li>U+13281 EGYPTIAN HIEROGLYPH O033: try adding egyptian-hieroglyphs</li>
<li>U+13282 EGYPTIAN HIEROGLYPH O033A: try adding egyptian-hieroglyphs</li>
<li>U+13283 EGYPTIAN HIEROGLYPH O034: try adding egyptian-hieroglyphs</li>
<li>U+13284 EGYPTIAN HIEROGLYPH O035: try adding egyptian-hieroglyphs</li>
<li>U+13285 EGYPTIAN HIEROGLYPH O036: try adding egyptian-hieroglyphs</li>
<li>U+13286 EGYPTIAN HIEROGLYPH O036A: try adding egyptian-hieroglyphs</li>
<li>U+13287 EGYPTIAN HIEROGLYPH O036B: try adding egyptian-hieroglyphs</li>
<li>U+13288 EGYPTIAN HIEROGLYPH O036C: try adding egyptian-hieroglyphs</li>
<li>U+13289 EGYPTIAN HIEROGLYPH O036D: try adding egyptian-hieroglyphs</li>
<li>U+1328A EGYPTIAN HIEROGLYPH O037: try adding egyptian-hieroglyphs</li>
<li>U+1328B EGYPTIAN HIEROGLYPH O038: try adding egyptian-hieroglyphs</li>
<li>U+1328C EGYPTIAN HIEROGLYPH O039: try adding egyptian-hieroglyphs</li>
<li>U+1328D EGYPTIAN HIEROGLYPH O040: try adding egyptian-hieroglyphs</li>
<li>U+1328E EGYPTIAN HIEROGLYPH O041: try adding egyptian-hieroglyphs</li>
<li>U+1328F EGYPTIAN HIEROGLYPH O042: try adding egyptian-hieroglyphs</li>
<li>U+13290 EGYPTIAN HIEROGLYPH O043: try adding egyptian-hieroglyphs</li>
<li>U+13291 EGYPTIAN HIEROGLYPH O044: try adding egyptian-hieroglyphs</li>
<li>U+13292 EGYPTIAN HIEROGLYPH O045: try adding egyptian-hieroglyphs</li>
<li>U+13293 EGYPTIAN HIEROGLYPH O046: try adding egyptian-hieroglyphs</li>
<li>U+13294 EGYPTIAN HIEROGLYPH O047: try adding egyptian-hieroglyphs</li>
<li>U+13295 EGYPTIAN HIEROGLYPH O048: try adding egyptian-hieroglyphs</li>
<li>U+13296 EGYPTIAN HIEROGLYPH O049: try adding egyptian-hieroglyphs</li>
<li>U+13297 EGYPTIAN HIEROGLYPH O050: try adding egyptian-hieroglyphs</li>
<li>U+13298 EGYPTIAN HIEROGLYPH O050A: try adding egyptian-hieroglyphs</li>
<li>U+13299 EGYPTIAN HIEROGLYPH O050B: try adding egyptian-hieroglyphs</li>
<li>U+1329A EGYPTIAN HIEROGLYPH O051: try adding egyptian-hieroglyphs</li>
<li>U+1329B EGYPTIAN HIEROGLYPH P001: try adding egyptian-hieroglyphs</li>
<li>U+1329C EGYPTIAN HIEROGLYPH P001A: try adding egyptian-hieroglyphs</li>
<li>U+1329D EGYPTIAN HIEROGLYPH P002: try adding egyptian-hieroglyphs</li>
<li>U+1329E EGYPTIAN HIEROGLYPH P003: try adding egyptian-hieroglyphs</li>
<li>U+1329F EGYPTIAN HIEROGLYPH P003A: try adding egyptian-hieroglyphs</li>
<li>U+132A0 EGYPTIAN HIEROGLYPH P004: try adding egyptian-hieroglyphs</li>
<li>U+132A1 EGYPTIAN HIEROGLYPH P005: try adding egyptian-hieroglyphs</li>
<li>U+132A2 EGYPTIAN HIEROGLYPH P006: try adding egyptian-hieroglyphs</li>
<li>U+132A3 EGYPTIAN HIEROGLYPH P007: try adding egyptian-hieroglyphs</li>
<li>U+132A4 EGYPTIAN HIEROGLYPH P008: try adding egyptian-hieroglyphs</li>
<li>U+132A5 EGYPTIAN HIEROGLYPH P009: try adding egyptian-hieroglyphs</li>
<li>U+132A6 EGYPTIAN HIEROGLYPH P010: try adding egyptian-hieroglyphs</li>
<li>U+132A7 EGYPTIAN HIEROGLYPH P011: try adding egyptian-hieroglyphs</li>
<li>U+132A8 EGYPTIAN HIEROGLYPH Q001: try adding egyptian-hieroglyphs</li>
<li>U+132A9 EGYPTIAN HIEROGLYPH Q002: try adding egyptian-hieroglyphs</li>
<li>U+132AA EGYPTIAN HIEROGLYPH Q003: try adding egyptian-hieroglyphs</li>
<li>U+132AB EGYPTIAN HIEROGLYPH Q004: try adding egyptian-hieroglyphs</li>
<li>U+132AC EGYPTIAN HIEROGLYPH Q005: try adding egyptian-hieroglyphs</li>
<li>U+132AD EGYPTIAN HIEROGLYPH Q006: try adding egyptian-hieroglyphs</li>
<li>U+132AE EGYPTIAN HIEROGLYPH Q007: try adding egyptian-hieroglyphs</li>
<li>U+132AF EGYPTIAN HIEROGLYPH R001: try adding egyptian-hieroglyphs</li>
<li>U+132B0 EGYPTIAN HIEROGLYPH R002: try adding egyptian-hieroglyphs</li>
<li>U+132B1 EGYPTIAN HIEROGLYPH R002A: try adding egyptian-hieroglyphs</li>
<li>U+132B2 EGYPTIAN HIEROGLYPH R003: try adding egyptian-hieroglyphs</li>
<li>U+132B3 EGYPTIAN HIEROGLYPH R003A: try adding egyptian-hieroglyphs</li>
<li>U+132B4 EGYPTIAN HIEROGLYPH R003B: try adding egyptian-hieroglyphs</li>
<li>U+132B5 EGYPTIAN HIEROGLYPH R004: try adding egyptian-hieroglyphs</li>
<li>U+132B6 EGYPTIAN HIEROGLYPH R005: try adding egyptian-hieroglyphs</li>
<li>U+132B7 EGYPTIAN HIEROGLYPH R006: try adding egyptian-hieroglyphs</li>
<li>U+132B8 EGYPTIAN HIEROGLYPH R007: try adding egyptian-hieroglyphs</li>
<li>U+132B9 EGYPTIAN HIEROGLYPH R008: try adding egyptian-hieroglyphs</li>
<li>U+132BA EGYPTIAN HIEROGLYPH R009: try adding egyptian-hieroglyphs</li>
<li>U+132BB EGYPTIAN HIEROGLYPH R010: try adding egyptian-hieroglyphs</li>
<li>U+132BC EGYPTIAN HIEROGLYPH R010A: try adding egyptian-hieroglyphs</li>
<li>U+132BD EGYPTIAN HIEROGLYPH R011: try adding egyptian-hieroglyphs</li>
<li>U+132BE EGYPTIAN HIEROGLYPH R012: try adding egyptian-hieroglyphs</li>
<li>U+132BF EGYPTIAN HIEROGLYPH R013: try adding egyptian-hieroglyphs</li>
<li>U+132C0 EGYPTIAN HIEROGLYPH R014: try adding egyptian-hieroglyphs</li>
<li>U+132C1 EGYPTIAN HIEROGLYPH R015: try adding egyptian-hieroglyphs</li>
<li>U+132C2 EGYPTIAN HIEROGLYPH R016: try adding egyptian-hieroglyphs</li>
<li>U+132C3 EGYPTIAN HIEROGLYPH R016A: try adding egyptian-hieroglyphs</li>
<li>U+132C4 EGYPTIAN HIEROGLYPH R017: try adding egyptian-hieroglyphs</li>
<li>U+132C5 EGYPTIAN HIEROGLYPH R018: try adding egyptian-hieroglyphs</li>
<li>U+132C6 EGYPTIAN HIEROGLYPH R019: try adding egyptian-hieroglyphs</li>
<li>U+132C7 EGYPTIAN HIEROGLYPH R020: try adding egyptian-hieroglyphs</li>
<li>U+132C8 EGYPTIAN HIEROGLYPH R021: try adding egyptian-hieroglyphs</li>
<li>U+132C9 EGYPTIAN HIEROGLYPH R022: try adding egyptian-hieroglyphs</li>
<li>U+132CA EGYPTIAN HIEROGLYPH R023: try adding egyptian-hieroglyphs</li>
<li>U+132CB EGYPTIAN HIEROGLYPH R024: try adding egyptian-hieroglyphs</li>
<li>U+132CC EGYPTIAN HIEROGLYPH R025: try adding egyptian-hieroglyphs</li>
<li>U+132CD EGYPTIAN HIEROGLYPH R026: try adding egyptian-hieroglyphs</li>
<li>U+132CE EGYPTIAN HIEROGLYPH R027: try adding egyptian-hieroglyphs</li>
<li>U+132CF EGYPTIAN HIEROGLYPH R028: try adding egyptian-hieroglyphs</li>
<li>U+132D0 EGYPTIAN HIEROGLYPH R029: try adding egyptian-hieroglyphs</li>
<li>U+132D1 EGYPTIAN HIEROGLYPH S001: try adding egyptian-hieroglyphs</li>
<li>U+132D2 EGYPTIAN HIEROGLYPH S002: try adding egyptian-hieroglyphs</li>
<li>U+132D3 EGYPTIAN HIEROGLYPH S002A: try adding egyptian-hieroglyphs</li>
<li>U+132D4 EGYPTIAN HIEROGLYPH S003: try adding egyptian-hieroglyphs</li>
<li>U+132D5 EGYPTIAN HIEROGLYPH S004: try adding egyptian-hieroglyphs</li>
<li>U+132D6 EGYPTIAN HIEROGLYPH S005: try adding egyptian-hieroglyphs</li>
<li>U+132D7 EGYPTIAN HIEROGLYPH S006: try adding egyptian-hieroglyphs</li>
<li>U+132D8 EGYPTIAN HIEROGLYPH S006A: try adding egyptian-hieroglyphs</li>
<li>U+132D9 EGYPTIAN HIEROGLYPH S007: try adding egyptian-hieroglyphs</li>
<li>U+132DA EGYPTIAN HIEROGLYPH S008: try adding egyptian-hieroglyphs</li>
<li>U+132DB EGYPTIAN HIEROGLYPH S009: try adding egyptian-hieroglyphs</li>
<li>U+132DC EGYPTIAN HIEROGLYPH S010: try adding egyptian-hieroglyphs</li>
<li>U+132DD EGYPTIAN HIEROGLYPH S011: try adding egyptian-hieroglyphs</li>
<li>U+132DE EGYPTIAN HIEROGLYPH S012: try adding egyptian-hieroglyphs</li>
<li>U+132DF EGYPTIAN HIEROGLYPH S013: try adding egyptian-hieroglyphs</li>
<li>U+132E0 EGYPTIAN HIEROGLYPH S014: try adding egyptian-hieroglyphs</li>
<li>U+132E1 EGYPTIAN HIEROGLYPH S014A: try adding egyptian-hieroglyphs</li>
<li>U+132E2 EGYPTIAN HIEROGLYPH S014B: try adding egyptian-hieroglyphs</li>
<li>U+132E3 EGYPTIAN HIEROGLYPH S015: try adding egyptian-hieroglyphs</li>
<li>U+132E4 EGYPTIAN HIEROGLYPH S016: try adding egyptian-hieroglyphs</li>
<li>U+132E5 EGYPTIAN HIEROGLYPH S017: try adding egyptian-hieroglyphs</li>
<li>U+132E6 EGYPTIAN HIEROGLYPH S017A: try adding egyptian-hieroglyphs</li>
<li>U+132E7 EGYPTIAN HIEROGLYPH S018: try adding egyptian-hieroglyphs</li>
<li>U+132E8 EGYPTIAN HIEROGLYPH S019: try adding egyptian-hieroglyphs</li>
<li>U+132E9 EGYPTIAN HIEROGLYPH S020: try adding egyptian-hieroglyphs</li>
<li>U+132EA EGYPTIAN HIEROGLYPH S021: try adding egyptian-hieroglyphs</li>
<li>U+132EB EGYPTIAN HIEROGLYPH S022: try adding egyptian-hieroglyphs</li>
<li>U+132EC EGYPTIAN HIEROGLYPH S023: try adding egyptian-hieroglyphs</li>
<li>U+132ED EGYPTIAN HIEROGLYPH S024: try adding egyptian-hieroglyphs</li>
<li>U+132EE EGYPTIAN HIEROGLYPH S025: try adding egyptian-hieroglyphs</li>
<li>U+132EF EGYPTIAN HIEROGLYPH S026: try adding egyptian-hieroglyphs</li>
<li>U+132F0 EGYPTIAN HIEROGLYPH S026A: try adding egyptian-hieroglyphs</li>
<li>U+132F1 EGYPTIAN HIEROGLYPH S026B: try adding egyptian-hieroglyphs</li>
<li>U+132F2 EGYPTIAN HIEROGLYPH S027: try adding egyptian-hieroglyphs</li>
<li>U+132F3 EGYPTIAN HIEROGLYPH S028: try adding egyptian-hieroglyphs</li>
<li>U+132F4 EGYPTIAN HIEROGLYPH S029: try adding egyptian-hieroglyphs</li>
<li>U+132F5 EGYPTIAN HIEROGLYPH S030: try adding egyptian-hieroglyphs</li>
<li>U+132F6 EGYPTIAN HIEROGLYPH S031: try adding egyptian-hieroglyphs</li>
<li>U+132F7 EGYPTIAN HIEROGLYPH S032: try adding egyptian-hieroglyphs</li>
<li>U+132F8 EGYPTIAN HIEROGLYPH S033: try adding egyptian-hieroglyphs</li>
<li>U+132F9 EGYPTIAN HIEROGLYPH S034: try adding egyptian-hieroglyphs</li>
<li>U+132FA EGYPTIAN HIEROGLYPH S035: try adding egyptian-hieroglyphs</li>
<li>U+132FB EGYPTIAN HIEROGLYPH S035A: try adding egyptian-hieroglyphs</li>
<li>U+132FC EGYPTIAN HIEROGLYPH S036: try adding egyptian-hieroglyphs</li>
<li>U+132FD EGYPTIAN HIEROGLYPH S037: try adding egyptian-hieroglyphs</li>
<li>U+132FE EGYPTIAN HIEROGLYPH S038: try adding egyptian-hieroglyphs</li>
<li>U+132FF EGYPTIAN HIEROGLYPH S039: try adding egyptian-hieroglyphs</li>
<li>U+13300 EGYPTIAN HIEROGLYPH S040: try adding egyptian-hieroglyphs</li>
<li>U+13301 EGYPTIAN HIEROGLYPH S041: try adding egyptian-hieroglyphs</li>
<li>U+13302 EGYPTIAN HIEROGLYPH S042: try adding egyptian-hieroglyphs</li>
<li>U+13303 EGYPTIAN HIEROGLYPH S043: try adding egyptian-hieroglyphs</li>
<li>U+13304 EGYPTIAN HIEROGLYPH S044: try adding egyptian-hieroglyphs</li>
<li>U+13305 EGYPTIAN HIEROGLYPH S045: try adding egyptian-hieroglyphs</li>
<li>U+13306 EGYPTIAN HIEROGLYPH S046: try adding egyptian-hieroglyphs</li>
<li>U+13307 EGYPTIAN HIEROGLYPH T001: try adding egyptian-hieroglyphs</li>
<li>U+13308 EGYPTIAN HIEROGLYPH T002: try adding egyptian-hieroglyphs</li>
<li>U+13309 EGYPTIAN HIEROGLYPH T003: try adding egyptian-hieroglyphs</li>
<li>U+1330A EGYPTIAN HIEROGLYPH T003A: try adding egyptian-hieroglyphs</li>
<li>U+1330B EGYPTIAN HIEROGLYPH T004: try adding egyptian-hieroglyphs</li>
<li>U+1330C EGYPTIAN HIEROGLYPH T005: try adding egyptian-hieroglyphs</li>
<li>U+1330D EGYPTIAN HIEROGLYPH T006: try adding egyptian-hieroglyphs</li>
<li>U+1330E EGYPTIAN HIEROGLYPH T007: try adding egyptian-hieroglyphs</li>
<li>U+1330F EGYPTIAN HIEROGLYPH T007A: try adding egyptian-hieroglyphs</li>
<li>U+13310 EGYPTIAN HIEROGLYPH T008: try adding egyptian-hieroglyphs</li>
<li>U+13311 EGYPTIAN HIEROGLYPH T008A: try adding egyptian-hieroglyphs</li>
<li>U+13312 EGYPTIAN HIEROGLYPH T009: try adding egyptian-hieroglyphs</li>
<li>U+13313 EGYPTIAN HIEROGLYPH T009A: try adding egyptian-hieroglyphs</li>
<li>U+13314 EGYPTIAN HIEROGLYPH T010: try adding egyptian-hieroglyphs</li>
<li>U+13315 EGYPTIAN HIEROGLYPH T011: try adding egyptian-hieroglyphs</li>
<li>U+13316 EGYPTIAN HIEROGLYPH T011A: try adding egyptian-hieroglyphs</li>
<li>U+13317 EGYPTIAN HIEROGLYPH T012: try adding egyptian-hieroglyphs</li>
<li>U+13318 EGYPTIAN HIEROGLYPH T013: try adding egyptian-hieroglyphs</li>
<li>U+13319 EGYPTIAN HIEROGLYPH T014: try adding egyptian-hieroglyphs</li>
<li>U+1331A EGYPTIAN HIEROGLYPH T015: try adding egyptian-hieroglyphs</li>
<li>U+1331B EGYPTIAN HIEROGLYPH T016: try adding egyptian-hieroglyphs</li>
<li>U+1331C EGYPTIAN HIEROGLYPH T016A: try adding egyptian-hieroglyphs</li>
<li>U+1331D EGYPTIAN HIEROGLYPH T017: try adding egyptian-hieroglyphs</li>
<li>U+1331E EGYPTIAN HIEROGLYPH T018: try adding egyptian-hieroglyphs</li>
<li>U+1331F EGYPTIAN HIEROGLYPH T019: try adding egyptian-hieroglyphs</li>
<li>U+13320 EGYPTIAN HIEROGLYPH T020: try adding egyptian-hieroglyphs</li>
<li>U+13321 EGYPTIAN HIEROGLYPH T021: try adding egyptian-hieroglyphs</li>
<li>U+13322 EGYPTIAN HIEROGLYPH T022: try adding egyptian-hieroglyphs</li>
<li>U+13323 EGYPTIAN HIEROGLYPH T023: try adding egyptian-hieroglyphs</li>
<li>U+13324 EGYPTIAN HIEROGLYPH T024: try adding egyptian-hieroglyphs</li>
<li>U+13325 EGYPTIAN HIEROGLYPH T025: try adding egyptian-hieroglyphs</li>
<li>U+13326 EGYPTIAN HIEROGLYPH T026: try adding egyptian-hieroglyphs</li>
<li>U+13327 EGYPTIAN HIEROGLYPH T027: try adding egyptian-hieroglyphs</li>
<li>U+13328 EGYPTIAN HIEROGLYPH T028: try adding egyptian-hieroglyphs</li>
<li>U+13329 EGYPTIAN HIEROGLYPH T029: try adding egyptian-hieroglyphs</li>
<li>U+1332A EGYPTIAN HIEROGLYPH T030: try adding egyptian-hieroglyphs</li>
<li>U+1332B EGYPTIAN HIEROGLYPH T031: try adding egyptian-hieroglyphs</li>
<li>U+1332C EGYPTIAN HIEROGLYPH T032: try adding egyptian-hieroglyphs</li>
<li>U+1332D EGYPTIAN HIEROGLYPH T032A: try adding egyptian-hieroglyphs</li>
<li>U+1332E EGYPTIAN HIEROGLYPH T033: try adding egyptian-hieroglyphs</li>
<li>U+1332F EGYPTIAN HIEROGLYPH T033A: try adding egyptian-hieroglyphs</li>
<li>U+13330 EGYPTIAN HIEROGLYPH T034: try adding egyptian-hieroglyphs</li>
<li>U+13331 EGYPTIAN HIEROGLYPH T035: try adding egyptian-hieroglyphs</li>
<li>U+13332 EGYPTIAN HIEROGLYPH T036: try adding egyptian-hieroglyphs</li>
<li>U+13333 EGYPTIAN HIEROGLYPH U001: try adding egyptian-hieroglyphs</li>
<li>U+13334 EGYPTIAN HIEROGLYPH U002: try adding egyptian-hieroglyphs</li>
<li>U+13335 EGYPTIAN HIEROGLYPH U003: try adding egyptian-hieroglyphs</li>
<li>U+13336 EGYPTIAN HIEROGLYPH U004: try adding egyptian-hieroglyphs</li>
<li>U+13337 EGYPTIAN HIEROGLYPH U005: try adding egyptian-hieroglyphs</li>
<li>U+13338 EGYPTIAN HIEROGLYPH U006: try adding egyptian-hieroglyphs</li>
<li>U+13339 EGYPTIAN HIEROGLYPH U006A: try adding egyptian-hieroglyphs</li>
<li>U+1333A EGYPTIAN HIEROGLYPH U006B: try adding egyptian-hieroglyphs</li>
<li>U+1333B EGYPTIAN HIEROGLYPH U007: try adding egyptian-hieroglyphs</li>
<li>U+1333C EGYPTIAN HIEROGLYPH U008: try adding egyptian-hieroglyphs</li>
<li>U+1333D EGYPTIAN HIEROGLYPH U009: try adding egyptian-hieroglyphs</li>
<li>U+1333E EGYPTIAN HIEROGLYPH U010: try adding egyptian-hieroglyphs</li>
<li>U+1333F EGYPTIAN HIEROGLYPH U011: try adding egyptian-hieroglyphs</li>
<li>U+13340 EGYPTIAN HIEROGLYPH U012: try adding egyptian-hieroglyphs</li>
<li>U+13341 EGYPTIAN HIEROGLYPH U013: try adding egyptian-hieroglyphs</li>
<li>U+13342 EGYPTIAN HIEROGLYPH U014: try adding egyptian-hieroglyphs</li>
<li>U+13343 EGYPTIAN HIEROGLYPH U015: try adding egyptian-hieroglyphs</li>
<li>U+13344 EGYPTIAN HIEROGLYPH U016: try adding egyptian-hieroglyphs</li>
<li>U+13345 EGYPTIAN HIEROGLYPH U017: try adding egyptian-hieroglyphs</li>
<li>U+13346 EGYPTIAN HIEROGLYPH U018: try adding egyptian-hieroglyphs</li>
<li>U+13347 EGYPTIAN HIEROGLYPH U019: try adding egyptian-hieroglyphs</li>
<li>U+13348 EGYPTIAN HIEROGLYPH U020: try adding egyptian-hieroglyphs</li>
<li>U+13349 EGYPTIAN HIEROGLYPH U021: try adding egyptian-hieroglyphs</li>
<li>U+1334A EGYPTIAN HIEROGLYPH U022: try adding egyptian-hieroglyphs</li>
<li>U+1334B EGYPTIAN HIEROGLYPH U023: try adding egyptian-hieroglyphs</li>
<li>U+1334C EGYPTIAN HIEROGLYPH U023A: try adding egyptian-hieroglyphs</li>
<li>U+1334D EGYPTIAN HIEROGLYPH U024: try adding egyptian-hieroglyphs</li>
<li>U+1334E EGYPTIAN HIEROGLYPH U025: try adding egyptian-hieroglyphs</li>
<li>U+1334F EGYPTIAN HIEROGLYPH U026: try adding egyptian-hieroglyphs</li>
<li>U+13350 EGYPTIAN HIEROGLYPH U027: try adding egyptian-hieroglyphs</li>
<li>U+13351 EGYPTIAN HIEROGLYPH U028: try adding egyptian-hieroglyphs</li>
<li>U+13352 EGYPTIAN HIEROGLYPH U029: try adding egyptian-hieroglyphs</li>
<li>U+13353 EGYPTIAN HIEROGLYPH U029A: try adding egyptian-hieroglyphs</li>
<li>U+13354 EGYPTIAN HIEROGLYPH U030: try adding egyptian-hieroglyphs</li>
<li>U+13355 EGYPTIAN HIEROGLYPH U031: try adding egyptian-hieroglyphs</li>
<li>U+13356 EGYPTIAN HIEROGLYPH U032: try adding egyptian-hieroglyphs</li>
<li>U+13357 EGYPTIAN HIEROGLYPH U032A: try adding egyptian-hieroglyphs</li>
<li>U+13358 EGYPTIAN HIEROGLYPH U033: try adding egyptian-hieroglyphs</li>
<li>U+13359 EGYPTIAN HIEROGLYPH U034: try adding egyptian-hieroglyphs</li>
<li>U+1335A EGYPTIAN HIEROGLYPH U035: try adding egyptian-hieroglyphs</li>
<li>U+1335B EGYPTIAN HIEROGLYPH U036: try adding egyptian-hieroglyphs</li>
<li>U+1335C EGYPTIAN HIEROGLYPH U037: try adding egyptian-hieroglyphs</li>
<li>U+1335D EGYPTIAN HIEROGLYPH U038: try adding egyptian-hieroglyphs</li>
<li>U+1335E EGYPTIAN HIEROGLYPH U039: try adding egyptian-hieroglyphs</li>
<li>U+1335F EGYPTIAN HIEROGLYPH U040: try adding egyptian-hieroglyphs</li>
<li>U+13360 EGYPTIAN HIEROGLYPH U041: try adding egyptian-hieroglyphs</li>
<li>U+13361 EGYPTIAN HIEROGLYPH U042: try adding egyptian-hieroglyphs</li>
<li>U+13362 EGYPTIAN HIEROGLYPH V001: try adding egyptian-hieroglyphs</li>
<li>U+13363 EGYPTIAN HIEROGLYPH V001A: try adding egyptian-hieroglyphs</li>
<li>U+13364 EGYPTIAN HIEROGLYPH V001B: try adding egyptian-hieroglyphs</li>
<li>U+13365 EGYPTIAN HIEROGLYPH V001C: try adding egyptian-hieroglyphs</li>
<li>U+13366 EGYPTIAN HIEROGLYPH V001D: try adding egyptian-hieroglyphs</li>
<li>U+13367 EGYPTIAN HIEROGLYPH V001E: try adding egyptian-hieroglyphs</li>
<li>U+13368 EGYPTIAN HIEROGLYPH V001F: try adding egyptian-hieroglyphs</li>
<li>U+13369 EGYPTIAN HIEROGLYPH V001G: try adding egyptian-hieroglyphs</li>
<li>U+1336A EGYPTIAN HIEROGLYPH V001H: try adding egyptian-hieroglyphs</li>
<li>U+1336B EGYPTIAN HIEROGLYPH V001I: try adding egyptian-hieroglyphs</li>
<li>U+1336C EGYPTIAN HIEROGLYPH V002: try adding egyptian-hieroglyphs</li>
<li>U+1336D EGYPTIAN HIEROGLYPH V002A: try adding egyptian-hieroglyphs</li>
<li>U+1336E EGYPTIAN HIEROGLYPH V003: try adding egyptian-hieroglyphs</li>
<li>U+1336F EGYPTIAN HIEROGLYPH V004: try adding egyptian-hieroglyphs</li>
<li>U+13370 EGYPTIAN HIEROGLYPH V005: try adding egyptian-hieroglyphs</li>
<li>U+13371 EGYPTIAN HIEROGLYPH V006: try adding egyptian-hieroglyphs</li>
<li>U+13372 EGYPTIAN HIEROGLYPH V007: try adding egyptian-hieroglyphs</li>
<li>U+13373 EGYPTIAN HIEROGLYPH V007A: try adding egyptian-hieroglyphs</li>
<li>U+13374 EGYPTIAN HIEROGLYPH V007B: try adding egyptian-hieroglyphs</li>
<li>U+13375 EGYPTIAN HIEROGLYPH V008: try adding egyptian-hieroglyphs</li>
<li>U+13376 EGYPTIAN HIEROGLYPH V009: try adding egyptian-hieroglyphs</li>
<li>U+13377 EGYPTIAN HIEROGLYPH V010: try adding egyptian-hieroglyphs</li>
<li>U+13378 EGYPTIAN HIEROGLYPH V011: try adding egyptian-hieroglyphs</li>
<li>U+13379 EGYPTIAN HIEROGLYPH V011A: try adding egyptian-hieroglyphs</li>
<li>U+1337A EGYPTIAN HIEROGLYPH V011B: try adding egyptian-hieroglyphs</li>
<li>U+1337B EGYPTIAN HIEROGLYPH V011C: try adding egyptian-hieroglyphs</li>
<li>U+1337C EGYPTIAN HIEROGLYPH V012: try adding egyptian-hieroglyphs</li>
<li>U+1337D EGYPTIAN HIEROGLYPH V012A: try adding egyptian-hieroglyphs</li>
<li>U+1337E EGYPTIAN HIEROGLYPH V012B: try adding egyptian-hieroglyphs</li>
<li>U+1337F EGYPTIAN HIEROGLYPH V013: try adding egyptian-hieroglyphs</li>
<li>U+13380 EGYPTIAN HIEROGLYPH V014: try adding egyptian-hieroglyphs</li>
<li>U+13381 EGYPTIAN HIEROGLYPH V015: try adding egyptian-hieroglyphs</li>
<li>U+13382 EGYPTIAN HIEROGLYPH V016: try adding egyptian-hieroglyphs</li>
<li>U+13383 EGYPTIAN HIEROGLYPH V017: try adding egyptian-hieroglyphs</li>
<li>U+13384 EGYPTIAN HIEROGLYPH V018: try adding egyptian-hieroglyphs</li>
<li>U+13385 EGYPTIAN HIEROGLYPH V019: try adding egyptian-hieroglyphs</li>
<li>U+13386 EGYPTIAN HIEROGLYPH V020: try adding egyptian-hieroglyphs</li>
<li>U+13387 EGYPTIAN HIEROGLYPH V020A: try adding egyptian-hieroglyphs</li>
<li>U+13388 EGYPTIAN HIEROGLYPH V020B: try adding egyptian-hieroglyphs</li>
<li>U+13389 EGYPTIAN HIEROGLYPH V020C: try adding egyptian-hieroglyphs</li>
<li>U+1338A EGYPTIAN HIEROGLYPH V020D: try adding egyptian-hieroglyphs</li>
<li>U+1338B EGYPTIAN HIEROGLYPH V020E: try adding egyptian-hieroglyphs</li>
<li>U+1338C EGYPTIAN HIEROGLYPH V020F: try adding egyptian-hieroglyphs</li>
<li>U+1338D EGYPTIAN HIEROGLYPH V020G: try adding egyptian-hieroglyphs</li>
<li>U+1338E EGYPTIAN HIEROGLYPH V020H: try adding egyptian-hieroglyphs</li>
<li>U+1338F EGYPTIAN HIEROGLYPH V020I: try adding egyptian-hieroglyphs</li>
<li>U+13390 EGYPTIAN HIEROGLYPH V020J: try adding egyptian-hieroglyphs</li>
<li>U+13391 EGYPTIAN HIEROGLYPH V020K: try adding egyptian-hieroglyphs</li>
<li>U+13392 EGYPTIAN HIEROGLYPH V020L: try adding egyptian-hieroglyphs</li>
<li>U+13393 EGYPTIAN HIEROGLYPH V021: try adding egyptian-hieroglyphs</li>
<li>U+13394 EGYPTIAN HIEROGLYPH V022: try adding egyptian-hieroglyphs</li>
<li>U+13395 EGYPTIAN HIEROGLYPH V023: try adding egyptian-hieroglyphs</li>
<li>U+13396 EGYPTIAN HIEROGLYPH V023A: try adding egyptian-hieroglyphs</li>
<li>U+13397 EGYPTIAN HIEROGLYPH V024: try adding egyptian-hieroglyphs</li>
<li>U+13398 EGYPTIAN HIEROGLYPH V025: try adding egyptian-hieroglyphs</li>
<li>U+13399 EGYPTIAN HIEROGLYPH V026: try adding egyptian-hieroglyphs</li>
<li>U+1339A EGYPTIAN HIEROGLYPH V027: try adding egyptian-hieroglyphs</li>
<li>U+1339B EGYPTIAN HIEROGLYPH V028: try adding egyptian-hieroglyphs</li>
<li>U+1339C EGYPTIAN HIEROGLYPH V028A: try adding egyptian-hieroglyphs</li>
<li>U+1339D EGYPTIAN HIEROGLYPH V029: try adding egyptian-hieroglyphs</li>
<li>U+1339E EGYPTIAN HIEROGLYPH V029A: try adding egyptian-hieroglyphs</li>
<li>U+1339F EGYPTIAN HIEROGLYPH V030: try adding egyptian-hieroglyphs</li>
<li>U+133A0 EGYPTIAN HIEROGLYPH V030A: try adding egyptian-hieroglyphs</li>
<li>U+133A1 EGYPTIAN HIEROGLYPH V031: try adding egyptian-hieroglyphs</li>
<li>U+133A2 EGYPTIAN HIEROGLYPH V031A: try adding egyptian-hieroglyphs</li>
<li>U+133A3 EGYPTIAN HIEROGLYPH V032: try adding egyptian-hieroglyphs</li>
<li>U+133A4 EGYPTIAN HIEROGLYPH V033: try adding egyptian-hieroglyphs</li>
<li>U+133A5 EGYPTIAN HIEROGLYPH V033A: try adding egyptian-hieroglyphs</li>
<li>U+133A6 EGYPTIAN HIEROGLYPH V034: try adding egyptian-hieroglyphs</li>
<li>U+133A7 EGYPTIAN HIEROGLYPH V035: try adding egyptian-hieroglyphs</li>
<li>U+133A8 EGYPTIAN HIEROGLYPH V036: try adding egyptian-hieroglyphs</li>
<li>U+133A9 EGYPTIAN HIEROGLYPH V037: try adding egyptian-hieroglyphs</li>
<li>U+133AA EGYPTIAN HIEROGLYPH V037A: try adding egyptian-hieroglyphs</li>
<li>U+133AB EGYPTIAN HIEROGLYPH V038: try adding egyptian-hieroglyphs</li>
<li>U+133AC EGYPTIAN HIEROGLYPH V039: try adding egyptian-hieroglyphs</li>
<li>U+133AD EGYPTIAN HIEROGLYPH V040: try adding egyptian-hieroglyphs</li>
<li>U+133AE EGYPTIAN HIEROGLYPH V040A: try adding egyptian-hieroglyphs</li>
<li>U+133AF EGYPTIAN HIEROGLYPH W001: try adding egyptian-hieroglyphs</li>
<li>U+133B0 EGYPTIAN HIEROGLYPH W002: try adding egyptian-hieroglyphs</li>
<li>U+133B1 EGYPTIAN HIEROGLYPH W003: try adding egyptian-hieroglyphs</li>
<li>U+133B2 EGYPTIAN HIEROGLYPH W003A: try adding egyptian-hieroglyphs</li>
<li>U+133B3 EGYPTIAN HIEROGLYPH W004: try adding egyptian-hieroglyphs</li>
<li>U+133B4 EGYPTIAN HIEROGLYPH W005: try adding egyptian-hieroglyphs</li>
<li>U+133B5 EGYPTIAN HIEROGLYPH W006: try adding egyptian-hieroglyphs</li>
<li>U+133B6 EGYPTIAN HIEROGLYPH W007: try adding egyptian-hieroglyphs</li>
<li>U+133B7 EGYPTIAN HIEROGLYPH W008: try adding egyptian-hieroglyphs</li>
<li>U+133B8 EGYPTIAN HIEROGLYPH W009: try adding egyptian-hieroglyphs</li>
<li>U+133B9 EGYPTIAN HIEROGLYPH W009A: try adding egyptian-hieroglyphs</li>
<li>U+133BA EGYPTIAN HIEROGLYPH W010: try adding egyptian-hieroglyphs</li>
<li>U+133BB EGYPTIAN HIEROGLYPH W010A: try adding egyptian-hieroglyphs</li>
<li>U+133BC EGYPTIAN HIEROGLYPH W011: try adding egyptian-hieroglyphs</li>
<li>U+133BD EGYPTIAN HIEROGLYPH W012: try adding egyptian-hieroglyphs</li>
<li>U+133BE EGYPTIAN HIEROGLYPH W013: try adding egyptian-hieroglyphs</li>
<li>U+133BF EGYPTIAN HIEROGLYPH W014: try adding egyptian-hieroglyphs</li>
<li>U+133C0 EGYPTIAN HIEROGLYPH W014A: try adding egyptian-hieroglyphs</li>
<li>U+133C1 EGYPTIAN HIEROGLYPH W015: try adding egyptian-hieroglyphs</li>
<li>U+133C2 EGYPTIAN HIEROGLYPH W016: try adding egyptian-hieroglyphs</li>
<li>U+133C3 EGYPTIAN HIEROGLYPH W017: try adding egyptian-hieroglyphs</li>
<li>U+133C4 EGYPTIAN HIEROGLYPH W017A: try adding egyptian-hieroglyphs</li>
<li>U+133C5 EGYPTIAN HIEROGLYPH W018: try adding egyptian-hieroglyphs</li>
<li>U+133C6 EGYPTIAN HIEROGLYPH W018A: try adding egyptian-hieroglyphs</li>
<li>U+133C7 EGYPTIAN HIEROGLYPH W019: try adding egyptian-hieroglyphs</li>
<li>U+133C8 EGYPTIAN HIEROGLYPH W020: try adding egyptian-hieroglyphs</li>
<li>U+133C9 EGYPTIAN HIEROGLYPH W021: try adding egyptian-hieroglyphs</li>
<li>U+133CA EGYPTIAN HIEROGLYPH W022: try adding egyptian-hieroglyphs</li>
<li>U+133CB EGYPTIAN HIEROGLYPH W023: try adding egyptian-hieroglyphs</li>
<li>U+133CC EGYPTIAN HIEROGLYPH W024: try adding egyptian-hieroglyphs</li>
<li>U+133CD EGYPTIAN HIEROGLYPH W024A: try adding egyptian-hieroglyphs</li>
<li>U+133CE EGYPTIAN HIEROGLYPH W025: try adding egyptian-hieroglyphs</li>
<li>U+133CF EGYPTIAN HIEROGLYPH X001: try adding egyptian-hieroglyphs</li>
<li>U+133D0 EGYPTIAN HIEROGLYPH X002: try adding egyptian-hieroglyphs</li>
<li>U+133D1 EGYPTIAN HIEROGLYPH X003: try adding egyptian-hieroglyphs</li>
<li>U+133D2 EGYPTIAN HIEROGLYPH X004: try adding egyptian-hieroglyphs</li>
<li>U+133D3 EGYPTIAN HIEROGLYPH X004A: try adding egyptian-hieroglyphs</li>
<li>U+133D4 EGYPTIAN HIEROGLYPH X004B: try adding egyptian-hieroglyphs</li>
<li>U+133D5 EGYPTIAN HIEROGLYPH X005: try adding egyptian-hieroglyphs</li>
<li>U+133D6 EGYPTIAN HIEROGLYPH X006: try adding egyptian-hieroglyphs</li>
<li>U+133D7 EGYPTIAN HIEROGLYPH X006A: try adding egyptian-hieroglyphs</li>
<li>U+133D8 EGYPTIAN HIEROGLYPH X007: try adding egyptian-hieroglyphs</li>
<li>U+133D9 EGYPTIAN HIEROGLYPH X008: try adding egyptian-hieroglyphs</li>
<li>U+133DA EGYPTIAN HIEROGLYPH X008A: try adding egyptian-hieroglyphs</li>
<li>U+133DB EGYPTIAN HIEROGLYPH Y001: try adding egyptian-hieroglyphs</li>
<li>U+133DC EGYPTIAN HIEROGLYPH Y001A: try adding egyptian-hieroglyphs</li>
<li>U+133DD EGYPTIAN HIEROGLYPH Y002: try adding egyptian-hieroglyphs</li>
<li>U+133DE EGYPTIAN HIEROGLYPH Y003: try adding egyptian-hieroglyphs</li>
<li>U+133DF EGYPTIAN HIEROGLYPH Y004: try adding egyptian-hieroglyphs</li>
<li>U+133E0 EGYPTIAN HIEROGLYPH Y005: try adding egyptian-hieroglyphs</li>
<li>U+133E1 EGYPTIAN HIEROGLYPH Y006: try adding egyptian-hieroglyphs</li>
<li>U+133E2 EGYPTIAN HIEROGLYPH Y007: try adding egyptian-hieroglyphs</li>
<li>U+133E3 EGYPTIAN HIEROGLYPH Y008: try adding egyptian-hieroglyphs</li>
<li>U+133E4 EGYPTIAN HIEROGLYPH Z001: try adding egyptian-hieroglyphs</li>
<li>U+133E5 EGYPTIAN HIEROGLYPH Z002: try adding egyptian-hieroglyphs</li>
<li>U+133E6 EGYPTIAN HIEROGLYPH Z002A: try adding egyptian-hieroglyphs</li>
<li>U+133E7 EGYPTIAN HIEROGLYPH Z002B: try adding egyptian-hieroglyphs</li>
<li>U+133E8 EGYPTIAN HIEROGLYPH Z002C: try adding egyptian-hieroglyphs</li>
<li>U+133E9 EGYPTIAN HIEROGLYPH Z002D: try adding egyptian-hieroglyphs</li>
<li>U+133EA EGYPTIAN HIEROGLYPH Z003: try adding egyptian-hieroglyphs</li>
<li>U+133EB EGYPTIAN HIEROGLYPH Z003A: try adding egyptian-hieroglyphs</li>
<li>U+133EC EGYPTIAN HIEROGLYPH Z003B: try adding egyptian-hieroglyphs</li>
<li>U+133ED EGYPTIAN HIEROGLYPH Z004: try adding egyptian-hieroglyphs</li>
<li>U+133EE EGYPTIAN HIEROGLYPH Z004A: try adding egyptian-hieroglyphs</li>
<li>U+133EF EGYPTIAN HIEROGLYPH Z005: try adding egyptian-hieroglyphs</li>
<li>U+133F0 EGYPTIAN HIEROGLYPH Z005A: try adding egyptian-hieroglyphs</li>
<li>U+133F1 EGYPTIAN HIEROGLYPH Z006: try adding egyptian-hieroglyphs</li>
<li>U+133F2 EGYPTIAN HIEROGLYPH Z007: try adding egyptian-hieroglyphs</li>
<li>U+133F3 EGYPTIAN HIEROGLYPH Z008: try adding egyptian-hieroglyphs</li>
<li>U+133F4 EGYPTIAN HIEROGLYPH Z009: try adding egyptian-hieroglyphs</li>
<li>U+133F5 EGYPTIAN HIEROGLYPH Z010: try adding egyptian-hieroglyphs</li>
<li>U+133F6 EGYPTIAN HIEROGLYPH Z011: try adding egyptian-hieroglyphs</li>
<li>U+133F7 EGYPTIAN HIEROGLYPH Z012: try adding egyptian-hieroglyphs</li>
<li>U+133F8 EGYPTIAN HIEROGLYPH Z013: try adding egyptian-hieroglyphs</li>
<li>U+133F9 EGYPTIAN HIEROGLYPH Z014: try adding egyptian-hieroglyphs</li>
<li>U+133FA EGYPTIAN HIEROGLYPH Z015: try adding egyptian-hieroglyphs</li>
<li>U+133FB EGYPTIAN HIEROGLYPH Z015A: try adding egyptian-hieroglyphs</li>
<li>U+133FC EGYPTIAN HIEROGLYPH Z015B: try adding egyptian-hieroglyphs</li>
<li>U+133FD EGYPTIAN HIEROGLYPH Z015C: try adding egyptian-hieroglyphs</li>
<li>U+133FE EGYPTIAN HIEROGLYPH Z015D: try adding egyptian-hieroglyphs</li>
<li>U+133FF EGYPTIAN HIEROGLYPH Z015E: try adding egyptian-hieroglyphs</li>
<li>U+13400 EGYPTIAN HIEROGLYPH Z015F: try adding egyptian-hieroglyphs</li>
<li>U+13401 EGYPTIAN HIEROGLYPH Z015G: try adding egyptian-hieroglyphs</li>
<li>U+13402 EGYPTIAN HIEROGLYPH Z015H: try adding egyptian-hieroglyphs</li>
<li>U+13403 EGYPTIAN HIEROGLYPH Z015I: try adding egyptian-hieroglyphs</li>
<li>U+13404 EGYPTIAN HIEROGLYPH Z016: try adding egyptian-hieroglyphs</li>
<li>U+13405 EGYPTIAN HIEROGLYPH Z016A: try adding egyptian-hieroglyphs</li>
<li>U+13406 EGYPTIAN HIEROGLYPH Z016B: try adding egyptian-hieroglyphs</li>
<li>U+13407 EGYPTIAN HIEROGLYPH Z016C: try adding egyptian-hieroglyphs</li>
<li>U+13408 EGYPTIAN HIEROGLYPH Z016D: try adding egyptian-hieroglyphs</li>
<li>U+13409 EGYPTIAN HIEROGLYPH Z016E: try adding egyptian-hieroglyphs</li>
<li>U+1340A EGYPTIAN HIEROGLYPH Z016F: try adding egyptian-hieroglyphs</li>
<li>U+1340B EGYPTIAN HIEROGLYPH Z016G: try adding egyptian-hieroglyphs</li>
<li>U+1340C EGYPTIAN HIEROGLYPH Z016H: try adding egyptian-hieroglyphs</li>
<li>U+1340D EGYPTIAN HIEROGLYPH AA001: try adding egyptian-hieroglyphs</li>
<li>U+1340E EGYPTIAN HIEROGLYPH AA002: try adding egyptian-hieroglyphs</li>
<li>U+1340F EGYPTIAN HIEROGLYPH AA003: try adding egyptian-hieroglyphs</li>
<li>U+13410 EGYPTIAN HIEROGLYPH AA004: try adding egyptian-hieroglyphs</li>
<li>U+13411 EGYPTIAN HIEROGLYPH AA005: try adding egyptian-hieroglyphs</li>
<li>U+13412 EGYPTIAN HIEROGLYPH AA006: try adding egyptian-hieroglyphs</li>
<li>U+13413 EGYPTIAN HIEROGLYPH AA007: try adding egyptian-hieroglyphs</li>
<li>U+13414 EGYPTIAN HIEROGLYPH AA007A: try adding egyptian-hieroglyphs</li>
<li>U+13415 EGYPTIAN HIEROGLYPH AA007B: try adding egyptian-hieroglyphs</li>
<li>U+13416 EGYPTIAN HIEROGLYPH AA008: try adding egyptian-hieroglyphs</li>
<li>U+13417 EGYPTIAN HIEROGLYPH AA009: try adding egyptian-hieroglyphs</li>
<li>U+13418 EGYPTIAN HIEROGLYPH AA010: try adding egyptian-hieroglyphs</li>
<li>U+13419 EGYPTIAN HIEROGLYPH AA011: try adding egyptian-hieroglyphs</li>
<li>U+1341A EGYPTIAN HIEROGLYPH AA012: try adding egyptian-hieroglyphs</li>
<li>U+1341B EGYPTIAN HIEROGLYPH AA013: try adding egyptian-hieroglyphs</li>
<li>U+1341C EGYPTIAN HIEROGLYPH AA014: try adding egyptian-hieroglyphs</li>
<li>U+1341D EGYPTIAN HIEROGLYPH AA015: try adding egyptian-hieroglyphs</li>
<li>U+1341E EGYPTIAN HIEROGLYPH AA016: try adding egyptian-hieroglyphs</li>
<li>U+1341F EGYPTIAN HIEROGLYPH AA017: try adding egyptian-hieroglyphs</li>
<li>U+13420 EGYPTIAN HIEROGLYPH AA018: try adding egyptian-hieroglyphs</li>
<li>U+13421 EGYPTIAN HIEROGLYPH AA019: try adding egyptian-hieroglyphs</li>
<li>U+13422 EGYPTIAN HIEROGLYPH AA020: try adding egyptian-hieroglyphs</li>
<li>U+13423 EGYPTIAN HIEROGLYPH AA021: try adding egyptian-hieroglyphs</li>
<li>U+13424 EGYPTIAN HIEROGLYPH AA022: try adding egyptian-hieroglyphs</li>
<li>U+13425 EGYPTIAN HIEROGLYPH AA023: try adding egyptian-hieroglyphs</li>
<li>U+13426 EGYPTIAN HIEROGLYPH AA024: try adding egyptian-hieroglyphs</li>
<li>U+13427 EGYPTIAN HIEROGLYPH AA025: try adding egyptian-hieroglyphs</li>
<li>U+13428 EGYPTIAN HIEROGLYPH AA026: try adding egyptian-hieroglyphs</li>
<li>U+13429 EGYPTIAN HIEROGLYPH AA027: try adding egyptian-hieroglyphs</li>
<li>U+1342A EGYPTIAN HIEROGLYPH AA028: try adding egyptian-hieroglyphs</li>
<li>U+1342B EGYPTIAN HIEROGLYPH AA029: try adding egyptian-hieroglyphs</li>
<li>U+1342C EGYPTIAN HIEROGLYPH AA030: try adding egyptian-hieroglyphs</li>
<li>U+1342D EGYPTIAN HIEROGLYPH AA031: try adding egyptian-hieroglyphs</li>
<li>U+1342E EGYPTIAN HIEROGLYPH AA032: try adding egyptian-hieroglyphs</li>
<li>U+1342F EGYPTIAN HIEROGLYPH V011D: try adding egyptian-hieroglyphs</li>
<li>U+13441 EGYPTIAN HIEROGLYPH FULL BLANK: try adding egyptian-hieroglyphs</li>
<li>U+13442 EGYPTIAN HIEROGLYPH HALF BLANK: try adding egyptian-hieroglyphs</li>
<li>U+13443 EGYPTIAN HIEROGLYPH LOST SIGN: try adding egyptian-hieroglyphs</li>
<li>U+13444 EGYPTIAN HIEROGLYPH HALF LOST SIGN: try adding egyptian-hieroglyphs</li>
<li>U+13445 EGYPTIAN HIEROGLYPH TALL LOST SIGN: try adding egyptian-hieroglyphs</li>
<li>U+13446 EGYPTIAN HIEROGLYPH WIDE LOST SIGN: try adding egyptian-hieroglyphs</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Combined length of family and style must not exceed 32 characters. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.name.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Name ID 6 'NotoSansEgyptianHieroglyphs-Regular' exceeds 27 characters. This has been found to cause problems with PostScript printers, especially on Mac platforms.</p>
 [code: nameid6-too-long]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ j̦̀ j̦́ ĵ̦ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Southern Kisi (Latn, 360,000 speakers), Han (Latn, 6 speakers), Koonzime (Latn, 40,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Navajo (Latn, 166,319 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Heiltsuk (Latn, 300 speakers), Avokaya (Latn, 100,000 speakers), South Central Banda (Latn, 244,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Gulay (Latn, 250,478 speakers), Sar (Latn, 500,000 speakers), Ebira (Latn, 2,200,000 speakers), Nzakara (Latn, 50,000 speakers), Mfumte (Latn, 79,000 speakers), Mundani (Latn, 34,000 speakers), Lugbara (Latn, 2,200,000 speakers), Vute (Latn, 21,000 speakers), Basaa (Latn, 332,940 speakers), Teke-Ebo (Latn, 260,000 speakers), Aghem (Latn, 38,843 speakers), Ngbaka (Latn, 1,020,000 speakers), Mango (Latn, 77,000 speakers), Zapotec (Latn, 490,000 speakers), Fur (Latn, 1,230,163 speakers), Makaa (Latn, 221,000 speakers), Ma’di (Latn, 584,000 speakers), Dan (Latn, 1,099,244 speakers), Bafut (Latn, 158,146 speakers), Cicipu (Latn, 44,000 speakers), Ekpeye (Latn, 226,000 speakers), Igbo (Latn, 27,823,640 speakers), Kom (Latn, 360,685 speakers), Ejagham (Latn, 120,000 speakers), Yala (Latn, 200,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Bete-Bendi (Latn, 100,000 speakers), Kaska (Latn, 125 speakers), Nateni (Latn, 100,000 speakers), Dii (Latn, 71,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* u13004 (U+13004): L&lt;&lt;228.0,789.0&gt;--&lt;339.0,614.0&gt;&gt;/L&lt;&lt;339.0,614.0&gt;--&lt;256.0,813.0&gt;&gt; = 9.746066721350674

* u1300F (U+1300F): B&lt;&lt;637.5,644.0&gt;-&lt;661.0,606.0&gt;-&lt;681.0,563.0&gt;&gt;/B&lt;&lt;681.0,563.0&gt;-&lt;677.0,571.0&gt;-&lt;674.5,581.0&gt;&gt; = 1.6211459136531066

* u1302A (U+1302A): B&lt;&lt;538.5,21.0&gt;-&lt;571.0,22.0&gt;-&lt;601.0,24.0&gt;&gt;/L&lt;&lt;601.0,24.0&gt;--&lt;538.0,24.0&gt;&gt; = 3.8140748342903783

* u1302A (U+1302A): L&lt;&lt;395.0,24.0&gt;--&lt;364.0,24.0&gt;&gt;/B&lt;&lt;364.0,24.0&gt;-&lt;388.0,22.0&gt;-&lt;415.0,21.0&gt;&gt; = 4.763641690726143

* u1302B (U+1302B): B&lt;&lt;592.5,21.0&gt;-&lt;625.0,22.0&gt;-&lt;655.0,24.0&gt;&gt;/L&lt;&lt;655.0,24.0&gt;--&lt;592.0,24.0&gt;&gt; = 3.8140748342903783

* u1302B (U+1302B): L&lt;&lt;449.0,24.0&gt;--&lt;418.0,24.0&gt;&gt;/B&lt;&lt;418.0,24.0&gt;-&lt;442.0,22.0&gt;-&lt;469.0,21.0&gt;&gt; = 4.763641690726143

* u1302C (U+1302C): B&lt;&lt;619.5,274.0&gt;-&lt;619.0,290.0&gt;-&lt;613.0,309.0&gt;&gt;/B&lt;&lt;613.0,309.0&gt;-&lt;615.0,281.0&gt;-&lt;608.5,261.5&gt;&gt; = 13.439951593747935

* u1302C (U+1302C): B&lt;&lt;632.5,364.0&gt;-&lt;642.0,341.0&gt;-&lt;645.0,317.0&gt;&gt;/B&lt;&lt;645.0,317.0&gt;-&lt;648.0,341.0&gt;-&lt;657.5,364.0&gt;&gt; = 14.25003269780357

* u1302C (U+1302C): L&lt;&lt;1023.0,148.0&gt;--&lt;1016.0,340.0&gt;&gt;/B&lt;&lt;1016.0,340.0&gt;-&lt;1016.0,338.0&gt;-&lt;1014.0,338.0&gt;&gt; = 2.0879838327232854

* u13030 (U+13030): L&lt;&lt;358.0,442.0&gt;--&lt;357.0,441.0&gt;&gt;/B&lt;&lt;357.0,441.0&gt;-&lt;372.0,453.0&gt;-&lt;391.0,453.0&gt;&gt; = 6.340191745909908

* u13031 (U+13031): L&lt;&lt;358.0,442.0&gt;--&lt;357.0,441.0&gt;&gt;/B&lt;&lt;357.0,441.0&gt;-&lt;372.0,453.0&gt;-&lt;391.0,453.0&gt;&gt; = 6.340191745909908

* u13048 (U+13048): L&lt;&lt;318.0,0.0&gt;--&lt;318.0,292.0&gt;&gt;/L&lt;&lt;318.0,292.0&gt;--&lt;247.0,0.0&gt;&gt; = 13.666300072913529

* u1305A (U+1305A): B&lt;&lt;368.5,958.5&gt;-&lt;376.0,967.0&gt;-&lt;388.0,970.0&gt;&gt;/B&lt;&lt;388.0,970.0&gt;-&lt;381.0,969.0&gt;-&lt;373.0,973.0&gt;&gt; = 5.906141113770435

* u1305F (U+1305F): L&lt;&lt;219.0,940.0&gt;--&lt;159.0,907.0&gt;&gt;/B&lt;&lt;159.0,907.0&gt;-&lt;185.0,915.0&gt;-&lt;200.0,917.5&gt;&gt; = 11.70806477392071

* u13060 (U+13060): L&lt;&lt;251.0,795.0&gt;--&lt;173.0,795.0&gt;&gt;/B&lt;&lt;173.0,795.0&gt;-&lt;188.0,792.0&gt;-&lt;213.5,788.5&gt;&gt; = 11.309932474020195

* u13061 (U+13061): L&lt;&lt;300.0,795.0&gt;--&lt;222.0,795.0&gt;&gt;/B&lt;&lt;222.0,795.0&gt;-&lt;237.0,792.0&gt;-&lt;262.5,788.5&gt;&gt; = 11.309932474020195

* u13062 (U+13062): B&lt;&lt;507.5,936.0&gt;-&lt;502.0,954.0&gt;-&lt;500.0,967.0&gt;&gt;/B&lt;&lt;500.0,967.0&gt;-&lt;498.0,941.0&gt;-&lt;490.0,912.0&gt;&gt; = 13.144867617550734

* u13065 (U+13065): B&lt;&lt;310.0,896.0&gt;-&lt;314.0,882.0&gt;-&lt;327.0,870.0&gt;&gt;/B&lt;&lt;327.0,870.0&gt;-&lt;306.0,891.0&gt;-&lt;306.0,922.0&gt;&gt; = 2.2906100426384346

* u13065 (U+13065): B&lt;&lt;449.0,922.0&gt;-&lt;449.0,898.0&gt;-&lt;435.0,879.0&gt;&gt;/B&lt;&lt;435.0,879.0&gt;-&lt;442.0,887.0&gt;-&lt;445.0,896.0&gt;&gt; = 4.801573349873815

* u1306D (U+1306D): B&lt;&lt;611.0,890.0&gt;-&lt;618.0,886.0&gt;-&lt;615.0,876.0&gt;&gt;/L&lt;&lt;615.0,876.0&gt;--&lt;669.0,977.0&gt;&gt; = 11.432098130067416

* u1306D (U+1306D): L&lt;&lt;549.0,580.0&gt;--&lt;650.0,906.0&gt;&gt;/L&lt;&lt;650.0,906.0&gt;--&lt;579.0,783.0&gt;&gt; = 12.781264614159975

* u1306E (U+1306E): B&lt;&lt;442.0,778.0&gt;-&lt;430.0,768.0&gt;-&lt;413.0,766.0&gt;&gt;/L&lt;&lt;413.0,766.0&gt;--&lt;456.0,762.0&gt;&gt; = 12.024382477701632

* u1306E (U+1306E): L&lt;&lt;345.0,771.0&gt;--&lt;388.0,768.0&gt;&gt;/B&lt;&lt;388.0,768.0&gt;-&lt;372.0,772.0&gt;-&lt;361.5,784.0&gt;&gt; = 10.045330369496687

* u1306E (U+1306E): L&lt;&lt;359.0,952.0&gt;--&lt;351.0,841.0&gt;&gt;/B&lt;&lt;351.0,841.0&gt;-&lt;356.0,858.0&gt;-&lt;370.0,868.5&gt;&gt; = 12.267242522251085

* u1306E (U+1306E): L&lt;&lt;456.0,762.0&gt;--&lt;459.0,803.0&gt;&gt;/B&lt;&lt;459.0,803.0&gt;-&lt;454.0,788.0&gt;-&lt;442.0,778.0&gt;&gt; = 14.25003269780357

* u1306F (U+1306F): B&lt;&lt;320.0,756.5&gt;-&lt;316.0,757.0&gt;-&lt;312.0,758.0&gt;&gt;/B&lt;&lt;312.0,758.0&gt;-&lt;318.0,755.0&gt;-&lt;322.0,751.0&gt;&gt; = 12.528807709151492

* u1306F (U+1306F): B&lt;&lt;355.5,740.5&gt;-&lt;353.0,740.0&gt;-&lt;352.0,740.0&gt;&gt;/B&lt;&lt;352.0,740.0&gt;-&lt;378.0,734.0&gt;-&lt;398.0,716.0&gt;&gt; = 12.994616791916512

* u1306F (U+1306F): L&lt;&lt;280.0,942.0&gt;--&lt;271.0,832.0&gt;&gt;/B&lt;&lt;271.0,832.0&gt;-&lt;276.0,849.0&gt;-&lt;290.0,859.5&gt;&gt; = 11.712122475153018

* u13074 (U+13074): B&lt;&lt;249.0,958.5&gt;-&lt;256.0,967.0&gt;-&lt;269.0,970.0&gt;&gt;/B&lt;&lt;269.0,970.0&gt;-&lt;262.0,969.0&gt;-&lt;254.0,973.0&gt;&gt; = 4.864514437760454

* u13088 (U+13088): B&lt;&lt;446.5,342.5&gt;-&lt;436.0,304.0&gt;-&lt;419.0,272.0&gt;&gt;/B&lt;&lt;419.0,272.0&gt;-&lt;453.0,316.0&gt;-&lt;474.0,364.0&gt;&gt; = 9.714766078209031

* u1308A (U+1308A): L&lt;&lt;187.0,397.0&gt;--&lt;187.0,398.0&gt;&gt;/B&lt;&lt;187.0,398.0&gt;-&lt;185.0,388.0&gt;-&lt;178.5,357.0&gt;&gt; = 11.309932474020195

* u130A6 (U+130A6): B&lt;&lt;399.0,47.0&gt;-&lt;407.0,35.0&gt;-&lt;410.0,36.0&gt;&gt;/L&lt;&lt;410.0,36.0&gt;--&lt;326.0,11.0&gt;&gt; = 1.8609410660127526

* u130A7 (U+130A7): B&lt;&lt;572.0,453.5&gt;-&lt;548.0,448.0&gt;-&lt;526.0,443.0&gt;&gt;/L&lt;&lt;526.0,443.0&gt;--&lt;725.0,443.0&gt;&gt; = 12.80426606528674

* u130A8 (U+130A8): B&lt;&lt;879.0,453.5&gt;-&lt;855.0,448.0&gt;-&lt;833.0,443.0&gt;&gt;/L&lt;&lt;833.0,443.0&gt;--&lt;1032.0,443.0&gt;&gt; = 12.80426606528674

* u130C3 (U+130C3): B&lt;&lt;475.0,483.5&gt;-&lt;450.0,511.0&gt;-&lt;444.0,556.0&gt;&gt;/L&lt;&lt;444.0,556.0&gt;--&lt;444.0,69.0&gt;&gt; = 7.594643368591447

* u130C3 (U+130C3): B&lt;&lt;869.0,483.5&gt;-&lt;844.0,511.0&gt;-&lt;838.0,556.0&gt;&gt;/L&lt;&lt;838.0,556.0&gt;--&lt;838.0,69.0&gt;&gt; = 7.594643368591447

* u130C3 (U+130C3): L&lt;&lt;444.0,1015.0&gt;--&lt;444.0,605.0&gt;&gt;/B&lt;&lt;444.0,605.0&gt;-&lt;448.0,636.0&gt;-&lt;460.5,677.0&gt;&gt; = 7.352379359892374

* u130C3 (U+130C3): L&lt;&lt;838.0,1015.0&gt;--&lt;838.0,605.0&gt;&gt;/B&lt;&lt;838.0,605.0&gt;-&lt;842.0,636.0&gt;-&lt;854.5,677.0&gt;&gt; = 7.352379359892374

* u130C4 (U+130C4): B&lt;&lt;1049.5,677.0&gt;-&lt;1062.0,636.0&gt;-&lt;1065.0,605.0&gt;&gt;/L&lt;&lt;1065.0,605.0&gt;--&lt;1065.0,1015.0&gt;&gt; = 5.527540151656126

* u130C4 (U+130C4): B&lt;&lt;655.5,677.0&gt;-&lt;668.0,636.0&gt;-&lt;671.0,605.0&gt;&gt;/L&lt;&lt;671.0,605.0&gt;--&lt;671.0,1015.0&gt;&gt; = 5.527540151656126

* u130C4 (U+130C4): L&lt;&lt;1065.0,69.0&gt;--&lt;1065.0,556.0&gt;&gt;/B&lt;&lt;1065.0,556.0&gt;-&lt;1060.0,511.0&gt;-&lt;1034.5,483.5&gt;&gt; = 6.340191745909908

* u130C4 (U+130C4): L&lt;&lt;671.0,69.0&gt;--&lt;671.0,556.0&gt;&gt;/B&lt;&lt;671.0,556.0&gt;-&lt;666.0,511.0&gt;-&lt;640.5,483.5&gt;&gt; = 6.340191745909908

* u130D4 (U+130D4): L&lt;&lt;519.0,298.0&gt;--&lt;669.0,302.0&gt;&gt;/L&lt;&lt;669.0,302.0&gt;--&lt;668.0,302.0&gt;&gt; = 1.5275254422129318

* u130D4 (U+130D4): L&lt;&lt;669.0,302.0&gt;--&lt;668.0,302.0&gt;&gt;/L&lt;&lt;668.0,302.0&gt;--&lt;817.0,325.0&gt;&gt; = 8.775055744479651

* u130D7 (U+130D7): B&lt;&lt;1074.5,284.5&gt;-&lt;1084.0,254.0&gt;-&lt;1094.0,232.0&gt;&gt;/B&lt;&lt;1094.0,232.0&gt;-&lt;1088.0,261.0&gt;-&lt;1084.5,292.5&gt;&gt; = 12.754585604977335

* u130D7 (U+130D7): B&lt;&lt;1121.5,510.5&gt;-&lt;1127.0,534.0&gt;-&lt;1129.0,550.0&gt;&gt;/B&lt;&lt;1129.0,550.0&gt;-&lt;1126.0,540.0&gt;-&lt;1119.5,525.0&gt;&gt; = 9.574227885091789

* u130D9 (U+130D9): B&lt;&lt;269.0,728.0&gt;-&lt;275.0,770.0&gt;-&lt;261.0,810.0&gt;&gt;/B&lt;&lt;261.0,810.0&gt;-&lt;263.0,794.0&gt;-&lt;261.5,776.5&gt;&gt; = 12.165029870286897

* u130DA (U+130DA): B&lt;&lt;446.0,898.0&gt;-&lt;470.0,932.0&gt;-&lt;476.0,975.0&gt;&gt;/B&lt;&lt;476.0,975.0&gt;-&lt;471.0,960.0&gt;-&lt;461.0,945.5&gt;&gt; = 10.491477012331599

* u130DB (U+130DB): B&lt;&lt;583.5,323.0&gt;-&lt;549.0,318.0&gt;-&lt;523.0,313.0&gt;&gt;/L&lt;&lt;523.0,313.0&gt;--&lt;607.0,313.0&gt;&gt; = 10.885527054658743

* u130DC (U+130DC): L&lt;&lt;570.0,233.0&gt;--&lt;398.0,198.0&gt;&gt;/L&lt;&lt;398.0,198.0&gt;--&lt;504.0,207.0&gt;&gt; = 6.648888259978554

* u130EF (U+130EF): B&lt;&lt;1343.5,381.0&gt;-&lt;1338.0,403.0&gt;-&lt;1327.0,425.0&gt;&gt;/B&lt;&lt;1327.0,425.0&gt;-&lt;1331.0,409.0&gt;-&lt;1333.5,392.5&gt;&gt; = 12.528807709151492

* u130F0 (U+130F0): B&lt;&lt;1525.5,593.0&gt;-&lt;1499.0,652.0&gt;-&lt;1467.0,685.0&gt;&gt;/B&lt;&lt;1467.0,685.0&gt;-&lt;1482.0,661.0&gt;-&lt;1494.5,638.0&gt;&gt; = 12.113212795334356

* u130F1 (U+130F1): L&lt;&lt;340.0,558.0&gt;--&lt;339.0,559.0&gt;&gt;/B&lt;&lt;339.0,559.0&gt;-&lt;345.0,549.0&gt;-&lt;350.5,538.5&gt;&gt; = 14.036243467926484

* u130F2 (U+130F2): B&lt;&lt;369.5,910.0&gt;-&lt;333.0,859.0&gt;-&lt;310.0,800.0&gt;&gt;/B&lt;&lt;310.0,800.0&gt;-&lt;342.0,854.0&gt;-&lt;378.5,897.5&gt;&gt; = 9.353313908019095

* u130F3 (U+130F3): B&lt;&lt;430.5,922.5&gt;-&lt;401.0,881.0&gt;-&lt;382.0,833.0&gt;&gt;/B&lt;&lt;382.0,833.0&gt;-&lt;408.0,877.0&gt;-&lt;437.5,912.0&gt;&gt; = 8.983916423521316

* u130F6 (U+130F6): B&lt;&lt;422.0,924.0&gt;-&lt;403.0,888.0&gt;-&lt;376.0,856.0&gt;&gt;/B&lt;&lt;376.0,856.0&gt;-&lt;411.0,883.0&gt;-&lt;443.0,914.5&gt;&gt; = 12.196379734973

* u130F6 (U+130F6): L&lt;&lt;198.0,203.0&gt;--&lt;231.0,280.0&gt;&gt;/L&lt;&lt;231.0,280.0&gt;--&lt;183.0,211.0&gt;&gt; = 11.625898643308558

* u13104 (U+13104): L&lt;&lt;546.0,57.0&gt;--&lt;339.0,11.0&gt;&gt;/L&lt;&lt;339.0,11.0&gt;--&lt;511.0,23.0&gt;&gt; = 8.537894610721718

* u13106 (U+13106): L&lt;&lt;887.0,135.0&gt;--&lt;612.0,84.0&gt;&gt;/L&lt;&lt;612.0,84.0&gt;--&lt;894.0,106.0&gt;&gt; = 6.045549529392515

* u13108 (U+13108): B&lt;&lt;366.0,922.0&gt;-&lt;377.0,948.0&gt;-&lt;387.0,967.0&gt;&gt;/B&lt;&lt;387.0,967.0&gt;-&lt;369.0,947.0&gt;-&lt;350.5,913.5&gt;&gt; = 14.228671894756625

* u13108 (U+13108): B&lt;&lt;98.5,909.0&gt;-&lt;86.0,937.0&gt;-&lt;71.0,955.0&gt;&gt;/B&lt;&lt;71.0,955.0&gt;-&lt;76.0,947.0&gt;-&lt;79.5,937.5&gt;&gt; = 7.8001878841816605

* u13110 (U+13110): B&lt;&lt;460.5,345.5&gt;-&lt;431.0,381.0&gt;-&lt;394.0,424.0&gt;&gt;/B&lt;&lt;394.0,424.0&gt;-&lt;396.0,420.0&gt;-&lt;396.0,417.0&gt;&gt; = 14.145795494102968

* u13125 (U+13125): L&lt;&lt;147.0,933.0&gt;--&lt;183.0,378.0&gt;&gt;/L&lt;&lt;183.0,378.0&gt;--&lt;218.0,933.0&gt;&gt; = 7.319752660587253

* u13128 (U+13128): L&lt;&lt;414.0,333.0&gt;--&lt;415.0,334.0&gt;&gt;/B&lt;&lt;415.0,334.0&gt;-&lt;406.0,320.0&gt;-&lt;395.0,294.0&gt;&gt; = 12.2647737278924

* u13128 (U+13128): L&lt;&lt;607.0,333.0&gt;--&lt;608.0,334.0&gt;&gt;/B&lt;&lt;608.0,334.0&gt;-&lt;599.0,320.0&gt;-&lt;588.0,294.0&gt;&gt; = 12.2647737278924

* u1313F (U+1313F): B&lt;&lt;230.0,28.0&gt;-&lt;229.0,40.0&gt;-&lt;237.0,42.0&gt;&gt;/L&lt;&lt;237.0,42.0&gt;--&lt;130.0,35.0&gt;&gt; = 10.29325517223935

* u13140 (U+13140): B&lt;&lt;230.0,28.0&gt;-&lt;229.0,40.0&gt;-&lt;237.0,42.0&gt;&gt;/L&lt;&lt;237.0,42.0&gt;--&lt;130.0,35.0&gt;&gt; = 10.29325517223935

* u13140 (U+13140): B&lt;&lt;489.0,28.0&gt;-&lt;489.0,41.0&gt;-&lt;496.0,42.0&gt;&gt;/L&lt;&lt;496.0,42.0&gt;--&lt;394.0,35.0&gt;&gt; = 4.204194650471878

* u13141 (U+13141): B&lt;&lt;253.0,28.0&gt;-&lt;253.0,41.0&gt;-&lt;260.0,42.0&gt;&gt;/L&lt;&lt;260.0,42.0&gt;--&lt;153.0,35.0&gt;&gt; = 4.387114058468793

* u13142 (U+13142): B&lt;&lt;1104.0,50.5&gt;-&lt;1133.0,34.0&gt;-&lt;1151.0,23.0&gt;&gt;/B&lt;&lt;1151.0,23.0&gt;-&lt;1147.0,27.0&gt;-&lt;1146.5,37.0&gt;&gt; = 13.570434385161448

* u13142 (U+13142): B&lt;&lt;697.0,36.5&gt;-&lt;704.0,33.0&gt;-&lt;705.0,31.0&gt;&gt;/B&lt;&lt;705.0,31.0&gt;-&lt;702.0,39.0&gt;-&lt;696.5,45.5&gt;&gt; = 6.009005957494474

* u13142 (U+13142): L&lt;&lt;1232.0,159.0&gt;--&lt;1101.0,226.0&gt;&gt;/B&lt;&lt;1101.0,226.0&gt;-&lt;1128.0,207.0&gt;-&lt;1158.0,184.5&gt;&gt; = 8.046702442878855

* u13143 (U+13143): B&lt;&lt;183.5,837.0&gt;-&lt;188.0,827.0&gt;-&lt;190.0,818.0&gt;&gt;/B&lt;&lt;190.0,818.0&gt;-&lt;190.0,820.0&gt;-&lt;189.5,824.0&gt;&gt; = 12.528807709151492

* u13144 (U+13144): B&lt;&lt;183.5,837.0&gt;-&lt;188.0,827.0&gt;-&lt;190.0,818.0&gt;&gt;/B&lt;&lt;190.0,818.0&gt;-&lt;190.0,820.0&gt;-&lt;189.5,824.0&gt;&gt; = 12.528807709151492

* u13145 (U+13145): B&lt;&lt;280.0,875.0&gt;-&lt;284.0,868.0&gt;-&lt;285.0,861.0&gt;&gt;/B&lt;&lt;285.0,861.0&gt;-&lt;285.0,863.0&gt;-&lt;284.5,866.0&gt;&gt; = 8.13010235415596

* u13146 (U+13146): B&lt;&lt;221.5,894.5&gt;-&lt;225.0,888.0&gt;-&lt;226.0,882.0&gt;&gt;/B&lt;&lt;226.0,882.0&gt;-&lt;226.0,884.0&gt;-&lt;225.5,886.0&gt;&gt; = 9.462322208025613

* u13146 (U+13146): B&lt;&lt;263.0,891.0&gt;-&lt;263.0,886.0&gt;-&lt;261.0,884.0&gt;&gt;/B&lt;&lt;261.0,884.0&gt;-&lt;269.0,889.0&gt;-&lt;275.5,897.0&gt;&gt; = 12.994616791916483

* u13147 (U+13147): B&lt;&lt;399.0,853.5&gt;-&lt;403.0,845.0&gt;-&lt;404.0,837.0&gt;&gt;/L&lt;&lt;404.0,837.0&gt;--&lt;404.0,847.0&gt;&gt; = 7.125016348901757

* u13148 (U+13148): B&lt;&lt;156.5,420.5&gt;-&lt;100.0,477.0&gt;-&lt;68.0,580.0&gt;&gt;/B&lt;&lt;68.0,580.0&gt;-&lt;72.0,506.0&gt;-&lt;99.0,451.0&gt;&gt; = 14.16489623398697

* u13148 (U+13148): B&lt;&lt;321.5,894.5&gt;-&lt;325.0,888.0&gt;-&lt;326.0,882.0&gt;&gt;/L&lt;&lt;326.0,882.0&gt;--&lt;326.0,889.0&gt;&gt; = 9.462322208025613

* u13149 (U+13149): B&lt;&lt;141.0,903.0&gt;-&lt;149.0,892.0&gt;-&lt;152.0,880.0&gt;&gt;/L&lt;&lt;152.0,880.0&gt;--&lt;152.0,887.0&gt;&gt; = 14.036243467926457

* u13149 (U+13149): B&lt;&lt;190.0,889.0&gt;-&lt;190.0,884.0&gt;-&lt;188.0,882.0&gt;&gt;/B&lt;&lt;188.0,882.0&gt;-&lt;195.0,887.0&gt;-&lt;201.5,895.0&gt;&gt; = 9.462322208025574

* u1314B (U+1314B): B&lt;&lt;231.0,746.5&gt;-&lt;236.0,738.0&gt;-&lt;237.0,730.0&gt;&gt;/B&lt;&lt;237.0,730.0&gt;-&lt;237.0,738.0&gt;-&lt;239.0,749.5&gt;&gt; = 7.125016348901757

* u1314B (U+1314B): B&lt;&lt;310.5,885.0&gt;-&lt;287.0,922.0&gt;-&lt;264.0,945.0&gt;&gt;/L&lt;&lt;264.0,945.0&gt;--&lt;343.0,812.0&gt;&gt; = 14.290325081817693

* u1314B (U+1314B): B&lt;&lt;572.0,816.5&gt;-&lt;575.0,811.0&gt;-&lt;576.0,806.0&gt;&gt;/L&lt;&lt;576.0,806.0&gt;--&lt;576.0,812.0&gt;&gt; = 11.309932474020195

* u1314B (U+1314B): B&lt;&lt;607.0,813.0&gt;-&lt;607.0,810.0&gt;-&lt;605.0,808.0&gt;&gt;/B&lt;&lt;605.0,808.0&gt;-&lt;611.0,812.0&gt;-&lt;617.0,820.5&gt;&gt; = 11.309932474020195

* u1314D (U+1314D): B&lt;&lt;654.5,350.5&gt;-&lt;668.0,340.0&gt;-&lt;677.0,328.0&gt;&gt;/B&lt;&lt;677.0,328.0&gt;-&lt;672.0,340.0&gt;-&lt;664.0,351.5&gt;&gt; = 14.25003269780357

* u1314F (U+1314F): B&lt;&lt;141.0,688.5&gt;-&lt;160.0,701.0&gt;-&lt;191.0,706.0&gt;&gt;/L&lt;&lt;191.0,706.0&gt;--&lt;146.0,710.0&gt;&gt; = 14.24195490573626

* u13158 (U+13158): B&lt;&lt;257.5,987.0&gt;-&lt;265.0,971.0&gt;-&lt;270.0,937.0&gt;&gt;/B&lt;&lt;270.0,937.0&gt;-&lt;270.0,951.0&gt;-&lt;272.0,967.5&gt;&gt; = 8.365886124032546

* u1315A (U+1315A): B&lt;&lt;214.5,753.5&gt;-&lt;212.0,739.0&gt;-&lt;208.0,722.0&gt;&gt;/L&lt;&lt;208.0,722.0&gt;--&lt;208.0,723.0&gt;&gt; = 13.240519915187184

* u1315A (U+1315A): L&lt;&lt;208.0,722.0&gt;--&lt;208.0,723.0&gt;&gt;/B&lt;&lt;208.0,723.0&gt;-&lt;204.0,701.0&gt;-&lt;199.0,676.0&gt;&gt; = 10.304846468766044

* u1315C (U+1315C): B&lt;&lt;133.5,768.5&gt;-&lt;105.0,731.0&gt;-&lt;89.0,701.0&gt;&gt;/B&lt;&lt;89.0,701.0&gt;-&lt;128.0,762.0&gt;-&lt;184.0,806.5&gt;&gt; = 4.520094536746334

* u1315D (U+1315D): B&lt;&lt;111.5,829.5&gt;-&lt;91.0,802.0&gt;-&lt;79.0,779.0&gt;&gt;/B&lt;&lt;79.0,779.0&gt;-&lt;108.0,824.0&gt;-&lt;148.5,856.5&gt;&gt; = 5.246719695901301

* u1315D (U+1315D): B&lt;&lt;77.0,815.5&gt;-&lt;61.0,780.0&gt;-&lt;60.0,760.0&gt;&gt;/B&lt;&lt;60.0,760.0&gt;-&lt;66.0,783.0&gt;-&lt;86.5,816.5&gt;&gt; = 11.758468762519849

* u1315E (U+1315E): B&lt;&lt;87.5,786.0&gt;-&lt;67.0,746.0&gt;-&lt;66.0,710.0&gt;&gt;/B&lt;&lt;66.0,710.0&gt;-&lt;83.0,774.0&gt;-&lt;128.5,825.0&gt;&gt; = 13.284541730444204

* u1315F (U+1315F): B&lt;&lt;139.0,478.0&gt;-&lt;169.0,444.0&gt;-&lt;195.0,423.0&gt;&gt;/B&lt;&lt;195.0,423.0&gt;-&lt;167.0,449.0&gt;-&lt;141.5,485.5&gt;&gt; = 3.9513600105462134

* u1315F (U+1315F): B&lt;&lt;160.5,482.5&gt;-&lt;191.0,443.0&gt;-&lt;221.0,420.0&gt;&gt;/B&lt;&lt;221.0,420.0&gt;-&lt;203.0,437.0&gt;-&lt;178.5,466.5&gt;&gt; = 5.887243397021908

* u1315F (U+1315F): B&lt;&lt;415.5,622.5&gt;-&lt;382.0,655.0&gt;-&lt;366.0,680.0&gt;&gt;/B&lt;&lt;366.0,680.0&gt;-&lt;371.0,666.0&gt;-&lt;375.0,647.0&gt;&gt; = 12.96541901313951

* u13160 (U+13160): B&lt;&lt;118.0,494.5&gt;-&lt;100.0,470.0&gt;-&lt;88.0,447.0&gt;&gt;/B&lt;&lt;88.0,447.0&gt;-&lt;116.0,489.0&gt;-&lt;151.5,516.5&gt;&gt; = 6.137255949261901

* u13160 (U+13160): B&lt;&lt;155.5,503.5&gt;-&lt;120.0,478.0&gt;-&lt;94.0,436.0&gt;&gt;/B&lt;&lt;94.0,436.0&gt;-&lt;112.0,458.0&gt;-&lt;134.5,478.0&gt;&gt; = 7.529926777687556

* u13162 (U+13162): B&lt;&lt;1024.5,19.0&gt;-&lt;1016.0,12.0&gt;-&lt;1011.0,0.0&gt;&gt;/B&lt;&lt;1011.0,0.0&gt;-&lt;1014.0,4.0&gt;-&lt;1022.5,9.5&gt;&gt; = 14.25003269780357

* u13162 (U+13162): B&lt;&lt;1244.0,9.5&gt;-&lt;1252.0,4.0&gt;-&lt;1255.0,0.0&gt;&gt;/B&lt;&lt;1255.0,0.0&gt;-&lt;1250.0,12.0&gt;-&lt;1241.5,19.0&gt;&gt; = 14.25003269780357

* u13162 (U+13162): B&lt;&lt;1314.5,19.0&gt;-&lt;1306.0,12.0&gt;-&lt;1301.0,0.0&gt;&gt;/B&lt;&lt;1301.0,0.0&gt;-&lt;1304.0,4.0&gt;-&lt;1312.5,9.5&gt;&gt; = 14.25003269780357

* u13162 (U+13162): B&lt;&lt;1534.0,9.5&gt;-&lt;1542.0,4.0&gt;-&lt;1545.0,0.0&gt;&gt;/B&lt;&lt;1545.0,0.0&gt;-&lt;1540.0,12.0&gt;-&lt;1531.5,19.0&gt;&gt; = 14.25003269780357

* u13162 (U+13162): B&lt;&lt;282.5,19.0&gt;-&lt;274.0,12.0&gt;-&lt;269.0,0.0&gt;&gt;/B&lt;&lt;269.0,0.0&gt;-&lt;272.0,4.0&gt;-&lt;280.0,9.5&gt;&gt; = 14.25003269780357

* u13162 (U+13162): B&lt;&lt;502.0,9.5&gt;-&lt;510.0,4.0&gt;-&lt;513.0,0.0&gt;&gt;/B&lt;&lt;513.0,0.0&gt;-&lt;508.0,12.0&gt;-&lt;499.5,19.0&gt;&gt; = 14.25003269780357

* u13162 (U+13162): B&lt;&lt;572.5,19.0&gt;-&lt;564.0,12.0&gt;-&lt;559.0,0.0&gt;&gt;/B&lt;&lt;559.0,0.0&gt;-&lt;562.0,4.0&gt;-&lt;570.0,9.5&gt;&gt; = 14.25003269780357

* u13162 (U+13162): B&lt;&lt;653.5,19.0&gt;-&lt;645.0,12.0&gt;-&lt;640.0,0.0&gt;&gt;/B&lt;&lt;640.0,0.0&gt;-&lt;643.0,4.0&gt;-&lt;651.5,9.5&gt;&gt; = 14.25003269780357

* u13162 (U+13162): B&lt;&lt;873.0,9.5&gt;-&lt;881.0,4.0&gt;-&lt;884.0,0.0&gt;&gt;/B&lt;&lt;884.0,0.0&gt;-&lt;879.0,12.0&gt;-&lt;870.5,19.0&gt;&gt; = 14.25003269780357

* u13162 (U+13162): B&lt;&lt;943.5,19.0&gt;-&lt;935.0,12.0&gt;-&lt;930.0,0.0&gt;&gt;/B&lt;&lt;930.0,0.0&gt;-&lt;933.0,4.0&gt;-&lt;941.5,9.5&gt;&gt; = 14.25003269780357

* u13163 (U+13163): B&lt;&lt;182.0,723.5&gt;-&lt;184.0,735.0&gt;-&lt;195.0,751.0&gt;&gt;/L&lt;&lt;195.0,751.0&gt;--&lt;194.0,750.0&gt;&gt; = 10.491477012331599

* u13163 (U+13163): B&lt;&lt;608.0,896.5&gt;-&lt;581.0,899.0&gt;-&lt;558.0,903.0&gt;&gt;/B&lt;&lt;558.0,903.0&gt;-&lt;566.0,901.0&gt;-&lt;584.5,897.0&gt;&gt; = 4.170436524842054

* u13163 (U+13163): L&lt;&lt;195.0,751.0&gt;--&lt;194.0,750.0&gt;&gt;/B&lt;&lt;194.0,750.0&gt;-&lt;196.0,753.0&gt;-&lt;209.0,769.0&gt;&gt; = 11.309932474020227

* u13163 (U+13163): L&lt;&lt;203.0,927.0&gt;--&lt;70.0,827.0&gt;&gt;/L&lt;&lt;70.0,827.0&gt;--&lt;207.0,917.0&gt;&gt; = 3.6364779789756203

* u13163 (U+13163): L&lt;&lt;214.0,910.0&gt;--&lt;75.0,819.0&gt;&gt;/L&lt;&lt;75.0,819.0&gt;--&lt;223.0,902.0&gt;&gt; = 3.9276371523491687

* u13164 (U+13164): B&lt;&lt;636.0,892.5&gt;-&lt;609.0,895.0&gt;-&lt;586.0,899.0&gt;&gt;/B&lt;&lt;586.0,899.0&gt;-&lt;594.0,897.0&gt;-&lt;612.5,893.0&gt;&gt; = 4.170436524842054

* u13164 (U+13164): L&lt;&lt;288.0,944.0&gt;--&lt;167.0,874.0&gt;&gt;/L&lt;&lt;167.0,874.0&gt;--&lt;298.0,923.0&gt;&gt; = 9.541814649219015

* u13165 (U+13165): B&lt;&lt;199.5,815.5&gt;-&lt;206.0,826.0&gt;-&lt;222.0,836.0&gt;&gt;/L&lt;&lt;222.0,836.0&gt;--&lt;221.0,835.0&gt;&gt; = 12.994616791916512

* u13165 (U+13165): B&lt;&lt;460.5,769.0&gt;-&lt;414.0,795.0&gt;-&lt;351.0,796.0&gt;&gt;/L&lt;&lt;351.0,796.0&gt;--&lt;352.0,796.0&gt;&gt; = 0.9093804491989697

* u13165 (U+13165): L&lt;&lt;222.0,836.0&gt;--&lt;221.0,835.0&gt;&gt;/B&lt;&lt;221.0,835.0&gt;-&lt;225.0,838.0&gt;-&lt;239.0,847.5&gt;&gt; = 8.13010235415596

* u13165 (U+13165): L&lt;&lt;234.0,968.0&gt;--&lt;73.0,925.0&gt;&gt;/L&lt;&lt;73.0,925.0&gt;--&lt;234.0,957.0&gt;&gt; = 3.712085985563048

* u13165 (U+13165): L&lt;&lt;237.0,948.0&gt;--&lt;75.0,915.0&gt;&gt;/L&lt;&lt;75.0,915.0&gt;--&lt;243.0,937.0&gt;&gt; = 4.053265058318664

* u13165 (U+13165): L&lt;&lt;351.0,796.0&gt;--&lt;352.0,796.0&gt;&gt;/L&lt;&lt;352.0,796.0&gt;--&lt;283.0,798.0&gt;&gt; = 1.6602823689826889

* u13166 (U+13166): L&lt;&lt;121.0,951.0&gt;--&lt;77.0,924.0&gt;&gt;/L&lt;&lt;77.0,924.0&gt;--&lt;122.0,940.0&gt;&gt; = 11.961666074778089

* u13168 (U+13168): B&lt;&lt;1024.0,405.5&gt;-&lt;1070.0,406.0&gt;-&lt;1105.0,406.0&gt;&gt;/B&lt;&lt;1105.0,406.0&gt;-&lt;1087.0,407.0&gt;-&lt;1051.0,410.0&gt;&gt; = 3.1798301198641643

* u13169 (U+13169): B&lt;&lt;886.0,353.0&gt;-&lt;908.0,353.0&gt;-&lt;912.0,353.0&gt;&gt;/B&lt;&lt;912.0,353.0&gt;-&lt;896.0,354.0&gt;-&lt;867.0,356.5&gt;&gt; = 3.576334374997269

* u1316A (U+1316A): L&lt;&lt;144.0,831.0&gt;--&lt;98.0,831.0&gt;&gt;/L&lt;&lt;98.0,831.0&gt;--&lt;142.0,820.0&gt;&gt; = 14.036243467926484

* u1316B (U+1316B): L&lt;&lt;127.0,704.0&gt;--&lt;89.0,704.0&gt;&gt;/L&lt;&lt;89.0,704.0&gt;--&lt;125.0,695.0&gt;&gt; = 14.036243467926484

* u13177 (U+13177): L&lt;&lt;179.0,932.0&gt;--&lt;130.0,944.0&gt;&gt;/L&lt;&lt;130.0,944.0&gt;--&lt;179.0,918.0&gt;&gt; = 14.190183916098917

* u13177 (U+13177): L&lt;&lt;180.0,904.0&gt;--&lt;130.0,879.0&gt;&gt;/L&lt;&lt;130.0,879.0&gt;--&lt;184.0,892.0&gt;&gt; = 13.02919480794374

* u1317A (U+1317A): B&lt;&lt;1367.5,356.5&gt;-&lt;1343.0,361.0&gt;-&lt;1314.0,367.0&gt;&gt;/L&lt;&lt;1314.0,367.0&gt;--&lt;1382.0,335.0&gt;&gt; = 13.511754470035868

* u1317B (U+1317B): B&lt;&lt;109.0,140.5&gt;-&lt;109.0,135.0&gt;-&lt;110.0,130.0&gt;&gt;/B&lt;&lt;110.0,130.0&gt;-&lt;111.0,153.0&gt;-&lt;117.5,183.5&gt;&gt; = 13.799485396019362

* u1317B (U+1317B): B&lt;&lt;93.5,148.0&gt;-&lt;95.0,138.0&gt;-&lt;97.0,130.0&gt;&gt;/B&lt;&lt;97.0,130.0&gt;-&lt;96.0,135.0&gt;-&lt;96.0,140.5&gt;&gt; = 2.726310993906212

* u1317C (U+1317C): B&lt;&lt;172.0,140.0&gt;-&lt;188.0,114.0&gt;-&lt;201.0,95.0&gt;&gt;/B&lt;&lt;201.0,95.0&gt;-&lt;191.0,118.0&gt;-&lt;180.0,148.0&gt;&gt; = 10.881779047892769

* u1317C (U+1317C): B&lt;&lt;194.0,151.0&gt;-&lt;205.0,118.0&gt;-&lt;215.0,95.0&gt;&gt;/B&lt;&lt;215.0,95.0&gt;-&lt;211.0,118.0&gt;-&lt;205.5,150.0&gt;&gt; = 13.6327587328677

* u1317D (U+1317D): L&lt;&lt;540.0,107.0&gt;--&lt;406.0,277.0&gt;&gt;/B&lt;&lt;406.0,277.0&gt;-&lt;426.0,232.0&gt;-&lt;441.0,190.5&gt;&gt; = 14.283936989890815

* u1317E (U+1317E): L&lt;&lt;510.0,-112.0&gt;--&lt;620.0,-169.0&gt;&gt;/L&lt;&lt;620.0,-169.0&gt;--&lt;525.0,-101.0&gt;&gt; = 8.202318947150347

* u1317F (U+1317F): B&lt;&lt;125.0,697.0&gt;-&lt;86.0,677.0&gt;-&lt;73.0,628.0&gt;&gt;/B&lt;&lt;73.0,628.0&gt;-&lt;85.0,650.0&gt;-&lt;116.0,667.0&gt;&gt; = 13.751845218040552

* u13180 (U+13180): B&lt;&lt;989.5,747.5&gt;-&lt;956.0,753.0&gt;-&lt;932.0,759.0&gt;&gt;/B&lt;&lt;932.0,759.0&gt;-&lt;987.0,732.0&gt;-&lt;1044.0,708.0&gt;&gt; = 12.110597767654385

* u13188 (U+13188): B&lt;&lt;1129.0,727.0&gt;-&lt;1129.0,724.0&gt;-&lt;1128.0,722.0&gt;&gt;/L&lt;&lt;1128.0,722.0&gt;--&lt;1146.0,746.0&gt;&gt; = 10.304846468766044

* u13189 (U+13189): B&lt;&lt;151.0,142.0&gt;-&lt;212.0,151.0&gt;-&lt;246.0,162.0&gt;&gt;/B&lt;&lt;246.0,162.0&gt;-&lt;233.0,161.0&gt;-&lt;217.0,159.5&gt;&gt; = 13.529214407011676

* u13189 (U+13189): B&lt;&lt;212.0,258.5&gt;-&lt;228.0,258.0&gt;-&lt;241.0,258.0&gt;&gt;/B&lt;&lt;241.0,258.0&gt;-&lt;225.0,262.0&gt;-&lt;200.5,265.0&gt;&gt; = 14.036243467926484

* u1318A (U+1318A): L&lt;&lt;744.0,47.0&gt;--&lt;765.0,54.0&gt;&gt;/L&lt;&lt;765.0,54.0&gt;--&lt;744.0,52.0&gt;&gt; = 12.994616791916455

* u1318B (U+1318B): L&lt;&lt;667.0,367.0&gt;--&lt;686.0,374.0&gt;&gt;/L&lt;&lt;686.0,374.0&gt;--&lt;667.0,372.0&gt;&gt; = 14.21585347367354

* u1318C (U+1318C): L&lt;&lt;788.0,47.0&gt;--&lt;809.0,54.0&gt;&gt;/L&lt;&lt;809.0,54.0&gt;--&lt;788.0,52.0&gt;&gt; = 12.994616791916455

* u1319E (U+1319E): B&lt;&lt;180.5,508.0&gt;-&lt;148.0,498.0&gt;-&lt;122.0,484.0&gt;&gt;/B&lt;&lt;122.0,484.0&gt;-&lt;148.0,494.0&gt;-&lt;182.0,503.5&gt;&gt; = 7.2632447405845

* u131A2 (U+131A2): B&lt;&lt;111.5,245.0&gt;-&lt;91.0,236.0&gt;-&lt;64.0,216.0&gt;&gt;/B&lt;&lt;64.0,216.0&gt;-&lt;86.0,230.0&gt;-&lt;116.0,235.5&gt;&gt; = 4.0576630761366435

* u131A2 (U+131A2): B&lt;&lt;116.0,328.0&gt;-&lt;86.0,333.0&gt;-&lt;64.0,348.0&gt;&gt;/B&lt;&lt;64.0,348.0&gt;-&lt;91.0,327.0&gt;-&lt;111.5,318.5&gt;&gt; = 3.588106673889246

* u131A2 (U+131A2): B&lt;&lt;127.0,124.5&gt;-&lt;115.0,104.0&gt;-&lt;108.0,88.0&gt;&gt;/B&lt;&lt;108.0,88.0&gt;-&lt;121.0,106.0&gt;-&lt;142.5,128.0&gt;&gt; = 12.208275223621452

* u131A2 (U+131A2): B&lt;&lt;142.5,436.0&gt;-&lt;121.0,458.0&gt;-&lt;108.0,475.0&gt;&gt;/B&lt;&lt;108.0,475.0&gt;-&lt;115.0,460.0&gt;-&lt;127.0,439.5&gt;&gt; = 12.388463153308495

* u131A3 (U+131A3): B&lt;&lt;674.5,324.0&gt;-&lt;676.0,318.0&gt;-&lt;677.0,312.0&gt;&gt;/L&lt;&lt;677.0,312.0&gt;--&lt;677.0,313.0&gt;&gt; = 9.462322208025613

* u131A7 (U+131A7): B&lt;&lt;1037.5,281.5&gt;-&lt;1000.0,284.0&gt;-&lt;954.0,288.0&gt;&gt;/L&lt;&lt;954.0,288.0&gt;--&lt;993.0,277.0&gt;&gt; = 10.78143293534273

* u131AB (U+131AB): B&lt;&lt;341.0,960.0&gt;-&lt;359.0,975.0&gt;-&lt;375.0,982.0&gt;&gt;/L&lt;&lt;375.0,982.0&gt;--&lt;372.0,981.0&gt;&gt; = 5.1944289077348

* u131AE (U+131AE): B&lt;&lt;110.0,108.0&gt;-&lt;87.0,136.0&gt;-&lt;75.0,161.0&gt;&gt;/B&lt;&lt;75.0,161.0&gt;-&lt;87.0,122.0&gt;-&lt;114.5,84.5&gt;&gt; = 8.538276855252917

* u131AE (U+131AE): B&lt;&lt;556.5,3.5&gt;-&lt;532.0,-10.0&gt;-&lt;514.0,-24.0&gt;&gt;/B&lt;&lt;514.0,-24.0&gt;-&lt;552.0,-6.0&gt;-&lt;603.5,11.0&gt;&gt; = 12.528807709151492

* u131B0 (U+131B0): B&lt;&lt;266.0,644.0&gt;-&lt;266.0,649.0&gt;-&lt;265.0,653.0&gt;&gt;/L&lt;&lt;265.0,653.0&gt;--&lt;265.0,652.0&gt;&gt; = 14.036243467926484

* u131B0 (U+131B0): L&lt;&lt;265.0,653.0&gt;--&lt;265.0,652.0&gt;&gt;/B&lt;&lt;265.0,652.0&gt;-&lt;258.0,685.0&gt;-&lt;249.5,723.0&gt;&gt; = 11.976132444203333

* u131B2 (U+131B2): B&lt;&lt;639.0,474.0&gt;-&lt;613.0,459.0&gt;-&lt;592.0,443.0&gt;&gt;/B&lt;&lt;592.0,443.0&gt;-&lt;636.0,464.0&gt;-&lt;696.5,483.5&gt;&gt; = 11.790077850449174

* u131C7 (U+131C7): L&lt;&lt;208.0,550.0&gt;--&lt;313.0,137.0&gt;&gt;/L&lt;&lt;313.0,137.0&gt;--&lt;313.0,171.0&gt;&gt; = 14.264512298079907

* u131C9 (U+131C9): L&lt;&lt;208.0,550.0&gt;--&lt;313.0,137.0&gt;&gt;/L&lt;&lt;313.0,137.0&gt;--&lt;313.0,171.0&gt;&gt; = 14.264512298079907

* u131E5 (U+131E5): B&lt;&lt;867.5,368.0&gt;-&lt;852.0,380.0&gt;-&lt;836.0,393.0&gt;&gt;/B&lt;&lt;836.0,393.0&gt;-&lt;848.0,378.0&gt;-&lt;863.0,355.0&gt;&gt; = 12.246332859680393

* u13222 (U+13222): B&lt;&lt;508.5,935.0&gt;-&lt;512.0,929.0&gt;-&lt;513.0,923.0&gt;&gt;/L&lt;&lt;513.0,923.0&gt;--&lt;512.0,930.0&gt;&gt; = 1.3322198538694188

* u13222 (U+13222): B&lt;&lt;549.0,932.0&gt;-&lt;549.0,927.0&gt;-&lt;547.0,925.0&gt;&gt;/B&lt;&lt;547.0,925.0&gt;-&lt;555.0,930.0&gt;-&lt;561.5,938.0&gt;&gt; = 12.994616791916483

* u13227 (U+13227): B&lt;&lt;908.5,441.0&gt;-&lt;854.0,411.0&gt;-&lt;783.0,394.0&gt;&gt;/L&lt;&lt;783.0,394.0&gt;--&lt;1036.0,394.0&gt;&gt; = 13.465208094811695

* u13227 (U+13227): L&lt;&lt;277.0,394.0&gt;--&lt;450.0,394.0&gt;&gt;/B&lt;&lt;450.0,394.0&gt;-&lt;378.0,411.0&gt;-&lt;322.0,441.0&gt;&gt; = 13.284866484902187

* u13228 (U+13228): B&lt;&lt;908.5,441.0&gt;-&lt;854.0,411.0&gt;-&lt;783.0,394.0&gt;&gt;/L&lt;&lt;783.0,394.0&gt;--&lt;1036.0,394.0&gt;&gt; = 13.465208094811695

* u13228 (U+13228): L&lt;&lt;277.0,394.0&gt;--&lt;450.0,394.0&gt;&gt;/B&lt;&lt;450.0,394.0&gt;-&lt;378.0,411.0&gt;-&lt;322.0,441.0&gt;&gt; = 13.284866484902187

* u1322C (U+1322C): L&lt;&lt;240.0,557.0&gt;--&lt;181.0,545.0&gt;&gt;/L&lt;&lt;181.0,545.0&gt;--&lt;216.0,546.0&gt;&gt; = 9.859985975969055

* u1322F (U+1322F): B&lt;&lt;395.5,860.0&gt;-&lt;381.0,829.0&gt;-&lt;380.0,812.0&gt;&gt;/B&lt;&lt;380.0,812.0&gt;-&lt;386.0,832.0&gt;-&lt;404.0,861.0&gt;&gt; = 13.332783570563812

* u1322F (U+1322F): B&lt;&lt;425.0,873.0&gt;-&lt;407.0,849.0&gt;-&lt;397.0,829.0&gt;&gt;/B&lt;&lt;397.0,829.0&gt;-&lt;422.0,868.0&gt;-&lt;457.5,896.5&gt;&gt; = 6.0958615445957545

* u13233 (U+13233): L&lt;&lt;558.0,405.0&gt;--&lt;514.0,394.0&gt;&gt;/L&lt;&lt;514.0,394.0&gt;--&lt;1174.0,394.0&gt;&gt; = 14.036243467926484

* u13234 (U+13234): L&lt;&lt;558.0,405.0&gt;--&lt;514.0,394.0&gt;&gt;/L&lt;&lt;514.0,394.0&gt;--&lt;1174.0,394.0&gt;&gt; = 14.036243467926484

* u13236 (U+13236): B&lt;&lt;394.0,601.5&gt;-&lt;397.0,583.0&gt;-&lt;399.0,566.0&gt;&gt;/L&lt;&lt;399.0,566.0&gt;--&lt;399.0,567.0&gt;&gt; = 6.709836807756896

* u13236 (U+13236): B&lt;&lt;404.5,742.0&gt;-&lt;402.0,727.0&gt;-&lt;399.0,711.0&gt;&gt;/L&lt;&lt;399.0,711.0&gt;--&lt;399.0,712.0&gt;&gt; = 10.61965527615514

* u13236 (U+13236): L&lt;&lt;399.0,566.0&gt;--&lt;399.0,567.0&gt;&gt;/B&lt;&lt;399.0,567.0&gt;-&lt;402.0,551.0&gt;-&lt;404.5,536.0&gt;&gt; = 10.61965527615514

* u13236 (U+13236): L&lt;&lt;399.0,711.0&gt;--&lt;399.0,712.0&gt;&gt;/B&lt;&lt;399.0,712.0&gt;-&lt;397.0,695.0&gt;-&lt;394.0,677.0&gt;&gt; = 6.709836807756896

* u13237 (U+13237): B&lt;&lt;579.5,946.5&gt;-&lt;583.0,940.0&gt;-&lt;584.0,934.0&gt;&gt;/B&lt;&lt;584.0,934.0&gt;-&lt;584.0,936.0&gt;-&lt;583.5,938.0&gt;&gt; = 9.462322208025613

* u1323A (U+1323A): B&lt;&lt;722.0,805.5&gt;-&lt;725.0,801.0&gt;-&lt;726.0,796.0&gt;&gt;/B&lt;&lt;726.0,796.0&gt;-&lt;726.0,797.0&gt;-&lt;725.5,798.5&gt;&gt; = 11.309932474020195

* u13241 (U+13241): B&lt;&lt;1100.5,408.5&gt;-&lt;1090.0,398.0&gt;-&lt;1067.0,394.0&gt;&gt;/L&lt;&lt;1067.0,394.0&gt;--&lt;1174.0,394.0&gt;&gt; = 9.865806943084365

* u13241 (U+13241): B&lt;&lt;389.5,710.5&gt;-&lt;378.0,704.0&gt;-&lt;368.0,696.0&gt;&gt;/B&lt;&lt;368.0,696.0&gt;-&lt;383.0,703.0&gt;-&lt;408.0,712.0&gt;&gt; = 13.642914775990052

* u13241 (U+13241): B&lt;&lt;447.0,397.0&gt;-&lt;417.0,397.0&gt;-&lt;396.0,394.0&gt;&gt;/L&lt;&lt;396.0,394.0&gt;--&lt;503.0,394.0&gt;&gt; = 8.13010235415596

* u13241 (U+13241): B&lt;&lt;895.0,396.5&gt;-&lt;872.0,396.0&gt;-&lt;856.0,394.0&gt;&gt;/L&lt;&lt;856.0,394.0&gt;--&lt;993.0,394.0&gt;&gt; = 7.125016348901757

* u13241 (U+13241): L&lt;&lt;277.0,394.0&gt;--&lt;314.0,394.0&gt;&gt;/B&lt;&lt;314.0,394.0&gt;-&lt;296.0,397.0&gt;-&lt;283.0,407.0&gt;&gt; = 9.462322208025613

* u13241 (U+13241): L&lt;&lt;396.0,394.0&gt;--&lt;503.0,394.0&gt;&gt;/B&lt;&lt;503.0,394.0&gt;-&lt;491.0,396.0&gt;-&lt;476.0,396.5&gt;&gt; = 9.462322208025613

* u13241 (U+13241): L&lt;&lt;568.0,394.0&gt;--&lt;817.0,394.0&gt;&gt;/L&lt;&lt;817.0,394.0&gt;--&lt;789.0,399.0&gt;&gt; = 10.124671655397806

* u13241 (U+13241): L&lt;&lt;856.0,394.0&gt;--&lt;993.0,394.0&gt;&gt;/B&lt;&lt;993.0,394.0&gt;-&lt;977.0,396.0&gt;-&lt;960.0,396.5&gt;&gt; = 7.125016348901757

* u13246 (U+13246): B&lt;&lt;1028.0,402.0&gt;-&lt;1022.0,396.0&gt;-&lt;1007.0,394.0&gt;&gt;/L&lt;&lt;1007.0,394.0&gt;--&lt;1051.0,394.0&gt;&gt; = 7.594643368591447

* u13246 (U+13246): B&lt;&lt;1133.0,415.5&gt;-&lt;1114.0,397.0&gt;-&lt;1083.0,394.0&gt;&gt;/L&lt;&lt;1083.0,394.0&gt;--&lt;1174.0,394.0&gt;&gt; = 5.527540151656126

* u13246 (U+13246): B&lt;&lt;513.0,757.0&gt;-&lt;488.0,746.0&gt;-&lt;468.0,735.0&gt;&gt;/B&lt;&lt;468.0,735.0&gt;-&lt;495.0,746.0&gt;-&lt;519.5,751.0&gt;&gt; = 6.644447920890547

* u13246 (U+13246): B&lt;&lt;535.0,402.5&gt;-&lt;517.0,396.0&gt;-&lt;495.0,394.0&gt;&gt;/L&lt;&lt;495.0,394.0&gt;--&lt;750.0,394.0&gt;&gt; = 5.1944289077348

* u13246 (U+13246): L&lt;&lt;1007.0,394.0&gt;--&lt;1051.0,394.0&gt;&gt;/B&lt;&lt;1051.0,394.0&gt;-&lt;1038.0,395.0&gt;-&lt;1028.0,402.0&gt;&gt; = 4.398705354995508

* u13246 (U+13246): L&lt;&lt;49.0,394.0&gt;--&lt;193.0,394.0&gt;&gt;/B&lt;&lt;193.0,394.0&gt;-&lt;174.0,395.0&gt;-&lt;168.0,401.0&gt;&gt; = 3.012787504183286

* u13246 (U+13246): L&lt;&lt;495.0,394.0&gt;--&lt;750.0,394.0&gt;&gt;/B&lt;&lt;750.0,394.0&gt;-&lt;740.0,396.0&gt;-&lt;732.0,401.5&gt;&gt; = 11.309932474020195

* u13247 (U+13247): B&lt;&lt;840.0,443.5&gt;-&lt;835.0,432.0&gt;-&lt;835.0,433.0&gt;&gt;/L&lt;&lt;835.0,433.0&gt;--&lt;830.0,394.0&gt;&gt; = 7.3057595333108205

* u13249 (U+13249): B&lt;&lt;480.5,899.0&gt;-&lt;472.0,891.0&gt;-&lt;470.0,876.0&gt;&gt;/B&lt;&lt;470.0,876.0&gt;-&lt;472.0,881.0&gt;-&lt;482.5,889.5&gt;&gt; = 14.206766117760358

* u13249 (U+13249): B&lt;&lt;580.0,867.0&gt;-&lt;580.0,863.0&gt;-&lt;579.0,862.0&gt;&gt;/B&lt;&lt;579.0,862.0&gt;-&lt;585.0,866.0&gt;-&lt;590.0,872.5&gt;&gt; = 11.309932474020195

* u1324A (U+1324A): B&lt;&lt;401.5,607.0&gt;-&lt;360.0,650.0&gt;-&lt;337.0,725.0&gt;&gt;/B&lt;&lt;337.0,725.0&gt;-&lt;341.0,656.0&gt;-&lt;369.5,611.0&gt;&gt; = 13.73124980377496

* u1324A (U+1324A): B&lt;&lt;472.0,981.5&gt;-&lt;465.0,975.0&gt;-&lt;463.0,962.0&gt;&gt;/B&lt;&lt;463.0,962.0&gt;-&lt;465.0,967.0&gt;-&lt;472.0,973.5&gt;&gt; = 13.055247223796563

* u1324A (U+1324A): B&lt;&lt;522.5,957.0&gt;-&lt;525.0,953.0&gt;-&lt;526.0,948.0&gt;&gt;/B&lt;&lt;526.0,948.0&gt;-&lt;526.0,950.0&gt;-&lt;525.5,951.0&gt;&gt; = 11.309932474020195

* u1324A (U+1324A): B&lt;&lt;905.0,707.0&gt;-&lt;906.0,716.0&gt;-&lt;907.0,725.0&gt;&gt;/L&lt;&lt;907.0,725.0&gt;--&lt;896.0,695.0&gt;&gt; = 13.796111682338214

* u13251 (U+13251): L&lt;&lt;297.0,309.0&gt;--&lt;470.0,322.0&gt;&gt;/L&lt;&lt;470.0,322.0&gt;--&lt;297.0,347.0&gt;&gt; = 12.52020055451659

* u13251 (U+13251): L&lt;&lt;704.0,347.0&gt;--&lt;534.0,322.0&gt;&gt;/L&lt;&lt;534.0,322.0&gt;--&lt;704.0,309.0&gt;&gt; = 12.738817400913714

* u13261 (U+13261): B&lt;&lt;321.5,694.5&gt;-&lt;326.0,685.0&gt;-&lt;328.0,676.0&gt;&gt;/B&lt;&lt;328.0,676.0&gt;-&lt;328.0,678.0&gt;-&lt;327.5,682.0&gt;&gt; = 12.528807709151492

* u13262 (U+13262): L&lt;&lt;443.0,338.0&gt;--&lt;626.0,351.0&gt;&gt;/L&lt;&lt;626.0,351.0&gt;--&lt;443.0,376.0&gt;&gt; = 11.842503183847368

* u13262 (U+13262): L&lt;&lt;870.0,376.0&gt;--&lt;690.0,351.0&gt;&gt;/L&lt;&lt;690.0,351.0&gt;--&lt;870.0,338.0&gt;&gt; = 12.03801893623486

* u1329B (U+1329B): B&lt;&lt;1076.5,139.0&gt;-&lt;1015.0,119.0&gt;-&lt;941.0,105.0&gt;&gt;/L&lt;&lt;941.0,105.0&gt;--&lt;1150.0,105.0&gt;&gt; = 10.713123022791033

* u1329B (U+1329B): L&lt;&lt;294.0,105.0&gt;--&lt;491.0,105.0&gt;&gt;/B&lt;&lt;491.0,105.0&gt;-&lt;386.0,125.0&gt;-&lt;303.5,157.5&gt;&gt; = 10.784297867562596

* u1329C (U+1329C): B&lt;&lt;354.5,341.5&gt;-&lt;416.0,362.0&gt;-&lt;489.0,375.0&gt;&gt;/L&lt;&lt;489.0,375.0&gt;--&lt;280.0,375.0&gt;&gt; = 10.09750438407527

* u1329C (U+1329C): L&lt;&lt;1136.0,375.0&gt;--&lt;940.0,375.0&gt;&gt;/B&lt;&lt;940.0,375.0&gt;-&lt;1046.0,356.0&gt;-&lt;1128.0,323.0&gt;&gt; = 10.162083194000747

* u1329D (U+1329D): L&lt;&lt;208.0,98.0&gt;--&lt;352.0,98.0&gt;&gt;/B&lt;&lt;352.0,98.0&gt;-&lt;291.0,111.0&gt;-&lt;234.0,136.0&gt;&gt; = 12.030596096537845

* u1329E (U+1329E): B&lt;&lt;952.5,156.5&gt;-&lt;907.0,137.0&gt;-&lt;857.0,125.0&gt;&gt;/L&lt;&lt;857.0,125.0&gt;--&lt;1015.0,125.0&gt;&gt; = 13.495733280795811

* u1329F (U+1329F): B&lt;&lt;995.5,157.5&gt;-&lt;946.0,138.0&gt;-&lt;895.0,125.0&gt;&gt;/L&lt;&lt;895.0,125.0&gt;--&lt;1052.0,125.0&gt;&gt; = 14.300277449185575

* u1329F (U+1329F): L&lt;&lt;191.0,125.0&gt;--&lt;349.0,125.0&gt;&gt;/B&lt;&lt;349.0,125.0&gt;-&lt;329.0,130.0&gt;-&lt;296.0,141.0&gt;&gt; = 14.036243467926484

* u132A0 (U+132A0): B&lt;&lt;882.5,140.5&gt;-&lt;832.0,121.0&gt;-&lt;780.0,109.0&gt;&gt;/L&lt;&lt;780.0,109.0&gt;--&lt;950.0,109.0&gt;&gt; = 12.994616791916512

* u132A0 (U+132A0): L&lt;&lt;164.0,109.0&gt;--&lt;333.0,109.0&gt;&gt;/B&lt;&lt;333.0,109.0&gt;-&lt;281.0,121.0&gt;-&lt;230.5,140.5&gt;&gt; = 12.994616791916512

* u132BF (U+132BF): B&lt;&lt;261.5,838.5&gt;-&lt;265.0,832.0&gt;-&lt;266.0,826.0&gt;&gt;/B&lt;&lt;266.0,826.0&gt;-&lt;266.0,828.0&gt;-&lt;265.5,830.0&gt;&gt; = 9.462322208025613

* u132BF (U+132BF): B&lt;&lt;303.0,835.0&gt;-&lt;303.0,830.0&gt;-&lt;301.0,828.0&gt;&gt;/B&lt;&lt;301.0,828.0&gt;-&lt;309.0,833.0&gt;-&lt;315.5,841.0&gt;&gt; = 12.994616791916483

* u132C4 (U+132C4): B&lt;&lt;405.0,213.0&gt;-&lt;399.0,225.0&gt;-&lt;390.0,258.0&gt;&gt;/L&lt;&lt;390.0,258.0&gt;--&lt;398.0,124.0&gt;&gt; = 11.838530511286404

* u132C4 (U+132C4): B&lt;&lt;455.5,297.0&gt;-&lt;443.0,318.0&gt;-&lt;433.0,333.0&gt;&gt;/B&lt;&lt;433.0,333.0&gt;-&lt;444.0,308.0&gt;-&lt;457.0,277.0&gt;&gt; = 9.940573033112985

* u132C5 (U+132C5): B&lt;&lt;546.5,257.5&gt;-&lt;541.0,272.0&gt;-&lt;536.0,288.0&gt;&gt;/L&lt;&lt;536.0,288.0&gt;--&lt;547.0,148.0&gt;&gt; = 12.861443156346018

* u132C5 (U+132C5): B&lt;&lt;612.5,291.5&gt;-&lt;598.0,309.0&gt;-&lt;583.0,333.0&gt;&gt;/B&lt;&lt;583.0,333.0&gt;-&lt;594.0,310.0&gt;-&lt;606.5,285.0&gt;&gt; = 6.445418036259604

* u132C6 (U+132C6): B&lt;&lt;269.0,455.5&gt;-&lt;266.0,478.0&gt;-&lt;264.0,494.0&gt;&gt;/L&lt;&lt;264.0,494.0&gt;--&lt;264.0,-66.0&gt;&gt; = 7.125016348901757

* u132CD (U+132CD): L&lt;&lt;466.0,855.0&gt;--&lt;530.0,205.0&gt;&gt;/L&lt;&lt;530.0,205.0&gt;--&lt;594.0,855.0&gt;&gt; = 11.246610604107827

* u132D9 (U+132D9): B&lt;&lt;208.5,158.0&gt;-&lt;202.0,209.0&gt;-&lt;200.0,270.0&gt;&gt;/L&lt;&lt;200.0,270.0&gt;--&lt;192.0,211.0&gt;&gt; = 9.599703247416315

* u132DC (U+132DC): B&lt;&lt;1012.5,394.5&gt;-&lt;1037.0,332.0&gt;-&lt;1053.0,267.0&gt;&gt;/B&lt;&lt;1053.0,267.0&gt;-&lt;1048.0,338.0&gt;-&lt;1024.0,397.5&gt;&gt; = 9.800387305794994

* u132DC (U+132DC): B&lt;&lt;1024.0,397.5&gt;-&lt;1000.0,457.0&gt;-&lt;965.0,506.0&gt;&gt;/B&lt;&lt;965.0,506.0&gt;-&lt;988.0,457.0&gt;-&lt;1012.5,394.5&gt;&gt; = 10.392892161295432

* u132E6 (U+132E6): B&lt;&lt;324.5,373.0&gt;-&lt;331.0,312.0&gt;-&lt;332.0,236.0&gt;&gt;/B&lt;&lt;332.0,236.0&gt;-&lt;333.0,312.0&gt;-&lt;339.0,373.0&gt;&gt; = 1.5076966661411237

* u132E6 (U+132E6): B&lt;&lt;512.5,325.5&gt;-&lt;515.0,279.0&gt;-&lt;517.0,236.0&gt;&gt;/B&lt;&lt;517.0,236.0&gt;-&lt;519.0,278.0&gt;-&lt;521.0,325.0&gt;&gt; = 5.389311759973354

* u132E6 (U+132E6): B&lt;&lt;696.0,364.5&gt;-&lt;702.0,300.0&gt;-&lt;703.0,221.0&gt;&gt;/B&lt;&lt;703.0,221.0&gt;-&lt;704.0,300.0&gt;-&lt;709.5,364.5&gt;&gt; = 1.4504485981183235

* u132F9 (U+132F9): B&lt;&lt;301.0,195.0&gt;-&lt;292.0,300.0&gt;-&lt;279.0,404.0&gt;&gt;/L&lt;&lt;279.0,404.0&gt;--&lt;235.0,-11.0&gt;&gt; = 13.17713965396727

* u13325 (U+13325): L&lt;&lt;318.0,579.0&gt;--&lt;313.0,746.0&gt;&gt;/L&lt;&lt;313.0,746.0&gt;--&lt;307.0,579.0&gt;&gt; = 3.772576142474701

* u1337D (U+1337D): B&lt;&lt;672.0,254.5&gt;-&lt;645.0,270.0&gt;-&lt;621.0,282.0&gt;&gt;/B&lt;&lt;621.0,282.0&gt;-&lt;638.0,268.0&gt;-&lt;652.5,254.5&gt;&gt; = 12.90740867126579

* u13394 (U+13394): B&lt;&lt;766.0,641.5&gt;-&lt;751.0,650.0&gt;-&lt;752.0,650.0&gt;&gt;/L&lt;&lt;752.0,650.0&gt;--&lt;728.0,655.0&gt;&gt; = 11.768288932020628

* u13394 (U+13394): B&lt;&lt;841.5,627.0&gt;-&lt;820.0,634.0&gt;-&lt;800.0,639.0&gt;&gt;/B&lt;&lt;800.0,639.0&gt;-&lt;805.0,637.0&gt;-&lt;817.0,629.0&gt;&gt; = 7.765166018425308

* u133AC (U+133AC): B&lt;&lt;186.5,373.0&gt;-&lt;190.0,331.0&gt;-&lt;196.0,255.0&gt;&gt;/B&lt;&lt;196.0,255.0&gt;-&lt;204.0,304.0&gt;-&lt;208.0,369.0&gt;&gt; = 13.78659023520154

* u133AC (U+133AC): B&lt;&lt;329.5,383.5&gt;-&lt;333.0,323.0&gt;-&lt;338.0,273.0&gt;&gt;/B&lt;&lt;338.0,273.0&gt;-&lt;344.0,342.0&gt;-&lt;347.5,380.5&gt;&gt; = 10.680333865609908

* u133C3 (U+133C3): B&lt;&lt;364.5,752.5&gt;-&lt;387.0,723.0&gt;-&lt;391.0,679.0&gt;&gt;/B&lt;&lt;391.0,679.0&gt;-&lt;395.0,723.0&gt;-&lt;417.5,752.5&gt;&gt; = 10.388857815469619

* u133C3 (U+133C3): B&lt;&lt;401.5,572.5&gt;-&lt;394.0,619.0&gt;-&lt;391.0,646.0&gt;&gt;/B&lt;&lt;391.0,646.0&gt;-&lt;389.0,619.0&gt;-&lt;380.5,572.5&gt;&gt; = 10.576586544968738

* u133C3 (U+133C3): B&lt;&lt;607.0,752.5&gt;-&lt;629.0,723.0&gt;-&lt;633.0,679.0&gt;&gt;/B&lt;&lt;633.0,679.0&gt;-&lt;637.0,723.0&gt;-&lt;660.0,752.5&gt;&gt; = 10.388857815469619

* u133C3 (U+133C3): B&lt;&lt;644.0,572.5&gt;-&lt;636.0,619.0&gt;-&lt;633.0,646.0&gt;&gt;/B&lt;&lt;633.0,646.0&gt;-&lt;631.0,619.0&gt;-&lt;623.0,572.5&gt;&gt; = 10.576586544968738

* u133C5 (U+133C5): B&lt;&lt;364.5,752.5&gt;-&lt;387.0,723.0&gt;-&lt;391.0,679.0&gt;&gt;/B&lt;&lt;391.0,679.0&gt;-&lt;395.0,723.0&gt;-&lt;417.5,752.5&gt;&gt; = 10.388857815469619

* u133C5 (U+133C5): B&lt;&lt;401.5,572.5&gt;-&lt;394.0,619.0&gt;-&lt;391.0,646.0&gt;&gt;/B&lt;&lt;391.0,646.0&gt;-&lt;389.0,619.0&gt;-&lt;380.5,572.5&gt;&gt; = 10.576586544968738

* u133C5 (U+133C5): B&lt;&lt;607.0,752.5&gt;-&lt;629.0,723.0&gt;-&lt;633.0,679.0&gt;&gt;/B&lt;&lt;633.0,679.0&gt;-&lt;637.0,723.0&gt;-&lt;660.0,752.5&gt;&gt; = 10.388857815469619

* u133C5 (U+133C5): B&lt;&lt;644.0,572.5&gt;-&lt;636.0,619.0&gt;-&lt;633.0,646.0&gt;&gt;/B&lt;&lt;633.0,646.0&gt;-&lt;631.0,619.0&gt;-&lt;623.0,572.5&gt;&gt; = 10.576586544968738

* u133C5 (U+133C5): B&lt;&lt;849.0,752.5&gt;-&lt;871.0,723.0&gt;-&lt;875.0,679.0&gt;&gt;/B&lt;&lt;875.0,679.0&gt;-&lt;879.0,723.0&gt;-&lt;902.0,752.5&gt;&gt; = 10.388857815469619

* u133C5 (U+133C5): B&lt;&lt;886.0,572.5&gt;-&lt;878.0,619.0&gt;-&lt;875.0,646.0&gt;&gt;/B&lt;&lt;875.0,646.0&gt;-&lt;873.0,619.0&gt;-&lt;865.0,572.5&gt;&gt; = 10.576586544968738

* u133CE (U+133CE): B&lt;&lt;418.0,585.5&gt;-&lt;418.0,593.0&gt;-&lt;418.0,599.0&gt;&gt;/B&lt;&lt;418.0,599.0&gt;-&lt;413.0,567.0&gt;-&lt;405.5,538.5&gt;&gt; = 8.880659150520234

* u133CE (U+133CE): B&lt;&lt;419.5,566.0&gt;-&lt;419.0,578.0&gt;-&lt;419.0,570.0&gt;&gt;/B&lt;&lt;419.0,570.0&gt;-&lt;418.0,578.0&gt;-&lt;418.0,585.5&gt;&gt; = 7.125016348901757

* u13418 (U+13418): L&lt;&lt;72.0,96.0&gt;--&lt;1256.0,28.0&gt;&gt;/L&lt;&lt;1256.0,28.0&gt;--&lt;100.0,240.0&gt;&gt; = 7.105029497311982

* u13427 (U+13427): L&lt;&lt;496.0,389.0&gt;--&lt;528.0,-40.0&gt;&gt;/L&lt;&lt;528.0,-40.0&gt;--&lt;561.0,389.0&gt;&gt; = 8.66461630814273
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* U1336F (U+1336F): L&lt;&lt;327.0,409.0&gt;--&lt;325.0,756.0&gt;&gt;

* U1336F (U+1336F): L&lt;&lt;344.0,756.0&gt;--&lt;347.0,409.0&gt;&gt;

* u1301F (U+1301F): L&lt;&lt;678.0,588.0&gt;--&lt;552.0,589.0&gt;&gt;

* u1303B (U+1303B): L&lt;&lt;169.0,105.0&gt;--&lt;170.0,337.0&gt;&gt;

* u1303B (U+1303B): L&lt;&lt;191.0,329.0&gt;--&lt;189.0,99.0&gt;&gt;

* u1303B (U+1303B): L&lt;&lt;735.0,408.0&gt;--&lt;734.0,551.0&gt;&gt;

* u1303C (U+1303C): L&lt;&lt;179.0,105.0&gt;--&lt;180.0,337.0&gt;&gt;

* u1303C (U+1303C): L&lt;&lt;200.0,329.0&gt;--&lt;198.0,99.0&gt;&gt;

* u1303C (U+1303C): L&lt;&lt;341.0,558.0&gt;--&lt;471.0,559.0&gt;&gt;

* u13056 (U+13056): L&lt;&lt;169.0,105.0&gt;--&lt;170.0,337.0&gt;&gt;

* u13056 (U+13056): L&lt;&lt;191.0,329.0&gt;--&lt;189.0,99.0&gt;&gt;

* u1309C (U+1309C): L&lt;&lt;438.0,104.0&gt;--&lt;563.0,103.0&gt;&gt;

* u1309C (U+1309C): L&lt;&lt;959.0,103.0&gt;--&lt;1084.0,104.0&gt;&gt;

* u130BB (U+130BB): L&lt;&lt;67.0,-136.0&gt;--&lt;201.0,-135.0&gt;&gt;

* u130BB (U+130BB): L&lt;&lt;736.0,-136.0&gt;--&lt;870.0,-135.0&gt;&gt;

* u130BC (U+130BC): L&lt;&lt;106.0,-136.0&gt;--&lt;240.0,-135.0&gt;&gt;

* u130BC (U+130BC): L&lt;&lt;775.0,-136.0&gt;--&lt;909.0,-135.0&gt;&gt;

* u130BF (U+130BF): L&lt;&lt;384.0,-273.0&gt;--&lt;577.0,-272.0&gt;&gt;

* u130C1 (U+130C1): L&lt;&lt;252.0,-274.0&gt;--&lt;530.0,-273.0&gt;&gt;

* u130D3 (U+130D3): L&lt;&lt;211.0,340.0&gt;--&lt;210.0,479.0&gt;&gt;

* u130D5 (U+130D5): L&lt;&lt;822.0,18.0&gt;--&lt;1072.0,19.0&gt;&gt;

* u130D6 (U+130D6): L&lt;&lt;325.0,245.0&gt;--&lt;326.0,92.0&gt;&gt;

* u130F4 (U+130F4): L&lt;&lt;928.0,-86.0&gt;--&lt;927.0,57.0&gt;&gt;

* u130F9 (U+130F9): L&lt;&lt;258.0,54.0&gt;--&lt;103.0,55.0&gt;&gt;

* u13112 (U+13112): L&lt;&lt;854.0,612.0&gt;--&lt;856.0,322.0&gt;&gt;

* u1311A (U+1311A): L&lt;&lt;452.0,148.0&gt;--&lt;453.0,11.0&gt;&gt;

* u13125 (U+13125): L&lt;&lt;173.0,8.0&gt;--&lt;172.0,277.0&gt;&gt;

* u13125 (U+13125): L&lt;&lt;193.0,278.0&gt;--&lt;192.0,8.0&gt;&gt;

* u13144 (U+13144): L&lt;&lt;894.0,557.0&gt;--&lt;895.0,955.0&gt;&gt;

* u13144 (U+13144): L&lt;&lt;915.0,928.0&gt;--&lt;914.0,611.0&gt;&gt;

* u1315A (U+1315A): L&lt;&lt;311.0,19.0&gt;--&lt;471.0,20.0&gt;&gt;

* u1315A (U+1315A): L&lt;&lt;514.0,19.0&gt;--&lt;656.0,20.0&gt;&gt;

* u1315E (U+1315E): L&lt;&lt;592.0,78.0&gt;--&lt;591.0,252.0&gt;&gt;

* u1315F (U+1315F): L&lt;&lt;833.0,257.0&gt;--&lt;834.0,68.0&gt;&gt;

* u1316C (U+1316C): L&lt;&lt;184.0,843.0&gt;--&lt;49.0,844.0&gt;&gt;

* u13174 (U+13174): L&lt;&lt;778.0,660.0&gt;--&lt;906.0,659.0&gt;&gt;

* u13175 (U+13175): L&lt;&lt;778.0,660.0&gt;--&lt;906.0,659.0&gt;&gt;

* u1317B (U+1317B): L&lt;&lt;780.0,230.0&gt;--&lt;781.0,486.0&gt;&gt;

* u131AE (U+131AE): L&lt;&lt;981.0,12.0&gt;--&lt;713.0,10.0&gt;&gt;

* u131B1 (U+131B1): L&lt;&lt;1315.0,190.0&gt;--&lt;952.0,187.0&gt;&gt;

* u131B2 (U+131B2): L&lt;&lt;826.0,504.0&gt;--&lt;1112.0,506.0&gt;&gt;

* u1324B (U+1324B): L&lt;&lt;716.0,557.0&gt;--&lt;715.0,977.0&gt;&gt;

* u1324B (U+1324B): L&lt;&lt;734.0,958.0&gt;--&lt;736.0,557.0&gt;&gt;

* u132A1 (U+132A1): L&lt;&lt;630.0,793.0&gt;--&lt;631.0,678.0&gt;&gt;

* u132A3 (U+132A3): L&lt;&lt;632.0,94.0&gt;--&lt;906.0,93.0&gt;&gt;

* u132A3 (U+132A3): L&lt;&lt;920.0,73.0&gt;--&lt;634.0,75.0&gt;&gt;

* u132DF (U+132DF): L&lt;&lt;194.0,-203.0&gt;--&lt;425.0,-202.0&gt;&gt;

* u13343 (U+13343): L&lt;&lt;1196.0,112.0&gt;--&lt;361.0,114.0&gt;&gt;

* u13343 (U+13343): L&lt;&lt;351.0,319.0&gt;--&lt;1176.0,317.0&gt;&gt;

* u13343 (U+13343): L&lt;&lt;360.0,133.0&gt;--&lt;1176.0,131.0&gt;&gt;

* u13344 (U+13344): L&lt;&lt;1455.0,112.0&gt;--&lt;570.0,114.0&gt;&gt;

* u13344 (U+13344): L&lt;&lt;570.0,134.0&gt;--&lt;1435.0,131.0&gt;&gt;

* u13344 (U+13344): L&lt;&lt;629.0,319.0&gt;--&lt;1435.0,317.0&gt;&gt;

* u13422 (U+13422): L&lt;&lt;102.0,347.0&gt;--&lt;103.0,-172.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 2 | 9 | 118 | 6 | 116 | 0 | 
| 0% | 0% | 1% | 4% | 47% | 2% | 46% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
