# Mathematical Foundations of Natural Language Processing

A Quarto book package for a mathematical introduction to natural language processing, aimed at MA Applied Mathematics and MS Statistics students.

## Main audience

- MA/MS Applied Mathematics students
- MS Statistics students
- mathematically mature data science and AI students

## Focus

The book emphasizes clean mathematical explanations of NLP:

- text as finite sequences and empirical data;
- documents as vectors and matrices;
- language models as conditional probability distributions;
- embeddings as maps into vector spaces;
- attention as similarity-weighted linear averaging;
- transformers as nonlinear sequence operators;
- training as likelihood-based optimization;
- evaluation as statistical inference under uncertainty.

## Build

Install Quarto, then run:

```bash
quarto preview
```

or

```bash
quarto render
```

## Suggested repository name

```text
Book-NLP-Math
```

Suggested GitHub Pages URL:

```text
https://wanghemath.github.io/Book-NLP-Math/
```

## Package structure

```text
_quarto.yml
index.qmd
introduction.qmd
roadmap.qmd
notation.qmd
math-background.qmd
chapters/
labs/
interactive-htmls/
labs-summary.qmd
interactive-htmls.qmd
final-projects.qmd
python-reference.qmd
references.bib
references.qmd
styles.scss
```
