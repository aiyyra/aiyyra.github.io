---
title: "A Hectic Month"
date: 2025-04-30
permalink: /posts/2025/04/a-hectic-month/
tags:
  - life
---

# Hectic Month

The title of this post is really accurate. Hello evryone, Afiq is here and I almost miss this month post. This month is the week of eid, house moving and family engagements.  
There is a lot of life update this month. A lot of new things that I experienced personally. Never have I think about what is needed when moving house, what do I need to when registering new house. There is a lot more to learn in this life. Not to forget the flow of engagements in Malay culture is also new to me. So, having someone close to do it is trully remarkable.

# Assesment

I did not think I accomplish any remarkable things in my path for AI enginnering. Most of it is just learning fundamentals architecture or approach for deep learning within their specific domain.

## Computer Vision

I learn a lot of basics and fundamentals things on Computer Vision. This include a deep understanding on Core things such as Convolution and Pooling up to R-CNN. I also learn the resnet architecture, where they apply residual connections in the hidden layer to overcome vanishing gradient or "memory loss" in the nodes. This residual connections was also reintroduce when I learn U-net architecture as a massive supporting role in this architecture. There is not much to say for this one as it is more simple than I thought.

## Generative Model

For Generative Model, I mainly learn 2 differences approach in the basic architecture.

### 1. Latent approach.

I learn the concept of seaching for latent element. In simple terms it is basically kind of similar to reducing the dataset demension to incorporate only important features. Firstly, The classic method of finding a latent variable is Using Auto Encoders. This is like the founding of this domain. In this architecture, Data is compressend into number of "latent variables" and the output will be reconstructed from the latent variables. This architectures share a close structure with classic NeuralNet to find the latent variables (usually use RMSE for loss).

VAE - an upgrade from autoencoder. VAE helps with Generation parts which the classic approach lacks. The main different between VAE and AutoEncoder is that, In VAE the latent variables are calculate and stored in Standardized Distribution. This helps in generation parts of the Architectures, ensuring more rigid consistency in the latent effects into the output. Note that to Apply this architecture. Reparameterization tricks with KL divergence needs to be introduced to enable the model to backpropogate into the stastical parts of the model.

### 2. GAN.

Generative Adversarial Network is a much simpler and less mathemathics model. The Idea is very much simple. Two interconnected Model (Generation and Detection) are created and forced to challanges each other. The generation will generate a fake picture based on the dataset, while the detection will try to detect if the generated picture is fake. Both models will keep on learning and improve each other. This is a famous architecture in things like deepfake.

## Reinforcement Learning

Lastly, I also learn RL architecture.  
The key features of a RL archi is Reward function. I learn what it is, what discounted reward function is and how it is used. While Reward is the important, Q-functions on the other hand is the main character compared to others. This is the function that calculate the State and Action of the agent. Then, this Q-function is used to generate policy. - Value based Policy or Action Based Policy. But here is the tricks, no one compute Q-function directly. Usual Approach is creatung a DQN to mimics or calulate the value from Q-functions.
