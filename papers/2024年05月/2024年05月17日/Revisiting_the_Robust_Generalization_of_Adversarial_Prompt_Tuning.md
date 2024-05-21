# 再次探讨对抗性提示调优的鲁棒泛化问题

发布时间：2024年05月17日

`Agent

这篇论文主要关注的是视觉-语言模型（如CLIP）在面对对抗性攻击时的鲁棒性和泛化能力。论文提出了一种新的框架——自适应一致性引导的对抗性提示调优（CAPT），旨在通过多模态学习优化图像与文本特征对齐，增强模型在对抗环境下的稳健性，同时保持其在正常数据上的准确性。这种研究属于Agent的范畴，因为它涉及开发和优化模型以应对特定环境（对抗性环境）中的挑战，类似于Agent在特定环境中执行任务和适应环境的能力。此外，论文中的方法和实验设计也体现了对模型在复杂和变化环境中的行为和性能的深入研究，这是Agent研究的核心内容。` `计算机视觉`

> Revisiting the Robust Generalization of Adversarial Prompt Tuning

# 摘要

> 为了确保视觉-语言模型如CLIP在面对对抗性攻击时仍能保持零-shot泛化能力，我们需要深入理解其脆弱性。当前的防御策略通过对抗性微调结合提示学习，虽提升了模型的鲁棒性，但过拟合问题限制了其泛化能力的提升。为此，我们开发了自适应一致性引导的对抗性提示调优（CAPT）框架，通过多模态学习优化对抗性示例的图像与文本特征对齐，并借助CLIP的泛化优势，增强模型在对抗环境下的稳健性，同时不损及其在正常数据上的准确性。我们还创新性地设计了自适应一致性目标函数，以确保模型在处理对抗性与正常输入时的一致性。通过在14个数据集和多种数据稀疏设置下的广泛实验，CAPT展现了其在分布内性能和跨数据集泛化方面的卓越表现。

> Understanding the vulnerability of large-scale pre-trained vision-language models like CLIP against adversarial attacks is key to ensuring zero-shot generalization capacity on various downstream tasks. State-of-the-art defense mechanisms generally adopt prompt learning strategies for adversarial fine-tuning to improve the adversarial robustness of the pre-trained model while keeping the efficiency of adapting to downstream tasks. Such a setup leads to the problem of over-fitting which impedes further improvement of the model's generalization capacity on both clean and adversarial examples. In this work, we propose an adaptive Consistency-guided Adversarial Prompt Tuning (i.e., CAPT) framework that utilizes multi-modal prompt learning to enhance the alignment of image and text features for adversarial examples and leverage the strong generalization of pre-trained CLIP to guide the model-enhancing its robust generalization on adversarial examples while maintaining its accuracy on clean ones. We also design a novel adaptive consistency objective function to balance the consistency of adversarial inputs and clean inputs between the fine-tuning model and the pre-trained model. We conduct extensive experiments across 14 datasets and 4 data sparsity schemes (from 1-shot to full training data settings) to show the superiority of CAPT over other state-of-the-art adaption methods. CAPT demonstrated excellent performance in terms of the in-distribution performance and the generalization under input distribution shift and across datasets.

![再次探讨对抗性提示调优的鲁棒泛化问题](../../../paper_images/2405.11154/model.png)

[Arxiv](https://arxiv.org/abs/2405.11154)