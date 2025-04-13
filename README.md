# 📊 `socsci-metro`: A Metropolis-Based Beamer Theme for Social Science Presentations

**`socsci-metro`** is a LaTeX Beamer theme built on top of `metropolis`, tailored for social science, sociology, and empirical research presentations. It enhances the clean visual style of `metropolis` with structure and function specific to research communication.

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

## 📷 Example Slide

![Example Slide](./example_slide.png)

## 🛠 Usage

```latex
\usepackage{socsci-metro}  % Make sure this .sty file is in the same folder or LaTeX path
```

Then structure your slides using built-in environments like:

```latex
\begin{rqbox}
What explains variation in social trust across welfare regimes?
\end{rqbox}

\begin{methodbox}
Mixed-effects model with interaction terms for welfare type × year.
\end{methodbox}
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

