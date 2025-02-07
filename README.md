# jurLaTeX - Template for Legal Academic Writing

A LaTeX template specifically designed for legal academic writing in German, featuring proper legal citation styles and document structuring.

## Overview

This template provides a standardized format for legal academic documents, with built-in support for:
- German legal citation styles
- Proper document structuring (chapters, sections, etc.)
- Bibliography management
- German language support

## Prerequisites

To use this template, you'll need:
1. A LaTeX distribution installed on your computer:
   - For Windows: Install [MiKTeX](https://miktex.org/download)
   - For macOS: Install [MacTeX](https://www.tug.org/mactex/mactex-download.html)
   - For Linux: Install TeX Live (`sudo apt-get install texlive-full` for Ubuntu)
2. A text editor (recommended: [TeXstudio](https://www.texstudio.org/) or [Visual Studio Code](https://code.visualstudio.com/) with LaTeX Workshop extension)

## Getting Started

1. Download or clone this repository
2. Open the template in your chosen text editor
3. Start writing by editing `main.tex`

## Document Structure

The template uses the following hierarchy for document structuring:
- Kapitel (Chapter): Numbered as "Kapitel 1", "Kapitel 2", etc.
- Abschnitte (Sections): Lettered as A., B., C., etc.
- Unterabschnitte (Subsections): Numbered as I., II., III., etc.
- Further subsections: Numbered as 1., 2., 3., etc.
- Paragraphs: Lettered as a., b., c., etc.
- Subparagraphs: Numbered as (1), (2), (3), etc.

## Citations and Bibliography

1. Add your references to `literatur.bib` in BibTeX format
2. Cite sources in your text using `\cite{key}`
3. The template supports various citation types:
   - Court decisions
   - Books
   - Journal articles
   - Book chapters
   - Commentary entries
   - Websites
   - Government documents

## Compilation

To properly compile your document with citations:
1. Compile with LaTeX/pdfLaTeX/XeLaTeX
2. Run citeproc-lua on the file
3. Compile again with LaTeX/pdfLaTeX/XeLaTeX (1-2 times)

Most modern LaTeX editors will handle this automatically.

## Work in Progress

This template is currently under development. Feel free to contribute improvements or report issues.

## License

This template uses a custom citation style (jurzitat.csl) which is licensed under Creative Commons Attribution-ShareAlike 3.0.
