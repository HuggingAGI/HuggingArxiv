# 具有资源受限设备的微型 Transformer 的高效联邦微调

发布时间：2024年11月12日

`LLM应用` `机器学习` `联邦学习`

> Efficient Federated Finetuning of Tiny Transformers with Resource-Constrained Devices

# 摘要

> 近年来，通过 Transformer 结构的大型语言模型（LLM）在许多机器学习任务中占据主导地位，尤其是文本处理。然而，这些模型需要大量的数据进行训练，并导致高资源需求，特别是在大量的浮点运算（FLOP）和所需的大量内存方面。为了以参数高效的方式微调这样的模型，像 Adapter 或 LoRA 这样的技术已经被开发出来。然而，我们观察到，在联邦学习（FL）中使用 LoRA 时，虽然仍然是参数高效的，但在内存和 FLOP 方面是低效的。基于这一观察，我们开发了一种新颖的层微调方案，允许跨设备 FL 中的设备利用预训练的神经网络（NN），同时遵守给定的资源约束。我们表明，我们提出的方案在处理同质或异质计算和内存约束时优于当前的先进水平，并且在有限的通信方面与 LoRA 相当，从而在 FL 训练中实现了显著更高的准确性。

> In recent years, Large Language Models (LLMs) through Transformer structures have dominated many machine learning tasks, especially text processing. However, these models require massive amounts of data for training and induce high resource requirements, particularly in terms of the large number of Floating Point Operations (FLOPs) and the high amounts of memory needed. To fine-tune such a model in a parameter-efficient way, techniques like Adapter or LoRA have been developed. However, we observe that the application of LoRA, when used in federated learning (FL), while still being parameter-efficient, is memory and FLOP inefficient. Based on that observation, we develop a novel layer finetuning scheme that allows devices in cross-device FL to make use of pretrained neural networks (NNs) while adhering to given resource constraints. We show that our presented scheme outperforms the current state of the art when dealing with homogeneous or heterogeneous computation and memory constraints and is on par with LoRA regarding limited communication, thereby achieving significantly higher accuracies in FL training.

[Arxiv](https://arxiv.org/abs/2411.07826)