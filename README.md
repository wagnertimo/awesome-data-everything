# AI or Deep Learning Resources

## About

A curated list of deep learning articles, blog posts, papers, projects or repositories capturing the evolution of AI models; predominantly Deep Learning advancements.

This is an ongoing list and classification or survey of advancments in the AI community. It briefly elaborates notions and lists literature reviews for further exploration. The main goal of the list is to demonstrate different research fields, latest and past, and their evolution, dependence or 

> NOTE: reading bullets are classified in:
> - *introductionary*: lightweight, semi-sientific, brief overview, non-famous researcher
> - *cult*: deeper, sientific, heavyly cited, famous research
> etc. 


### Deep Learning

- Overview
  - *cult*: "Deep Learning" [Ian Goodfellow; book; 2016](https://www.deeplearningbook.org/)
  - *cult*: "Deep Learning with Python" [François Chollet; book; 2018](https://tanthiamhuat.files.wordpress.com/2018/03/deeplearningwithpython.pdf)
  - "Applications of Deep Neural Networks with keras" [Jeff Heaton; book; 2020](https://arxiv.org/pdf/2009.05673.pdf) 

- General websites etc.
  - Papers, resources, guides, blogs, interviews etc. on Application of ML and its systems: https://applyingml.com/
  - Full-Stack Deep Learning YouTube channel: https://www.youtube.com/c/FullStackDeepLearning

#### Fundamentals

- *introductionary*: "Yes you should understand backprop" [Andrej Karparthy; blog; 2016](https://karpathy.medium.com/yes-you-should-understand-backprop-e2f06eab496b)
  - "Lecture 4: Backpropagation, Neural Networks 1" [Andrej Karparthy; YouTube; 2016](https://www.youtube.com/watch?v=i94OvYb6noo) 

#### Architectures

- Multilayer Perceptron (MLP)
- Convolutional Neural Networks (CNN)
- Recurrent Neural Networks (RNN)
- Generative Adverserial Networks (GAN)
- Transformer Networks
  - *cult*: "Attention is all you need"


#### Self-Supervised Learning

- Overview
  - *introductionary*: "The rise of self-supervised learning" [Jonathan Bgn; blog post; 2020-12-03](https://jonathanbgn.com/2020/12/31/self-supervised-learning.html)
  - *cult*: "Self-supervised learning: The dark matter of intelligence" [Meta AI; blog post; 2021-03-04](https://ai.facebook.com/blog/self-supervised-learning-the-dark-matter-of-intelligence/)
    - Video explanation of blog post [Yannic Kilcher; YouTube; 2021-03-11](https://www.youtube.com/watch?v=Ag1bw8MfHGQ)  
  - *cult*: "Energy-Based Models for Self-Supervised Learning" [Yann LeCun; YouTube; 2020-11-11](https://www.youtube.com/watch?v=BqgnnrojVBI)

- Natural Language Processing (NLP)
  - Autoregressive Language Modeling (predicting next word):
    - GPT-1/2/3
  - Masked Language Modeling (predicting missing words, Denoising Autoencoder):
    - *cult*: "BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding" [Google; blog post + paper; 2018-11-02](https://ai.googleblog.com/2018/11/open-sourcing-bert-state-of-art-pre.html)
  - Context Learning / Word Embeddings:
    - word2vec
    - GLoVe

- Computer Vision (CV)
  - Contrastive Learning: *need lot of data and predominantly negative pairs (hard negative mining) -> sampling*
    - *cult*: "SimCLR: A Simple Framework for Contrastive Learning of Visual Representations" [Google; paper + github; 2020-06-17](https://github.com/google-research/simclr)
  - Denoising AE (Image Inpainting): *reconstructing good BUT latent variables are bad for downstream tasks*
    - GANs
  - Non Contrastive Embedding: *non-contrastive methods for latent-variable energy-based model (for image, video, speech, and other signals)*
    - way to go for the future: "most promising ways to build machines that have the background knowledge, or 'common sense'" (Yan LeCun, Meta AI)
    - *cult*: "SEER: The start of a more powerful, flexible, and accessible era for computer vision" [2021-03-04](https://ai.facebook.com/blog/seer-the-start-of-a-more-powerful-flexible-and-accessible-era-for-computer-vision/)
      - uses SwAV
    - BYOL from DeepMind

- Automatic Speech Recognition (ASR)
  - Contrastive Learning:
    - wave2vec

#### Generative Models

- CV:
  - Generative Adverserial Networks (GAN) 
  - Variational Autoencoder (VAE)
  - DALL-E


### MLOps

- Architecture / Concepts
  - *introductionary*: "MLOps Architecture Guide" [Neptune AI; blog post; 2022-03-31](https://neptune.ai/blog/mlops-architecture-guide)
  - *cult*: "Hidden Technical Debt in Machine Learning Systems" [Google; paper; 2015-01](https://proceedings.neurips.cc/paper/2015/file/86df7dcfd896fcaf2674f757a2463eba-Paper.pdf)
  - "Building an ML Platform from Scratch: Live Coding Session" [MLOps Community ; YouTube; 2021](https://www.youtube.com/watch?v=s8Jj9gzQ3xA)

- Tools
  - "A curated list of MLOps projects" [MLOps.toys](https://mlops.toys/feature-store)
