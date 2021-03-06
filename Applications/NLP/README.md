## TF-IDF 

可用于文本关键词提取。该模型基于词频，将文本转换成向量，而不考虑词序。

Code example:

## LSA 潜在语义分析

通过词频统计，我们可以得到文本的特征向量，向量具有一定语义表达的能力。LSA是在此基础上挖掘文本的潜在语义，构建主题模型等。

遍历语料库，得到全部文本-单词的权重矩阵，权重即求得的TF-IDF值。建立文本-单词权重矩阵X后，可以通过SVD奇异值分解的方式将矩阵X转换为它的低秩逼近矩阵。


## PLSA 概率潜在语义分析

## LDA 隐含狄利克雷分布

## HMM 隐马尔科夫模型

## CRF 条件随机场

## Neural Networks 神经网络

## Word2Vec

Word2Vec attempts to understand meaning and semantic relationships among words. It works in a way that is similar to deep approaches, such as recurrent neural nets or deep neural nets, but is computationally more efficient.

### Practice
- **Sentiment Analysis**(情感分析)
    - [Kaggle competition: Bag of Words Meets Bags of Popcorn](../kaggle/BagOfWordsMeetsBagsOfPopcorn)
    - [kaggle link](https://www.kaggle.com/c/word2vec-nlp-tutorial)

# References
- Word2Vec paper: [Efficient Estimation of Word Representations in Vector Space](http://arxiv.org/pdf/1301.3781v3.pdf)
- Deep Learning for NLP
    - [https://cs224d.stanford.edu/lecture_notes/notes1.pdf](https://cs224d.stanford.edu/lecture_notes/notes1.pdf)
- Google Word2Vec Model
    - [https://arxiv.org/pdf/1310.4546.pdf](https://arxiv.org/pdf/1310.4546.pdf)
    - [http://mccormickml.com/2016/04/12/googles-pretrained-word2vec-model-in-python/](http://mccormickml.com/2016/04/12/googles-pretrained-word2vec-model-in-python/)
