# 本研究旨在探索如何通过整合用户检索信息，优化大型语言模型在跨领域序列推荐中的表现。

发布时间：2024年06月05日

`LLM应用

这篇论文主要探讨了如何将大型语言模型（LLM）应用于跨域序列推荐（CDSR）中，以解决冷启动问题并提升推荐系统的性能。论文提出了URLLM框架，该框架通过用户检索方法和LLM的域接地技术，实现了信息的无缝整合和特定域内容的生成。这一应用展示了LLM在推荐系统领域的实际应用价值，因此归类为LLM应用。` `电子商务` `推荐系统`

> Exploring User Retrieval Integration towards Large Language Models for Cross-Domain Sequential Recommendation

# 摘要

> 跨域序列推荐（CDSR）致力于挖掘并转移用户在不同领域的序列偏好，以解决冷启动难题。传统模型虽通过用户和项目建模捕捉协同信息，却忽视了宝贵的语义信息。大型语言模型（LLM）的强大语义推理能力启发了我们，将其引入以更精准地捕捉语义信息。然而，将LLM融入CDSR面临两大挑战：信息的无缝整合与特定域内容的生成。为此，我们创新性地提出了URLLM框架，旨在通过用户检索方法与LLM的域接地技术，提升CDSR的性能。我们首先设计了一种双图序列模型，捕捉多元信息，并运用对齐与对比学习促进域间知识迁移。接着，通过用户检索生成模型，将结构信息与LLM无缝融合，充分发挥其推理潜能。此外，我们还开发了特定域策略与细化模块，以防止域外内容生成。在亚马逊平台上的大量实验验证了URLLM在信息整合与特定域生成方面的优越性，超越了现有基准。项目代码已公开于https://github.com/TingJShen/URLLM。

> Cross-Domain Sequential Recommendation (CDSR) aims to mine and transfer users' sequential preferences across different domains to alleviate the long-standing cold-start issue. Traditional CDSR models capture collaborative information through user and item modeling while overlooking valuable semantic information. Recently, Large Language Model (LLM) has demonstrated powerful semantic reasoning capabilities, motivating us to introduce them to better capture semantic information. However, introducing LLMs to CDSR is non-trivial due to two crucial issues: seamless information integration and domain-specific generation. To this end, we propose a novel framework named URLLM, which aims to improve the CDSR performance by exploring the User Retrieval approach and domain grounding on LLM simultaneously. Specifically, we first present a novel dual-graph sequential model to capture the diverse information, along with an alignment and contrastive learning method to facilitate domain knowledge transfer. Subsequently, a user retrieve-generation model is adopted to seamlessly integrate the structural information into LLM, fully harnessing its emergent inferencing ability. Furthermore, we propose a domain-specific strategy and a refinement module to prevent out-of-domain generation. Extensive experiments on Amazon demonstrated the information integration and domain-specific generation ability of URLLM in comparison to state-of-the-art baselines. Our code is available at https://github.com/TingJShen/URLLM

![本研究旨在探索如何通过整合用户检索信息，优化大型语言模型在跨领域序列推荐中的表现。](../../../paper_images/2406.03085/x1.png)

![本研究旨在探索如何通过整合用户检索信息，优化大型语言模型在跨领域序列推荐中的表现。](../../../paper_images/2406.03085/x2.png)

![本研究旨在探索如何通过整合用户检索信息，优化大型语言模型在跨领域序列推荐中的表现。](../../../paper_images/2406.03085/x3.png)

![本研究旨在探索如何通过整合用户检索信息，优化大型语言模型在跨领域序列推荐中的表现。](../../../paper_images/2406.03085/x4.png)

![本研究旨在探索如何通过整合用户检索信息，优化大型语言模型在跨领域序列推荐中的表现。](../../../paper_images/2406.03085/x5.png)

[Arxiv](https://arxiv.org/abs/2406.03085)