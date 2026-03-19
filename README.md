# modulo-1
\documentclass[lighthipster]{simplehipstercv}
\usepackage[utf8]{inputenc}
\usepackage[default]{raleway}
\usepackage[margin=1.2cm, a4paper]{geometry}
\usepackage{xcolor}
\usepackage{tikz} 

\newlength{\rightcolwidth}
\newlength{\leftcolwidth}
\setlength{\leftcolwidth}{0.23\textwidth}
\setlength{\rightcolwidth}{0.75\textwidth}

\title{CV Gerardo Martín Fernández}

\pagestyle{empty}
\begin{document}

\thispagestyle{empty}

\simpleheader{headercolour}{Gerardo Martín}{Fernández}{Estudiante de Ingeniería Industrial}{white}

\subsection*{}
\vspace{4em}

\setlength{\columnsep}{1.5cm}
\columnratio{0.25}[0.70]
\begin{paracol}{2}
\hbadness5000

\footnotesize
{\setasidefontcolour
\flushright
\begin{center}
    \begin{tikzpicture}
        \clip (0,0) circle (1.8cm);
        \node at (0,0) {\includegraphics[width=3.8cm]{gera.png}}; 
    \end{tikzpicture}
\end{center}

\vspace{1em}

\bg{cvgreen}{white}{Sobre mí}\\[0.5em]
{\footnotesize
Puntualidad. Buen trabajo en equipo y organización. Buena resolución de problemas. Gran capacidad para aprender y excelente comunicación.}

\bigskip

\bg{cvgreen}{white}{Habilidades}\\[0.5em]
Trabajo en Equipo \\ 
Liderazgo \\ 
Resolución de Problemas \\ 
Organización

\bigskip

\bg{cvgreen}{white}{Contacto}\\[0.5em]
\textbf{22 años} \\
Guaymallén, Mendoza \\
\vspace{0.5em}
\infobubble{\faPhone}{cvgreen}{white}{2612197526} \\
\vspace{0.5em}
\infobubble{\faEnvelope}{cvgreen}{white}{gerafernandez2003@gmail.com}
\vspace{6em}
}

\switchcolumn

\small
\section*{Experiencia Laboral}

\begin{tabular}{r| p{0.55\textwidth} c}
    \cvevent{2023--Pres.}{Mozo}{Atención al Cliente}{Las Palapas, Gran Hotel Potrerillos}{Servicio de excelencia en eventos y gastronomía.}{} \\
    \cvevent{2023--Pres.}{Mozo}{Atención al Cliente}{MAAL MAX}{Desempeño en entorno dinámico y de alta demanda.}{} \\
    \cvevent{2023--2025}{Mozo}{Eventos Especiales}{Hernán Cattáneo, Potrerillos}{Temporadas de diciembre en eventos de gran escala.}{} \\
    \cvevent{2022--2023}{Cocinero}{Gastronomía}{Nostra Nonna Pizza}{Elaboración y control de calidad de productos.}{} 
\end{tabular}
\vspace{3em}

\section*{Educación}
\begin{tabular}{r p{0.65\textwidth} c}
    \cvdegree{Act.}{Ingeniería Industrial}{Grado}{Universidad Nacional de Cuyo, FING}{Estudiante avanzado.}{} \\
    \cvdegree{2021}{Bachiller}{Secundario}{Colegio Universitario Central}{Ciencias Sociales y Humanidades.}{}
\end{tabular}

\vfill{}

\end{paracol}

\end{document}
