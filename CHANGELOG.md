<!--*- coding: utf-8; fill-column: 80; truncate-lines: t; -*-
vim:se noet lbr tw=80 sts=0 sw=4 ts=4 nowrap: -->

Change-log
================================================================================

This project adheres to [Semantic Versioning](http://semver.org).


[Unpublished](https://github.com/Alhadis/language-fonts/compare/v1.4.0...HEAD)
--------------------------------------------------------------------------------
* Disabled OpenType ligatures in [XLFD] strings


[v1.4.0]
--------------------------------------------------------------------------------
**July 2nd, 2021**  
* Added automatic indentation of FontForge keywords
* Added grammars for [Standard Bézier][bez] and [Fontinfo][fd] files
* Added recognition of Vim and Emacs modelines
* Added snippets for FontForge scripting
* Added support for comment-toggling in BDF and SFD files
* Added support for line-continuation in FontForge scripts
* Added `.ff` to supported FontForge script extensions
* Fixed broken hashbang recognition in FontForge scripts
* Fixed highlighting of SFD `GaspTable` fields without colons
* Fixed missing highlighting of BDF comments which precede `STARTFONT`
* Fixed missing highlighting of FontForge's Unicode codepoint literals
* Fixed [various inaccuracies][linguist#5271] related to modeline matching
* Improved tokenisation of FontForge procedure calls


[v1.3.0]
--------------------------------------------------------------------------------
**September 6th, 2018:**  
Added syntax highlighting for several more formats:

* [FIGlet fonts and control files][fig]: `.flc`, `.flf`, `.tlf`
* [Glyph bitmap distribution files][bdf]: `.bdf`
* [X font directory lists][dir]: `fonts.{dir,scale,alias}`, `encodings.dir`


[v1.2.0]
--------------------------------------------------------------------------------
**July 23rd, 2017:**  
Added syntax highlighting for [Adobe Font Metrics][afm] (`*.afm`).


[v1.1.1]
--------------------------------------------------------------------------------
**October 27th, 2016:**  
Added `rvrn` and `vrtr` to OpenType's feature-tag list.


[v1.1.0]
--------------------------------------------------------------------------------
**October 27th, 2016:**  
Added syntax highlighting for [OpenType feature files][fea].


[v1.0.0]
--------------------------------------------------------------------------------
**August 28th, 2016:**  
Initial release. Adds syntax highlighting for FontForge scripts.


<!-- Referenced links --------------------------------------------------------->
[afm]: https://adobe-type-tools.github.io/font-tech-notes/pdfs/5004.AFM_Spec.pdf
[bdf]: https://adobe-type-tools.github.io/font-tech-notes/pdfs/5005.BDF_Spec.pdf
[bez]: https://github.com/adobe-type-tools/psautohint/blob/HEAD/doc/bezformat.md
[dir]: https://www.x.org/archive/X11R7.5/doc/man/man1/mkfontdir.1.html
[fd]:  https://adobe-type-tools.github.io/afdko/MakeOTFUserGuide#fontinfo
[fea]: https://adobe-type-tools.github.io/afdko/OpenTypeFeatureFileSpecification
[fig]: http://www.figlet.org/figlet-man.html
[linguist#5271]: https://github.com/github-linguist/linguist/pull/5271
[xlfd]: https://x.org/archive/X11R7.6/doc/xorg-docs/specs/XLFD/xlfd.pdf
[v1.0.0]: https://github.com/Alhadis/language-fontforge/releases/v1.0.0
[v1.1.0]: https://github.com/Alhadis/language-fontforge/releases/v1.1.0
[v1.1.1]: https://github.com/Alhadis/language-fontforge/releases/v1.1.1
[v1.2.0]: https://github.com/Alhadis/language-fontforge/releases/v1.2.0
[v1.3.0]: https://github.com/Alhadis/language-fontforge/releases/v1.3.0
[v1.4.0]: https://github.com/Alhadis/language-fontforge/releases/v1.4.0
