# squad2.0-bert
A Question Answering (QA) model to predict answers for given pairs of context paragraph and question.

* [Colab Notebook](https://colab.research.google.com/drive/10ruy21T41erelEMq5d4d9DNHHz4_t-uK)  
The notebook serves to train a Question Answering (QA) model to predict answers for given pairs of **context paragraph** and **question** using the  [The Standford Question Answering Dataset](https://rajpurkar.github.io/SQuAD-explorer/) (SQuAD). The answers are confined to be either a **span of text** in the context paragraph or **no answer**, in case the model classifies the question to be unanswerable.
The QA model trained is [Bidirectional Encoder Representations from Transformers](https://arxiv.org/abs/1810.04805) (BERT) (Devlin et al., 2018) with an additional [Gating mechanism](https://www.aclweb.org/anthology/P18-1234) proposed by Xue & Li (2018) in the classification layer. The codes are modified based on [Google's TensorFlow code and pre-trained models for BERT](https://github.com/google-research/bert/blob/master/run_squad.py).

* This repository also comes with my academic paper and presentation of findings throughout the project in my part-time study in Master of Statistics in the University of Hong Kong.
