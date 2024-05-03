# CACTUS：化学智能代理与科学工具的连接平台

发布时间：2024年05月01日

`Agent` `人工智能`

> CACTUS: Chemistry Agent Connecting Tool-Usage to Science

# 摘要

> 大型语言模型（LLMs）在众多领域展现出巨大潜力，但它们往往难以获取和推理特定领域的知识与工具。本文提出了 CACTUS（Chemistry Agent Connecting Tool-Usage to Science），这是一款集成了化学信息学工具的基于 LLM 的智能代理，旨在提升化学和分子探索领域的高级推理与问题解决能力。我们采用了包括 Gemma-7b、Falcon-7b、MPT-7b、Llama2-7b 和 Mistral-7b 在内的多种开源 LLMs，对数千个化学问题进行了基准测试，以评估 CACTUS 的性能。测试结果显示，CACTUS 在性能上显著超越了基础 LLMs，尤其是 Gemma-7b 和 Mistral-7b 模型，在不同提示策略下均达到了最高准确率。此外，我们还研究了领域特定提示和硬件配置对模型性能的影响，突显了提示工程的重要性以及在消费级硬件上部署小型模型的潜力，而不会显著损失准确性。CACTUS 结合了开源 LLMs 的认知能力与领域特定工具，能够助力研究人员在分子属性预测、相似性搜索和药物相似性评估等任务中取得进展。CACTUS 在化学信息学领域是一个重要的里程碑，为化学和分子发现领域的研究者提供了一个灵活的工具。它通过整合开源 LLMs 的优势与领域特定工具，有望推动科学发展，开拓新的研究领域，探索新的、有效的和安全的治疗方案、催化剂和材料。CACTUS 还能够与自动化实验平台整合，并实时做出基于数据的决策，为自动化发现开辟了新的可能性。

> Large language models (LLMs) have shown remarkable potential in various domains, but they often lack the ability to access and reason over domain-specific knowledge and tools. In this paper, we introduced CACTUS (Chemistry Agent Connecting Tool-Usage to Science), an LLM-based agent that integrates cheminformatics tools to enable advanced reasoning and problem-solving in chemistry and molecular discovery. We evaluate the performance of CACTUS using a diverse set of open-source LLMs, including Gemma-7b, Falcon-7b, MPT-7b, Llama2-7b, and Mistral-7b, on a benchmark of thousands of chemistry questions. Our results demonstrate that CACTUS significantly outperforms baseline LLMs, with the Gemma-7b and Mistral-7b models achieving the highest accuracy regardless of the prompting strategy used. Moreover, we explore the impact of domain-specific prompting and hardware configurations on model performance, highlighting the importance of prompt engineering and the potential for deploying smaller models on consumer-grade hardware without significant loss in accuracy. By combining the cognitive capabilities of open-source LLMs with domain-specific tools, CACTUS can assist researchers in tasks such as molecular property prediction, similarity searching, and drug-likeness assessment. Furthermore, CACTUS represents a significant milestone in the field of cheminformatics, offering an adaptable tool for researchers engaged in chemistry and molecular discovery. By integrating the strengths of open-source LLMs with domain-specific tools, CACTUS has the potential to accelerate scientific advancement and unlock new frontiers in the exploration of novel, effective, and safe therapeutic candidates, catalysts, and materials. Moreover, CACTUS's ability to integrate with automated experimentation platforms and make data-driven decisions in real time opens up new possibilities for autonomous discovery.

[Arxiv](https://arxiv.org/abs/2405.00972)