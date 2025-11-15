# GEMINI.md

## Directory Overview

This directory contains the LaTeX source files for a PhD proposal titled "SELECTION OF VARIABLES FOR CLUSTER ANALYSIS WITH APPLICATION TO DHS DATA IN CAMEROON". The project is authored by Ayendoh Terrence Sama and supervised by Dr. M.S. Madukaife and Dr. E.O. Ossai.

The proposal focuses on developing a procedure for variable selection in cluster analysis, particularly for high-dimensional data like the Demographic and Health Surveys (DHS) data from Cameroon.

## Key Files

*   `proposal.tex`: This is the main LaTeX file for the proposal. It defines the document structure, includes necessary packages, and contains the text for all sections of the proposal, from the title page to the expected results.

*   `references.bib`: This file contains the bibliography for the proposal in BibTeX format. It includes references to academic articles and books related to cluster analysis, variable selection, and machine learning.

*   `images/logo.png`: This is the logo image file used in the title page of the proposal.

## Usage

The contents of this directory are intended to be compiled using a LaTeX distribution (e.g., TeX Live, MiKTeX) to produce a PDF document of the PhD proposal. The main file to be compiled is `proposal.tex`. The compilation process will also use the `references.bib` file to generate the bibliography and the `images/logo.png` file for the title page.

To compile the document, you would typically use a command-line tool like `pdflatex` along with `bibtex`:

```bash
pdflatex proposal.tex
bibtex proposal
pdflatex proposal.tex
pdflatex proposal.tex
```
