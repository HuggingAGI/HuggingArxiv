# FedDTPT：用于黑箱大型语言模型的联邦式离散且可转移的提示调优

发布时间：2024年11月01日

`LLM应用` `联邦学习`

> FedDTPT: Federated Discrete and Transferable Prompt Tuning for Black-Box Large Language Models

# 摘要

> 近年来，大型语言模型（LLMs）显著推动了自然语言处理（NLP）领域的进步。利用特定场景的数据对 LLMs 进行微调，能让这些基础模型更出色地适应各类下游任务。但微调过程存在隐私泄露风险，在集中式数据处理场景中尤甚。为消除用户的隐私顾虑，引入了联邦学习（FL）来降低从多源集中收集数据带来的风险。然而，LLMs 自身的隐私也极为关键，潜在的恶意攻击威胁着其安全性，这在当前研究中关注度有限。所以，构建一个可信的多方模型微调环境必不可少。另外，大型 LLMs 的本地部署会带来巨大的存储成本和高额的计算需求。为应对这些难题，我们首次提出针对黑箱大型语言模型的联邦离散和可转移提示调整，即 FedDTPT。在客户端优化阶段，我们采用基于令牌级别的离散提示优化方法，借助基于预测准确率的反馈回路，通过 MLM API 实现无梯度的提示优化。在服务器优化方面，我们运用基于语义相似度的注意力机制来筛选所有本地提示令牌，同时结合嵌入距离肘部检测和 DBSCAN 聚类策略来强化筛选过程。实验结果显示，与前沿方法相比，我们的方法在黑箱环境中准确率更高、通信开销更低，且对非独立同分布数据具有更强的稳健性。而且，优化后的提示具有可转移性。

> In recent years, large language models (LLMs) have significantly advanced the field of natural language processing (NLP). By fine-tuning LLMs with data from specific scenarios, these foundation models can better adapt to various downstream tasks. However, the fine-tuning process poses privacy leakage risks, particularly in centralized data processing scenarios. To address user privacy concerns, federated learning (FL) has been introduced to mitigate the risks associated with centralized data collection from multiple sources. Nevertheless, the privacy of LLMs themselves is equally critical, as potential malicious attacks challenge their security, an issue that has received limited attention in current research. Consequently, establishing a trusted multi-party model fine-tuning environment is essential. Additionally, the local deployment of large LLMs incurs significant storage costs and high computational demands. To address these challenges, we propose for the first time a federated discrete and transferable prompt tuning, namely FedDTPT, for black-box large language models. In the client optimization phase, we adopt a token-level discrete prompt optimization method that leverages a feedback loop based on prediction accuracy to drive gradient-free prompt optimization through the MLM API. For server optimization, we employ an attention mechanism based on semantic similarity to filter all local prompt tokens, along with an embedding distance elbow detection and DBSCAN clustering strategy to enhance the filtering process. Experimental results demonstrate that, compared to state-of-the-art methods, our approach achieves higher accuracy, reduced communication overhead, and robustness to non-iid data in a black-box setting. Moreover, the optimized prompts are transferable.

[Arxiv](https://arxiv.org/abs/2411.00985)