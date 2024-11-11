# DiffLM：通过扩散语言模型实现可控的合成数据生成

发布时间：2024年11月05日

`LLM应用` `数据合成` `结构化数据`

> DiffLM: Controllable Synthetic Data Generation via Diffusion Language Models

# 摘要

> 大型语言模型（LLMs）的最新进展显著增强了它们的知识和生成能力，导致利用 LLMs 进行高质量数据合成的兴趣激增。然而，通过提示 LLMs 进行合成数据生成仍然具有挑战性，因为 LLMs 对目标数据分布的理解有限以及提示工程的复杂性，特别是对于结构化格式的数据。为了解决这些问题，我们引入了 DiffLM，这是一个基于变分自编码器（VAE）的可控数据合成框架，它进一步（1）利用扩散模型在学习到的潜在分布中保留更多原始分布和格式结构的信息，（2）通过即插即用的潜在特征注入模块将目标分布知识的学习与 LLM 的生成目标解耦。由于我们观察到 VAE 的潜在表示与真实数据分布之间存在显著差异，因此将潜在扩散模块引入我们的框架以学习完全表达性的潜在分布。对具有结构化格式数据（即表格、代码和工具数据）的七个真实世界数据集的评估表明，DiffLM 生成高质量的数据，在某些情况下，下游任务的性能超过真实数据 2 - 7％。数据和代码在内部审查完成后将公开可用。

> Recent advancements in large language models (LLMs) have significantly enhanced their knowledge and generative capabilities, leading to a surge of interest in leveraging LLMs for high-quality data synthesis. However, synthetic data generation via prompting LLMs remains challenging due to LLMs' limited understanding of target data distributions and the complexity of prompt engineering, especially for structured formatted data. To address these issues, we introduce DiffLM, a controllable data synthesis framework based on variational autoencoder (VAE), which further (1) leverages diffusion models to reserve more information of original distribution and format structure in the learned latent distribution and (2) decouples the learning of target distribution knowledge from the LLM's generative objectives via a plug-and-play latent feature injection module. As we observed significant discrepancies between the VAE's latent representations and the real data distribution, the latent diffusion module is introduced into our framework to learn a fully expressive latent distribution. Evaluations on seven real-world datasets with structured formatted data (i.e., Tabular, Code and Tool data) demonstrate that DiffLM generates high-quality data, with performance on downstream tasks surpassing that of real data by 2-7 percent in certain cases. The data and code will be publicly available upon completion of internal review.

[Arxiv](https://arxiv.org/abs/2411.03250)