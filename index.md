---
layout: default
---

# Multilingual Contextual Lemmatization
<div class="button-row">
  <a class="btn btn-primary" href="https://github.com/hitz-zentroa/multilingual-contextual-lemmatization">View on GitHub</a>
  <a class="btn" href="#publications">Publications</a>
</div>

## Overview
This repository brings together research on multilingual contextual lemmatization across languages with varying levels of morphological complexity. In particular, we study how contextual representations, morphological information, edit-script design, and multilingual transfer affect lemmatization performance across languages and domains.

The repository is structured around three publications that form the basis of this line of research.

## Publications {#publications}

### On the Role of Morphological Information for Contextual Lemmatization

**Olia Toporkov and Rodrigo Agerri.** *Computational Linguistics*, 50(1), 2024, pp. 157-191.

[Paper](https://aclanthology.org/2024.cl-1.6/) · [PDF](https://aclanthology.org/2024.cl-1.6.pdf)

This work investigates the role of morphological information in contextual lemmatization across six languages with different levels of morphological complexity. It evaluates whether explicit morphological features are necessary when using modern contextual representations, considering both in-domain and out-of-domain settings.

### Evaluating Shortest Edit Script Methods for Contextual Lemmatization

**Olia Toporkov and Rodrigo Agerri.** *LREC-COLING 2024*.

[Paper](https://aclanthology.org/2024.lrec-main.572/) · [PDF](https://aclanthology.org/2024.lrec-main.572.pdf)

This paper studies how different Shortest Edit Script (SES) representations affect contextual lemmatization. The experiments cover seven languages and compare multilingual and language-specific pretrained encoder models in both in-domain and out-of-domain settings.

### Lemma Dilemma: On Lemma Generation Without Domain- or Language-Specific Training Data

[Paper](https://aclanthology.org/2025.findings-emnlp.988/) · [PDF](https://aclanthology.org/2025.findings-emnlp.988.pdf)

This work explores contextual lemmatization when domain- or language-specific training data is unavailable. It compares supervised encoder-based approaches and cross-lingual transfer with direct in-context lemma generation using large language models (LLMs) across 12 languages.

## Languages

Experiments across these papers include languages with different morphological profiles, including **Basque, Czech, English, Polish, Russian, Spanish, and Turkish**.

## Citation

If you use this repository, please cite the paper(s) relevant to the experiments or models you use. BibTeX entries are available from the ACL Anthology pages linked above.

## Authors and affiliation

Developed at **HiTZ — Basque Center for Language Technology**, University of the Basque Country (UPV/EHU).
