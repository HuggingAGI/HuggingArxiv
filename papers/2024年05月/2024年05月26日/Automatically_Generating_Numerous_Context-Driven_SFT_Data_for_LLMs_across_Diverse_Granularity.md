# 自动为大型语言模型（LLMs）生成多样粒度下的丰富上下文驱动SFT数据

发布时间：2024年05月26日

`Agent

这篇论文主要讨论了如何从自定义语料库中构建高质量的查询-响应对，这对于开发定制领域AI助手或角色扮演代理等应用至关重要。论文提出的AugCon方法能够自动生成多样性、高质量和高保真度的上下文驱动SFT数据，这对于构建和优化AI代理系统是非常关键的。因此，这篇论文更适合归类到Agent分类中，因为它专注于提高AI代理的性能和适应性。` `人工智能`

> Automatically Generating Numerous Context-Driven SFT Data for LLMs across Diverse Granularity

# 摘要

> 在众多应用中，如定制领域AI助手或角色扮演代理的开发，从自定义语料库中构建高质量的查询-响应对对于监督微调大型语言模型至关重要。然而，人工标注数据的获取成本高昂，且现有自动化方法难以捕捉多样的上下文细节，往往产生同质化数据。为此，我们创新性地提出了AugCon方法，它能自动生成高多样性、高质量和高保真度的上下文驱动SFT数据，覆盖多个粒度级别。AugCon利用Context-Split-Tree（CST）生成查询，并通过对比学习训练评分器，协同优化查询。最后，通过自对齐与自改进的结合，确保了响应的高保真度。我们进行了包括人工和自动评估在内的广泛实验，覆盖了英语和中文中的一个测试场景和四个常用基准。实验结果显示，AugCon在生成高质量、高保真度的SFT数据方面显著优于其他先进方法。所有相关代码、数据集及微调模型将在https://github.com/quanshr/AugCon公开。

> Constructing high-quality query-response pairs from custom corpus is crucial for supervised fine-tuning (SFT) large language models (LLMs) in many applications, like creating domain-specific AI assistants or roleplaying agents. However, sourcing this data through human annotation is costly, and existing automated methods often fail to capture the diverse range of contextual granularity and tend to produce homogeneous data. To tackle these issues, we introduce a novel method named AugCon, capable of automatically generating context-driven SFT data across multiple levels of granularity with high diversity, quality and fidelity. AugCon begins by generating queries using the Context-Split-Tree (CST), an innovative approach for recursively deriving queries and splitting context to cover full granularity. Then, we train a scorer through contrastive learning to collaborate with CST to rank and refine queries. Finally, a synergistic integration of self-alignment and self-improving is introduced to obtain high-fidelity responses.
  Extensive experiments are conducted incorporating both human and automatic evaluations, encompassing a test scenario and four widely-used benchmarks in English and Chinese. The results highlight the significant advantages of AugCon in producing high diversity, quality, and fidelity SFT data against several state-of-the-art methods. All of our code, dataset, and fine-tuned model will be available at: https://github.com/quanshr/AugCon.

[Arxiv](https://arxiv.org/abs/2405.16579)