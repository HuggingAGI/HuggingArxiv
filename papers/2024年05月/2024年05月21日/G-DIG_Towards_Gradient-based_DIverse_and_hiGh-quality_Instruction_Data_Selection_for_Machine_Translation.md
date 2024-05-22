# G-DIG：探索基于梯度的方法，以实现机器翻译中多样化且高质量的指令数据选择

发布时间：2024年05月21日

`LLM应用

这篇论文主要关注大型语言模型（LLMs）在机器翻译任务中的应用，特别是在指令微调阶段如何自动筛选高质量且多样化的数据。论文提出了一种基于梯度的方法，通过分析训练中每个样本对模型的影响，并结合影响函数和高质量种子数据来挑选有益的样本。此外，还通过梯度聚类与重采样来提升数据的多样性。这种方法的应用性质和对LLM在特定任务上的优化使其适合归类为LLM应用。` `机器翻译` `数据筛选`

> G-DIG: Towards Gradient-based DIverse and hiGh-quality Instruction Data Selection for Machine Translation

# 摘要

> 大型语言模型（LLMs）在通用场景中表现出色，通过指令微调，它们能在多任务中与人类协同。但指令数据的多样性与质量仍是微调的两大难题。为此，本文创新性地提出了一种基于梯度的方法，旨在为机器翻译自动筛选出高质量且多样化的指令微调数据。我们的核心创新在于深入分析训练中每个样本对模型的影响，通过影响函数结合一小批高质量种子数据，挑选出对模型有益的样本。同时，为提升数据多样性，我们通过梯度聚类与重采样，确保样本对模型的影响多样化。在WMT22和FLORES翻译任务上的广泛实验表明，我们的方法表现卓越，深入分析也证实了其有效性与泛化能力。

> Large Language Models (LLMs) have demonstrated remarkable abilities in general scenarios. Instruction finetuning empowers them to align with humans in various tasks. Nevertheless, the Diversity and Quality of the instruction data remain two main challenges for instruction finetuning. With regard to this, in this paper, we propose a novel gradient-based method to automatically select high-quality and diverse instruction finetuning data for machine translation. Our key innovation centers around analyzing how individual training examples influence the model during training. Specifically, we select training examples that exert beneficial influences on the model as high-quality ones by means of Influence Function plus a small high-quality seed dataset. Moreover, to enhance the diversity of the training data we maximize the variety of influences they have on the model by clustering on their gradients and resampling. Extensive experiments on WMT22 and FLORES translation tasks demonstrate the superiority of our methods, and in-depth analysis further validates their effectiveness and generalization.

[Arxiv](https://arxiv.org/abs/2405.12915)