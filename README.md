# 🚦 Smart Traffic Lights Using Local AI

An **IEEE conference-format LaTeX project** evaluating adaptive traffic signal control systems. This study contrasts cloud-based processing with local edge AI computing and highlights architectural gaps in emergency vehicle routing.

## 📦 Repository Structure

* **`main.tex`**: The primary LaTeX source file containing document text, formatted metadata, a data comparison table, and a built-in TikZ system architecture flowchart.
* **`reference.bib`**: The BibTeX file containing verified research citations for Deep Reinforcement Learning and machine-vision optimizations.

## 🛠️ How to Compile

You can compile this project locally using any standard LaTeX distribution (like TeX Live or MiKTeX) or upload it directly to [Overleaf](https://overleaf.com).

### Local Compilation via CLI
Run the following sequence in your terminal to resolve citations and cross-references correctly:

```bash
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

## 📜 Dependencies
The document relies on standard academic packages including `IEEEtran`, `cite`, `booktabs` (for clean tables), and `tikz` (with `positioning` and `arrows.meta` libraries for layout generation).
