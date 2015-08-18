DESYbeamer
==========

LaTeX beamer theme for DESY style

## Install:

1. Keep in same folder as your main TeX file
2. $TEX/texmf/tex/latex

# Usage:

```latex
\definecolor{cDESYBlue}{RGB}{0,133,215}
\definecolor{cDESYOrange}{RGB}{242,142,0}
\definecolor{desycyan}{RGB}{0,166,235}

\mode<presentation>{
  \usetheme{desy}
  \setbeamercovered{transparent}
}

\setbeamercolor{block title}{fg=white,bg=cDESYBlue}
\setbeamercolor{block body}{fg=white,bg=desycyan}

\setbeamercolor{footnote}{fg=black}
\setbeamercolor{footnote mark}{fg=black}
```
