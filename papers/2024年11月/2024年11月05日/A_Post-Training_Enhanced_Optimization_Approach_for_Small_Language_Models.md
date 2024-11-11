# 一种针对小型语言模型的训练后增强优化方法

发布时间：2024年11月05日

`LLM应用` `语言模型` `模型训练`

> A Post-Training Enhanced Optimization Approach for Small Language Models

# 摘要

> 这篇论文深入研究了小型语言模型的连续后训练优化方法，并为小型语言模型提出了一种连续后训练对齐数据构建方法。该方法的核心基于大型模型的数据指导，优化对齐数据的多样性和准确性。此外，为了验证本文方法的有效性，我们使用 Qwen2-0.5B-Instruct 模型作为小型语言模型的基线模型，利用我们提出的方法构建的对齐数据集，我们训练并比较了几组实验，包括 SFT（监督微调）后训练实验和 KTO（卡尼曼特沃斯基优化）后训练实验，以及 SFT-KTO 两阶段后训练实验和模型权重融合实验。最后，我们评估和分析了后训练模型的性能，并确认我们提出的连续后训练优化方法能够显著提高小型语言模型的性能。

> This paper delves into the continuous post-training optimization methods for small language models, and proposes a continuous post-training alignment data construction method for small language models. The core of this method is based on the data guidance of large models, optimizing the diversity and accuracy of alignment data. In addition, to verify the effectiveness of the methods in this paper, we used Qwen2-0.5B-Instruct model as the baseline model for small language models, using the alignment dataset constructed by our proposed method, we trained and compared several groups of experiments, including SFT (Supervised Fine Tuning) post-training experiment and KTO (Kahneman Tversky optimization) post-training experiment, as well as SFT-KTO two-stage post-training experiment and model weight fusion experiment. Finally, we evaluated and analyzed the performance of post-training models, and confirmed that the continuous post-training optimization method proposed by us can significantly improve the performance of small language models.

[Arxiv](https://arxiv.org/abs/2411.02939)