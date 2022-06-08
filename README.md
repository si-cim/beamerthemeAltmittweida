# LaTeX Beamer Theme: Altmittweida

## Installation on Linux

```sh
git clone git@github.com:si-cim/beamerthemeAltmittweida.git $TEXMFHOME/tex/latex/beamerthemeAltmittweida
```

## Example

```
\documentclass[aspectratio=169]{beamer}
\usepackage[T1]{fontenc}

\usetheme{Altmittweida}
\beamertemplatenavigationsymbolsempty

\usepackage{ubuntu}

\title{An Example}
\author{Max Mustermann}
\date{\today}

\begin{document}
{\fontUbuntu

\maketitle

\begin{frame}[plain]{{\fontUbuntu Frame Title}}{{\fontUbuntu Frame Subtitle...}}
  \begin{block}{{\fontUbuntu Alphabets}}
    \begin{itemize}
    \item a
    \item b
    \item c
    \end{itemize}
  \end{block}
  \begin{block}{{\fontUbuntu Numbers}}
    \begin{enumerate}
    \item One
    \item Two
    \item Three
    \end{enumerate}
  \end{block}
\end{frame}

}
\end{document}
```

The same example is available as the file `exmaple.tex`.

## Usage

**Compile twice for the title page to work properly!**

## TODO

1. ~Use the HSMW blue for block titles.~
2. Add theme option to use the Ubuntu font.
