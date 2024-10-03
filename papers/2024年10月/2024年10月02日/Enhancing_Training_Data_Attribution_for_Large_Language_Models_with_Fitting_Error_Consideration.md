# 考虑拟合误差，提升大型语言模型的训练数据归属

发布时间：2024年10月02日

`LLM理论` `数据安全` `人工智能`

> Enhancing Training Data Attribution for Large Language Models with Fitting Error Consideration

# 摘要

> 大型语言模型 (LLM) 的黑箱特性使得解释结果变得困难，进而影响了数据知识产权保护和幻觉追踪等问题。训练数据归因 (TDA) 方法被视为解决这些问题的有效手段。然而，现有的 TDA 方法依赖于影响函数，并假设模型达到了最小化的经验风险，这在实际中难以实现，且模型训练中的拟合误差可能影响来源的准确性。为此，我们提出了一种名为 Debias and Denoise Attribution (DDA) 的新方法，通过解决拟合误差来增强影响函数。具体而言，去偏策略通过消除基础模型中的知识偏差来提升影响函数的性能，而去噪策略则通过平滑技术减少训练过程中不同程度的拟合引起的影响分数差异。实验结果显示，我们的方法在平均 AUC 上达到了 91.64%，显著优于现有方法。此外，DDA 在不同来源和规模的模型（如 LLaMA2、QWEN2 和 Mistral）上展现出强大的通用性和可扩展性。

> The black-box nature of large language models (LLMs) poses challenges in interpreting results, impacting issues such as data intellectual property protection and hallucination tracing. Training data attribution (TDA) methods are considered effective solutions to address these challenges. Most recent TDA methods rely on influence functions, assuming the model achieves minimized empirical risk. However, achieving this criterion is difficult, and sourcing accuracy can be compromised by fitting errors during model training. In this paper, we introduce a novel TDA method called Debias and Denoise Attribution (DDA), which enhances influence functions by addressing fitting errors. Specifically, the debias strategy seeks to improve the performance of influence functions by eliminating the knowledge bias present in the base model before fine-tuning, while the denoise strategy aims to reduce discrepancies in influence scores arising from varying degrees of fitting during the training process through smoothing techniques. Experimental results demonstrate that our method significantly outperforms existing approaches, achieving an averaged AUC of 91.64%. Moreover, DDA exhibits strong generality and scalability across various sources and different-scale models like LLaMA2, QWEN2, and Mistral.

[Arxiv](https://arxiv.org/abs/2410.01285)