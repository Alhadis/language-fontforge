<!--*- coding: utf-8; fill-column: 80; truncate-lines: t; -*-
vim:se noet lbr tw=80 sts=0 sw=4 ts=4 nowrap: -->

Font-file language support
================================================================================

Adds syntax highlighting for several font-related text formats:

* [Adobe font metrics][afm]: `.afm`
* [Standard Bézier][bez]: `.bez`
* [FIGlet fonts and control files][fig]: `.flc`, `.flf`, `.tlf`
* [Fontinfo files][fd]: `fontinfo`
* [FontForge's built-in scripting language][pe]: `.ff`, `.pe`
* [Glyph bitmap distribution files][bdf]: `.bdf`
* [OpenType feature files][fea]: `.fea`
* [Spline font databases][sfd]: `.sfd`
* [X font directory lists][dir]: `fonts.{dir,scale,alias}`, `encodings.dir`

Originally, only FontForge scripts were supported (hence the package's name).
Over time, additional formats were added which were considered too niche to
warrant their own repositories. Many of these grammars are now used by GitHub
for highlighting their respective formats. Others may be added in the future:

* [Adobe Font List][afl]: `AdobeFnt_CMaps.lst`
* [<samp>fc-list</samp>][fc]: `fc-list`
* [Ideograph Variations Database][ivd]:
	* Registered collections: `*_collections.txt`
	* Unicode sequences: `*_sequences.txt`
* [MakeOTF][mak]-related formats:
	* `GlyphOrderAndAliasDB`
	* `FontMenuNameDB`
* [MetaFont][mf]: `.mf`
* [YAFF][yaf]: `.yaff`


Previews
--------------------------------------------------------------------------------

> FontForge's scripting language:
![Highlighted `.pe` file][p1]

> OpenType feature files:
![Highlighted `.fea` file][p2]

> Adobe font metrics:
![Highlighted `.afm` file][p3]


<!-- Referenced links --------------------------------------------------------->
[afl]: http://fileformats.archiveteam.org/wiki/Adobe_Font_List
[afm]: https://adobe-type-tools.github.io/font-tech-notes/pdfs/5004.AFM_Spec.pdf
[bez]: https://github.com/adobe-type-tools/psautohint/blob/HEAD/doc/bezformat.md
[bdf]: https://adobe-type-tools.github.io/font-tech-notes/pdfs/5005.BDF_Spec.pdf
[dir]: https://www.x.org/archive/X11R7.5/doc/man/man1/mkfontdir.1.html
[fc]:  https://www.mankier.com/1/fc-list
[fea]: https://adobe-type-tools.github.io/afdko/OpenTypeFeatureFileSpecification
[fig]: http://www.figlet.org/figlet-man.html
[fd]:  https://adobe-type-tools.github.io/afdko/MakeOTFUserGuide#fontinfo
[ivd]: http://unicode.org/reports/tr37/#w1aac11b1
[mak]: https://adobe-type-tools.github.io/afdko/MakeOTFUserGuide
[mf]:  https://en.wikipedia.org/wiki/Metafont
[pe]:  https://fontforge.org/docs/scripting/scripting.html
[sfd]: https://fontforge.org/docs/techref/sfdformat.html
[yaf]: https://github.com/robhagemans/monobit/blob/408d7fd/YAFF.md
[p1]:  https://github.com/Alhadis/language-fontforge/raw/36ff453/prev-1.png
[p2]:  https://github.com/Alhadis/language-fontforge/raw/36ff453/prev-2.png
[p3]:  https://github.com/Alhadis/language-fontforge/raw/36ff453/prev-3.png
