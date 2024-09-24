# Flat-LoRA：平坦损失景观上的低秩适应

发布时间：2024年09月22日

`LLM理论` `人工智能` `机器学习`

> Flat-LoRA: Low-Rank Adaption over a Flat Loss Landscape

# 摘要

> 微调大规模预训练模型成本高昂。LoRA 通过优化低秩矩阵，提供了一种高效的微调方法。然而，LoRA 优化空间与全参数空间的关系常被忽视，可能导致泛化性能受损。我们提出 Flat-LoRA，旨在寻找全参数空间平坦区域的低秩适应，通过随机权重扰动和改进的扰动生成策略，保持训练效率并提升性能。实验证明，Flat-LoRA 在自然语言处理和图像分类任务中表现出色。

> Fine-tuning large-scale pre-trained models is prohibitively expensive in terms of computational and memory costs. Low-Rank Adaptation (LoRA), a popular Parameter-Efficient Fine-Tuning (PEFT) method, provides an efficient way to fine-tune models by optimizing only a low-rank matrix. Despite recent progress made in improving LoRA's performance, the connection between the LoRA optimization space and the original full parameter space is often overlooked. A solution that appears flat in the LoRA space may exist sharp directions in the full parameter space, potentially harming generalization performance. In this paper, we propose Flat-LoRA, an efficient approach that seeks a low-rank adaptation located in a flat region of the full parameter space.Instead of relying on the well-established sharpness-aware minimization approach, which can incur significant computational and memory burdens, we utilize random weight perturbation with a Bayesian expectation loss objective to maintain training efficiency and design a refined perturbation generation strategy for improved performance. Experiments on natural language processing and image classification tasks with various architectures demonstrate the effectiveness of our approach.

[Arxiv](https://arxiv.org/abs/2409.14396)