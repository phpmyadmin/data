Usage
-----

* Edit the conservancy-phpmyadmin-fsa.tex with your favorite editor.
Have a look at the [Latex manual](https://en.wikibooks.org/wiki/LaTeX) on how to use latex.

* To compile a tex file and generate a pdf :

latex conservancy-phpmyadmin-fsa.tex && dvipdf conservancy-phpmyadmin-fsa.dvi

or

pdflatex conservancy-phpmyadmin-fsa.tex

(but draftcopy is not compatible with pdflatex, so the DRAFT watermark will not be visible)

Installation
------------

To install latex tools (on Debian/Ubuntu/...) :

apt-get install texlive-latex-recommended

The required macros should already be present in the same directory as the tex file,
but if you want to compile your own or update them :

First install the gv tool, needed to compile the macros (on Debian/Ubuntu/...) :

apt-get install gv

Download (and compile) the additional macros:

* [draftcopy](http://www.ctan.org/tex-archive/macros/latex/contrib/draftcopy)
* [enumitem](http://www.ctan.org/tex-archive/macros/latex/contrib/enumitem)


