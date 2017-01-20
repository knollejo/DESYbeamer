# Logos

## Helmholtz Association logo

The logo of the Helmholtz association is shown in the lower left corner of the first slide. It comes with the word _association_ in German or English. Specify by including one of the following lines in the LaTeX header:

* `\setbeamertemplate{helmholtz logo}[en]` for English (default)
* `\setbeamertemplate{helmholtz logo}[de]` for German

## DESY logo and other logos

In the lower right corner of the first slide and, smaller, on all other slides, the logo of DESY and, if applicable, other logos are shown. The default behaviour, to show only the DESY logo, is enforced by the following command:

* `\setbeamertemplate{logos}[desy]` (default)

This style has options to include the logo of the CMS collaboration:

* `\setbeamertemplate{logos}[desycms]` for the logos of DESY and CMS
* `\setbeamertemplate{logos}[desycmsbril]` for the logos of DESY, CMS and the BRIL group

For other cases, the existing options can be overwritten:
```latex
\setbeamertemplate{other logo in title}{
	\includegraphics[height=1.4cm]{logo1}
	\hspace{0.5cm}
	\includegraphics[height=1.4cm]{logo2}
	...
}
\setbeamertemplate{logo in foot}{
	\includegraphics[height=0.85cm]{logo1}
	\hspace{0.2cm}
	\includegraphics[height=0.85cm]{logo2}
	...
}
```
