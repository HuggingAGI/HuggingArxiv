# 跨越语言界限：大规模实施跨语言持续预训练

发布时间：2024年07月02日

`LLM理论` `人工智能` `计算机科学`

> Breaking Language Barriers: Cross-Lingual Continual Pre-Training at Scale

# 摘要

> 近年来，大型语言模型（LLM）在迈向人工通用智能方面取得了显著进展。然而，从头开始训练这些模型需要庞大的计算资源和海量文本数据。本文探索了一种替代方法：通过从现有预训练 LLM 中不断预训练（CPT）来构建新语言的 LLM，而非使用随机初始化参数。通过在 40 种不同模型大小（从 40M 到 5B 参数）上的并行实验，我们发现：1) CPT 收敛更快，并以可扩展方式节省大量资源；2) CPT 遵循 Hoffmann 等人（2022）提出的扩展缩放定律，包含联合数据-参数缩放项；3) 根据我们估计的缩放因子，CPT 的计算最优数据-参数分配显著不同；4) 大规模迁移的有效性受训练持续时间和语言特性影响，而对数据重放具有鲁棒性，这是一种有效缓解 CPT 中灾难性遗忘的方法。我们希望这些发现能为研究社区提供关于大规模 LLM 可迁移性的更深入见解。

> In recent years, Large Language Models (LLMs) have made significant strides towards Artificial General Intelligence. However, training these models from scratch requires substantial computational resources and vast amounts of text data. In this paper, we explore an alternative approach to constructing an LLM for a new language by continually pretraining (CPT) from existing pretrained LLMs, instead of using randomly initialized parameters. Based on parallel experiments on 40 model sizes ranging from 40M to 5B parameters, we find that 1) CPT converges faster and saves significant resources in a scalable manner; 2) CPT adheres to an extended scaling law derived from Hoffmann et al. (2022) with a joint data-parameter scaling term; 3) The compute-optimal data-parameter allocation for CPT markedly differs based on our estimated scaling factors; 4) The effectiveness of transfer at scale is influenced by training duration and linguistic properties, while robust to data replaying, a method that effectively mitigates catastrophic forgetting in CPT. We hope our findings provide deeper insights into the transferability of LLMs at scale for the research community.

[Arxiv](https://arxiv.org/abs/2407.02118)