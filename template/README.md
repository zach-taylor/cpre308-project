# Template

This folder contains a sample document structure.
It uses the IEEEtran document class.

## Contents
It is organized as follows:

 - a main.tex file: Contains the header information, and controls structure for the whole document.  Includes other necessary documents.
 - other *.tex files: Contains sample text to show structure.  You will also find examples on how to reference sections, make figures and tables, and cite sources.
 - refeence.bib: Will contain bibtex entries for the reference section

## Compiling
The simplest way to compile is with:

    latexmk main.tex -pdf -pvc

`latexmk` is a special command that calls the appropriate latex engine, as well as generate citations.
The `-pdf` option simply tells it to generate a pdf file
The `-pvc` option tells it to enter preview mode.
In preview mode, it watches for any updates you make to your source files and recompiles when necessary - very useful.

Otherwise, you can use:

    pdflatex main.tex
    bibtex main.tex
    pdflatex main.tex
    pdflatex main.tex

Notice the multiple passes here - latex needs to first scan your document to determine which citations to include, generate the bibliography, then include it, then make sure the reference numbers are correct.
`latexmk` takes care of this for you and is the recommended option.
