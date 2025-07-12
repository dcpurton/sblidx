# sblidx – A LaTeX style for Society of Biblical Literature indices

The `sblidx` package provides a LaTeX style for for creating indices in line
with the requirements of the Society of Biblical Literature. Indices for
ancient sources (via `bibleref-sbl`), modern authors (via `biblatex-sbl`) and
subjects are supported. Number ranges are compressed and indexed items in
notes are indicated using n. and nn.

## Installation from TeXLive or MiKTeX

The `sblidx` package is in TeXLive and MiKTeX and can be installed in the
usual way through your distribution. E.g., in TeXLive by running:

```
tlmgr install sblidx
```

## Installation from CTAN

Download and unpack `sblidx.zip` from CTAN at https://ctan.org/pkg/sblidx

Change to the `sblidx` directory, then run:

```
tex sblidx.ins
```

to generate `sblidx.sty`.

Copy `sblidx.sty` to `$TEXMFHOME/tex/latex/sblidx/` and `sblidx.pdf` to
`$TEXMFHOME/doc/latex/sblidx/`.

You can find `$TEXMFHOME` by running:

```
kpsewhich -var-value=TEXMFHOME
```

## Installation from Git Source

`sblidx` uses the `l3build` system.

Clone the git repository using:

```
git clone https://github.com/dcpurton/sblidx.git
```

Change to the `sblidx` directory, and then the style file (`sblidx.sty`) and
documentation (`sblidx.pdf`) can be installed by running:

```
l3build install --full
```

## Licence

```
Copyright (c) 2025 David Purton <dcpurton@marshwiggle.net>

This work may be distributed and/or modified under the conditions of
the LaTeX Project Public License, either version 1.3c of this license
or (at your option) any later version. The latest version of this
license is in
   http://www.latex-project.org/lppl.txt
and version 1.3c or later is part of all distributions of LaTeX
version 2005/12/01 or later.

This work is "maintained" (as per the LPPL maintenance status)
by David Purton.

This work consists of the files sblidx.ins, sblidx.dtx, README.md,
and the derived files sblidx.sty and sblidx.pdf
```
