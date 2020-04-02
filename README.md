Font-file language support
==========================

Adds syntax highlighting for several font-related text formats:

* [Adobe font metrics][afm]: `.afm`
* [FIGlet fonts and control files][fig]: `.flc`, `.flf`, `.tlf`
* [FontForge's built-in scripting language][pe]: `.ff`, `.pe`
* [Glyph bitmap distribution files][bdf]: `.bdf`
* [OpenType feature files][fea]: `.fea`
* [Spline font databases][sfd]: `.sfd`
* [X font directory lists][dir]: `fonts.dir`, `fonts.scale`, `fonts.alias`, `encodings.dir`

Originally, only FontForge scripts were supported (hence the package's name).
Over time, additional formats were added which were considered too niche to
warrant their own repositories. Many of these grammars are now used by GitHub
for highlighting their respective formats. Others may be added in the future.


Previews
--------

> FontForge's scripting language:
![Highlighted `.pe` file](https://raw.githubusercontent.com/Alhadis/language-fontforge/master/prev-1.png)

> OpenType feature files:
![Highlighted `.fea` file](https://raw.githubusercontent.com/Alhadis/language-fontforge/master/prev-2.png)

> Adobe font metrics:
![Highlighted `.afm` file](https://raw.githubusercontent.com/Alhadis/language-fontforge/master/prev-3.png)


[Referenced links]:_____________________________________________________________
[afm]: https://adobe.com/content/dam/Adobe/en/devnet/font/pdfs/5004.AFM_Spec.pdf
[bdf]: https://adobe.com/content/dam/Adobe/en/devnet/font/pdfs/5005.BDF_Spec.pdf
[dir]: https://www.x.org/archive/X11R7.5/doc/man/man1/mkfontdir.1.html
[fea]: https://adobe-type-tools.github.io/afdko/OpenTypeFeatureFileSpecification.html
[fig]: http://www.figlet.org/figlet-man.html
[pe]:  https://fontforge.org/docs/scripting/scripting.html
[sfd]: https://fontforge.org/docs/techref/sfdformat.html
