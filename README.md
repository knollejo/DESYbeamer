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

\begin{frame}[plain]
	\titlepage
\end{frame}

\end{document}
```
