# 通过重要性加权，大型语言模型能够实现自我提升。

发布时间：2024年08月19日

`LLM理论` `人工智能` `机器学习`

> Importance Weighting Can Help Large Language Models Self-Improve

# 摘要

> 大型语言模型 (LLM) 在多任务应用中表现出色，但高质量数据集下的外部监督微调成本高昂。为此，LLM 自我改进方法应运而生，典型方法是在自生成数据上训练 LLM，其中不稳定数据需被过滤。本文提出，过滤高分布偏移的正确样本也能提升改进效果。我们引入 DS 权重指标，结合自一致性全面过滤样本，微调模型。实验表明，仅需小规模有效集计算 DS 权重，即可显著提升 LLM 自我改进的推理能力，性能媲美依赖预训练奖励模型外部监督的方法。

> Large language models (LLMs) have shown remarkable capability in numerous tasks and applications. However, fine-tuning LLMs using high-quality datasets under external supervision remains prohibitively expensive. In response, LLM self-improvement approaches have been vibrantly developed recently. The typical paradigm of LLM self-improvement involves training LLM on self-generated data, part of which may be detrimental and should be filtered out due to the unstable data quality. While current works primarily employs filtering strategies based on answer correctness, in this paper, we demonstrate that filtering out correct but with high distribution shift extent (DSE) samples could also benefit the results of self-improvement. Given that the actual sample distribution is usually inaccessible, we propose a new metric called DS weight to approximate DSE, inspired by the Importance Weighting methods. Consequently, we integrate DS weight with self-consistency to comprehensively filter the self-generated samples and fine-tune the language model. Experiments show that with only a tiny valid set (up to 5\% size of the training set) to compute DS weight, our approach can notably promote the reasoning ability of current LLM self-improvement methods. The resulting performance is on par with methods that rely on external supervision from pre-trained reward models.

[Arxiv](https://arxiv.org/abs/2408.09849)