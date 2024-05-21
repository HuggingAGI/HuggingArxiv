# 再探对抗性提示调优的鲁棒泛化之谜

发布时间：2024年05月17日

`Agent

理由：这篇论文主要关注的是视觉-语言模型（如CLIP）在面对对抗性攻击时的鲁棒性和泛化能力，并提出了一种新的自适应一致性引导的对抗性提示调优框架（CAPT）。这个框架通过优化对抗性示例的特征对齐来提升模型的稳健性，同时保持对干净样本的准确性。这种针对特定模型（如CLIP）的鲁棒性增强方法，以及通过自适应一致性目标函数来确保模型在不同输入下的一致性，更符合Agent类别的定义，即关注模型在特定环境下的行为和性能优化。` `计算机视觉`

> Revisiting the Robust Generalization of Adversarial Prompt Tuning

# 摘要

> 为了确保视觉-语言模型如CLIP在面对对抗性攻击时仍能保持零-shot泛化能力，我们必须深入理解其脆弱性。当前的防御策略多采用提示学习进行对抗性微调，虽提升了鲁棒性，却易导致过拟合，影响模型在不同样本上的泛化能力。为此，我们开发了自适应一致性引导的对抗性提示调优框架（CAPT），通过多模态提示学习优化对抗性示例的特征对齐，并借助CLIP的泛化优势，提升模型在对抗性环境下的稳健性，同时不损及干净样本的准确性。我们设计了一种新的自适应一致性目标函数，确保模型在处理对抗性和非对抗性输入时的一致性。通过在14个数据集和多种数据稀疏性条件下的大量实验，CAPT展现了其在分布内性能和跨数据集泛化方面的卓越表现。

> Understanding the vulnerability of large-scale pre-trained vision-language models like CLIP against adversarial attacks is key to ensuring zero-shot generalization capacity on various downstream tasks. State-of-the-art defense mechanisms generally adopt prompt learning strategies for adversarial fine-tuning to improve the adversarial robustness of the pre-trained model while keeping the efficiency of adapting to downstream tasks. Such a setup leads to the problem of over-fitting which impedes further improvement of the model's generalization capacity on both clean and adversarial examples. In this work, we propose an adaptive Consistency-guided Adversarial Prompt Tuning (i.e., CAPT) framework that utilizes multi-modal prompt learning to enhance the alignment of image and text features for adversarial examples and leverage the strong generalization of pre-trained CLIP to guide the model-enhancing its robust generalization on adversarial examples while maintaining its accuracy on clean ones. We also design a novel adaptive consistency objective function to balance the consistency of adversarial inputs and clean inputs between the fine-tuning model and the pre-trained model. We conduct extensive experiments across 14 datasets and 4 data sparsity schemes (from 1-shot to full training data settings) to show the superiority of CAPT over other state-of-the-art adaption methods. CAPT demonstrated excellent performance in terms of the in-distribution performance and the generalization under input distribution shift and across datasets.

![再探对抗性提示调优的鲁棒泛化之谜](../../../paper_images/2405.11154/model.png)

[Arxiv](https://arxiv.org/abs/2405.11154)