## Introduction about Generative AI

## Overview

Generative AI, also known as generative modeling, is a branch of artiﬁcial intelligence that focuses on creating models capable of generating new data that resembles a given dataset. These models are trained to learn and understand the underlying patterns and structures within the data, allowing them to generate new samples that share similar characteristics.

Generative AI models operate by learning the probability distribution of the training data and then sampling from this distribution to create new instances. They can be broadly classiﬁed into two categories: generative models and generative adversarial networks (GANs).

| Name | Description |
|-|-|
| LLM | Language model that generates text based on learned patterns and context. |  
| Embedding model | Model that represents words or sentences as dense vectors, capturing semantic relationships. |
| DAAS2 | D company specific technology solutions. |

Generative Models: Variational Autoencoders (VAEs): These models learn a latent representation of the data and use this representation to generate new samples. VAEs are trained to maximize the likelihood of generating the input data, while also ensuring that the latent space follows a speciﬁc distribution, typically a Gaussian distribution.

Autoregressive Models: These models generate new samples by modeling the conditional probability of each data point given the previous data points. Examples of autoregressive models include PixelCNN and WaveNet.

Restricted Boltzmann Machines (RBMs): These models are a type of generative stochastic artiﬁcial neural network that learn the probability distribution of the data. They consist of visible and hidden units, and through an iterative process, they adjust their weights to better approximate the input data distribution.

## Generative Adversarial Networks (GANs):

generator tries to produce samples that are indistinguishable from the real data, while the discriminator tries to diNerentiate between real and fake samples. The generator and discriminator are trained in an adversarial manner, with the generator aiming to fool the discriminator and the discriminator trying to accurately identify real and fake samples. This competition leads to the generator producing increasingly realistic samples.

• Conditional GANs (cGANs): In addition to generating new samples, cGANs also consider additional information, known as conditioning variables, to generate samples that satisfy speciﬁc conditions. For example, given an input image of a cat, a cGAN can generate diNerent images of cats in various poses or with diNerent attributes.

Generative AI has various applications, including image synthesis, text generation, music composition, and video generation. It has the potential to revolutionize ﬁelds like art, entertainment, design, and content creation by enabling machines to create new content that resembles human creations.