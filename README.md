# LaTeX Template for Studying Math with Steps

A clean, printable LaTeX study sheet with a dark night-sky background and color-coded step boxes for working through math problems.

## What it looks like

- Deep blue night background with subtle stars
- 5 pastel-colored boxes labeled Step 1 through Step 5
- Designed for A4 paper at a compact 0.5 inch margin

## Requirements

Any LaTeX distribution with these packages:

- `amsmath`, `amssymb` — math symbols
- `tcolorbox` — colored boxes
- `tikz` — star background
- `xcolor`, `pagecolor`, `eso-pic` — colors and background
- `lmodern`, `microtype` — sharp typography

## Usage

1. Open `main.tex`
2. Fill in each Step box with your problem and working
3. Compile with `pdflatex main.tex`

## File structure

```
main.tex      — the template source
.gitignore    — excludes LaTeX build artifacts
```
