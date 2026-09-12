# m152

Solutions and practice exercises for the Swiss ICT module **152 – Web design and
implementation with a markup language**. Each folder under `Uebungen/` is a small,
self-contained HTML/CSS exercise.

## Contents

- `Uebungen/UebungX-Y/` — individual exercises, mostly an `index.html` with its
  own stylesheet.
- Some exercises use **Sass** (`.scss` partials compiled to `style.css`).
- A few include supporting material (a demo video, a licence PDF).

## Tech

- HTML5, CSS3, Sass (SCSS).

## Usage

Open any exercise directly in a browser:

```bash
open Uebungen/Uebung1-1/index.html
```

For the Sass-based exercises, edit the `.scss` files and recompile:

```bash
sass Uebungen/Uebung9-1/style.scss Uebungen/Uebung9-1/style.css
```
