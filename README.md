# latex-apa7-stu-example

An example of a APA7 student paper in LaTeX using BibLaTeX for references.
The manual for the APA7 LaTeX package is available [here](https://ctan.org/pkg/apa7)
and the BibLaTeX manual [here](https://ctan.org/pkg/biblatex-apa).

## Pre-requisites

A [LaTeX distribution](https://www.latex-project.org/get/) needs to be installed.
If you're using R then [TinyTeX](https://yihui.org/tinytex/) could be an alternative.

## Compile PDF

1. Create files needed to create reference: `pdflatex example`
2. Compile references: `biber example` (rerun when new references are used in the manuscript)
3. Compile PDF: `pdflatex example`
4. Compile PDF: `pdflatex example` (sometimes needed to get page breaks right)
