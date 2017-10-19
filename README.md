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
* Include a title page for the backup section with the ```\backup``` command (no need to call ```\appendix``` additionally), or use ```\backup[Supplementary\\Material]``` to modify the default headline. Use ```\thankyou``` to write out thanks on the backup slide.
* Change the way the slide number is written on each slide with ```\setbeamertemplate{page number in foot}[option]```, with the options ```page``` for Page 2, ```page/total``` for Page 2/7, ```slide``` for Slide 2, ```slide/total``` for Slide 2/7, ```number``` for 2, ```number/total``` for 2/7.
* Use ```\etem``` or ```\atem``` to print item labels in emphasized or alerted colors.
* Use the frame option ```vertical``` to print the logos in the frame footer vertically aligned instead of horizontally.
* By default, the title on the title page ends with an orange dot. Use ```\setbeamertemplate{dot in title}[none]``` in the preamble to remove this dot.

## ToDo:

* Doesn't work with global text size other than 10pt.
