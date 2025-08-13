---
title: "HANA: A HAndwritten NAme Database for Offline Handwritten Text Recognition"
collection: publications.published
permalink: /publication/hana
excerpt: ''
author: 'Christian M. Dahl, Torben S. D. Johansen, Emil N. Sørensen, and Simon F. Wittrock'
date: 2023-01-01
venue: 'Explorations in Economic History'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S0014498322000511'
citation: 'HANA: A HAndwritten NAme Database for Offline Handwritten Text”. In: Explorations in Economic History 87. Methodological Advances in the Extraction and Analysis of Historical Data, p. 101473. issn: 0014-4983. doi: https://doi.org/10. 1016/j.eeh.2022.101473.'
---

**Authors**: 
The paper is written by Christian M. Dahl, Torben S. D. Johansen, Emil N. Sørensen, and Simon F. Wittrock.

**Download**: 
You can access the paper [here](https://www.sciencedirect.com/science/article/pii/S0014498322000511) or the earlier arXiv version [here](https://arxiv.org/abs/2101.10862).

**Code and Data**: You can find the code for the project [here](https://github.com/TorbenSDJohansen/HANA) and the database [here](https://www.kaggle.com/datasets/sdusimonwittrock/hana-database).

**Abtract**:
Methods for linking individuals across historical data sets, typically in combination with AI based transcription models, are developing rapidly. Perhaps the single most important identifier for linking is personal names. However, personal names are prone to enumeration and transcription errors and although modern linking methods are designed to handle such challenges, these sources of errors are critical and should be minimized. For this purpose, improved transcription methods and large-scale databases are crucial components. This paper describes and provides documentation for HANA, a newly constructed large-scale database which consists of more than 3.3 million names. The database contains more than 105 thousand unique names with a total of more than 1.1 million images of personal names, which proves useful for transfer learning to other settings. We provide three examples hereof, obtaining significantly improved transcription accuracy on both Danish and US census data. In addition, we present benchmark results for deep learning models automatically transcribing the personal names from the scanned documents. Through making more challenging large-scale databases publicly available we hope to foster more sophisticated, accurate, and robust models for handwritten text recognition.

## Citing
If you would like to cite our paper, please use
```bibtex
@article{dahl2023hana,
    author = {Dahl, Christian M. and Johansen, Torben S. D. and S{\o}rensen, Emil N. and Wittrock, Simon F.},
    title = {HANA: A HAndwritten NAme Database for Offline Handwritten Text},
    journal = {Explorations in Economic History},
    volume = {87},
    pages = {101473},
    year = {2023},
    note = {Methodological Advances in the Extraction and Analysis of Historical Data},
    issn = {0014-4983},
    doi = {https://doi.org/10.1016/j.eeh.2022.101473},
    url = {https://www.sciencedirect.com/science/article/pii/S0014498322000511}
}
```
or (as a reference to the earlier arXiv version)
```bibtex
@misc{dahl2022hana,
      title={HANA: A HAndwritten NAme Database for Offline Handwritten Text Recognition}, 
      author={Christian M. Dahl and Torben Johansen and Emil N. Sørensen and Simon Wittrock},
      year={2022},
      eprint={2101.10862},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```