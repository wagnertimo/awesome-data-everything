### Deep Learning

- Overview
  - *cult*: "Deep Learning" [Ian Goodfellow; book; 2016](https://www.deeplearningbook.org/)
  - *cult*: "Deep Learning with Python" [François Chollet; book; 2018](https://tanthiamhuat.files.wordpress.com/2018/03/deeplearningwithpython.pdf)
  - "Applications of Deep Neural Networks with keras" [Jeff Heaton; book; 2020](https://arxiv.org/pdf/2009.05673.pdf) 
  - *cult*: "Deep Learning with Pytorch" [NYU CENTER FOR DATA SCIENCE; course; 2020](https://atcold.github.io/pytorch-Deep-Learning/)

- Philosophical debates
  - *cult*: "What AI Can Tell Us About Intelligence: Can deep learning systems learn to manipulate symbols?" [Yann LeCun & Jacob Browning; Blog; 2022-06](https://www.noemamag.com/what-ai-can-tell-us-about-intelligence/)
  - *cult*: "Deep Learning Is Hitting a Wall: What would it take for artificial intelligence to make real progress?" [Gary Marcus; Blog; 2022-03](https://nautil.us/deep-learning-is-hitting-a-wall-14467/)

- General resources
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

#### Large Language Models

- DALL-E series:
  - DALL-E: "a 12-billion parameter version of GPT-3 trained to generate images from text descriptions, using a dataset of text–image pairs" [OpenAI; Blog & Paper; 2021-01](https://openai.com/blog/dall-e/)
  - DALL-E 2: "generates more realistic and accurate images with 4x greater resolution." [OpenAI; Blog & Paper; 2022-04](https://openai.com/dall-e-2/) 
- GPT series:
  - GPT: "diverse language tasks with a scalable, task-agnostic system" [OpenAI; Blog & Paper; 2018-06](https://openai.com/blog/language-unsupervised/)
  - GPT-2: "a successor to GPT was trained simply to predict the next word in 40GB of Internet text. A large transformer-based language model with 1.5 billion parameters, trained on a dataset of 8 million web pages." [OpenAI; Blog & Paper; 2019-02](https://openai.com/blog/better-language-models/) 
  - GPT-3: "an autoregressive language model with 175 billion parameters" [OpenAI; Blog & Paper; 2020-05](https://openai.com/blog/openai-api/) 
- Gato: "A Generalist Agent: a multi-modal, multi-task, multi-embodiment generalist policy" [DeepMind; Blog & Paper; 2022-05](https://www.deepmind.com/publications/a-generalist-agent)
- Flamingo: "a single visual language model (VLM) for few-shot learning on a wide range of open-ended multimodal tasks" [DeepMind; Blog & Paper; 2022-04](https://www.deepmind.com/blog/tackling-multiple-tasks-with-a-single-visual-language-model)
- LaMDA: "LLM trained on dialogue" [Google; Blog & Paper, 2021-05](https://blog.google/technology/ai/lamda/)
- PaLM: "a 540-billion parameter, dense decoder-only Transformer model trained with the Pathways system" [Google; Blog & Paper; 2022-04](https://ai.googleblog.com/2022/04/pathways-language-model-palm-scaling-to.html)