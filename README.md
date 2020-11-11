# Résumé

LaTeX source for the [Résumé of Daniel Dietrich](https://resume.danieldietrich.dev)

Download the .pdf version [here](https://resume.danieldietrich.dev/daniel-dietrich-resume.pdf).

## Instructions

The résumé is automatically deployed to [gh-pages](https://pages.github.com) by a [GitHub Action](.github/workflows/deploy.yml) when pushing to the `main` branch.

To manually build the .pdf on a local machine, an installation of [Texlive](https://www.tug.org/texlive/) is required.

```sh
pdflatex daniel-dietrich-resume.tex
```

The output is written to the file `daniel-dietrich-resume.pdf`.