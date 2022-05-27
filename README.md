# Class Dependent Effects of Regularization in Sequential Models and Language Data

Various forms of regularization are used to prevent over-fitting in nearly every widely used neural network model nowadays. Recent studies, specifically the paper [**The Effects of Regularization and Data Augmentation are Class Dependent**](https://arxiv.org/abs/2204.03632) by Yann LeCun have shown that while regularization can improve accuracy as a whole in image classification problems, the accuracy of certain classes is drastically lowered, even with uniformed regularizers like weight decay. This study explores whether these class-specific biases caused by regularization are present in Natural Language Processing (NLP) classification tasks. This study tests various types of sequential models of different complexities, including RNN, LSTM, and Pretrained BERT on different datasets with different numbers of classes. These models are then trained with different types of uninformed regularization. Ultimately, through performing these experiments it is empirically shown that more complex models, such as LSTMs and BERT trained and finetuned on high-class datasets are more prone to show class biases.

## Code
The code for the study is organized within two directories asdf and asdf.
