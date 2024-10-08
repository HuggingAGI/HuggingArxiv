# MINER：探索多模态大型语言模型中特定模态神经元的深层模式

发布时间：2024年10月07日

`LLM理论` `人工智能` `多模态分析`

> MINER: Mining the Underlying Pattern of Modality-Specific Neurons in Multimodal Large Language Models

# 摘要

> 近年来，多模态大型语言模型（MLLM）在整合多种模态方面取得了显著进展，但缺乏可解释性仍是其在需要决策透明度的场景中应用的主要障碍。当前的神经元级解释方法主要集中在知识定位或特定语言和领域的分析上，对多模态的探索仍显不足。为此，我们提出了MINER框架，用于挖掘MLLM中的模态特定神经元（MSN），涵盖模态分离、重要性分数计算、分数聚合和神经元选择四个阶段。实验结果显示，停用仅2%的MSN即可显著降低MLLM性能，不同模态在较低层收敛，MSN影响多模态关键信息的最终收敛，并揭示了语义探针和语义端粒两个值得深入研究的现象。源代码已公开。

> In recent years, multimodal large language models (MLLMs) have significantly advanced, integrating more modalities into diverse applications. However, the lack of explainability remains a major barrier to their use in scenarios requiring decision transparency. Current neuron-level explanation paradigms mainly focus on knowledge localization or language- and domain-specific analyses, leaving the exploration of multimodality largely unaddressed. To tackle these challenges, we propose MINER, a transferable framework for mining modality-specific neurons (MSNs) in MLLMs, which comprises four stages: (1) modality separation, (2) importance score calculation, (3) importance score aggregation, (4) modality-specific neuron selection. Extensive experiments across six benchmarks and two representative MLLMs show that (I) deactivating ONLY 2% of MSNs significantly reduces MLLMs performance (0.56 to 0.24 for Qwen2-VL, 0.69 to 0.31 for Qwen2-Audio), (II) different modalities mainly converge in the lower layers, (III) MSNs influence how key information from various modalities converges to the last token, (IV) two intriguing phenomena worth further investigation, i.e., semantic probing and semantic telomeres. The source code is available at this URL.

[Arxiv](https://arxiv.org/abs/2410.04819)