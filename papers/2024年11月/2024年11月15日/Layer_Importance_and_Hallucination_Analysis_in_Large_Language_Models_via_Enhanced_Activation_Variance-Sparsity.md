# 通过增强激活方差-稀疏性对大型语言模型的层重要性和幻觉进行分析

发布时间：2024年11月15日

`LLM理论` `模型优化`

> Layer Importance and Hallucination Analysis in Large Language Models via Enhanced Activation Variance-Sparsity

# 摘要

> 评估大型语言模型（LLMs）中不同层的重要性，对于优化模型性能和可解释性意义重大。本文率先运用激活方差 - 稀疏度得分（AVSS）来探究层的重要性，此得分融合了归一化的激活方差与稀疏度，以量化每层对整体模型性能的贡献。基于 AVSS 给层排序并剪掉影响最小的 25%，我们在问答、语言建模和情感分类等任务中的实验表明，能保留超 90%的原始性能，凸显出 LLM 架构中潜在的冗余。以 AVSS 为基础，我们提出了一个用于评估各层幻觉倾向的增强版（EAVSS）。这一改进方法引入了幻觉特定激活方差（HSAV）和幻觉特定稀疏度（HSS）指标，能够精准识别易产生幻觉的层。通过在这些层上融入对比学习，我们有效减轻了幻觉的生成，有助于打造更强大、更高效的 LLMs（最大性能提升达 12%）。我们在 NQ、SciQ、TriviaQA、TruthfulQA 和 WikiQA 数据集上的成果，证实了该方法的有效性，为 LLMs 中的层重要性评估和幻觉减轻提供了一个全面的框架。

> Evaluating the importance of different layers in large language models (LLMs) is crucial for optimizing model performance and interpretability. This paper first explores layer importance using the Activation Variance-Sparsity Score (AVSS), which combines normalized activation variance and sparsity to quantify each layer's contribution to overall model performance. By ranking layers based on AVSS and pruning the least impactful 25\%, our experiments on tasks such as question answering, language modeling, and sentiment classification show that over 90\% of the original performance is retained, highlighting potential redundancies in LLM architectures. Building on AVSS, we propose an enhanced version tailored to assess hallucination propensity across layers (EAVSS). This improved approach introduces Hallucination-Specific Activation Variance (HSAV) and Hallucination-Specific Sparsity (HSS) metrics, allowing precise identification of hallucination-prone layers. By incorporating contrastive learning on these layers, we effectively mitigate hallucination generation, contributing to more robust and efficient LLMs(The maximum performance improvement is 12\%). Our results on the NQ, SciQ, TriviaQA, TruthfulQA, and WikiQA datasets demonstrate the efficacy of this method, offering a comprehensive framework for both layer importance evaluation and hallucination mitigation in LLMs.

[Arxiv](https://arxiv.org/abs/2411.10069)