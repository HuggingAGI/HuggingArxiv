# 为了加快变换模型的训练速度，我们提出了一个多层次的框架。

发布时间：2024年04月06日

`LLM理论` `能源效率`

> A Multi-Level Framework for Accelerating Training Transformer Models

# 摘要

> 像Bert、GPT和ViT这样的大规模深度学习模型正引领着自然语言处理和计算机视觉等领域的革命。但这些模型的训练对计算资源的巨大需求，也带来了能源消耗和碳排放的急剧上升。因此，寻求高效的训练方法以降低成本显得尤为迫切。我们从训练过程中发现的特征图和注意力的相似性出发，提出了一个多层次的训练加速框架。该框架采用合并、解合并和插值三种基本操作，通过V型循环训练过程，逐步调整模型大小，并通过这些操作在不同层级间传递参数。核心思想是，小模型快速训练得到的参数，能为更大网络的下一层提供高质量的中间解。插值操作则有助于打破解合并后的神经元对称性，优化收敛效果。实验表明，这一框架在保持性能的同时，能将BERT/GPT-Base模型的训练计算成本降低约20%，BERT-Large模型的训练成本更是大幅减少至51.6%。

> The fast growing capabilities of large-scale deep learning models, such as Bert, GPT and ViT, are revolutionizing the landscape of NLP, CV and many other domains. Training such models, however, poses an unprecedented demand for computing power, which incurs exponentially increasing energy cost and carbon dioxide emissions. It is thus critical to develop efficient training solutions to reduce the training costs. Motivated by a set of key observations of inter- and intra-layer similarities among feature maps and attentions that can be identified from typical training processes, we propose a multi-level framework for training acceleration. Specifically, the framework is based on three basic operators, Coalescing, De-coalescing and Interpolation, which can be orchestrated to build a multi-level training framework. The framework consists of a V-cycle training process, which progressively down- and up-scales the model size and projects the parameters between adjacent levels of models via coalescing and de-coalescing. The key idea is that a smaller model that can be trained for fast convergence and the trained parameters provides high-qualities intermediate solutions for the next level larger network. The interpolation operator is designed to break the symmetry of neurons incurred by de-coalescing for better convergence performance. Our experiments on transformer-based language models (e.g. Bert, GPT) as well as a vision model (e.g. DeiT) prove that the proposed framework reduces the computational cost by about 20% on training BERT/GPT-Base models and up to 51.6% on training the BERT-Large model while preserving the performance.

![为了加快变换模型的训练速度，我们提出了一个多层次的框架。](../../../paper_images/2404.07999/x1.png)

![为了加快变换模型的训练速度，我们提出了一个多层次的框架。](../../../paper_images/2404.07999/x2.png)

![为了加快变换模型的训练速度，我们提出了一个多层次的框架。](../../../paper_images/2404.07999/x3.png)

![为了加快变换模型的训练速度，我们提出了一个多层次的框架。](../../../paper_images/2404.07999/x4.png)

![为了加快变换模型的训练速度，我们提出了一个多层次的框架。](../../../paper_images/2404.07999/x5.png)

![为了加快变换模型的训练速度，我们提出了一个多层次的框架。](../../../paper_images/2404.07999/x6.png)

![为了加快变换模型的训练速度，我们提出了一个多层次的框架。](../../../paper_images/2404.07999/x7.png)

![为了加快变换模型的训练速度，我们提出了一个多层次的框架。](../../../paper_images/2404.07999/x8.png)

![为了加快变换模型的训练速度，我们提出了一个多层次的框架。](../../../paper_images/2404.07999/x9.png)

![为了加快变换模型的训练速度，我们提出了一个多层次的框架。](../../../paper_images/2404.07999/x10.png)

![为了加快变换模型的训练速度，我们提出了一个多层次的框架。](../../../paper_images/2404.07999/x11.png)

![为了加快变换模型的训练速度，我们提出了一个多层次的框架。](../../../paper_images/2404.07999/x12.png)

![为了加快变换模型的训练速度，我们提出了一个多层次的框架。](../../../paper_images/2404.07999/x13.png)

![为了加快变换模型的训练速度，我们提出了一个多层次的框架。](../../../paper_images/2404.07999/x14.png)

![为了加快变换模型的训练速度，我们提出了一个多层次的框架。](../../../paper_images/2404.07999/x15.png)

![为了加快变换模型的训练速度，我们提出了一个多层次的框架。](../../../paper_images/2404.07999/x16.png)

![为了加快变换模型的训练速度，我们提出了一个多层次的框架。](../../../paper_images/2404.07999/x17.png)

![为了加快变换模型的训练速度，我们提出了一个多层次的框架。](../../../paper_images/2404.07999/x18.png)

![为了加快变换模型的训练速度，我们提出了一个多层次的框架。](../../../paper_images/2404.07999/x19.png)

![为了加快变换模型的训练速度，我们提出了一个多层次的框架。](../../../paper_images/2404.07999/x20.png)

![为了加快变换模型的训练速度，我们提出了一个多层次的框架。](../../../paper_images/2404.07999/x21.png)

![为了加快变换模型的训练速度，我们提出了一个多层次的框架。](../../../paper_images/2404.07999/x22.png)

[Arxiv](https://arxiv.org/abs/2404.07999)