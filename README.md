# jurLaTeX - Template for German Legal Academic Writing

A LaTeX template specifically designed for legal academic writing in German, featuring proper legal citation styles and document structuring.

WORK IN PROGRESS - MAY BE BROKEN

## Overview

This template provides a standardized format for legal academic documents, with built-in support for:
- German legal citation styles
- Proper document structuring (chapters, sections, etc.)
- Bibliography management

## Prerequisites

To use this template, you'll need:
1. A LaTeX distribution installed on your computer:
   - For Windows: Install [MiKTeX](https://miktex.org/download)
   - For macOS: Install [MacTeX](https://www.tug.org/mactex/mactex-download.html)
   - For Linux: Install TeX Live (`sudo apt-get install texlive-full` for Ubuntu)
2. A text editor (recommended: [Visual Studio Code](https://code.visualstudio.com/) with LaTeX Workshop extension)

## Citations and Bibliography

1. Add your references to `literatur.bib` in BibTeX format.
2. Optional: Adjust csl file to your liking
3. Cite sources in your text using `\cite{key}`

## Compilation

To properly compile your document with citations:
1. Compile with LaTeX/pdfLaTeX/XeLaTeX
2. Run citeproc-lua on the file
3. Compile again with LaTeX/pdfLaTeX/XeLaTeX (1-2 times)
