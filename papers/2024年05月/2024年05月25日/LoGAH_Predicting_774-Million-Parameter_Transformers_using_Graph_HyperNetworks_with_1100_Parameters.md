# LoGAH：利用仅占1/100参数的图超网络，精准预测77400万参数的变压器模型

发布时间：2024年05月25日

`LLM理论

理由：这篇论文主要关注的是大型语言模型（LLM）的初始化问题，特别是通过开发一种新型的Graph HyperNetworks（GHNs）即LoGAH来优化大型神经网络的初始参数预测。这种方法旨在解决预训练大型模型成本高昂的问题，并通过精确预测初始参数来优化模型的收敛。因此，这项工作更偏向于LLM的理论研究，即如何通过技术改进来优化模型的初始化和性能，而不是直接应用于特定的Agent或RAG系统，也不是直接讨论LLM的应用场景。` `模型优化`

> LoGAH: Predicting 774-Million-Parameter Transformers using Graph HyperNetworks with 1/100 Parameters

# 摘要

> 深度学习模型的良好初始化对于加速和优化收敛至关重要。然而，预训练大型模型对许多研究者来说成本过高，因此对初始参数的精确预测变得尤为重要。Graph HyperNetworks（GHNs）近期在初始化大型视觉模型方面展现出优异性能，但预测宽网络参数时需大量复制小参数块，导致参数需求激增，限制了其实际应用。为此，我们开发了LoGAH（低秩图超网络），一种采用低秩参数解码器的GHN，能在不大幅增加参数量的前提下扩展至更宽网络。LoGAH使我们能高效预测7.74亿参数的大型神经网络。实验表明，使用LoGAH初始化的ViT和GPT-2模型性能优于随机或现有超网络初始化的模型。此外，LoGAH在小数据集上的训练结果显示了其在大型任务上迁移学习的潜力。相关代码已发布于https://github.com/Blackzxy/LoGAH。

> A good initialization of deep learning models is essential since it can help them converge better and faster. However, pretraining large models is unaffordable for many researchers, which makes a desired prediction for initial parameters more necessary nowadays. Graph HyperNetworks (GHNs), one approach to predicting model parameters, have recently shown strong performance in initializing large vision models. Unfortunately, predicting parameters of very wide networks relies on copying small chunks of parameters multiple times and requires an extremely large number of parameters to support full prediction, which greatly hinders its adoption in practice. To address this limitation, we propose LoGAH (Low-rank GrAph Hypernetworks), a GHN with a low-rank parameter decoder that expands to significantly wider networks without requiring as excessive increase of parameters as in previous attempts. LoGAH allows us to predict the parameters of 774-million large neural networks in a memory-efficient manner. We show that vision and language models (i.e., ViT and GPT-2) initialized with LoGAH achieve better performance than those initialized randomly or using existing hypernetworks. Furthermore, we show promising transfer learning results w.r.t. training LoGAH on small datasets and using the predicted parameters to initialize for larger tasks. We provide the codes in https://github.com/Blackzxy/LoGAH .

![LoGAH：利用仅占1/100参数的图超网络，精准预测77400万参数的变压器模型](../../../paper_images/2405.16287/x1.png)

![LoGAH：利用仅占1/100参数的图超网络，精准预测77400万参数的变压器模型](../../../paper_images/2405.16287/x2.png)

![LoGAH：利用仅占1/100参数的图超网络，精准预测77400万参数的变压器模型](../../../paper_images/2405.16287/x3.png)

![LoGAH：利用仅占1/100参数的图超网络，精准预测77400万参数的变压器模型](../../../paper_images/2405.16287/x4.png)

![LoGAH：利用仅占1/100参数的图超网络，精准预测77400万参数的变压器模型](../../../paper_images/2405.16287/x5.png)

![LoGAH：利用仅占1/100参数的图超网络，精准预测77400万参数的变压器模型](../../../paper_images/2405.16287/x6.png)

![LoGAH：利用仅占1/100参数的图超网络，精准预测77400万参数的变压器模型](../../../paper_images/2405.16287/x7.png)

[Arxiv](https://arxiv.org/abs/2405.16287)