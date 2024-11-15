# PTR：针对大型语言模型的精度驱动型工具推荐

发布时间：2024年11月14日

`LLM应用` `语言模型` `工具推荐`

> PTR: Precision-Driven Tool Recommendation for Large Language Models

# 摘要

> 利用外部工具来增强大型语言模型（LLM），其解决复杂问题的能力得到了显著提升。不过，即便 LLM 的解析能力持续进步，鉴于外部工具数量庞大，在提示中同时纳入所有可用工具仍不现实。所以，从数量和质量两方面考虑，为 LLM 提供一套针对特定任务的精准工具集极为关键。当下的工具检索方法主要是优化工具的排名列表，然后直接把固定数量排名靠前的工具打包成工具集。但这些方法常常无法在执行前为 LLM 配备最优工具集，因为不同任务的最优工具数量各异，从而导致工具冗余或不合适等低效情况，阻碍了对最相关工具的即时获取。本文应对了为 LLM 推荐精准工具集的挑战。我们引入了工具推荐问题，明确了其范畴，并提出了一种新颖的精度驱动工具推荐（PTR）方法。PTR 借助历史工具包的使用情况获取初始的精简工具集，并通过进行工具匹配动态调整工具集，最终实现基于多视图的工具添加。此外，我们还推出了一个新的数据集 RecTools 以及一个指标 TRACC，旨在评估 LLM 工具推荐的效果。我们通过全面实验进一步验证了我们的设计选择，在两个开放基准和我们的 RecTools 数据集上展现出了令人期待的准确性。

> By augmenting Large Language Models (LLMs) with external tools, their capacity to solve complex problems has been significantly enhanced. However, despite ongoing advancements in the parsing capabilities of LLMs, incorporating all available tools simultaneously in the prompt remains impractical due to the vast number of external tools. Consequently, it is essential to provide LLMs with a precise set of tools tailored to the specific task, considering both quantity and quality. Current tool retrieval methods primarily focus on refining the ranking list of tools and directly packaging a fixed number of top-ranked tools as the tool set. However, these approaches often fail to equip LLMs with the optimal set of tools prior to execution, since the optimal number of tools for different tasks could be different, resulting in inefficiencies such as redundant or unsuitable tools, which impede immediate access to the most relevant tools. This paper addresses the challenge of recommending precise toolsets for LLMs. We introduce the problem of tool recommendation, define its scope, and propose a novel Precision-driven Tool Recommendation (PTR) approach. PTR captures an initial, concise set of tools by leveraging historical tool bundle usage and dynamically adjusts the tool set by performing tool matching, culminating in a multi-view-based tool addition. Additionally, we present a new dataset, RecTools, and a metric, TRACC, designed to evaluate the effectiveness of tool recommendation for LLMs. We further validate our design choices through comprehensive experiments, demonstrating promising accuracy across two open benchmarks and our RecTools dataset.

[Arxiv](https://arxiv.org/abs/2411.09613)