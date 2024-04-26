# AAPL：为视觉-语言模型引入属性，以增强提示学习的效果。

发布时间：2024年04月25日

`LLM应用` `计算机视觉` `机器学习`

> AAPL: Adding Attributes to Prompt Learning for Vision-Language Models

# 摘要

> 最新进展的大型预训练视觉-语言模型在零样本任务上取得了显著成效。在此基础上，如CoOp和CoCoOp等最新研究提出了提示学习技术，通过将提示中的上下文替换为可训练的向量，显著提升了性能。但对未见类别的识别提升有限，传统零样本学习中常用的数据增强技术也面临挑战。我们的实验揭示了CoOp和CoCoOp的一个问题：传统图像增强所学习的上下文对已知类别存在偏见，这不利于推广到未知类别。为应对这一挑战，我们引入了对抗性标记嵌入技术，以在可学习提示中引入偏差时，将低层次的视觉增强特征与高层次的类别信息解耦。我们提出的新方法“为提示学习添加属性”（AAPL）通过聚焦于未见类别的高层次特征，引导可学习上下文有效提取文本特征。经过11个数据集的实验验证，AAPL在少样本学习、零样本学习、跨数据集和领域泛化等多个任务中均展现出优于现有方法的性能。

> Recent advances in large pre-trained vision-language models have demonstrated remarkable performance on zero-shot downstream tasks. Building upon this, recent studies, such as CoOp and CoCoOp, have proposed the use of prompt learning, where context within a prompt is replaced with learnable vectors, leading to significant improvements over manually crafted prompts. However, the performance improvement for unseen classes is still marginal, and to tackle this problem, data augmentation has been frequently used in traditional zero-shot learning techniques. Through our experiments, we have identified important issues in CoOp and CoCoOp: the context learned through traditional image augmentation is biased toward seen classes, negatively impacting generalization to unseen classes. To address this problem, we propose adversarial token embedding to disentangle low-level visual augmentation features from high-level class information when inducing bias in learnable prompts. Through our novel mechanism called "Adding Attributes to Prompt Learning", AAPL, we guide the learnable context to effectively extract text features by focusing on high-level features for unseen classes. We have conducted experiments across 11 datasets, and overall, AAPL shows favorable performances compared to the existing methods in few-shot learning, zero-shot learning, cross-dataset, and domain generalization tasks.

![AAPL：为视觉-语言模型引入属性，以增强提示学习的效果。](../../../paper_images/2404.16804/x1.png)

![AAPL：为视觉-语言模型引入属性，以增强提示学习的效果。](../../../paper_images/2404.16804/x2.png)

![AAPL：为视觉-语言模型引入属性，以增强提示学习的效果。](../../../paper_images/2404.16804/x3.png)

![AAPL：为视觉-语言模型引入属性，以增强提示学习的效果。](../../../paper_images/2404.16804/x4.png)

![AAPL：为视觉-语言模型引入属性，以增强提示学习的效果。](../../../paper_images/2404.16804/x5.png)

![AAPL：为视觉-语言模型引入属性，以增强提示学习的效果。](../../../paper_images/2404.16804/x6.png)

![AAPL：为视觉-语言模型引入属性，以增强提示学习的效果。](../../../paper_images/2404.16804/x7.png)

[Arxiv](https://arxiv.org/abs/2404.16804)