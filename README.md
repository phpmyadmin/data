presentations
=============

The presentations use the beamer template for LaTeX.

Installation
------------

To install (on Debian/Ubuntu/...) :

apt-get install latex-beamer

Usage
-----

To compile a tex file and generate a pdf :

pdflatex presentation.tex

To create handouts, add "handout" to the class options

\documentclass[14pti,handout]{beamer}
