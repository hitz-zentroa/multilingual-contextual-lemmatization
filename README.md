# multilingual-contextual-lemmatization

This repository brings together research on multilingual contextual lemmatization across languages with varying levels of morphological complexity. In particular, we study how contextual representations, morphological information, edit-script design, and multilingual transfer affect lemmatization performance across languages and domains.

The repository is structured around three publications that form the basis of this line of research.

## Publications

### 1. [On the Role of Morphological Information for Contextual Lemmatization](https://aclanthology.org/2024.cl-1.6/)

**Olia Toporkov and Rodrigo Agerri**  
*Computational Linguistics*, 50(1), 2024, pp. 157–191.

This work investigates the role of morphological information in contextual lemmatization across six languages with different levels of morphological complexity. It evaluates whether explicit morphological features are necessary when using modern contextual representations, considering both in-domain and out-of-domain settings.

```bibtex
@article{toporkov-agerri-2024-role,
    title = "On the Role of Morphological Information for Contextual Lemmatization",
    author = "Toporkov, Olia  and
      Agerri, Rodrigo",
    journal = "Computational Linguistics",
    volume = "50",
    number = "1",
    month = mar,
    year = "2024",
    address = "Cambridge, MA",
    publisher = "MIT Press",
    url = "https://aclanthology.org/2024.cl-1.6/",
    doi = "10.1162/coli_a_00497",
    pages = "157--191"
}
```

---

### 2. [Evaluating Shortest Edit Script Methods for Contextual Lemmatization](https://aclanthology.org/2024.lrec-main.572/)

**Olia Toporkov and Rodrigo Agerri**  
*Proceedings of LREC-COLING 2024*, 2024, pp. 6451–6463.

This work studies how different Shortest Edit Script (SES) representations affect contextual lemmatization. The experiments cover seven languages and compare multilingual and language-specific pretrained encoder models in both in-domain and out-of-domain settings.

```bibtex
@inproceedings{toporkov-agerri-2024-evaluating,
    title = "Evaluating Shortest Edit Script Methods for Contextual Lemmatization",
    author = "Toporkov, Olia  and
      Agerri, Rodrigo",
    booktitle = "Proceedings of the 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation (LREC-COLING 2024)",
    month = may,
    year = "2024",
    address = "Torino, Italia",
    publisher = "ELRA and ICCL",
    url = "https://aclanthology.org/2024.lrec-main.572/",
    pages = "6451--6463"
}
```

---

### 3. [Lemma Dilemma: On Lemma Generation Without Domain- or Language-Specific Training Data](https://aclanthology.org/2025.findings-emnlp.988/)

**Olia Toporkov, Alan Akbik, and Rodrigo Agerri**  
*Findings of the Association for Computational Linguistics: EMNLP 2025*, 2025, pp. 18219–18232.

This work explores contextual lemmatization when domain- or language-specific training data is unavailable. It compares supervised encoder-based approaches and cross-lingual transfer with direct in-context lemma generation using large language models (LLMs) across 12 languages.

```bibtex
@inproceedings{toporkov-etal-2025-lemma,
    title = "Lemma Dilemma: On Lemma Generation Without Domain- or Language-Specific Training Data",
    author = "Toporkov, Olia  and
      Akbik, Alan  and
      Agerri, Rodrigo",
    booktitle = "Findings of the Association for Computational Linguistics: EMNLP 2025",
    month = nov,
    year = "2025",
    address = "Suzhou, China",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2025.findings-emnlp.988/",
    doi = "10.18653/v1/2025.findings-emnlp.988",
    pages = "18219--18232"
}
```

## Citation

If you use the code, models, or resources provided in this repository, please cite the publication most relevant to your use case. If your work builds on the overall line of research, you may cite all three publications.

## Repository Structure

The repository is organized according to the three publications above. Each corresponding directory contains the code, resources, and experimental configurations associated with that work.

## License

Please refer to the repository license for information about permitted use and redistribution.
