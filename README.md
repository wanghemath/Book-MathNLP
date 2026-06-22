# Mathematical Foundations of Natural Language Processing

[![Quarto Book](https://img.shields.io/badge/Quarto-Book-blue)](https://quarto.org/)
[![Python](https://img.shields.io/badge/Python-3.10%2B-green)](https://www.python.org/)
[![Google Colab](https://img.shields.io/badge/Labs-Google%20Colab-orange)](https://colab.research.google.com/)
[![GitHub Pages](https://img.shields.io/badge/Site-GitHub%20Pages-lightgrey)](https://wanghemath.github.io/Book-MathNLP/)

This repository contains the source files for **Mathematical Foundations of Natural Language Processing**, a Quarto-based book on the mathematics behind modern NLP.

The goal of the book is to help students understand NLP not only as a collection of software tools, but as a sequence of mathematical representations:

```text
text -> tokens -> vectors -> matrices -> probability models -> neural networks -> transformers -> retrieval systems -> evaluation and responsibility
```

The book combines mathematical explanation, computational examples, interactive components, and Google Colab computer labs.

---

## Book website

After GitHub Pages is enabled, the book site is expected to be available at:

**https://wanghemath.github.io/Book-MathNLP/**

Repository:

**https://github.com/wanghemath/Book-MathNLP**

---

## Who this book is for

This book is designed for students who want a mathematically grounded introduction to NLP and large language models.

It is especially suitable for:

- graduate students in applied mathematics, statistics, data science, computer science, and AI;
- advanced undergraduates with linear algebra and probability background;
- students who want to understand how mathematical objects appear inside modern language technologies;
- independent learners who want guided Python labs in Google Colab.

The book assumes basic familiarity with:

- vectors and matrices;
- functions and finite sets;
- elementary probability;
- introductory Python.

The page `math-background.qmd` provides a compact mathematical bridge for students who need review.

---

## Main themes

The book develops NLP through several connected mathematical themes:

1. **Discrete structures**: tokens, vocabularies, strings, documents, finite sets.
2. **Linear algebra**: vectors, document-term matrices, embeddings, projections, SVD.
3. **Probability**: language models, likelihood, Bayes rules, smoothing, perplexity.
4. **Information theory**: entropy, cross-entropy, KL divergence, PMI.
5. **Optimization**: gradients, softmax cross-entropy, SGD, Adam, AdamW.
6. **Neural networks**: embeddings, recurrent models, attention, transformers.
7. **Retrieval and RAG**: sparse retrieval, dense retrieval, hybrid search, reranking.
8. **Graphs and topology**: dependency graphs, co-occurrence graphs, neighborhood graphs, persistence ideas.
9. **Evaluation and responsibility**: metrics, calibration, bias, fairness, uncertainty, and responsible deployment.

---

## Chapter and lab structure

Each chapter is paired with a Google Colab lab. The labs are designed for independent study: they include background explanation before programming, runnable examples, exercises, reflection questions, and mini-projects.

| Lab | Chapter topic | Colab |
|---:|---|---|
| 1 | What Is Natural Language Processing? | [Open in Colab](https://colab.research.google.com/github/wanghemath/Book-MathNLP/blob/main/labs/chapter-01-what-is-nlp.ipynb) |
| 2 | Text, Tokens, and Vocabularies | [Open in Colab](https://colab.research.google.com/github/wanghemath/Book-MathNLP/blob/main/labs/chapter-02-text-tokens-vocabularies.ipynb) |
| 3 | Documents as Vectors | [Open in Colab](https://colab.research.google.com/github/wanghemath/Book-MathNLP/blob/main/labs/chapter-03-documents-as-vectors.ipynb) |
| 4 | Probability and Language | [Open in Colab](https://colab.research.google.com/github/wanghemath/Book-MathNLP/blob/main/labs/chapter-04-probability-and-language.ipynb) |
| 5 | N-gram Language Models | [Open in Colab](https://colab.research.google.com/github/wanghemath/Book-MathNLP/blob/main/labs/chapter-05-ngram-language-models.ipynb) |
| 6 | Naive Bayes Text Classification | [Open in Colab](https://colab.research.google.com/github/wanghemath/Book-MathNLP/blob/main/labs/chapter-06-naive-bayes-text-classification.ipynb) |
| 7 | Vector Space Models | [Open in Colab](https://colab.research.google.com/github/wanghemath/Book-MathNLP/blob/main/labs/chapter-07-vector-space-models.ipynb) |
| 8 | Word Embeddings | [Open in Colab](https://colab.research.google.com/github/wanghemath/Book-MathNLP/blob/main/labs/chapter-08-word-embeddings.ipynb) |
| 9 | Geometry of Embeddings | [Open in Colab](https://colab.research.google.com/github/wanghemath/Book-MathNLP/blob/main/labs/chapter-09-geometry-of-embeddings.ipynb) |
| 10 | Neural Networks for Text | [Open in Colab](https://colab.research.google.com/github/wanghemath/Book-MathNLP/blob/main/labs/chapter-10-neural-networks-for-text.ipynb) |
| 11 | Recurrent Neural Networks | [Open in Colab](https://colab.research.google.com/github/wanghemath/Book-MathNLP/blob/main/labs/chapter-11-recurrent-neural-networks.ipynb) |
| 12 | LSTM and GRU Models | [Open in Colab](https://colab.research.google.com/github/wanghemath/Book-MathNLP/blob/main/labs/chapter-12-lstm-gru-models.ipynb) |
| 13 | Attention Mechanisms | [Open in Colab](https://colab.research.google.com/github/wanghemath/Book-MathNLP/blob/main/labs/chapter-13-attention-mechanisms.ipynb) |
| 14 | Self-Attention | [Open in Colab](https://colab.research.google.com/github/wanghemath/Book-MathNLP/blob/main/labs/chapter-14-self-attention.ipynb) |
| 15 | Transformers | [Open in Colab](https://colab.research.google.com/github/wanghemath/Book-MathNLP/blob/main/labs/chapter-15-transformers.ipynb) |
| 16 | Positional Encoding and Sequence Geometry | [Open in Colab](https://colab.research.google.com/github/wanghemath/Book-MathNLP/blob/main/labs/chapter-16-positional-encoding.ipynb) |
| 17 | Autoregressive Language Models | [Open in Colab](https://colab.research.google.com/github/wanghemath/Book-MathNLP/blob/main/labs/chapter-17-autoregressive-language-models.ipynb) |
| 18 | Training Large Language Models | [Open in Colab](https://colab.research.google.com/github/wanghemath/Book-MathNLP/blob/main/labs/chapter-18-training-large-language-models.ipynb) |
| 19 | Embeddings, Retrieval, and RAG | [Open in Colab](https://colab.research.google.com/github/wanghemath/Book-MathNLP/blob/main/labs/chapter-19-embeddings-retrieval-rag.ipynb) |
| 20 | Evaluation of Language Models | [Open in Colab](https://colab.research.google.com/github/wanghemath/Book-MathNLP/blob/main/labs/chapter-20-evaluation-of-language-models.ipynb) |
| 21 | Information Theory for NLP | [Open in Colab](https://colab.research.google.com/github/wanghemath/Book-MathNLP/blob/main/labs/chapter-21-information-theory.ipynb) |
| 22 | Optimization for NLP | [Open in Colab](https://colab.research.google.com/github/wanghemath/Book-MathNLP/blob/main/labs/chapter-22-optimization-for-nlp.ipynb) |
| 23 | Graphs and Language | [Open in Colab](https://colab.research.google.com/github/wanghemath/Book-MathNLP/blob/main/labs/chapter-23-graphs-and-language.ipynb) |
| 24 | Topology, Geometry, and Language | [Open in Colab](https://colab.research.google.com/github/wanghemath/Book-MathNLP/blob/main/labs/chapter-24-topology-geometry-language.ipynb) |
| 25 | Ethics, Bias, and Responsibility | [Open in Colab](https://colab.research.google.com/github/wanghemath/Book-MathNLP/blob/main/labs/chapter-25-ethics-bias-responsibility.ipynb) |

---

## Suggested repository structure

```text
Book-MathNLP/
├── _quarto.yml
├── index.qmd
├── introduction.qmd
├── roadmap.qmd
├── math-background.qmd
├── notion.qmd
├── python-reference.qmd
├── labs-summary.qmd
├── references.qmd
├── references.bib
├── README.md
├── chapters/
│   ├── chapter-01-*.qmd
│   ├── chapter-02-*.qmd
│   └── ...
├── labs/
│   ├── chapter-01-what-is-nlp.ipynb
│   ├── chapter-02-text-tokens-vocabularies.ipynb
│   └── ...
├── assets/
│   ├── style.scss
│   └── interactive scripts, images, and data files
└── _book/
    └── rendered site, generated by Quarto
```

---

## How to use the book

### For students

A good workflow is:

1. Read the chapter.
2. Open the corresponding Colab lab.
3. Run all code cells once without editing.
4. Return to the mathematical explanations and connect formulas to code.
5. Complete the exercises.
6. Try the mini-project at the end of the lab.
7. Write a short reflection: what mathematical object did the model use, and what did the computation show?

### For instructors

The book can be used as:

- a full course text for mathematical NLP;
- a module inside a machine learning or AI course;
- a guided independent-study resource;
- a project-based supplement for courses on language models, transformers, or AI systems.

The labs may be assigned as weekly computer labs, homework supplements, or project preparation.

---

## Running the labs in Google Colab

Each notebook in the `labs/` folder can be opened directly in Google Colab.

A typical Colab link has the form:

```text
https://colab.research.google.com/github/wanghemath/Book-MathNLP/blob/main/labs/chapter-01-what-is-nlp.ipynb
```

Students do not need to install Python locally. In Colab, they can choose:

```text
Runtime -> Run all
```

Then they can save their own copy:

```text
File -> Save a copy in Drive
```

---

## Running the book locally

Install Quarto from:

```text
https://quarto.org/docs/get-started/
```

Then clone the repository:

```bash
git clone https://github.com/wanghemath/Book-MathNLP.git
cd Book-MathNLP
```

Preview the book:

```bash
quarto preview
```

Render the book:

```bash
quarto render
```

The rendered HTML site will appear in `_book/`.

---

## Recommended Python packages

The labs primarily use standard scientific Python tools:

```bash
pip install numpy pandas matplotlib scikit-learn scipy networkx
```

Some labs optionally introduce PyTorch-style tensor computation. In Google Colab, many packages are already available.

The labs are written to be lightweight and educational rather than computationally heavy.

---

## Pages in the book

Important supporting pages include:

- `index.qmd`: landing page and overview;
- `introduction.qmd`: motivation and book philosophy;
- `roadmap.qmd`: chapter-lab roadmap and suggested pacing;
- `math-background.qmd`: mathematical prerequisites and review;
- `notion.qmd`: notation and conventions;
- `python-reference.qmd`: coding reference for the labs;
- `labs-summary.qmd`: list of all Colab labs;
- `references.qmd`: bibliography guide;
- `references.bib`: BibTeX references.

---

## Possible course pacing

A 14-week semester can use the following rough pacing:

| Weeks | Topics |
|---:|---|
| 1--2 | Text, tokens, vocabularies, document vectors |
| 3--4 | Probability, language models, Naive Bayes |
| 5--6 | Vector space models, embeddings, geometry |
| 7--8 | Neural networks, RNNs, LSTM/GRU |
| 9--10 | Attention, self-attention, transformers |
| 11 | Autoregressive LMs and LLM training |
| 12 | Retrieval, RAG, and evaluation |
| 13 | Information theory, optimization, graphs, topology |
| 14 | Ethics, responsibility, and final projects |

---

## Final project ideas

Students may extend the labs into projects such as:

- comparing sparse, dense, and hybrid retrieval;
- building a small transparent RAG system;
- studying tokenization effects on entropy and perplexity;
- visualizing embedding geometry and hubness;
- auditing a classifier across subgroups;
- comparing decoding strategies for language generation;
- studying graph-based summaries of text corpora;
- exploring topology-based diagnostics of embedding spaces.

---

## Citation

If you use this book or labs in a course or project, please cite the repository:

```bibtex
@misc{wang_mathnlp,
  author = {Wang, He},
  title = {Mathematical Foundations of Natural Language Processing},
  howpublished = {GitHub repository},
  url = {https://github.com/wanghemath/Book-MathNLP},
  year = {2026}
}
```

---

## License

Choose a license appropriate for the intended use of the book.

Common choices include:

- **CC BY-NC-SA 4.0** for educational text and figures;
- **MIT License** for code examples;
- a combined license statement if text and code use different licenses.

A suggested structure is:

```text
Text and figures: Creative Commons Attribution-NonCommercial-ShareAlike 4.0
Code examples and notebooks: MIT License
```

---

## Acknowledgment

This book is built with Quarto, Python, Google Colab, and open-source scientific computing tools.

The guiding philosophy is simple:

> To understand modern NLP, students should see the mathematics and the computation side by side.
