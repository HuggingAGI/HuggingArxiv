# LLM4GRN：利用 LLM 探索因果基因调控网络，并通过合成数据生成进行评估。

发布时间：2024年10月21日

`LLM应用` `生物医学` `基因组学`

> LLM4GRN: Discovering Causal Gene Regulatory Networks with LLMs -- Evaluation through Synthetic Data Generation

# 摘要

> 基因调控网络 (GRN) 揭示了转录因子与单细胞 RNA 测序数据中目标基因的因果关系，这对解码疾病机制和发现治疗靶点至关重要。我们探索了大型语言模型 (LLM) 在 GRN 发现中的潜力，利用其生物学知识，或结合传统统计方法。为应对缺乏真实因果图的挑战，我们设计了基于任务的评估策略。具体而言，我们用 LLM 建议的 GRN 生成合成数据，并将其与原始数据对比。统计与生物学评估显示，LLM 能有效支持生物研究的统计建模与数据合成。

> Gene regulatory networks (GRNs) represent the causal relationships between transcription factors (TFs) and target genes in single-cell RNA sequencing (scRNA-seq) data. Understanding these networks is crucial for uncovering disease mechanisms and identifying therapeutic targets. In this work, we investigate the potential of large language models (LLMs) for GRN discovery, leveraging their learned biological knowledge alone or in combination with traditional statistical methods. We develop a task-based evaluation strategy to address the challenge of unavailable ground truth causal graphs. Specifically, we use the GRNs suggested by LLMs to guide causal synthetic data generation and compare the resulting data against the original dataset. Our statistical and biological assessments show that LLMs can support statistical modeling and data synthesis for biological research.

[Arxiv](https://arxiv.org/abs/2410.15828)