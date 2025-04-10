# 🧠 Domain-Adversarial Neural Network for Mortality Classification

This repository contains the LaTeX source code for the manuscript titled:

> **Domain-Adversarial Neural Network Approach for Reducing Tissue-of-Origin Signal in Explainable AI for Domain-Invariant Mortality Classification**

## 📄 Summary

This study introduces a Domain-Adversarial Neural Network (DANN) to mitigate tissue-of-origin bias in pan-cancer transcriptomic data, enhancing survival outcome predictions and interpretability via SHAP-based manifold learning.

## ✨ Key Highlights

- **Mitigates tissue-specific confounding effects** in pan-cancer survival analysis.
- **DANN architecture** composed of Feature Extractor, Label Predictor, and Domain Classifier.
- **Layer-aware SHAP values** used to interpret internal representations.
- **SHAP-based UMAP embeddings** outperform traditional feature visualization methods for mortality stratification.
- **Leiden clustering** on SHAP embeddings reveals biologically meaningful subpopulations.

## 📁 Repository Structure

```
.
├── main.tex                      # LaTeX manuscript
├── references.bib                # Bibliography file
├── figures/                      # All figures used in the manuscript
│   └── main figures/
│       ├── Figure 1.pdf
│       ├── Figure 2.pdf
│       └── ...
├── supplementary/               # Supplementary material (e.g., PDF files)
└── README.md                    # This file
```

## 🧪 Requirements

To compile the LaTeX document:

- `pdflatex` or `xelatex`
- `bibtex` or `biber`
- Packages used: `arxiv`, `graphicx`, `natbib`, `doi`, `hyperref`, `amsfonts`, etc.

Recommended LaTeX compilers: Overleaf, TeX Live, or MiKTeX.

## 🧬 Authors

- Cristian Padron-Manrique *(UNAM/INMEGEN)*
- Juan José Oropeza-Valdez *(UNAM C3)*
- Osbaldo Resendis-Antonio *(UNAM-INMEGEN)*

## 📬 Contact

For questions or collaborations:

- Cristian Padron-Manrique — inu_juliocesar@hotmail.com
- Juan José Oropeza — juan.oropeza@c3.unam.mx
- Osbaldo Resendis-Antonio — oresendis@inmegen.gob.mx

## 📜 License

This project is made available for academic use only.

