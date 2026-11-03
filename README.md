# burgholzer.me

Source for [burgholzer.me](https://burgholzer.me), built with Hugo and Hugo Blox.

## Prerequisites

- Hugo 0.169.0
- Go 1.19 or later (for Hugo modules)
- Node.js 24 or later

## Local development

```sh
npm ci
hugo server --disableFastRender
```

## Production build

```sh
npm ci
hugo --gc --minify
```

Netlify runs the same build command and deploys `public/`.

Author details and the biography are in `data/authors/admin.yaml`. The retired
Decap CMS admin is no longer included; edit the source files directly.

## CVs

The English and German LaTeX sources are in `cv/en` and `cv/de`. Each directory
contains the original template and bibliography files. The full publication list
is maintained on the TUM website. To rebuild a CV, use a TeX distribution with
`latexmk`, Biber, and the required LaTeX packages:

```sh
cd cv/en # or cv/de
latexmk -pdf -interaction=nonstopmode -halt-on-error cv.tex
```

Copy the English PDF to `static/uploads/resume.pdf` and the German PDF to
`static/uploads/lebenslauf.pdf` when publishing updates.
