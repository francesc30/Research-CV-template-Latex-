# Academic CV Templates — LaTeX

I built these CV templates while working on my own academic CV as a PhD candidate in environmental science. They started from the [NSF Biosketch template](https://www.overleaf.com/latex/examples/nsf-biosketch/xdmybvfqdmyr) on Overleaf, but I ended up redesigning them almost entirely to better reflect research impact rather than just background.

Feel free to use them, adapt them, and make them yours.

## Two versions

### `handy/` — Single file, easy to edit
For researchers early in their career or new to LaTeX. Everything is in one `main.tex` file — just open it, replace the content with yours, and compile. No folder structure to worry about.

### `advanced/` — Modular, easy to maintain
For researchers with a longer CV or who are comfortable with LaTeX. Content is split into separate files by section (`education.tex`, `research.tex`, `publications.tex`, etc.), making it easier to update individual sections without touching the rest.

Both versions share the same design philosophy: **research impact first**, clean blue accents, APA-formatted publications, and circled numbered bibliography entries.

## What makes them different from other templates

- Research-first structure: publications and conferences come before experience
- Clean blue accents with circled numbered bibliography entries
- APA-formatted publications powered by `biblatex` + `biber`
- Your name is automatically bolded in every citation
- Journal and conference names highlighted in blue
- FontAwesome5 icons for contact info
- Photo support in the header

## How to use

1. Clone or download this repository
2. Choose `starter/` or `advanced/`
3. Open in [Overleaf](https://www.overleaf.com) or your local LaTeX editor
4. Set compiler to **pdfLaTeX** and bibliography tool to **Biber**
5. Edit `main.tex` and `publications.bib` with your information
6. Compile and done

## Requirements

If compiling locally: TeX Live or MiKTeX, with `biblatex`, `fontawesome5`, `tikz`, `titlesec`, `enumitem`, `fancyhdr`, `geometry`.

## Inspired by

- [NSF Biosketch — Overleaf](https://www.overleaf.com/latex/examples/nsf-biosketch/xdmybvfqdmyr)
- [CV Tips and Samples — University of Illinois](https://grad.illinois.edu/CareerDevelopment)
- [Academic CV Guide — Newcastle University Careers Service](https://www.ncl.ac.uk/careers)

## License

Free to use and adapt for personal academic use. A mention or star is always appreciated!
