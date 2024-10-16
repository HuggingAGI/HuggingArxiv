# 联邦指令调优中的数据质量控制：大型语言模型的关键环节

发布时间：2024年10月15日

`LLM应用` `人工智能` `数据隐私`

> Data Quality Control in Federated Instruction-tuning of Large Language Models

# 摘要

> 借助大规模分布式数据，联邦学习 (FL) 能够在保护隐私的前提下，实现大型语言模型 (LLM) 的协作指令调优。尽管 FL 有效扩展了数据量，但当前研究对数据质量的关注仍显不足。为此，我们提出了一个新框架——带有数据质量控制 (FedDQC) 的联邦指令调优，通过测量数据质量来优化过滤和分层训练。我们设计了一种高效指标，用于评估每个客户端的指令-响应对齐 (IRA)，并通过单次推断识别潜在噪声数据。低 IRA 样本被过滤，以减少其负面影响。此外，我们提出了一种质量感知的分层训练方法，LLM 从高 IRA 数据逐步微调至低 IRA 数据，模拟了从易到难的学习过程。实验结果显示，我们的方法在 FL 中显著提升了混合质量数据训练的 LLM 性能。

> By leveraging massively distributed data, federated learning (FL) enables collaborative instruction tuning of large language models (LLMs) in a privacy-preserving way. While FL effectively expands the data quantity, the issue of data quality remains under-explored in the current literature on FL for LLMs. To address this gap, we propose a new framework of federated instruction tuning of LLMs with data quality control (FedDQC), which measures data quality to facilitate the subsequent filtering and hierarchical training processes. Our approach introduces an efficient metric to assess each client's instruction-response alignment (IRA), identifying potentially noisy data through single-shot inference. Low-IRA samples are potentially noisy and filtered to mitigate their negative impacts. To further utilize this IRA value, we propose a quality-aware hierarchical training paradigm, where LLM is progressively fine-tuned from high-IRA to low-IRA data, mirroring the easy-to-hard learning process. We conduct extensive experiments on 4 synthetic and a real-world dataset, and compare our method with baselines adapted from centralized setting. Results show that our method consistently and significantly improves the performance of LLMs trained on mix-quality data in FL.

[Arxiv](https://arxiv.org/abs/2410.11540)