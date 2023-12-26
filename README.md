![GitHub pull requests](https://img.shields.io/github/issues-pr/Silly-Machine/TuPy-Dataset)
[![GitHub issues](https://img.shields.io/github/issues/Silly-Machine/TuPy-Dataset.svg)](https://img.shields.io/github/issues/Silly-Machine/TuPy-Dataset.svg)
![GitHub last commit (branch)](https://img.shields.io/github/last-commit/Silly-Machine/TuPy-Dataset/main)
[![GitHub license](https://img.shields.io/badge/license-MIT-orange)](https://opensource.org/license/mit/)

# Portuguese Hate Speech Dataset (TuPy)

The Portuguese hate speech dataset (TuPy) is an annotated corpus designed to facilitate the development of advanced hate speech detection models using machine learning (ML) and natural language processing (NLP) techniques. TuPy is formed by 10000 thousand unpublished annotated tweets collected in 2023.

This repository is organized as follows:

```sh
root.
    ├── annotations   : classification given by annotators
    ├── raw corpus    : dataset before being split between annotators
    ├── tupy datasets : combined result of annotations
    └── README.md
```
## Voting process
To generate the binary matrices, we employed a straightforward voting process. Three distinct evaluations were assigned to each document. In cases where a document received two or more identical classifications, the adopted value is set to 1; otherwise, it is marked as 0.

## Acknowledge
The TuPy project is the result of the development of Felipe Oliveira's thesis and the work of several collaborators. This project is financed by the Federal University of Rio de Janeiro ([UFRJ](https://ufrj.br/)) and the Alberto Luiz Coimbra Institute for Postgraduate Studies and Research in Engineering ([COPPE](https://coppe.ufrj.br/)).
