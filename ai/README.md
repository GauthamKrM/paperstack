# AI & Machine Learning Research Papers

A curated collection of foundational and cutting-edge research papers in artificial intelligence, deep learning, natural language processing, computer vision, and reinforcement learning.

---

## Table of Contents

- [Language Models & Transformers](#language-models--transformers)
- [Training Techniques & Optimization](#training-techniques--optimization)
- [Computer Vision](#computer-vision)
- [Reinforcement Learning](#reinforcement-learning)
- [Model Architectures & Components](#model-architectures--components)
- [Efficient AI & Hardware](#efficient-ai--hardware)
- [Scaling & Distributed Training](#scaling--distributed-training)
- [Evaluation & Benchmarks](#evaluation--benchmarks)

---

## Language Models & Transformers

### Foundational Architecture
- **[Attention Is All You Need](https://arxiv.org/pdf/1706.03762)** - The original Transformer architecture
- **[Neural Probabilistic Language Model](https://www.jmlr.org/papers/volume3/bengio03a/bengio03a.pdf)** - Early neural language modeling approach
- **[Sequence to Sequence Learning with Neural Networks](https://arxiv.org/pdf/1409.3215)** - Seq2seq models with LSTMs

### GPT Series & Large Language Models
- **[GPT-2: Language Models are Unsupervised Multitask Learners](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf)** - Zero-shot learning and tokenization insights
- **[GPT-3](https://arxiv.org/pdf/2005.14165)** - Language models at 175B parameters scale
- **[Chain-of-Thought Prompting](https://arxiv.org/pdf/2201.11903)** - Eliciting reasoning in language models

### Tokenization & Representation
- **[Byte Pair Encoding (BPE)](https://arxiv.org/pdf/1508.07909)** - Subword tokenization algorithm
- **[MEGABYTE](https://arxiv.org/pdf/2305.07185)** - Predicting million-byte sequences with multiscale transformers
- **[Using Output Embedding to Improve Language Models](https://arxiv.org/pdf/1608.05859)** - Weight tying in language models

### Prompt Engineering & Context
- **[Learning to Compress Prompts with Gist Tokens](https://arxiv.org/pdf/2304.08467)** - Efficient prompt compression
- **[Efficient Training of Language Models to Fill in the Middle](https://arxiv.org/pdf/2207.14255)** - Infilling capabilities for code generation
- **[Beyond Context Limits](https://arxiv.org/pdf/2507.16784)** - Extending context windows in transformers

---

## Training Techniques & Optimization

### Regularization & Normalization
- **[Dropout](https://arxiv.org/pdf/1207.0580)** - Preventing neural network overfitting
- **[Deep Dive into Rectifiers](https://www.jmlr.org/papers/volume3/bengio03a/bengio03a.pdf)** - PReLU and initialization strategies

### Activation Functions
- **[GeLU (Gaussian Error Linear Units)](https://arxiv.org/pdf/1606.08415)** - Smooth activation function used in transformers

### Alignment & Human Feedback
- **[Deep Reinforcement Learning from Human Preferences](https://arxiv.org/pdf/1706.03741)** - RLHF foundations

---

## Computer Vision

### Convolutional Networks
- **[Going Deeper with Convolutions (Inception/GoogLeNet)](https://arxiv.org/pdf/1409.4842)** - Multi-scale feature extraction
- **[Deep Residual Learning for Image Recognition (ResNet)](https://arxiv.org/pdf/1512.03385)** - Skip connections for very deep networks

### Vision Transformers
- **[An Image is Worth 16x16 Words (ViT)](https://arxiv.org/pdf/2010.11929)** - Applying transformers to computer vision
- **[Taming Transformers for High-Resolution Image Synthesis](https://arxiv.org/pdf/2012.09841)** - VQGAN for image generation

### Multimodal Learning
- **[Deep Fragment Embedding for Bidirectional Image-Sentence Mapping](https://arxiv.org/pdf/1406.5679)** - Vision-language alignment
- **[Zero-Shot Learning](https://www.ibm.com/think/topics/zero-shot-learning)** - Recognizing unseen classes

---

## Reinforcement Learning

- **[DQN: Playing Atari with Deep Reinforcement Learning](https://arxiv.org/pdf/1312.5602)** - Deep Q-Networks
- **[DQN Implementation Guide](https://user.ceng.metu.edu.tr/~emre/resources/courses/AdvancedDL_Spring2017/DQN_Muhammed.pdf)** - Practical DQN tutorial
- **[Double DQN (DDQN)](https://arxiv.org/pdf/1509.06461)** - Addressing overestimation in Q-learning

---

## Model Architectures & Components

### Alternative Architectures
- **[Kolmogorov-Arnold Networks (KAN)](https://arxiv.org/pdf/2404.19756)** - Learnable activation functions on edges
- **[WaveNet](https://arxiv.org/pdf/1609.03499)** - Generative model for raw audio

### Attention Mechanisms
- **[Flash Attention](https://arxiv.org/pdf/2205.14135)** - Fast and memory-efficient exact attention
- **[Flash Attention 2](https://arxiv.org/pdf/2307.08691)** - Improved parallelism and work partitioning
- **[Online Softmax](https://arxiv.org/pdf/1805.02867)** - Online normalizer calculation for attention

---

## Efficient AI & Hardware

### Small Language Models
- **[Small Language Models (NVIDIA Research)](https://arxiv.org/pdf/2506.02153v1)** - Efficient models for resource-constrained environments

### Hardware Architecture
- **[NVIDIA A100 Architecture](https://images.nvidia.com/aem-dam/en-zz/Solutions/data-center/nvidia-ampere-architecture-whitepaper.pdf)** - GPU architecture for AI workloads

### Similarity Search & Retrieval
- **[Billion-Scale Similarity Search](https://arxiv.org/pdf/1702.08734)** - Efficient approximate nearest neighbor search with FAISS

---

## Scaling & Distributed Training

- **[GShard: Scaling Giant Models with Conditional Computation](https://arxiv.org/pdf/2006.16668)** - Mixture of Experts for efficient scaling
- **[Outrageously Large Neural Networks (MoE)](https://arxiv.org/pdf/1701.06538)** - Sparsely-gated mixture of experts layer

---

## Evaluation & Benchmarks

- **[HellaSwag](https://arxiv.org/pdf/1905.07830)** - Commonsense reasoning benchmark for language models

---

## License

This is a curated list of publicly available research papers. All papers remain under their original licenses and copyrights.