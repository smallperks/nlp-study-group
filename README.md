# 📓 NLP Study Group 

Background:
We originally started tracking the [FastAI course](https://github.com/fastai/course-nlp/). 

But because of a lack of depth, we decided instead to dissect blogs and tutorials. 

## **Week 0**

Introductions! 

What does your current work look like? How do you plan to use NLP?

--------
## **Week 1** 

1. What is NLP?

- A changing field
- Resources
- Tools
- Python libraries
- Example applications
- Ethics issues

Notebook: [What is NLP?](https://github.com/fastai/course-nlp/blob/master/1-what-is-nlp.ipynb)

Video(s):
- FastAI: [What is NLP?](https://www.youtube.com/watch?v=cce8ntxP_XI&list=PLtmWHNX-gukKocXQOkQjuVxglSDYWsSh9&index=2&t=0s)
- [SOTA 2019](https://www.youtube.com/watch?v=YxMW0w7ojek&feature=emb_logo) 


--------
## **Week 2** 

Video(s):
- FastAI: [Topic Modeling with SVD & NMF](https://www.youtube.com/watch?v=tG3pUwmGjsc&list=PLtmWHNX-gukKocXQOkQjuVxglSDYWsSh9&index=2)

Notebook: 
- [Topic Modeling with SVD & NMF](https://github.com/fastai/course-nlp/blob/master/2-svd-nmf-topic-modeling.ipynb)

Resources:
- [A Tutorial on PCA (closely related to SVD)](https://arxiv.org/pdf/1404.1100.pdf)
- [SVD article, explaining intuition behind factorizing to 3 different matrices](https://towardsdatascience.com/svd-8c2f72e264f)

## **Week 3**
Video(s):
- FastAI: [Logistic Regression & Naive Bayes](https://www.youtube.com/watch?v=hp2ipC5pW4I&list=PLtmWHNX-gukKocXQOkQjuVxglSDYWsSh9&index=4)


Notebook: 
- [Logistic Regression & Naive Bayes](https://github.com/fastai/course-nlp/blob/master/3-logreg-nb-imdb.ipynb)

Resources:
- [Baysean Inference](https://towardsdatascience.com/probability-concepts-explained-bayesian-inference-for-parameter-estimation-90e8930e5348)

Questions:
- Why is it when you plot the sorted document-term matrix it shows those waves

## **Week 4**
Skipped

## **Week 5**
Video(s):
- FastAI: [Transfer Learning](https://www.youtube.com/watch?v=PNNHaQUQqW8&list=PLtmWHNX-gukKocXQOkQjuVxglSDYWsSh9&index=8)

Notebook: 
- [Transfer Learning](https://github.com/fastai/course-nlp/blob/master/3-logreg-nb-imdb.ipynb)


Resources:
- [NLP's ImageNet Movement](https://thegradient.pub/nlp-imagenet/)
- [Cyclical Learning Rates](https://arxiv.org/pdf/1506.01186.pdf)
- [Stop using Word2Vec](https://multithreaded.stitchfix.com/blog/2017/10/18/stop-using-word2vec/)

Questions:
- When we pick a learning rate off the LR vs. Loss graph, we pick it halway down the descent to the lowest point. Why is that?

## **Week 6: Word2Vec**

Blogs:
* [Word Embeddings - Part 1: Intro](https://ruder.io/word-embeddings-1/)
* [Word Embeddings - Part 2: Approximating SoftMax](https://ruder.io/word-embeddings-softmax/index.html)

## **Week 7: Word2Vec**
* [Word Embeddings - Part 3: Secret Ingredients of Word2Vec](https://ruder.io/secret-word2vec/index.html)
* [Word Embeddings - Part 5: Future Trends](https://ruder.io/word-embeddings-2017/index.html)

Optional:
* [The illustrated Word2Vec](http://jalammar.github.io/illustrated-word2vec/)

## **Week 8: RNNs, LSTMs, GRUs**
* [The Unreasonable Effectiveness of RNNs](http://karpathy.github.io/2015/05/21/rnn-effectiveness/)
* [Illustrated Guide to LSTMs and GRUs](https://towardsdatascience.com/illustrated-guide-to-lstms-and-gru-s-a-step-by-step-explanation-44e9eb85bf21)
* [Understanding LSTM Networks](https://colah.github.io/posts/2015-08-Understanding-LSTMs/)

## **Week 9: LSTMs, Seq2Seq w/ Attn**
* [Tutorial on LSTMs: A Computational Perspective](https://towardsdatascience.com/tutorial-on-lstm-a-computational-perspective-f3417442c2cd)
* [Visualizing A Neural Machine Translation Model (Mechanics of Seq2seq Models With Attention)](https://jalammar.github.io/visualizing-neural-machine-translation-mechanics-of-seq2seq-models-with-attention/)
* [Seq2Seq with Attention and Beam Search](https://guillaumegenthial.github.io/sequence-to-sequence.html)

## **Week 10: Attention **
* [Attention and Augmented Recurrent Neural Networks](https://distill.pub/2016/augmented-rnns/)
* [Attention? Attention!](https://lilianweng.github.io/lil-log/2018/06/24/attention-attention.html#a-family-of-attention-mechanisms)
* [Attention is all you need](https://www.youtube.com/watch?v=iDulhoQ2pro)

Optional:
* [Intuitive Understanding of Attention Mechanism in Deep Learning](https://towardsdatascience.com/intuitive-understanding-of-attention-mechanism-in-deep-learning-6c9482aecf4f)
* [NLP FROM SCRATCH: TRANSLATION WITH A SEQUENCE TO SEQUENCE NETWORK AND ATTENTION](https://pytorch.org/tutorials/intermediate/seq2seq_translation_tutorial.html)
* [NEURAL MACHINE TRANSLATION BY JOINTLY LEARNING TO ALIGN AND TRANSLATE](https://arxiv.org/pdf/1409.0473.pdf)
  
## **Week 11: Implementation of Seq2Seq **

## **Other Resources**

### **Books**
- [Deep Learning Book](https://www.deeplearningbook.org/)
- [FastAI Book](https://github.com/fastai/fastbook)

### **Classes** 
- [Linear Algebra with code examples](https://hadrienj.github.io/tags/#linear-algebra)
- [Linear Algebra Class(MIT Opencourseware)](https://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/video-lectures/)
- [FastAI: Computational Linear Algebra](https://github.com/fastai/numerical-linear-algebra/blob/master/README.md)

### **Articles+**
- [A Primer in BERTology: What we know about how BERT works](https://arxiv.org/abs/2002.12327)
- [Awesome NLP](https://github.com/keon/awesome-nlp)
- [The Illustrated Transformer](http://jalammar.github.io/illustrated-transformer/)
- [The Illustrated BERT, ELMo, and co.](http://jalammar.github.io/illustrated-bert/)

### **Blogs**:
* [Distill](https://distill.pub/)
* [OpenAI](https://openai.com/blog/microscope/)
* [StichFix](https://multithreaded.stitchfix.com/blog/)
* [The Gradient](https://thegradient.pub/)
