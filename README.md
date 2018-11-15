%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
% Deedy - One Page Two Column Resume
% LaTeX Template
% Version 1.2 (16/9/2014)
%
% Original author:
% Debarghya Das (http://debarghyadas.com)
%
% Original repository:
% https://github.com/deedydas/Deedy-Resume
%
% IMPORTANT: THIS TEMPLATE NEEDS TO BE COMPILED WITH XeLaTeX
%
% This template uses several fonts not included with Windows/Linux by
% default. If you get compilation errors saying a font is missing, find the line
% on which the font is used and either change it to a font included with your
% operating system or comment the line out to use the default font.
% 
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
% 
% TODO:
% 1. Integrate biber/bibtex for article citation under publications.
% 2. Figure out a smoother way for the document to flow onto the next page.
% 3. Add styling information for a "Projects/Hacks" section.
% 4. Add location/address information
% 5. Merge OpenFont and MacFonts as a single sty with options.
% 
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
% CHANGELOG:
% v1.1:
% 1. Fixed several compilation bugs with \renewcommand
% 2. Got Open-source fonts (Windows/Linux support)
% 3. Added Last Updated
% 4. Move Title styling into .sty
% 5. Commented .sty file.
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
% Known Issues:
% 1. Overflows onto second page if any column's contents are more than the
% vertical limit
% 2. Hacky space on the first bullet point on the second column.
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%


\documentclass[]{deedy-resume-openfont}
\usepackage{fancyhdr}
 
\pagestyle{fancy}
\fancyhf{}
 
\begin{document}

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
%     LAST UPDATED DATE
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
\lastupdated

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
%     TITLE NAME
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
\namesection{Tanmay}{Chandekar}{ \urlstyle{same}\
799-708-3950 | \href{mailto:f20160134@hyderabad.bits-pilani.ac.in}{f20160134@hyderabad.bits-pilani.ac.in}
}

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
%     COLUMN ONE
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\begin{minipage}[t]{0.33\textwidth} 

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     EDUCATION
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Education} 

\subsection{BITS-Pilani University}
\descript{BE in Computer Science}
\location{Currently in 3rd year}
\location{May 2020 | Hyderabad, India}

\location {CGPA: 8.24 / 10}

\sectionsep

\subsection{Dinanath Junior College}
\descript{Electronics}
\location{March 2016 | Nagpur, India}
\location{XII percentage - 92.6}
\sectionsep



\subsection{Bhavans BP vidya mandir}
\location{April 2014|  Nagpur, India}
\location{X percentage - 95.8}
\sectionsep

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     LINKS
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Links} 
LinkedIn://  {\bf https://www.linkedin.com/in/tanmay-chandekar-6676ab134/} \\
Github:// {\bf https://github.com/tanmaychandekar98}
\sectionsep


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     COURSEWORK
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Coursework}
%\subsection{Pursuing}
Information Retrieval \\
Operating Systems \\
Artificial Intelligence \\
Cryptography \\
Computer Architecture \\
Theory of Computation \\
Principles of Programming language \\
%\sectionsep

%\subsection{Completed}
Data Structures and Algorithms \\
Object Oriented Programming \\
Software Engineering \\
Database Management System \\

Microprocessors \\
\sectionsep
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     SKILLS
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Skills}
\subsection{Programming}
Java \textbullet{}   C/C++ \textbullet{} Python  \\
Javascript \textbullet{} NodeJS \\
MySQL \textbullet{} MongoDB \\
CSS \textbullet{} HTML \\
\sectionsep
\subsection{Others}
Linux \textbullet{} RESTful Webservices \\
Angular \textbullet{} MEAN Stack \\
OpenCV \textbullet{} Caffe \textbullet{} Jquery\\
Docker \textbullet{} CNN

\sectionsep

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
%     COLUMN TWO
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\end{minipage} 
\hfill
\begin{minipage}[t]{0.66\textwidth} 

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     EXPERIENCE
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Internship}
\runsubsection{Reliance Jio}
\descript{| AI/ML Summer Intern }
\location{May 2018 - July 2018 | Navi Mumbai, India}
\vspace{\topsep}
\begin{tightemize}
\item Worked with the AI team to develop a facial recognition model .
\item Developing an access control system with facial recognition and replacing the existing card scanning system .
\item The project phases included : Research, New Product Development, Design, Testing 
\item Deep Learning frameworks (dlib and facenet) were used.
\end{tightemize}
\sectionsep


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     PROJECTS
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Projects}
\runsubsection{Twitter Sentiment Analysis}
\descript{| Sep 2018 – Present}
% Hacky fix for awkward extra vertical space
\begin{tightemize}
\item Use of Natural Language Processing and machine learning to determine the sentiment of people based on twitter feeds.
\item nltk library for python is used.
\item Classifier based on Naive Bayes Theorem .
\end{tightemize}
\sectionsep

\runsubsection{Music Search and Recommendation (IR)}
\descript{| Sep 2018 – Present}
% Hacky fix for awkward extra vertical space
\begin{tightemize}
\item Use of tf-idf method for retrieving documents from a provided dataset.
\item Recommender System based on SVD decomposition.
\end{tightemize}
\sectionsep


\runsubsection{Employee Time Cards System}
\descript{| Feb 2018 – April 2018}
% Hacky fix for awkward extra vertical space
\begin{tightemize}
\item An interactive and real-time application for companies to track their employees' working hours and generate their salary receipts.
\item It runs on Nodejs at the backend and MongoDB as the database server .
\item {\href{https://github.com/tanmaychandekar98/time-system}{https://github.com/tanmaychandekar98/time-system}}
\end{tightemize}
\sectionsep

\runsubsection{Cars Search Engine}
\descript{| April 2018 – April 2018}
% Hacky fix for awkward extra vertical space
\begin{tightemize}
\item A simple web based search engine for cars .
\item It is supported by Nodejs at the backend and SQL for database management.
\item {\href{https://github.com/tanmaychandekar98/cars-dbms}{https://github.com/tanmaychandekar98/cars-dbms}}
\end{tightemize}
\sectionsep

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     AWARDS
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Recognitions} 
July 2018 - Letter of Appreciation by \textbf{\href{https://www.linkedin.com/in/shaileshk/}{Shailesh Kumar}} (Chief Data Scientist , Jio)\\

\sectionsep

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     PUBLICATIONS
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Other Experiences}
\descript{Co-founder and CTO of startup FRAM.AI}
Personal Portfolio Management Service - To provide online financial advice and manage personal portfolio using machine learning techniques.\\
\vspace{\item}
\descript{Web Developer - Department of technical Arts}
Develop responsive websites for college fests.
Example - {\href{https://bits-atmos.org/}{https://bits-atmos.org/}}
\end{minipage} 
\end{document}  \documentclass[]{article}
