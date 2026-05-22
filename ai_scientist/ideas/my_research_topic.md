# Title: Exploring Learning Rate Schedules in Small Neural Networks

## Keywords
learning rate, training dynamics, small models, optimization

## TL;DR
How do different learning rate schedules affect the training of small neural networks? A simple investigation into optimization choices for compact models.

## Abstract
Despite the success of large neural networks, understanding training dynamics in small, resource-constrained models remains important for deployment in edge devices. In this work, we investigate the impact of learning rate schedules on the final performance of small convolutional neural networks. We systematically compare constant, step, cosine, and warmup schedules across three benchmark datasets: CIFAR-10, Fashion-MNIST, and a synthetic dataset. Our preliminary experiments suggest that cosine annealing with warmup consistently outperforms other schedules for small models, achieving up to 5% improvement in test accuracy. We also observe that the optimal initial learning rate scales inversely with model size. These findings provide practical guidelines for training efficient models in resource-limited settings and suggest directions for further investigation into the interaction between model capacity and optimization strategies.
