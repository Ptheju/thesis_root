Dimensionality Reduction thesis repository

Structure:
- `main.tex` : root LaTeX file
- `bibliography.bib` : BibTeX references
- `chapters/` : chapter source files
- `figures/` : high-resolution figures (300 DPI)

Build with:

```bash
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```
