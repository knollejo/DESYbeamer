# Title Graphics

## Files

This directory contains two images:

1. desy.jpg shows a view of the DESY site in Hamburg, taken from http://m.desy.de
1. cms.jpg shows a head-on view of the CMS detector at the CERN LHC, taken from http://cds.cern.ch/record/1344500

## Usage

Include in the LaTeX header one of:

* `\setbeamertemplate{titlegraphic}[desy]` for desy.jpg (default)
* `\setbeamertemplate{titlegraphic}[cms]` for cms.jpg
* For a user-defined image user.jpg (optimal ratio is 25:1), use
```latex
\setbeamertemplate{titlegraphic}[user]
\titlegraphic{\includegraphics[width=\paperwidth,height=3.2cm]{user.jpg}}
```
