# mipt-nlp2021
NLP course, MIPT

### Course instructors
Anton Emelianov (login-const@mail.ru, @king_menin), Alena Fenogenova (alenush93@gmail.com)

Telegram chat [mipt-nlp2021](https://t.me/joinchat/HlYsCUgkZ9sTL0mJ)

Videos [here](https://drive.google.com/drive/folders/1YbyT2wA4LEcaMitwuTr7fuYcpWeAWzIW?usp=sharing)

## Mark
```math
final_mark=sum_i (max_score(HW_i)) / count(HWs) * 10, i==1..4
```

## Lecture schedule

#### Week 1

* Lecture: [Intro to NLP](lectures/L1.Intro2NLP.pdf)
* Practical: [Text preprocessing](seminars/sem1/sem1_basic_text_processing.ipynb), [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/king-menin/mipt-nlp2021/blob/master/seminars/sem1/sem1_basic_text_processing.ipynb)
* [Video](https://drive.google.com/file/d/1DoD4Yaw-oFBSjK4awL0F_pXbdOMlfkwI/view?usp=sharing)

#### Week 2

* Lecture: [Word embeddings](lectures/L2.WordEmbeddings.pdf)

Distributional semantics. Count-based (pre-neural) methods. Word2Vec: learn vectors. GloVe: count, then learn. N-gram (collocations)
RusVectores. t-SNE.
* Practical: [word2vec, fasttext](seminars/sem2/2_embeddings.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/king-menin/mipt-nlp2021/blob/master/seminars/sem2/2_embeddings.ipynb)
* [HW1](HWs/hw1.ipynb)
* [Video](https://drive.google.com/file/d/1lD5k1b8LAJ8wSM45Z1TDYstXqqwYjb9L/view?usp=sharing)

#### Week 3

* Lecture: [RNN + CNN, Text classification](lectures/L3.TextClassification_BasicNNs_at_NLP.pdf)

Neural Language Models: Recurrent Models, Convolutional Models. Text classification (architectures)
* Practical: [Classification with LSTM, CNN](seminars/sem3/sem3_classification.ipynb), [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/king-menin/mipt-nlp2021/blob/master/seminars/sem3/sem3_classification.ipynb)
* [Video](https://drive.google.com/file/d/1i6X3Hv7bzC8-ZHKeVvuu_gabaYrfMygM/view?usp=sharing)

#### Week 4

* Lecture: Language modelling

Task description, methods (Markov Model, RNNs), evaluation (perplexity), Sequence Labelling (NER, pos-tagging, chunking etc.) N-gram language models, HMM, MEMM, CRF
* Practical: NER
* HW2

#### Week 5

* Lecture: Machine translation, Seq2seq

Basics: Encoder-Decoder framework, Training, Simple Models, Inference (e.g., beam search).  Eval (bleu). Parallel corpus, alignment techniques
* Practical: Seq2seq

#### Week 6

* Lecture: Language modeling 2. Attention. Transformers

Bahdanau Model. Attention: general, score functions, models. Transformer: self-attention, masked self-attention, multi-head attention; BERT, Subword Segmentation (BPE).
* HW3

#### Week 7

* Lecture: Transfer learning in NLP

ELMO, ULMFIT и Berthology (GPT-s, roberta…., t5, mt5)
* Practical: transformers models for classification task

#### Week 8

* Lecture & Practical: Syntax parsing

Syntax and Tagging

#### Week 9

* Lecture: Question answering

Squads (one-hop, multi-hop), architectures, retrieval and search, triplets wikidata, tf-idf, chat-bots
* HW4

#### Week 10

* Lecture: Summarization and simplification

#### Week 11

Lecture: Real cases and trends.

Few-shot, Zero-shot, Distillation

#### Week 12
TODO :-)

## Recommended Resources
### En

* [ruder.io](https://ruder.io/)
* [Jurafsky & Martin](https://web.stanford.edu/~jurafsky/slp3/)
* [Курс Лауры Каллмайер по МО для NLP](https://user.phil.hhu.de/~kallmeyer/MachineLearning/index.html)
* [Курс Нильса Раймерса по DL для NLP](https://github.com/UKPLab/deeplearning4nlp-tutorial)
* [Курс в Оксфорде по DL для NLP](https://github.com/UKPLab/deeplearning4nlp-tutorial)
* [Курс в Стенфорде по DL для NLP](http://cs224d.stanford.edu)
* [Reinforcment Learning for NLP](https://github.com/jiyfeng/rl4nlp)


### На русском (и про русский, в основном)

* [Курс nlp в яндексе](https://github.com/yandexdataschool/nlp_course)
* [НКРЯ](http://ruscorpora.ru)
* [Открытый корпус](http://opencorpora.org)
* [Дистрибутивные семантические модели для русского языка](http://rusvectores.org/ru/)
* [Морфология](https://tech.yandex.ru/mystem/)
* [Синтаксис](https://habrahabr.ru/post/317564/)
* [Томита-парсер](https://tech.yandex.ru/tomita/)
* [mathlingvo](http://mathlingvo.ru)
* [nlpub](https://nlpub.ru)
* [Text Visualisation browser](http://textvis.lnu.se)



## Literature

* Manning, Christopher D., and Hinrich Schütze. Foundations of statistical natural language processing. Vol. 999. Cambridge: MIT press, 1999.
* Martin, James H., and Daniel Jurafsky. "Speech and language processing." International Edition 710 (2000): 25.
* Cohen, Shay. "Bayesian analysis in natural language processing." Synthesis Lectures on Human Language Technologies 9, no. 2 (2016): 1-274.
* Goldberg, Yoav. "Neural Network Methods for Natural Language Processing." Synthesis Lectures on Human Language Technologies 10, no. 1 (2017): 1-309.

