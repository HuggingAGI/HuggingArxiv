# AVSS：通过激活方差-稀疏性分析对大型语言模型中的层重要性进行评估

发布时间：2024年11月04日

`LLM理论` `大型语言模型`

> AVSS: Layer Importance Evaluation in Large Language Models via Activation Variance-Sparsity Analysis

# 摘要

> 深度学习中对层重要性的评估一直是一个活跃的研究领域，对模型优化和可解释性具有重要意义。最近，大型语言模型（LLMs）在各个领域都备受瞩目，但有限的研究探索了 LLMs 中单个层的功能重要性和性能贡献，特别是从激活分布的角度。在这项工作中，我们提出了激活方差 - 稀疏度得分（AVSS），这是一种结合归一化激活方差和稀疏度的新指标，用于评估每一层对模型性能的贡献。通过基于 AVSS 识别和去除大约最低 25％的层，我们在问答、语言建模和情感分类等任务中实现了超过 90％的原始模型性能，这表明这些层可能不是必不可少的。我们的方法为识别不太关键的层提供了一种系统的方法，有助于构建高效的大型语言模型架构。

> The evaluation of layer importance in deep learning has been an active area of research, with significant implications for model optimization and interpretability. Recently, large language models (LLMs) have gained prominence across various domains, yet limited studies have explored the functional importance and performance contributions of individual layers within LLMs, especially from the perspective of activation distribution. In this work, we propose the Activation Variance-Sparsity Score (AVSS), a novel metric combining normalized activation variance and sparsity to assess each layer's contribution to model performance. By identifying and removing approximately the lowest 25% of layers based on AVSS, we achieve over 90% of original model performance across tasks such as question answering, language modeling, and sentiment classification, indicating that these layers may be non-essential. Our approach provides a systematic method for identifying less critical layers, contributing to efficient large language model architectures.

[Arxiv](https://arxiv.org/abs/2411.02117)