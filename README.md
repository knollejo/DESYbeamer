# DESYbeamer

LaTeX beamer theme for DESY corporate design, based on previous work of Artur Lobanov and Jan Hajer.

## Install:

1. Keep in same folder as your main TeX file
2. $TEX/texmf/tex/latex

## Usage:

```latex
\documentclass[10pt]{beamer}
\usetheme{desy}
\setbeamertemplate{titlegraphic}[cms]
\setbeamertemplate{logos}[desycms]

\title{Title}
\subtitle{Subtitle}
\author[N. Surname]{Name Surname}
\institute[ShortConf]{Conference Name}
\date{\today}

\begin{document}

\maketitle

\end{document}
```

## Features:

* Highlight text with ```\emph{}``` in DESY blue or ```\alert{}``` in DESY orange.
* Change the photo on the title slide (details in titlegraphics/README.md).
* Change the logos that appear on the bottom of each slide (details in logos/README.md).
* Include a title page for the backup section with the ```\backup``` command (no need to call ```\appendix``` additionally), or use ```\backup[Supplementary\\Material]``` to modify the default headline.

## ToDo:

* Doesn't work with global text size other than 10pt.
* If author or institute is longer than one line, the logos on the title page are pushed down.
