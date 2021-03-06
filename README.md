
# LaTeX-KOMA-template

This template is based on Karl Voit's LaTeX-KOMA template. It includes
(currently) changes from @dkales and @kaydoubleu.

What changed:

* Laterality: ~~twoside~~ &rarr; oneside
* Fontsize: ~~12pt~~ &rarr; 11pt
* Biblatexstyle: ~~authoryear~~ &rarr; alphabetic
* Dispositioncolor?
* Titlepage: ~~Thesis_TU_Graz~~ &rarr; Thesis_TU_Graz_-_kazemakase
  - According to:
    http://portal.tugraz.at/portal/page/portal/TU_Graz/Services/BDR/Oeffentlichkeitsarbeit/CD/Logo%20Anwendungsrichtlinien
  - Slight changes on the title page
* Minor changes in *template/pdf_settings.tex*
  - pagecolor: not set 
  - pdfpagemode: ~~None~~ &rarr; UseNone
* Minor changes in *template/preamble.tex*
  - DispositionColor: ~~{RGB}{\mydispositioncolor}~~ &rarr; {gray}{0} (black) 
  - Options of package biblatex modified

## Purpose of This Project

This is a generic template for [LaTeX](http://en.wikipedia.org/wiki/LaTeX)
documents using [KOMA Script](http://www.komascript.de/) classes which are
pretty common at least in German spoken countries.

The template does *not* want to contain each and every trick but should
provide a *clean*, *consistent* and *well documented* starting point for any
document exceeding a few pages. So if you plan to write a longer report,
a diploma thesis, a PhD thesis, or similar, this template should give you
a good basis.

The focus is that you - the author - is able to concentrate on the *content*
of your work rather than start fiddling around with the look of the document.
Several typographic optimizations are included in order to get a final document
that is optimized to deliver your content.

Please do read [Template-Documentation.pdf](https://github.com/novoid/LaTeX-KOMA-template/blob/master/Template-Documentation.pdf).

## Example Documents

In case you want to see some example documents generated via this
template, please do read [the Hall of Fame](https://github.com/novoid/LaTeX-KOMA-template/blob/master/Hall_of_fame.org).

Do me a favor and *do submit your final document* as well. It helps
other people in their decision process and adds up to a very cool
collection of results we can be proud of.

## Requirements

This template uses up-to-date technology like pdflatex, [biblatex](http://www.tex.ac.uk/tex-archive/info/translations/biblatex/de/)
(instead of BibTeX-Format), [biber](http://en.wikipedia.org/wiki/Biber_(LaTeX)) (instead of bibtex-compiler), and
optionally [GNU make.](http://www.gnu.org/s/make/)  You should be familiar with compiling LaTeX
documents by yourself. If you are new to LaTeX please get basic
knowledge from tutorial pages such as [this one](http://LaTeX.TUGraz.at).

You can find out more in [Template-Documentation.pdf](https://github.com/novoid/LaTeX-KOMA-template/blob/master/Template-Documentation.pdf).

## What Makes This Template Special?

The speciality of this consistent template is, that every setting in
the preamble is *well documented* (in LaTeX). You can generate the
documentation file "Template-Documentation.pdf" on your own by not
removing the template documentation include command in the main LaTeX
file and using [GNU make](http://www.gnu.org/software/make/) with the rule "templatedocu":

```sh
make templatedocu
```

This command results in the "[Template-Documentation.pdf](https://github.com/novoid/LaTeX-KOMA-template/blob/master/Template-Documentation.pdf)" file
containing the most current documentation of this template. Please
refer to this PDF file for further information about the template.

## How to Start?

Please do read the "[Template-Documentation.pdf](https://github.com/novoid/LaTeX-KOMA-template/blob/master/Template-Documentation.pdf)" file which contains a
"How to use this LaTeX template" section.

## License

This template is licensed under a [Creative Commons Attribution-ShareAlike 3.0 Unported (CC BY-SA 3.0) license](https://creativecommons.org/licenses/by-sa/3.0/):

- You can share (to copy, distribute and transmit) this template.
- You can remix (adapt) this template.
- You can make commercial use of the template.
- In case you modify this template and share the derived template: You
  must attribute the template such that you do not remove
  (co-)authorship of Karl Voit & LosFuzzys and you must not remove the URLs to 
  [the original repository on GitHub](https://github.com/novoid/LaTeX-KOMA-template).
- If you alter, transform, or build a new template upon this template,
  you may distribute the resulting template only under the same or
  similar license to this one.
- There are *no restrictions* of any kind, however, related to the
  resulting (PDF) document!
- You may remove the colophon (but it's not recommended).

## What Is Still Work in Progress?

Please have a look at the file "[template/todos.org](https://github.com/novoid/LaTeX-KOMA-template/blob/master/template/todos.org)".
