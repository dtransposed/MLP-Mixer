# MLP-Mixer

PyTorch implementation of [MLP-Mixer: An all-MLP Architecture for Vision](https://arxiv.org/abs/2105.01601).

## Description

My implementation of MLP-Mixer network. I use the architecture to perform image classification on CIFAR-10. Please note,
that no hyperparameter tuning or extensive image augmentation were performed, so there is still a lot of potential for
possible improvements. 

The whole code can be found in the jupiter notebook.

## Summary

Convolutional Neural Networks (CNNs) and transformers are two mainstream model architectures currently dominating computer vision and natural language processing. The authors of the paper, however, empirically show that neither convolution nor self-attenion are necessary; in fact, muti-layered perceptrons (MLPs) can also serve as a strong baseline. The authors present MLP-Mixer, an all-MLP mode architecture, that contains two types of layers: a token-mixing layer and a channel-mixing layer. Each of the layers "mix" per-location and per-feature information in the input. MLP-Mixer performs comparably to other state-of-the-art models, such as [ViT](https://arxiv.org/abs/2010.11929) or [EfficientNet](https://arxiv.org/abs/1905.11946).
