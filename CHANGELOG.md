Change-log
==========

This project adheres to [Semantic Versioning](http://semver.org).

[Unpublished]: ../../compare/v1.4.0...HEAD


[v1.4.0]
------------------------------------------------------------------------
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
* Fixed [various inaccuracies][1] related to modeline matching
* Improved tokenisation of FontForge procedure calls

[bez]: https://github.com/adobe-type-tools/psautohint/blob/99e1cb862/doc/bezformat.md
[fd]: https://github.com/adobe-type-tools/psautohint/blob/12bffdd/python/psautohint/fdTools.py
[1]: https://github.com/github/linguist/pull/5271


[v1.3.0]
------------------------------------------------------------------------
**September 6th, 2018:**  
Added syntax highlighting for several more formats:

* [FIGlet fonts and control files][fig]: `.flc`, `.flf`, `.tlf`
* [Glyph bitmap distribution files][bdf]: `.bdf`
* [X font directory lists][dir]: `fonts.dir`, `fonts.scale`, `fonts.alias`, `encodings.dir`

[fig]: http://www.figlet.org/figlet-man.html
[bdf]: https://adobe.com/content/dam/Adobe/en/devnet/font/pdfs/5005.BDF_Spec.pdf
[dir]: https://www.x.org/archive/X11R7.5/doc/man/man1/mkfontdir.1.html


[v1.2.0]
------------------------------------------------------------------------
**July 23rd, 2017:**  
Added syntax highlighting for [Adobe Font Metrics](https://adobe.com/content/dam/Adobe/en/devnet/font/pdfs/5004.AFM_Spec.pdf) (`*.afm`).


[v1.1.1]
------------------------------------------------------------------------
**October 27th, 2016:**  
Added `rvrn` and `vrtr` to OpenType's feature-tag list.


[v1.1.0]
------------------------------------------------------------------------
**October 27th, 2016:**  
Added syntax highlighting for [OpenType feature files](http://www.adobe.com/devnet/opentype/afdko/topic_feature_file_syntax.html).


[v1.0.0]
------------------------------------------------------------------------
**August 28th, 2016:**  
Initial release. Adds syntax highlighting for FontForge scripts.


[Referenced links]:_____________________________________________________
[v1.4.0]: https://github.com/Alhadis/language-fontforge/releases/v1.4.0
[v1.3.0]: https://github.com/Alhadis/language-fontforge/releases/v1.3.0
[v1.2.0]: https://github.com/Alhadis/language-fontforge/releases/v1.2.0
[v1.1.1]: https://github.com/Alhadis/language-fontforge/releases/v1.1.1
[v1.1.0]: https://github.com/Alhadis/language-fontforge/releases/v1.1.0
[v1.0.0]: https://github.com/Alhadis/language-fontforge/releases/v1.0.0
