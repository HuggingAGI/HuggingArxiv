# 卷积可微逻辑门网络

发布时间：2024年11月07日

`其他` `机器学习` `计算机视觉`

> Convolutional Differentiable Logic Gate Networks

# 摘要

> 摘要：随着机器学习模型的推理成本不断增加，人们对具有快速高效推理能力的模型越来越感兴趣。最近，有人提出了一种通过可微松弛直接学习逻辑门网络的方法。逻辑门网络比传统的神经网络方法更快，因为它们的推理只需要逻辑门运算符，如与非、或和异或，这些是当前硬件的基础构建块，可以高效执行。我们基于这个想法，通过深度逻辑门树卷积、逻辑或池化和残差初始化对其进行扩展。这使得逻辑门网络的规模扩大了一个数量级以上，并利用了卷积的范式。在 CIFAR-10 上，我们仅使用 6100 万个逻辑门就实现了 86.29%的准确率，这比最先进的技术有所提高，同时规模缩小了 29 倍。

> 
Abstract:With the increasing inference cost of machine learning models, there is a growing interest in models with fast and efficient inference. Recently, an approach for learning logic gate networks directly via a differentiable relaxation was proposed. Logic gate networks are faster than conventional neural network approaches because their inference only requires logic gate operators such as NAND, OR, and XOR, which are the underlying building blocks of current hardware and can be efficiently executed. We build on this idea, extending it by deep logic gate tree convolutions, logical OR pooling, and residual initializations. This allows scaling logic gate networks up by over one order of magnitude and utilizing the paradigm of convolution. On CIFAR-10, we achieve an accuracy of 86.29% using only 61 million logic gates, which improves over the SOTA while being 29x smaller.
    

[Arxiv](https://arxiv.org/pdf/2411.04732)