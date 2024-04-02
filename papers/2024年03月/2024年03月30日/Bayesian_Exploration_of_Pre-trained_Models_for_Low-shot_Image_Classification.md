# 通过贝叶斯方法探索预训练模型在低样本图像分类任务中的应用，旨在提高分类准确性和效率。

发布时间：2024年03月30日

`RAG` `计算机视觉` `图像分类`

> Bayesian Exploration of Pre-trained Models for Low-shot Image Classification

# 摘要

> 小样本图像分类是计算机视觉的基础任务，而像CLIP这样的大规模视觉-语言模型为该领域的研究带来了革命性进展。然而，现有基于CLIP的方法往往缺乏整合其他预训练模型的独特知识的能力。为了解决这一问题，本研究提出了一种基于高斯过程的新颖概率模型集成框架，它在处理小规模数据时表现出色。通过将CLIP用于均值函数，并将不同预训练模型构建的深度核集合用于核函数，我们成功整合了先验知识。该框架通过直接对分类标签进行回归，实现了直观的推断、不确定性的量化和超参数的合理调整。经过一系列标准的基准测试，我们的方法在预测性能上始终超越了现有的集成方法。我们还检验了该方法在非标准数据集上的鲁棒性及其不确定性估计的质量，结果表明，即便依赖于标签回归，我们的方法在模型校准方面依然优于大多数确定性基线。

> Low-shot image classification is a fundamental task in computer vision, and the emergence of large-scale vision-language models such as CLIP has greatly advanced the forefront of research in this field. However, most existing CLIP-based methods lack the flexibility to effectively incorporate other pre-trained models that encompass knowledge distinct from CLIP. To bridge the gap, this work proposes a simple and effective probabilistic model ensemble framework based on Gaussian processes, which have previously demonstrated remarkable efficacy in processing small data. We achieve the integration of prior knowledge by specifying the mean function with CLIP and the kernel function with an ensemble of deep kernels built upon various pre-trained models. By regressing the classification label directly, our framework enables analytical inference, straightforward uncertainty quantification, and principled hyper-parameter tuning. Through extensive experiments on standard benchmarks, we demonstrate that our method consistently outperforms competitive ensemble baselines regarding predictive performance. Additionally, we assess the robustness of our method and the quality of the yielded uncertainty estimates on out-of-distribution datasets. We also illustrate that our method, despite relying on label regression, still enjoys superior model calibration compared to most deterministic baselines.

![通过贝叶斯方法探索预训练模型在低样本图像分类任务中的应用，旨在提高分类准确性和效率。](../../../paper_images/2404.00312/x1.png)

![通过贝叶斯方法探索预训练模型在低样本图像分类任务中的应用，旨在提高分类准确性和效率。](../../../paper_images/2404.00312/x2.png)

![通过贝叶斯方法探索预训练模型在低样本图像分类任务中的应用，旨在提高分类准确性和效率。](../../../paper_images/2404.00312/x3.png)

![通过贝叶斯方法探索预训练模型在低样本图像分类任务中的应用，旨在提高分类准确性和效率。](../../../paper_images/2404.00312/x4.png)

![通过贝叶斯方法探索预训练模型在低样本图像分类任务中的应用，旨在提高分类准确性和效率。](../../../paper_images/2404.00312/x5.png)

![通过贝叶斯方法探索预训练模型在低样本图像分类任务中的应用，旨在提高分类准确性和效率。](../../../paper_images/2404.00312/x6.png)

![通过贝叶斯方法探索预训练模型在低样本图像分类任务中的应用，旨在提高分类准确性和效率。](../../../paper_images/2404.00312/x7.png)

![通过贝叶斯方法探索预训练模型在低样本图像分类任务中的应用，旨在提高分类准确性和效率。](../../../paper_images/2404.00312/x8.png)

![通过贝叶斯方法探索预训练模型在低样本图像分类任务中的应用，旨在提高分类准确性和效率。](../../../paper_images/2404.00312/x9.png)

![通过贝叶斯方法探索预训练模型在低样本图像分类任务中的应用，旨在提高分类准确性和效率。](../../../paper_images/2404.00312/x10.png)

![通过贝叶斯方法探索预训练模型在低样本图像分类任务中的应用，旨在提高分类准确性和效率。](../../../paper_images/2404.00312/x11.png)

![通过贝叶斯方法探索预训练模型在低样本图像分类任务中的应用，旨在提高分类准确性和效率。](../../../paper_images/2404.00312/x12.png)

![通过贝叶斯方法探索预训练模型在低样本图像分类任务中的应用，旨在提高分类准确性和效率。](../../../paper_images/2404.00312/x13.png)

![通过贝叶斯方法探索预训练模型在低样本图像分类任务中的应用，旨在提高分类准确性和效率。](../../../paper_images/2404.00312/x14.png)

![通过贝叶斯方法探索预训练模型在低样本图像分类任务中的应用，旨在提高分类准确性和效率。](../../../paper_images/2404.00312/x15.png)

![通过贝叶斯方法探索预训练模型在低样本图像分类任务中的应用，旨在提高分类准确性和效率。](../../../paper_images/2404.00312/x16.png)

![通过贝叶斯方法探索预训练模型在低样本图像分类任务中的应用，旨在提高分类准确性和效率。](../../../paper_images/2404.00312/x17.png)

![通过贝叶斯方法探索预训练模型在低样本图像分类任务中的应用，旨在提高分类准确性和效率。](../../../paper_images/2404.00312/x18.png)

![通过贝叶斯方法探索预训练模型在低样本图像分类任务中的应用，旨在提高分类准确性和效率。](../../../paper_images/2404.00312/x19.png)

![通过贝叶斯方法探索预训练模型在低样本图像分类任务中的应用，旨在提高分类准确性和效率。](../../../paper_images/2404.00312/x20.png)

![通过贝叶斯方法探索预训练模型在低样本图像分类任务中的应用，旨在提高分类准确性和效率。](../../../paper_images/2404.00312/x21.png)

![通过贝叶斯方法探索预训练模型在低样本图像分类任务中的应用，旨在提高分类准确性和效率。](../../../paper_images/2404.00312/x22.png)

![通过贝叶斯方法探索预训练模型在低样本图像分类任务中的应用，旨在提高分类准确性和效率。](../../../paper_images/2404.00312/x23.png)

![通过贝叶斯方法探索预训练模型在低样本图像分类任务中的应用，旨在提高分类准确性和效率。](../../../paper_images/2404.00312/x24.png)

![通过贝叶斯方法探索预训练模型在低样本图像分类任务中的应用，旨在提高分类准确性和效率。](../../../paper_images/2404.00312/x25.png)

![通过贝叶斯方法探索预训练模型在低样本图像分类任务中的应用，旨在提高分类准确性和效率。](../../../paper_images/2404.00312/x26.png)

![通过贝叶斯方法探索预训练模型在低样本图像分类任务中的应用，旨在提高分类准确性和效率。](../../../paper_images/2404.00312/x27.png)

![通过贝叶斯方法探索预训练模型在低样本图像分类任务中的应用，旨在提高分类准确性和效率。](../../../paper_images/2404.00312/x28.png)

[Arxiv](https://arxiv.org/abs/2404.00312)