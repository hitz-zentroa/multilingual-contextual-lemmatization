---
layout: default
---

# Multilingual Contextual Lemmatization


The work studies how contextual representations, morphological information, edit-script design, and multilingual transfer affect lemmatization across languages and domains.

<div class="button-row">
  <a class="btn btn-primary" href="https://github.com/hitz-zentroa/multilingual-contextual-lemmatization">View on GitHub</a>
  <a class="btn" href="#publications">Publications</a>
</div>

## Overview

Lemmatization maps an inflected word form to its canonical form or **lemma**. Contextual lemmatization uses the surrounding sentence to resolve ambiguity and improve predictions, especially in morphologically rich languages.

This repository covers three complementary directions:

1. **Morphological information** — investigating whether explicit morphosyntactic features are necessary when contextual encoders already capture morphology.
2. **Shortest Edit Scripts (SES)** — evaluating how different edit-script representations affect contextual lemmatization.
3. **Domain- and language-independent lemma generation** — exploring methods that reduce reliance on language- or domain-specific training data, including LLM-based approaches.

## Languages

Experiments across the papers include languages with different morphological profiles, including **Basque, Czech, English, Polish, Russian, Spanish, and Turkish**.

## Research themes

### Contextual representations and morphology

We study how much explicit morphological information contributes to contextual lemmatization and how robust different configurations are when evaluated outside the training domain.

### Shortest Edit Scripts

We compare SES representations used to transform a word form into its lemma, including strategies that separate casing from character-level edit operations.

### Multilingual and cross-domain generalization

A central goal is to build lemmatizers that transfer well across languages and domains rather than optimizing only for in-domain benchmarks.

### LLM-based lemma generation

Recent work extends the line of research toward lemma generation without relying on domain- or language-specific training data.

## Repository structure

```text
.
├── src/                  # Training and inference code
├── data/                 # Data preparation / pointers to datasets
├── scripts/              # Reproducibility and evaluation scripts
├── configs/              # Experiment configurations
├── results/              # Tables or exported results
├── _layouts/             # GitHub Pages layout
├── assets/               # Website styles and images
├── _config.yml           # GitHub Pages configuration
├── index.md              # Project website
└── README.md              # Repository documentation
```

> Adjust the folders above to match the actual codebase. The website itself only requires `_config.yml`, `index.md`, `_layouts/`, and `assets/`.

## Publications {#publications}

### On the Role of Morphological Information for Contextual Lemmatization

**Olia Toporkov and Rodrigo Agerri.** *Computational Linguistics*, 50(1), 2024.

[Paper](https://aclanthology.org/2024.cl-1.6/) · [PDF](https://aclanthology.org/2024.cl-1.6.pdf)

This work investigates the contribution of explicit morphological features to contextual lemmatization across languages with different degrees of morphological complexity, including out-of-domain evaluation.

### Evaluating Shortest Edit Script Methods for Contextual Lemmatization

**Olia Toporkov and Rodrigo Agerri.** *LREC-COLING 2024*.

[Paper](https://aclanthology.org/2024.lrec-main.572/) · [PDF](https://aclanthology.org/2024.lrec-main.572.pdf)

This paper compares Shortest Edit Script representations in a controlled contextual lemmatization setup and evaluates multilingual and language-specific encoder models in both in-domain and out-of-domain settings.

### Lemma Dilemma: On Lemma Generation Without Domain- or Language-Specific Training Data

[Paper](https://aclanthology.org/2025.findings-emnlp.988/) · [PDF](https://aclanthology.org/2025.findings-emnlp.988.pdf)

This work explores lemma generation when domain- or language-specific training data are unavailable, extending contextual lemmatization toward more flexible multilingual settings.

## Citation

If you use this repository, please cite the paper(s) relevant to the experiments or models you use. BibTeX entries are available from the ACL Anthology pages linked above.

## Authors and affiliation

Developed at **HiTZ — Basque Center for Language Technology**, University of the Basque Country (UPV/EHU).

## License

Add the license that applies to the code, models, and/or data in this repository. If different components use different licenses, document them separately.
