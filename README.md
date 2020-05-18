## Introduction

Data is the better half of machine learning models. This is why it is important to make sure that our models are exposed to quality data while they are training. Real data is noisy, unclean, and often confusing. In our lives also, lessons that are too confusing to grasp make it extremely difficult for us to actually learn a respective topic. The same drill applies to machine learning models too.

This repository contains code for a simple utility in TensorFlow and Keras that plots images from a training set that cause a model to incur high losses during its training. 

![](https://i.ibb.co/3T9ZRfM/media-images-top-losses-6-7adba246.png)

## About the files

- `plot_losses.ipynb` : Contains plot_top_loss utility to plot images with top losses.
- `Plot_Top_Losses_Keras_wandb.ipynb` : Weights and Biases(wandb) functionality is added with plot_top_loss utility.
- `Smoothing_Analysis.ipynb` : Contains label smoothing analysis with different smoothing factors.

## Topics
- Computer vision
- Deep Learning
- Keras
- CallBacks

The code is accompanied by [this report](https://app.wandb.ai/tulasi1729/plot-top-losses/reports/Plotting-top-loss-images-while-training-models--VmlldzoxMTI0NDk) that contains additional details. Check the report for detailed analysis and uses of this utility.

## Misc details
- Dataset used: MNIST
- Model used: A simple CNN like [this one](https://app.wandb.ai/tulasi1729/plot-top-losses/runs/mnist-demo-kerascallback/model?workspace=user-sayakpaul)
