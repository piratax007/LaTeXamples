# tikz2pdf

This script allows you to run a realtime previsualization of tikz pictures developed in a separed `pgf` file. To use
this, copy the `emacs_pdflatex_tikz_general_template.tex` or `emacs_xelatex_tikz_genaral_template.tex` into your source
project directory and make your tikz picture using a different file (anyone `.pgf`, `.tex` or `.tikz` extension is well)
and run the `tikz2pdf` script as follow:

```
tikz2pdf ENGINE TEMPLATE PICTURE_FILE
```
 where:
 - **ENGINE** is either `pdflatex` or `xelatex`.
 - **TEMPLATE** is one of the available templates (see up).
 - **PICTURE_FILE** is the `.pgf` (`.tex` or `.tikz`) file in that you will develop your picture.
 
**NOTE:** In order to use this script, you need to have an installation of `latexmk` and is highly recommendable to have
an installation of `okular`. 
