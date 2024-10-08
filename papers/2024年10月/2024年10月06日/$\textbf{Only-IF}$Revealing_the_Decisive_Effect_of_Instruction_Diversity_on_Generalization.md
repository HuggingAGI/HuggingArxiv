# $\textbf{仅限IF}$：揭秘指令多样性如何决定泛化效果

发布时间：2024年10月06日

`LLM理论` `人工智能`

> $\textbf{Only-IF}$:Revealing the Decisive Effect of Instruction Diversity on Generalization

# 摘要

> 理解和准确遵循指令对于大型语言模型 (LLM) 在各种任务中有效至关重要。我们通过严格实验发现，模型对未见指令的泛化能力 $\textbf{只有在训练数据在语义领域上足够多样化时才会出现}$。仅在有限领域内多样化无法确保稳健的泛化，而跨领域数据多样化即使在受限的数据预算下也能显著增强模型的适应性。我们还将分析扩展到现实世界场景，包括专家型和通用型模型的微调。结果表明，增加数据集的多样性比单纯增加数据量更能提升性能。我们的研究强调了数据多样化的重要性，并为优化模型性能提供了明确指导。

> Understanding and accurately following instructions is critical for large language models (LLMs) to be effective across diverse tasks. In this work, we rigorously examine the key factors that enable models to generalize to unseen instructions, providing insights to guide the collection of data for instruction-tuning. Through controlled experiments, inspired by the Turing-complete Markov algorithm, we demonstrate that such generalization $\textbf{only emerges}$ when training data is diversified enough across semantic domains. Our findings also reveal that merely diversifying within limited domains fails to ensure robust generalization. In contrast, cross-domain data diversification, even under constrained data budgets, significantly enhances a model's adaptability. We further extend our analysis to real-world scenarios, including fine-tuning of $\textit{$\textbf{specialist}$}$ and $\textit{$\textbf{generalist}$}$ models. In both cases, we demonstrate that 1) better performance can be achieved by increasing the diversity of an established dataset while keeping the data size constant, and 2) when scaling up the data, diversifying the semantics of instructions is more effective than simply increasing the quantity of similar data. Our research provides important insights for dataset collation, particularly when optimizing model performance by expanding training data for both specialist and generalist scenarios. We show that careful consideration of data diversification is key: training specialist models with data extending beyond their core domain leads to significant performance improvements, while generalist models benefit from diverse data mixtures that enhance their overall instruction-following capabilities across a wide range of applications. Our results highlight the critical role of strategic diversification and offer clear guidelines for improving data quality.

[Arxiv](https://arxiv.org/abs/2410.04717)