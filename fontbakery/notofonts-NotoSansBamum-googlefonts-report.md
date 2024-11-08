## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[7] NotoSansBamum[wght].ttf</summary>
<div>
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
    <summary>⚠️ <b>WARN</b> Detect any interpolation issues in the font. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Interpolation issues were found in the font:</p>
<pre><code>- Contour 1 start point differs in glyph 'uniA6DD' between location wght=400 and location wght=700

- Contour 1 in glyph 'uniA6DD': becomes underweight between wght=400 and wght=700.

- Contour 1 point 0 in glyph 'uniA6DD' has a kink between location wght=400 and location wght=700

- Contour order differs in glyph 'uniA6A5': [0, 1, 2] in wght=400, [0, 2, 1] in wght=700.
</code></pre>
 [code: interpolation-issues]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSansBamum/googlefonts/variable-ttf does not have an article.</p>
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
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, math, cherokee, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: todhri, math, old-permic, duployan, canadian-aboriginal, hebrew, syriac, tifinagh, tai-le, malayalam, coptic</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: oriya, sinhala, saurashtra, canadian-aboriginal, hanifi-rohingya, dogra, mahajani, siddham, masaram-gondi, balinese, thai, ahom, coptic, buhid, modi, rejang, nko, tai-tham, tai-le, meetei-mayek, thaana, pahawh-hmong, khudawadi, buginese, sharada, batak, adlam, mende-kikakui, kayah-li, khmer, duployan, gunjala-gondi, bhaiksuki, limbu, hebrew, javanese, phags-pa, hanunoo, devanagari, wancho, lao, tamil, kannada, tai-viet, gujarati, psalter-pahlavi, lepcha, sogdian, syriac, sundanese, osage, tibetan, grantha, kharoshthi, syloti-nagri, khojki, yi, marchen, symbols, elbasan, tagbanwa, tifinagh, miao, math, mongolian, telugu, cham, tagalog, malayalam, bengali, brahmi, warang-citi, myanmar, chakma, manichaean, caucasian-albanian, tirhuta, newa, soyombo, zanabazar-square, music, gurmukhi, new-tai-lue, armenian, old-permic, kaithi, mandaic, bassa-vah, takri</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>bamum</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Vute (Latn, 21,000 speakers), Zapotec (Latn, 490,000 speakers), Avokaya (Latn, 100,000 speakers), Gulay (Latn, 250,478 speakers), Makaa (Latn, 221,000 speakers), Kom (Latn, 360,685 speakers), Heiltsuk (Latn, 300 speakers), Aghem (Latn, 38,843 speakers), Igbo (Latn, 27,823,640 speakers), Dan (Latn, 1,099,244 speakers), Ekpeye (Latn, 226,000 speakers), Basaa (Latn, 332,940 speakers), Ma’di (Latn, 584,000 speakers), Bafut (Latn, 158,146 speakers), Nateni (Latn, 100,000 speakers), Mundani (Latn, 34,000 speakers), Dii (Latn, 71,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Belarusian (Cyrl, 10,064,517 speakers), Southern Kisi (Latn, 360,000 speakers), Mfumte (Latn, 79,000 speakers), Navajo (Latn, 166,319 speakers), Bete-Bendi (Latn, 100,000 speakers), Ebira (Latn, 2,200,000 speakers), Koonzime (Latn, 40,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Yala (Latn, 200,000 speakers), Cicipu (Latn, 44,000 speakers), Han (Latn, 6 speakers), Ejagham (Latn, 120,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Sar (Latn, 500,000 speakers), Fur (Latn, 1,230,163 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Nzakara (Latn, 50,000 speakers), Kaska (Latn, 125 speakers), South Central Banda (Latn, 244,000 speakers), Lugbara (Latn, 2,200,000 speakers), Mango (Latn, 77,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check the direction of the outermost contour in each glyph <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have a counter-clockwise outer contour:</p>
<pre><code>* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour
</code></pre>
 [code: ccw-outer-contour]



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
| 0 | 0 | 1 | 6 | 97 | 7 | 140 | 0 | 
| 0% | 0% | 0% | 2% | 39% | 3% | 56% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
