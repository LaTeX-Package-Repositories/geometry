# LaTeX Package: Geometry 2026/11/15 v6.2

Flexible and complete interface to document dimensions.

Copyright (C) 1996-2010 by Hideo Umeki <latexgeometry@gmail.com>

Copyright (C) 2018-2026 Hideo Umeki and David Carlisle
<https://github.com/LaTeX-Package-Repositories/geometry>

## Abstract
  This package provides a flexible and easy interface to page dimensions.
  You can set the page layout with intuitive parameters. For instance,
  if you want to set a margin to 2cm from each edge of the paper,
  you can go `\usepackage[margin=2cm]{geometry}`. With the `\newgeometry`
  command you can change the layout anywhere in the document.

CTAN: macros/latex/contrib/geometry

## Recent changes

#### Release 6.2
* Remove atbegshi dependency for the `showframe` and `showcrop` options.
* Fix `showframe` option when `reversemarginpar` is active ([#17](https://github.com/LaTeX-Package-Repositories/geometry/issues/17)).

#### Release 6.1
* Add additional ISO and JIS paper sizes ([#2](https://github.com/LaTeX-Package-Repositories/geometry/issues/2), [#23](https://github.com/LaTeX-Package-Repositories/geometry/issues/23)).
* Remove German translation geometry-de.(dtx|pdf) from CTAN; move to `unmaintained-german-translation` directory on GitHub.

#### Release 6.0
* Improve support for tagging.
* Cropmarks are tagged as artifacts.

#### Release 5.9
* Do not load ifxetex and ifpdf packages (use combined iftex package).
* Include German translation of the documentation.

#### Release 5.8
* Add xdvipdfmx and dvipdfmx alias for dvipdfm option.

#### Release 5.7
* Add support for luatex (with new command names introduced in luatex 0.85).

(See changes.txt for more history.)

## Files
  * README.md         -  this file
  * changes.txt       -  history of changes
  * geometry.dtx      -  including sources and documentation
  * geometry.pdf      -  print-ready documentation

## Installation

### Manual installation
  * To get geometry.sty out of geometry.dtx
    
    ```tex
    tex geometry.dtx
    ```
    or
    ```tex
    (la)tex geometry.ins
    ```
    (after first extraction).
  * To build documentation

    ```tex
    latex geometry.dtx
    ```
    or
    ```tex
    latex geometry.drv
    ```
    (after first extraction)
  * Put the derived files in the proper directories:
      -  tex/latex/geometry/geometry.sty
      -  doc/latex/geometry/geometry.pdf
      -  source/latex/geometry/geometry.dtx

### TeXLive
  * Use `tlmgr` command
    
    ```
    tlmgr show geometry          -- to check the package info
    ```
    ```
    sudo tlmgr update geometry   -- to update the package
    ```
  * You can use 'TeX Live Utility' instead of `tlmgr`, if on MacOSX.

### MikTeX
  * Use the MikTeX Update Wizard to update geometry package.

## License
  This work may be distributed and/or modified under the conditions
  of the LaTeX Project Public License, either version 1.3c of this
  license or (at your option) any later version. The latest version
  of this license is in https://www.latex-project.org/lppl.txt
  and version 1.3c or later is part of all distributions of LaTeX
  version 2005/12/01 or later.

---
Happy TeXing!
Hideo Umeki

EOF
