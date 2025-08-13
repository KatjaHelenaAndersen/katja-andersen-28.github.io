---
title: "DARE: A large-scale handwritten date recognition system"
collection: publications.published
permalink: /publication/dare
excerpt: ''
author: 'Christian M. Dahl, Torben S. D. Johansen, Emil N. Sørensen, Christian E. Westermann, and Simon F. Wittrock'
date: 2022-10-02
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2210.00503'
citation: 'Dahl, Christian M., Torben S. D. Johansen, Emil N. Sørensen, Christian E. Westermann, and Simon F. Wittrock (2022). “DARE: A large-scale handwritten DAte Recognition system”. In: arXiv preprint arXiv:2210.00503'
---

**Authors**: 
The paper is written by Christian M. Dahl, Torben S. D. Johansen, Emil N. Sørensen, Christian E. Westermann, and Simon F. Wittrock.

**Download**: 
You can access the working paper [here](https://arxiv.org/abs/2210.00503).

**Data**: You can find the database [here](https://www.kaggle.com/datasets/sdusimonwittrock/dare-database).

**Abtract**:
Handwritten text recognition for historical documents is an important task but it remains difficult due to a lack of sufficient training data in combination with a large variability of writing styles and degradation of historical documents. While recurrent neural network architectures are commonly used for handwritten text recognition, they are often computationally expensive to train and the benefit of recurrence drastically differs by task. For these reasons, it is important to consider non-recurrent architectures. In the context of handwritten date recognition, we propose an architecture based on the EfficientNetV2 class of models that is fast to train, robust to parameter choices, and accurately transcribes handwritten dates from a number of sources. For training, we introduce a database containing almost 10 million tokens, originating from more than 2.2 million handwritten dates which are segmented from different historical documents. As dates are some of the most common information on historical documents, and with historical archives containing millions of such documents, the efficient and automatic transcription of dates has the potential to lead to significant cost-savings over manual transcription. We show that training on handwritten text with high variability in writing styles result in robust models for general handwritten text recognition and that transfer learning from the DARE system increases transcription accuracy substantially, allowing one to obtain high accuracy even when using a relatively small training sample.

## Citing
If you would like to cite our paper, please use
```bibtex
@article{dahl2022dare,
  title={DARE: A large-scale handwritten {DA}te {Re}cognition system},
  author={Dahl, Christian M. and Johansen, Torben S. D. and S{\o}rensen, Emil N. and Westermann, Christian E. and Wittrock, Simon F.},
  journal={arXiv preprint arXiv:2210.00503},
  year={2022}
}
```