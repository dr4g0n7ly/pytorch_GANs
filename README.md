# pytorch_GANs

## What are GANs
GANs were originally proposed by Ian Goodfellow et al. in a seminal paper called Generative Adversarial Nets.

GANs are a framework where 2 models (usually neural networks), called generator (G) and discriminator (D), play a minimax game against each other. The generator is trying to learn the distribution of real data and is the network which we're usually interested in. During the game the goal of the generator is to trick the discriminator into "thinking" that the data it generates is real. The goal of the discriminator, on the other hand, is to correctly discriminate between the generated (fake) images and real images coming from some dataset (e.g. MNIST).
