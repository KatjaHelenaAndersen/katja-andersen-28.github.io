---
title: "Applications of machine learning in tabular document digitisation"
collection: publications.published
permalink: /publication/applications
excerpt: ''
author: 'Christian M. Dahl, Torben S. D. Johansen, Emil N. Sørensen, Christian E. Westermann, and Simon F. Wittrock'
date: 2023-01-19
venue: 'Historical Methods: A Journal of Quantitative and Interdisciplinary History'
paperurl: 'https://www.tandfonline.com/doi/abs/10.1080/01615440.2023.2164879'
citation: 'Dahl, Christian M., Torben S. D. Johansen, Emil N. Sørensen, Christian E. Westermann, and Simon F. Wittrock (2023). “Applications of machine learning in tabular document digitisation”. In: Historical Methods: A Journal of Quantitative and Interdisciplinary History 56.1, pp. 34–48. doi: 10.1080/01615440.2023.2164879.'
---

**Authors**: 
The paper is written by Christian M. Dahl, Torben S. D. Johansen, Emil N. Sørensen, Christian E. Westermann, and Simon F. Wittrock.

**Download**: 
You can access the paper [here](https://www.tandfonline.com/doi/abs/10.1080/01615440.2023.2164879) or the earlier arXiv version [here](https://arxiv.org/abs/2102.03239).

**Abtract**:
Data acquisition forms the primary step in all empirical research. The availability of data directly impacts the quality and extent of conclusions and insights. In particular, larger and more detailed datasets provide convincing answers even to complex research questions. The main problem is that large and detailed usually imply costly and difficult, especially when the data medium is paper and books. Human operators and manual transcription has been the traditional approach for collecting historical data. We instead advocate the use of modern machine learning techniques to automate the digitization and transcription process. We propose a customizable end-to-end transcription pipeline to perform layout classification, table segmentation, and transcribe handwritten text that is suitable for tabular data, as is common in, e.g., census lists and birth and death records. We showcase our pipeline through two applications: The first demonstrates that unsupervised layout classification applied to raw scans of nurse journals can be used to obtain valuable insights into an extended nurse home visiting program. The second application uses attention-based neural networks for handwritten text recognition to transcribe age and birth and death dates and includes a comparison to automated transcription using Transkribus in the regime of tabular data. We describe each step in our pipeline and provide implementation insights.

## Citing
If you would like to cite our paper, please use
```bibtex
@article{dahl2023applications,
    author = {Dahl, Christian M. and Johansen, Torben S. D. and S{\o}rensen, Emil N. and Westermann, Christian E. and Wittrock, Simon F.},
    title = {Applications of machine learning in tabular document digitisation},
    journal = {Historical Methods: A Journal of Quantitative and Interdisciplinary History},
    volume = {56},
    number = {1},
    pages = {34--48},
    year  = {2023},
    publisher = {Routledge},
    doi = {10.1080/01615440.2023.2164879},
}
```
or (as a reference to the earlier arXiv version)
```bibtex
@misc{dahl2021applications,
      author = {Dahl, Christian M. and Johansen, Torben S. D. and S{\o}rensen, Emil N. and Westermann, Christian E. and Wittrock, Simon F.},
      title = {Applications of machine learning in tabular document digitisation},
      year={2021},
      eprint={2102.03239},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```