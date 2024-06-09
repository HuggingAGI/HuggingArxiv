# 合成过采样：理论与实践——利用大型语言模型应对数据不平衡挑战

发布时间：2024年06月05日

`LLM应用

这篇论文介绍了一种创新的过采样方法OPAL，该方法利用大型语言模型（LLMs）生成高质量的合成数据，以解决数据不平衡和虚假相关性问题。这种方法特别关注于利用LLMs的能力来生成数据，以改善机器学习和数据科学中的数据分布问题。因此，这篇论文的内容与LLM的应用紧密相关，特别是在解决实际问题（如数据不平衡）方面的应用。` `机器学习` `数据科学`

> Synthetic Oversampling: Theory and A Practical Approach Using LLMs to Address Data Imbalance

# 摘要

> 在机器学习和数据科学领域，数据不平衡和虚假相关性是普遍难题。过采样技术，即通过人工手段增加少数类别的样本数量，已成为解决这些问题的常用策略。本文中，我们提出了OPAL（利用大型语言模型生成人工数据的过采样方法），一种创新的过采样策略，它借助大型语言模型（LLMs）为少数类别生成高质量的合成数据。与近期主要关注预测任务的合成数据生成研究不同，我们的方法专注于解决数据不平衡和虚假相关性问题。更为关键的是，我们提出了一套新理论，严格论证了使用合成数据的优势，并展示了变压器模型在生成标签和协变量高质量合成数据方面的潜力。此外，我们通过一系列详尽的数值实验，验证了我们提出的方法相较于其他代表性解决方案的优越性。

> Imbalanced data and spurious correlations are common challenges in machine learning and data science. Oversampling, which artificially increases the number of instances in the underrepresented classes, has been widely adopted to tackle these challenges. In this article, we introduce OPAL (\textbf{O}versam\textbf{P}ling with \textbf{A}rtificial \textbf{L}LM-generated data), a systematic oversampling approach that leverages the capabilities of large language models (LLMs) to generate high-quality synthetic data for minority groups. Recent studies on synthetic data generation using deep generative models mostly target prediction tasks. Our proposal differs in that we focus on handling imbalanced data and spurious correlations. More importantly, we develop a novel theory that rigorously characterizes the benefits of using the synthetic data, and shows the capacity of transformers in generating high-quality synthetic data for both labels and covariates. We further conduct intensive numerical experiments to demonstrate the efficacy of our proposed approach compared to some representative alternative solutions.

[Arxiv](https://arxiv.org/abs/2406.03628)