# 学习基础知识

原作者：[Suraj Subramanian](https://github.com/suraj813)、[Seth Juarez](https://github.com/sethjuarez/)、[Cassie Breviu](https://github.com/cassieview/)、[Dmitry Soshnikov]( Dmitry Soshnikov)、[Ari Bornstein](https://github.com/aribornstein/)

大多数机器学习工作流都涉及处理数据、创建模型、优化模型参数和保存经过训练的模型。本教程向您介绍在 PyTorch 中实现完整的机器学习工作流程，并提供每个概念的链接已帮助理解。

我们将使用 FashionMNIST 数据集来训练神经网络，预测输入图像是否属于以下类别之一：T恤/上衣、裤子、套头衫、连衣裙、外套、凉鞋、衬衫、运动鞋、包和靴子。

本教程需要您熟悉 Python 和深度学习的基本概念。

## 运行教程代码

- **在云服务器中**：这是最简单的入门方法！本文档最下方有一个“在 Google Colab 中运行”的链接，您可以在Google Colab 中打开一个代码位于完全托管的环境中的集成笔记本。

- **在本地运行**：此选项要求您首先在本地计算机上设置 PyTorch 和 TorchVision（[安装说明](https://pytorch.org/get-started/locally/)）。下载笔记本或将代码复制到您喜欢的 IDE 中。

## 如何学习本教程

**教程目录（学习顺序）**：

1. 张量（Tensor）
1. 数据集和数据加载器（Datasets and DataLoaders）
1. 变换（Transforms）
1. 创建模型（Build Model）
1. 自动求导（Autograd）
1. 优化循环（Optimization Loop）
1. 保存和加载模型（Save, Load and Use Model）

## 在Google Colab中运行

[Colab](https://colab.research.google.com/github/pytorch/tutorials/blob/gh-pages/_downloads/070179efc13bd796c5dd4af7bf52d5b9/intro.ipynb)