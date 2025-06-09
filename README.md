# PosterTeX

A clean, customizable LaTeX/Beamer template for academic poster presentations—PosterTeX makes it easy to turn your latest paper into a polished research poster. Inspired by the Gemini–UQ theme, PosterTeX adds new layout options, section styles, and a lightweight framework for organizing scientific posters.

📖 **Table of Contents**

1. [Why PosterTeX?](#why-postertex)
2. [Features](#features)
3. [Installation](#installation)
4. [Quick Start](#quick-start)
5. [Folder Structure](#folder-structure)
6. [Section Guide](#section-guide)
7. [Existing Posters](#existing-posters)
8. [Figures & Graphics](#figures--graphics)
9. [Customization](#customization)
10. [Contributing](#contributing)
11. [License](#license)
12. [Contact](#contact)

---

🎯 **Why PosterTeX?**

Researchers often struggle to translate dense academic papers into clear, visually appealing posters. PosterTeX:

- Provides a logical layout tailored to common research-paper elements.
- Enforces a consistent, easy-to-read design across sections.
- Is based on a battle-tested Beamer theme and fully compatible with Overleaf or local TeX installations.

---

✨ **Features**

- Seven built-in sections covering everything from your research gap to future work.
- Two figure slots with captions ready to showcase key diagrams.
- University logo support and title blocks you can easily swap out.
- Custom color palette and font choices consistent with academic posters.
- Minimal dependencies—nothing beyond standard LaTeX/Beamer packages.

---

🛠️ **Installation**

Clone this repository:

```bash
git clone https://github.com/yourusername/PosterTeX.git
```

Install any missing LaTeX packages (e.g., beamer, tikz, graphicx).
Open `poster.tex` in your editor or Overleaf.

---

⚡ **Quick Start**

1. Copy `poster.tex` (or `poster-example.tex`) to your working folder.
2. Replace the title, authors, and institution:

```latex
\title{Your Poster Title}
\author{Alice Smith \and Bob Jones}
\institute{University of Example}
```

3. Swap out `Logo-Right.png` for your own logo.
4. Edit each section in the template (see “Section Guide” below).
5. Compile with:

```bash
lualatex poster.tex
```

---

🗂️ **Template Structure**

```
Base Template/
├── main.tex              % Main beamer poster source
├── logos/
│   ├── Logo-Left.png
│   └── Logo-Right.png
├── README.md
└── LICENSE

Posters/
├── Paper1/
│   └── main.pdf
├── Paper2/
│   └── main.pdf
└── ...
```
-   `Base Template/`: All source files needed to create a new poster. 
- `main.tex`: Your entry point. Edit title, authors, and section bodies.
- `logos/`: Placeholder folder for logos.
-   `Posters/`: Contains subfolders for each paper, each with its own poster PDF.
---

📑 **Section Guide**

PosterTeX divides your poster into seven core panels—each panel maps to a familiar part of your research paper:

**Research Gap**
> Introduces the problem space and identifies what’s missing in the literature. Sets the stage by highlighting why your work matters.

**Main Contributions**
> A concise bullet list of your paper’s key innovations or discoveries. Quickly communicates your “so what.”

**Method Overview**
> Sketch out your proposed approach, experimental setup, or theoretical model. Often includes a simple diagram or flowchart.

**Key Findings**
> Summarize the most important results or data points. Focus on high-impact takeaways.

**Strengths & Weaknesses**
> An honest self-assessment. Shows reviewers you understand your method’s limitations and advantages.

**Future Directions**
> Propose extensions, open questions, or applications for follow-up work. Invites discussion and collaboration.

**Core Equation**
> Display your central mathematical expression or model derivation. Helps technically minded viewers grasp the formal underpinnings at a glance.

---
📂 **Existing Posters**

Browse and download existing posters directly:

- [LLMLingua-2: Faithful and Efficient Prompt Compression via Data Distillation](https://github.com/AliannejadiPourya/PosterTex/blob/main/Posters/LLMLingua-2%3A%20Faithful%20and%20Efficient%20Prompt%20Compression%20via%20Data%20Distillation/main.pdf)
- [LongLLMLingua: Accelerating and Enhancing LLMs in Long Context
Scenarios via Prompt Compression](https://github.com/AliannejadiPourya/PosterTex/blob/main/Posters/LongLLMLingua%3A%20Accelerating%20and%20Enhancing%20LLMs%20in%20Long%20Context%20Scenarios%20via%20Prompt%20Compression/main.pdf)
- [Evaluation of Attribution Bias in Retrieval-Augmented
Large Language Models](https://github.com/AliannejadiPourya/PosterTex/blob/main/Posters/Evaluation%20of%20Attribution%20Bias%20in%20Retrieval-Augmented%20Large%20Language%20Models/main.pdf)

*Simply click the link to view or download the poster PDF.*

---

🖼️ **Figures & Graphics**

PosterTeX reserves two figure slots—just drop your images into `graphics/` and reference them in `poster.tex`:

```latex
\begin{figure}
  \includegraphics[width=\linewidth]{your-figure1.png}
  \caption{An overview of our three RAG modes.}
\end{figure}
```

- **Figure 1:** Illustrate your workflow or architecture.
- **Figure 2:** Show sample results, data visualizations, or example layouts.

---

🎨 **Customization**

PosterTeX is designed for easy branding:

- **Logo:** Replace `logos/Logo-Right.png` with your institution’s emblem.
- **Colors:** Tweak `beamerthemePoster.sty` to adjust primary and accent colors.
- **Fonts:** Change `\setmainfont{…}` or standard LaTeX font commands in `poster.tex`.

---

🤝 **Contributing**

1. Fork the repo.
2. Create a feature branch:  
```bash
git checkout -b feature/my-improvement
```
3. Commit your changes and push:  
```bash
git push origin feature/my-improvement
```
4. Open a pull request.

We welcome bug reports, feature requests, and pull requests! 🚀

---

📜 **License**

This project is MIT-licensed. Feel free to use and modify PosterTeX for your own research.

---

📬 **Contact**

Pourya Aliannejadi  
✉️ alian.pourya@gmail.com  
📂 GitHub – [AliannejadiPourya/PosterTeX](https://github.com/AliannejadiPourya/PosterTeX)

