# 内存更少，GPU更小：压缩激活助力反向传播

发布时间：2024年09月18日

`LLM理论` `计算机科学` `人工智能`

> Less Memory Means smaller GPUs: Backpropagation with Compressed Activations

# 摘要

> 随着深度神经网络（DNN）规模的不断扩大，计算资源的需求也在飞速增长。特别是大型语言模型等先进架构，必须依赖配备数千个加速器（如 GPU 或 TPU）的超级计算机进行训练。然而，DNN 的内存占用也在急剧增加，而 GPU 的内存容量却相对有限。即使是一些较小的 DNN 架构，也无法在单个消费级 GPU 上以合理的小批量进行训练。为了应对这一挑战，我们提出了一种通过池化压缩反向传播激活图的方法，既能减少内存占用，又能降低数据移动量。实验结果表明，这种方法在保持预测精度的同时，成功将峰值内存消耗降低了 29%，尽管训练时间有所延长。

> The ever-growing scale of deep neural networks (DNNs) has lead to an equally rapid growth in computational resource requirements. Many recent architectures, most prominently Large Language Models, have to be trained using supercomputers with thousands of accelerators, such as GPUs or TPUs. Next to the vast number of floating point operations the memory footprint of DNNs is also exploding. In contrast, GPU architectures are notoriously short on memory. Even comparatively small architectures like some EfficientNet variants cannot be trained on a single consumer-grade GPU at reasonable mini-batch sizes. During training, intermediate input activations have to be stored until backpropagation for gradient calculation. These make up the vast majority of the memory footprint. In this work we therefore consider compressing activation maps for the backward pass using pooling, which can reduce both the memory footprint and amount of data movement. The forward computation remains uncompressed. We empirically show convergence and study effects on feature detection at the example of the common vision architecture ResNet. With this approach we are able to reduce the peak memory consumption by 29% at the cost of a longer training schedule, while maintaining prediction accuracy compared to an uncompressed baseline.

[Arxiv](https://arxiv.org/abs/2409.11902)