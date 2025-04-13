# 📊 `socsci-metro`: A Metropolis-Based Beamer Theme for Social Science Presentations

## 🔧 Built On

> **`socsci-metro`** is a LaTeX Beamer theme built on top of [Metropolis](https://github.com/matze/mtheme) Beamer theme, tailored for social science, sociology, and empirical research presentations. It enhances the clean visual style of `metropolis` with structure and function specific to research communication.presentations.

## ✨ Features

- 🧭 **Minimalist top navigation bar**  
  Clean, compact, and space-efficient — redesigned to avoid visual clutter while still indicating progress and section flow.
  
- 📌 **Research-focused content blocks**  
  Custom-colored `tcolorbox` environments for:
  - Research Questions
  - Hypotheses
  - Methodology
  - Key Findings
  - Notes / Instructor Commentary

- 🔠 **Improved typography & spacing**  
  Thoughtful control over list spacing, font sizing, and item markers to improve readability on-screen.

- 🧾 **Roman numeral continuation for multi-part frames**  
  Automatically numbered `(I)`, `(II)`, etc., for slides that extend a single topic.

## 📷 Previews

<p align="center">
  <img src="./preview/test_page-0001.jpg" width="500"/>
  <img src="./preview/test_page-0005.jpg" width="500"/>
  <img src="./preview/test_page-0006.jpg" width="500"/>
  <img src="./preview/test_page-0007.jpg" width="500"/>
  <img src="./preview/test_page-0010.jpg" width="500"/>
</p>


## 🛠 Usage

```latex
\usepackage{socsci-metro}  % Make sure this .sty file is in the same folder or LaTeX path
```

Complete snippet for all 5 custom box types:

```latex
% Research Question box
\begin{rqbox}
To what extent does banana distribution predict umbrella ownership among penguins in urban jazz environments?
\end{rqbox}

% Hypothesis box
\begin{hypobox}
Penguins exposed to funkier rhythms are 42\% more likely to carry pastel-colored umbrellas during non-leap years.
\end{hypobox}

% Methodology box
\begin{methodbox}
We applied a recursive toast model using 17 types of marmalade as interaction controls within a Bayesian kazoo framework.
\end{methodbox}

% Key Findings box
\begin{findingsbox}
Orange marmalade had a statistically significant effect on kazoo enthusiasm (p < 0.0042), especially during Thursdays.
\end{findingsbox}

% Notes / Commentary box
\begin{notesbox}
Future research should investigate why hedgehogs remain unaffected by both toast density and jazz exposure.
\end{notesbox}

```

## 📁 Contents

- `socsci-metro.sty` — The Beamer theme
- `demo.tex` — Minimal working example
- `README.md` — This file

## 🧑‍🏫 Designed For

- Sociology, political science, public policy, communication studies
- Students, instructors, and researchers giving structured academic talks
- Presentations using methods from social statistics and empirical research

## 📜 License

MIT License. See `LICENSE` for details.

