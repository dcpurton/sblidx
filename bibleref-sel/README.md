# bibleref-sbl

Society of Biblical Literature Style for the `bibleref` LaTeX Package

The `bibleref-sbl` package extends the `bibleref` package to support Bible
book names as specified by the *Society of Biblical Literature Handbook of
Style*.  This includes adjustment of abbreviations, addition of extra
Deuterocanonical books, an interface for acceptable options and correct index
sorting.

## Installation from TeXLive or MiKTeX

The `bibleref-sbl` package is in TeXLive and MiKTeX and can be installed in the
usual way through your distribution. E.g., in TeXLive by running:

```
tlmgr install bibleref-sbl
```

## Installation from CTAN

Download and unpack `bibleref-sbl.zip` from CTAN at
https://ctan.org/pkg/bibleref-sbl

Change to the `bibleref-sbl` directory, then run:

```
tex bibleref-sbl.ins
```

to generate `bibleref-sbl.sty`.

Copy `bibleref-sbl.sty` to `$TEXMFHOME/tex/latex/bibleref-sbl/` and
`bibleref-sbl.pdf` to `$TEXMFHOME/doc/latex/bibleref-sbl/`.

You can find `$TEXMFHOME` by running:

```
kpsewhich -var-value=TEXMFHOME
```

## Installation from Git Source

`bibleref-sbl` uses the `l3build` system.

Clone the git repository using:

```
git clone https://github.com/dcpurton/bibleref-sbl.git
```

Change to the `bibleref-sbl` directory, and then the style file
(`bibleref-sbl.sty`) and documentation (`bibleref-sbl.pdf`) can be installed
by running:

```
l3build install --full
```

## Licence

```
Copyright (c) 2026 David Purton <dcpurton@marshwiggle.net>

This work may be distributed and/or modified under the conditions of
the LaTeX Project Public License, either version 1.3c of this license
or (at your option) any later version. The latest version of this
license is in
   http://www.latex-project.org/lppl.txt
and version 1.3c or later is part of all distributions of LaTeX
version 2005/12/01 or later.

This work is "maintained" (as per the LPPL maintenance status)
by David Purton.

This work consists of the files bibleref-sbl.ins, bibleref-sbl.dtx,
README.md, and the derived files bibleref-sbl.sty and bibleref-sbl.pdf
```
