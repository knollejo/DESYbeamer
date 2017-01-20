# Logos

## Helmholtz Association logo

The logo of the Helmholtz association is shown in the lower left corner of the first slide. It comes with the word _association_ in German or English. Specify by including one of the following lines in the LaTeX header:

* `\setbeamertemplate{helmholtz logo in title}[en]` for English (default)
* `\setbeamertemplate{helmholtz logo in title}[de]` for German

## DESY logo and other logos

In the lower right corner of the second slide, the logo of DESY and, if applicable, other logos are shown. The default behaviour, to show only the DESY logo, is enforced by the following command:

* `\setbeamertemplate{other logo in title}[desy]` (default)

This style has options to include the logo of the CMS collaboration:

* `\setbeamertemplate{other logo in title}[desycms]` for the logos of DESY and CMS
* `\setbeamertemplate{other logo in title}[desycmsbril]` for the logos of DESY, CMS and the BRIL group

For other cases, the existing options can be overwritten:
```latex
\setbeamertemplate{other logo in title}{
	\includegraphics[height=1.4cm]{logo1}
	\hspace{0.5cm}
	\includegraphics[height=1.4cm]{logo2}
	...
}
```
