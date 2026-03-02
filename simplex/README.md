# simplex — Linguistic example environments for LaTeX

The `simplex` package provides:

- Three numbered example environments (`unlabeledexample`, `shortexample`,
  `example`) sharing a common counter with full `\label`/`\ref` support.
- Interlinear gloss macros (`\gll`, `\glll`, `\glt`, `\gln`, `\glend`)
  for word-aligned two- or three-line glosses, adapted from
  `covington.sty` and `gloss.tex` (van der Goot, 1991).

## Files

| File          | Description                         |
|---------------|-------------------------------------|
| `simplex.sty` | The package                         |
| `simplex.tex` | Documentation source                |
| `simplex.pdf` | Compiled documentation              |
| `README.md`   | This file                           |

## Installation

Copy `simplex.sty` to a directory on your TeX input path, e.g.:
```
$TEXMFHOME/tex/latex/simplex/
```

Then run `texhash` or `mktexlsr` if necessary.

## Usage
```latex
\usepackage{simplex}
```

See `simplex.pdf` for full documentation and examples.

## License

Copyright © Kyle Gorman.  
Distributed under the LaTeX Project Public License, version 1.3 or later.  
<http://www.latex-project.org/lppl.txt>

Portions adapted from `gloss.tex` (Marcel R. van der Goot, 1991) and
`covington.sty` (Michael Covington).
