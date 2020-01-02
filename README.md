LaTeX Package: Geometry 2020/01/02 v5.9
----------------------------------------
Flexible and complete interface to document dimensions.

Copyright (C) 1996-2010
by Hideo Umeki <latexgeometry@gmail.com>
Copyright (C) 2018-202
Hideo Umeki and David Carlisle https://github.com/davidcarlisle/geometry

Abstract:
  This package provides a flexible and easy interface to page dimensions.
  You can set the page layout with intuitive parameters. For instance,
  if you want to set a margin to 2cm from each edge of the paper,
  you can go \usepackage[margin=2cm]{geometry}. With \newgeometry command
  you can change the layout anywhere in the document.

CTAN: macros/latex/contrib/geometry

Recent changes:

[Release 5.9]
Do not load ifxetex and ifpdf packages (use combined iftex package)
Include German translation of the documentation.

[Release 5.8]
Add xdvipdfmx and dvipdfmx alias for dvipdfm option.

[Release 5.7]
Add support for luatex (with new comand names introduced in luatex 0.85)

(changes.txt for more history)

Files:
  * README.md         -  this file
  * changes.txt       -  history of changes
  * geometry.dtx      -  including sources and documentation
  * geometry.pdf      -  print-ready documentation
  * geometry-de.dtx   -  German translation
  * geometry-de.pdf   -  German translation

Installation: 
[manual installation]
  * To get geometry.sty out of geometry.dtx
        $ tex geometry.dtx 
    or  $ (la)tex geometry.ins (after first extraction)
  * To build documentation
        $ latex geometry.dtx  
    or  $ latex geometry.drv (after first extraction)
  * Put the derived files in the proper directories:
      -  tex/latex/geometry/geometry.sty
      -  doc/latex/geometry/geometry.pdf
      -  source/latex/geometry/geometry.dtx

[TeXLive]
  * Use 'tlmgr' command
        $ tlmgr show geometry          -- to check the package info
        $ sudo tlmgr update geometry   -- to update the package
  * You can use 'TeX Live Utility' instead of 'tlmgr', if on MacOSX.

[MikTeX]
  * Use the MikTeX Update Wizard to update geometry package.

License:
  This work may be distributed and/or modified under the conditions
  of the LaTeX Project Public License, either version 1.3c of this
  license or (at your option) any later version. The latest version
  of this license is in http://www.latex-project.org/lppl.txt
  and version 1.3c or later is part of all distributions of LaTeX
  version 2005/12/01 or later.

--
Happy TeXing!
Hideo Umeki
 
EOF