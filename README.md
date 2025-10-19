\documentclass[11pt, a4paper]{article}

% --- UNIVERSAL PREAMBLE BLOCK ---
% Setzt Seitenränder
\usepackage[a4paper, top=2.5cm, bottom=2.5cm, left=2.5cm, right=2.5cm]{geometry} 

% Fontspec für moderne Schriftsatz-Engines (wie XeLaTeX oder LuaLaTeX)
\usepackage{fontspec}

% Babel für die deutsche Sprache
\usepackage[ngerman, bidi=basic, provide=*]{babel}

% Definiert die verfügbaren Sprachen
\babelprovide[import, onchar=ids fonts]{ngerman}
\babelprovide[import, onchar=ids fonts]{english}

% Setzt die Hauptschriftart auf Noto Sans (modern und gut lesbar)
\babelfont{rm}{Noto Sans}

% Pakete für Tabellen und Kopfzeilen
\usepackage{booktabs}
\usepackage{tabularx}
\usepackage{hyperref}
\usepackage{amsmath}

% Dokumentinformationen
\title{\textbf{Bonusaufgabe: KI – Möglichkeiten, Grenzen und Auswirkungen}}
\author{Ihre Matrikelnummer / Ihr Name}
\date{\today}

\begin{document}

\maketitle
\thispagestyle{empty} % Keine Seitenzahl auf der ersten Seite

\begin{abstract}
Diese Kurzanalyse fasst die zentralen Fähigkeiten (Möglichkeiten) und die aktuellen Herausforderungen (Grenzen) der Künstlichen Intelligenz zusammen. Darüber hinaus werden die wichtigsten gesellschaftlichen Auswirkungen, insbesondere in den Bereichen Autonomes Fahren und Large Language Models (LLMs), beleuchtet.
\end{abstract}

\vspace{0.5cm}

\section{Gelöste und Ungelöste Probleme (Möglichkeiten und Grenzen)}

Die KI hat in spezifischen Bereichen massive Fortschritte gemacht, stößt jedoch außerhalb der reinen Mustererkennung auf fundamentale Grenzen.

\subsection{Möglichkeiten (Gelöste Probleme)}
Die KI ist besonders stark in Aufgaben, die auf Mustererkennung und Optimierung basieren:
\begin{itemize}
    \item \textbf{Mustererkennung:} Medizinische Diagnose (schnellere Erkennung von Tumoren), Objekterkennung.
    \item \textbf{Komplexe Optimierung:} Proteinfaltung (z.B. AlphaFold) und die Bewältigung komplexer Strategiespiele (Go, Schach).
    \item \textbf{Sprach- und Textverständnis:} Generierung kohärenter Texte, automatisierte Zusammenfassungen und Code-Generierung durch Large Language Models (LLMs).
\end{itemize}

\subsection{Grenzen (Ungelöste Probleme)}
Die folgenden Herausforderungen begrenzen die heutige KI stark:
\begin{itemize}
    \item \textbf{Kausalität:} KI findet Korrelationen, aber versteht oft nicht die tatsächliche Ursache und Wirkung (\textit{warum}). Dies führt zu mangelnder Erklärbarkeit.
    \item \textbf{Generalisierung:} KI kann Gelerntes kaum auf neue, unbekannte Situationen außerhalb ihres Trainingsdatensatzes übertragen (\textit{Out-of-Distribution}).
    \item \textbf{Common Sense:} Das intuitive, alltägliche Wissen über die physische und soziale Welt (Hausverstand) fehlt den Modellen noch.
    \item \textbf{Langzeitgedächtnis:} Aktuelle LLMs haben Schwierigkeiten, sich über sehr lange Zeiträume oder in komplexen Konversationen konsistent zu erinnern.
\end{itemize}

\section{Gesellschaftliche Auswirkungen und Risiken}

Die Integration von KI in kritische Sektoren hat weitreichende Konsequenzen.

\subsection{Autonomes Fahren}
\begin{itemize}
    \item \textbf{Chance:} Drastische Erhöhung der Verkehrssicherheit durch Eliminierung menschlichen Versagens. Optimierung des Verkehrsflusses.
    \item \textbf{Risiko:} Ungeklärte Haftungsfragen bei Unfällen. Ethische Dilemmata in Notfallsituationen. Hohe Anforderungen an die Systemzuverlässigkeit in unvorhersehbaren Realwelt-Szenarien (\textit{Corner Cases}).
\end{itemize}

\subsection{Large Language Models (LLMs)}
\begin{itemize}
    \item \textbf{Chance:} Produktivitätssteigerung in Wissensberufen; Absenkung der Schwelle zur Inhaltserstellung (Code, Skripte, Berichte).
    \item \textbf{Risiko 1: Halluzinationen:} Die Modelle erfinden Fakten oder Quellen, was eine ständige manuelle Überprüfung der Ergebnisse erfordert.
    \item \textbf{Risiko 2: Kognitiver Verfall:} Die Abhängigkeit von KI kann die menschliche Fähigkeit zur kritischen Recherche und zum Gedächtnis schwächen.
    \item \textbf{Risiko 3: Ressourcenverbrauch:} Das Training und der Betrieb großer Modelle erfordert immense Energie- und Wassermengen (ökologische Ethik).
\end{itemize}

\section*{Fazit}
KI ist ein \textbf{mächtiges Werkzeug}, dessen größten Nutzen es ist, Muster zu erkennen und Abläufe zu optimieren. Die zentrale \textbf{ethische Herausforderung} der Gesellschaft liegt darin, diese Technologie durch strenge Regulierung und die \textbf{unverzichtbare menschliche Kontrolle} so zu steuern, dass die gesellschaftlichen Vorteile die technologischen und kognitiven Risiken überwiegen.

\end{document}
