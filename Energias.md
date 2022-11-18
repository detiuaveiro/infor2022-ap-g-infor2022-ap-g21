\documentclass{report}
\usepackage[T1]{fontenc} % Fontes T1
\usepackage[utf8]{inputenc} % Input UTF8
\usepackage[backend=biber, style=ieee]{biblatex} % para usar bibliografia
\usepackage{csquotes}
\usepackage[portuguese]{babel} %Usar língua portuguesa
\usepackage{blindtext} % Gerar texto automaticamente
\usepackage[printonlyused]{acronym}
\usepackage{hyperref} % para autoref
\usepackage{graphicx}
\usepackage{indentfirst}

\bibliography{bibliografia}


\begin{document}
%%
% Definições
%

\def\titulo{Energias}
\def\data{DATA}
\def\autores{Francisco Franco, Tomás Oliveira}
\def\autorescontactos{(113275) franco.f04@ua.pt, (113939) tomas.esteves.oliveira@ua.pt}
\def\versao{VERSAO 1}
\def\departamento{Dept. de Eletrónica, Telecomunicações e Informática}
\def\empresa{Universidade de Aveiro}
\def\logotipo{ua.pdf}
%
%%%%%% CAPA %%%%%%
%
\begin{titlepage}

\begin{center}
%
\vspace*{50mm}
%
{\Huge \ Energias}\\ 
%
\vspace{10mm}
%
{\Large \empresa}\\
%
\vspace{10mm}
%
{\LARGE \autores}\\ 
%
\vspace{30mm}
%
\begin{figure}[h]
\center
\includegraphics{\logotipo}
\end{figure}
%
\vspace{30mm}
\end{center}
%
\begin{flushright}
\versao
\end{flushright}
\end{titlepage}

%%  Página de Título %%
\title{%
{\Huge\textbf{\titulo}}\\
{\Large \departamento\\ \empresa}
}
%
\author{%
    \autores \\
    \autorescontactos
}
%
\date{\today}
%
\maketitle

\pagenumbering{roman}

%%%%%% RESUMO %%%%%%
\begin{abstract}
Resumo de 200-300 palavras.
\end{abstract}

%%%%%% Agradecimentos %%%%%%
% Segundo glisc deveria aparecer após conclusão...
\renewcommand{\abstractname}{Agradecimentos}
\begin{abstract}
Eventuais agradecimentos.
Comentar bloco caso não existam agradecimentos a fazer.
\end{abstract}


\tableofcontents
% \listoftables     % descomentar se necessário
% \listoffigures    % descomentar se necessário


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
\clearpage
\pagenumbering{arabic}

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
\chapter{Introdução}
\label{chap.introducao}
\Large
No âmbito do relatório técnico da unidade curricular de IEI (Introdução à Engenharia informática) foi-nos atribuída a exploração de um tema à nossa escolha e decidimos optar pelas Energias. Neste trabalho iremos abordar, de uma maneira clara e objetiva, o que são estas energias e referir as vantagens e algumas desvantagens que estas trazem para a sociedade. Iremos também apresentar os principais tipos de energias bem como quando estas começaram a ser aplicadas. Consideramos que falar sobre este tema é indispensável, especialmente nos dias de hoje devido à guerra, pois estas energias renováveis são recursos inesgotáveis e evitam que Portugal seja dependente de outros países devido à importação de combustíveis fósseis, como é o caso do carvão e/ou o gás natural.


\chapter{Metodologia}
Neste projeto começamos por decidir qual o tema iriamos abordar acabando assim por optar pelas Energias devido à grande consideração e relevância que ambos atribuímos a esta temática. O trabalho foi feito maioritariamente de forma distanciada, utilizando métodos que nos foram introduzidos na unidade curricular de IEI, em que a cada elemento do grupo foram atribuídas tarefas e foram executadas com sucesso.

\label{chap.metodologia}

\chapter{Energias Renováveis}
\section{O que são as Energias Renováveis}

\section{Principais tipos de Energias Renováveis}


\subsection{Energia Solar}
\subsection{Energia Eólica}
\subsection{Energia Hidráulica}
\section{Quando é que começaram a ser aplicadas}
\section{Qual é a maior fonte de energia na natureza}
\section{Fatores a considerar:}
\subsection{Vantagens}
\subsection{Desvantagens}
\chapter{Energias não renováveis}
\section{Principais energias não renováveis}
\section{Desvantagens}


\label{chap.resultados}
Descreve os resultados obtidos.

\chapter{Confrontação das energias}
\label{chap.analise}
Analisa os resultados.

\chapter{Conclusões}
\label{chap.conclusao}
Apresenta conclusões.

\chapter*{Contribuições dos autores}
Resumir aqui o que cada autor fez no trabalho.
Usar abreviaturas para identificar os autores,
por exemplo AS para António Silva.

\vspace{10pt}
\textbf{Indicar a percentagem de contribuição de cada autor.}\\

\autores : xx\%, yy\%\\

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
\chapter*{Acrónimos}
\begin{acronym}
\acro{ua}[UA]{Universidade de Aveiro}
\acro{leci}[LECI]{Licenciatura em Engenharia de Computadores e Informática}
\acro{ee}[EE]{Energias}
\acro{Francisco}[FF]{Francisco Franco}
\acro{Tomás}[TO]{Tomás Oliveira}
\end{acronym}


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
\printbibliography

\end{document}
