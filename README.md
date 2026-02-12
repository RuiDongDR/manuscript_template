# Wang Lab Manuscript Template

This repository contains the official LaTeX manuscript template for the **Wang Group** at Columbia University ([wanggroup.org](https://wanggroup.org/)). It is designed to streamline the writing process for statistical genetics research, ensuring consistent notation and professional formatting.

## 🔗 Overleaf Access
**View/Clone the Read-Only Template:** [https://www.overleaf.com/read/djqdhgcsnmpz#8af975](https://www.overleaf.com/read/djqdhgcsnmpz#8af975)

---

## 🚀 Key Features

* **Statistical Notation:** Pre-configured macros for bold vectors and matrices, such as the linear model $y=X\beta+\epsilon$.
* **Software Formatting:** Built-in support for correctly rendering software like `R v4.5` and packages such as `data.table` and `ggplot2` without font-shape warnings.
* **Algorithmic Blocks:** Template structures for optimization procedures and iterative algorithms.
* **Collaborative Tools:** * **Author Feedback:** Dedicated sections for author-specific notes and proofreading status.
    * **Remark Commands:** Meta-comments for internal narrative flow and final checks.
* **Integrated Supplement:** Independent numbering for supplementary notes, ensuring equations and figures are prefixed with "S" (e.g., Equation S1, Table S1).

---

## 🛠 Usage

### Writing in LaTeX
The template is optimized for **XeLaTeX** to support professional typography[cite: 12].

* **Software Mentions:** Use `\texttt{\textnormal{R}}` for the R language to maintain visual consistency.
* **Bold Math:** Use custom macros for design matrices and parameter vectors to match the lab's notation style.

### Collaborative Drafting
During the drafting phase, use the highlighter and remark features to flag critical results or sections needing technical rigor.

---

## 📂 Repository Structure

* `main.tex`: The core manuscript file including the Abstract and Introduction.
* `online_methods.tex`: Detailed section for statistical models and computational implementation.
* `supplement.tex`: Separate file for derivations and supplementary empirical results.
* `references.bib`: Centralized bibliography managed via BibLaTeX.

---

## 🤝 Lab Contribution
When updating this template, please ensure that any new mathematical symbols or software citations are added to the global definitions to maintain consistency across all lab publications.


**Author:** Rui Dong, Gao Wang
**Updated:** February 12, 2026
