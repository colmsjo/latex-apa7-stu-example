# latex-apa7-stu-example

## Pre-requisites

A [LaTeX distribution](https://www.latex-project.org/get/) needs to be installed.
If you're using R then [TinyTeX](https://yihui.org/tinytex/) could be an alternative.

## Compile PDF

1. Create files needed to create reference: `pdflatex example`
2. Compile references: `biber example` (rerun when new references are using in the manuscript)
3. Compile PDF: `pdflatex example`
4. Compile PDF: `pdflatex example` (sometimes needed to get page breaks right)
