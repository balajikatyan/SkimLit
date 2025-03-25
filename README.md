# SkimLit
**Overview**
This repository contains an implementation of a deep learning model for sequential sentence classification in medical abstracts, inspired by the paper PubMed 200k RCT: A Dataset for Sequential Sentence Classification in Medical Abstracts by Franck Dernoncourt and Ji Young Lee.

The dataset consists of approximately 200,000 randomized controlled trial (RCT) abstracts from PubMed, where each sentence is classified into one of the following categories:

Background
Objective
Method
Result
Conclusion
This classification helps researchers efficiently skim through medical literature and extract relevant information.

**Model Architecture**
The model is implemented using LSTM-based neural networks to capture sequential dependencies in abstracts. It follows a bi-LSTM with CRF approach for sentence classification. The architecture includes:

Word Embeddings (Pre-trained embeddings or learned embeddings)
Bi-Directional LSTM (To capture context from both past and future sentences)
Conditional Random Fields (CRF) (For sequential sentence classification)

**Results:**
![image](https://github.com/user-attachments/assets/9d8dbdfa-94ae-440d-bf1e-09824a4c6d99)
![Uploading image.png…]()
