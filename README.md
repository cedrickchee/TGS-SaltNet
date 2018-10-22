# TGS-SaltNet

Kaggle competition—22nd place solution for [TGS Salt Identification Challenge](https://www.kaggle.com/c/tgs-salt-identification-challenge).

## General

I recently participated in a Kaggle competition, TGS Salt Identification Challenge and reached the 22nd place. This repository contains the final code which resulted in the best model. The code demonstrates usage of different important techniques using [fast.ai](http://www.fast.ai/) and [PyTorch](https://pytorch.org/).

1. Use ResNet model as an encoder for U-Net.
2. Add intermediate layers like [Bottleneck Attention Module(BAM)](http://bmvc2018.org/contents/papers/0092.pdf), [Squeeze & Excitation](https://arxiv.org/abs/1803.02579) blocks in a ResNet34 model which can be easily replicated for other network architectures.
3. Show how to add [Deep supervision](https://www.kaggle.com/c/tgs-salt-identification-challenge/discussion/65933) to the network, and calculate loss and combine loss at different scale. 

## Main software used

1. fastai version 0.7
2. PyTorch version 0.4
3. Python version 3.6

## Hardware required

The code was tested with TitanX GPU / 1080ti.

## Thanks

A special thanks to Heng CherKeng for his generous contributions to different ideas in the competition, for a long list of amazing Kaglle community members, Jeremy and fast.ai community for the amazing and flexible fastai framework.
