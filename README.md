# Math-4411-Divisibility
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
% Beamer Presentation
% LaTeX Template
% Version 1.0 (10/11/12)
%
% This template has been downloaded from:
% http://www.LaTeXTemplates.com
%
% License:
% CC BY-NC-SA 3.0
%(http://creativecommons.org/licenses/by-nc-sa/3.0/)
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

%----------------------------------------------------------------------------------------
%	PACKAGES AND THEMES
%----------------------------------------------------------------------------------------

\documentclass{beamer}

\mode<presentation> {

% The Beamer class comes with a number of default slide themes
% which change the colors and layouts of slides. Below this is a %list
% of all the themes, uncomment each in turn to see what they look %like.

%\usetheme{default}
%\usetheme{AnnArbor}
%\usetheme{Antibes}
%\usetheme{Bergen}
%\usetheme{Berkeley}
%\usetheme{Berlin}
%\usetheme{Boadilla}
%\usetheme{CambridgeUS}
%\usetheme{Copenhagen}
%\usetheme{Darmstadt}
%\usetheme{Dresden}
%\usetheme{Frankfurt}
%\usetheme{Goettingen}
%\usetheme{Hannover}
%\usetheme{Ilmenau}
%\usetheme{JuanLesPins}
%\usetheme{Luebeck}
\usetheme{Madrid}
%\usetheme{Malmoe}
%\usetheme{Marburg}
%\usetheme{Montpellier}
%\usetheme{PaloAlto}
%\usetheme{Pittsburgh}
%\usetheme{Rochester}
%\usetheme{Singapore}
%\usetheme{Szeged}
%\usetheme{Warsaw}

% As well as themes, the Beamer class has a number of color themes
% for any slide theme. Uncomment each of these in turn to see how %it
% changes the colors of your current slide theme.

%\usecolortheme{albatross}
%\usecolortheme{beaver}
%\usecolortheme{beetle}
%\usecolortheme{crane}
%\usecolortheme{dolphin}
%\usecolortheme{dove}
%\usecolortheme{fly}
%\usecolortheme{lily}
%\usecolortheme{orchid}
%\usecolortheme{rose}
%\usecolortheme{seagull}
%\usecolortheme{seahorse}
%\usecolortheme{whale}
%\usecolortheme{wolverine}

%\setbeamertemplate{footline} % To remove the footer line in all %slides uncomment this line
%\setbeamertemplate{footline}[page number] % To replace the footer %line in all slides with a simple slide count uncomment this line

%\setbeamertemplate{navigation symbols}{} % To remove the %navigation symbols from the bottom of all slides uncomment this %line
}

\usepackage{graphicx} % Allows including images
\graphicspath{ {./CryptographyFigures/} }
\usepackage{booktabs} % Allows the use of \toprule, \midrule and %\bottomrule in tables


\theoremstyle{plain}
\newtheorem{theorem}{Theorem}
\newtheorem{corollary}{Corollary}
\newtheorem*{main}{Main~Theorem}
\newtheorem{lemma}{Lemma}
\newtheorem{proposition}{Proposition}

\newcommand{\N}{{\mathbb N}}
\newcommand{\Z}{{\mathbb Z}}
\newcommand{\Q}{{\mathbb Q}}
\newcommand{\R}{{\mathbb R}}
\newcommand{\C}{{\mathbb C}}
\newcommand{\II}{{\mathcal I}}
\newcommand{\MM}{{\mathcal M}}
\newcommand{\EE}{{\mathcal E}}
\newcommand{\NN}{{\mathcal N}}
\newcommand{\LL}{{\mathcal L}}
\newcommand{\CU}{{\mathcal U}}
\newcommand{\CC}{{\mathcal C}}
\newcommand{\F}{{\mathcal F}}


\theoremstyle{definition}
\newtheorem{definition}{Definition}
\newtheorem{example}{Example}
\newtheorem{exercise}{Exercise}
\newtheorem{remark}{Remark}
\theoremstyle{remark}
\newtheorem*{notation}{Notation}

\numberwithin{equation}{section}


%----------------------------------------------------------------------------------------
%	TITLE PAGE
%----------------------------------------------------------------------------------------

\title[Math 4411]{Math 4411} % The short title appears at the bottom of every %slide, the full title is only on the title page

\author{Jaki Chowdhury} % Your name
\institute[Ohio Northern University] % Your institution %as it will appear on the bottom of every slide, may be %shorthand to save space
{
Ohio Northern University\\ % Your institution for the title page
\medskip
\textit{j-chowdhury@onu.edu} % Your email address
}
\date{\today} % Date, can be changed to a custom date

\begin{document}

\begin{frame}
\titlepage % Print the title page as the first slide
\end{frame}

\begin{frame}
\frametitle{Sets of Numbers}

$\N = \{ 1, 2, 3, \ldots \}$.

\vspace{.2in}
\pause
$\Z = \{ \ldots, -2, -1, 0, 1, 2, 3, \ldots \}$.

\vspace{.2in}
\pause
$\Q = \{ \frac{a}{b} : a, b \in \Z, b\neq 0 \}$.

\vspace{.2in}
\pause
$\R = \text{ the set of real numbers }$.

\vspace{.2in}
\pause
$\C = \{ a+bi : a, b \in \R\} (\text{ the set of complex numbers })$.

\end{frame}

%------------------------------------------------



\end{document}
