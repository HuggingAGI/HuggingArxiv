# 自动为LLMs生成多样粒度下的丰富上下文驱动SFT数据

发布时间：2024年05月26日

`Agent

理由：这篇论文主要关注的是如何从自定义语料库中构建高质量的查询-响应对，以用于监督微调大型语言模型，特别是在开发定制领域AI助手或角色扮演代理的应用中。提出的AugCon方法旨在自动生成多粒度、高质高保真的上下文驱动SFT数据，这对于构建和优化AI代理的行为和响应至关重要。因此，这篇论文更符合Agent分类，因为它专注于提高AI代理的性能和适应性。` `人工智能`

> Automatically Generating Numerous Context-Driven SFT Data for LLMs across Diverse Granularity

# 摘要

> 在众多应用中，如定制领域AI助手或角色扮演代理的开发，从自定义语料库中构建高质量的查询-响应对对于监督微调大型语言模型至关重要。然而，人工标注数据的获取成本高昂，且现有自动化方法难以捕捉上下文的多样性，导致数据同质化。为此，我们创新性地提出了AugCon方法，它能自动生成多粒度、高质高保真的上下文驱动SFT数据。AugCon利用Context-Split-Tree（CST）生成查询，并通过对比学习训练评分器，与CST协同优化查询。最后，通过自对齐与自改进的结合，确保了响应的高保真度。实验涵盖了人工与自动评估，包括一个测试场景和英汉四个常用基准，结果显示AugCon在生成多样化、高质量、高保真SFT数据方面显著优于现有技术。所有相关代码、数据集及微调模型将公开于：https://github.com/quanshr/AugCon。

> Constructing high-quality query-response pairs from custom corpus is crucial for supervised fine-tuning (SFT) large language models (LLMs) in many applications, like creating domain-specific AI assistants or roleplaying agents. However, sourcing this data through human annotation is costly, and existing automated methods often fail to capture the diverse range of contextual granularity and tend to produce homogeneous data. To tackle these issues, we introduce a novel method named AugCon, capable of automatically generating context-driven SFT data across multiple levels of granularity with high diversity, quality and fidelity. AugCon begins by generating queries using the Context-Split-Tree (CST), an innovative approach for recursively deriving queries and splitting context to cover full granularity. Then, we train a scorer through contrastive learning to collaborate with CST to rank and refine queries. Finally, a synergistic integration of self-alignment and self-improving is introduced to obtain high-fidelity responses.
  Extensive experiments are conducted incorporating both human and automatic evaluations, encompassing a test scenario and four widely-used benchmarks in English and Chinese. The results highlight the significant advantages of AugCon in producing high diversity, quality, and fidelity SFT data against several state-of-the-art methods. All of our code, dataset, and fine-tuned model will be available at: https://github.com/quanshr/AugCon.

[Arxiv](https://arxiv.org/abs/2405.16579)