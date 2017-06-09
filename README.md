This repository contains the TeX source for:

> Stachelek, J. and Madden, C.J., 2015. Application of inverse path distance weighting for high-density spatial mapping of coastal water quality patterns. International Journal of Geographical Information Science, 29(7), pp.1240-1250.

To build the pdf use a LaTeX IDE (such as MikTeX or RStudio) or run the following commands from the terminal:

```
cd tex
pdflatex stachmadden.tex
pdflatex stachmadden.tex # run a 2nd time to capture bib
cp stachmadden2015.pdf ../stachmadden2015.pdf
```
