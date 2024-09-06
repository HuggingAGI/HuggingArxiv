# ChartMoE：专为高级图表理解设计的专家混合连接器

发布时间：2024年09月05日

`LLM应用` `文档解析` `数据可视化`

> ChartMoE: Mixture of Expert Connector for Advanced Chart Understanding

# 摘要

> 自动图表理解在内容理解和文档解析中至关重要。多模态大型语言模型 (MLLM) 通过特定领域的对齐和微调，在图表理解方面表现出色。然而，图表领域的对齐训练应用仍待深入探索。为此，我们提出 ChartMoE，采用专家混合 (MoE) 架构替代传统线性投影器，以弥合模态差距。我们通过不同对齐任务训练多个线性连接器，作为不同专家的基础初始参数。此外，引入 ChartMoE-Align 数据集，包含超过 90 万张图表-表格-JSON-代码四元组，用于三种对齐任务。结合普通连接器，我们以四种方式初始化专家，并采用高质量知识学习优化 MoE 连接器和 LLM 参数。实验表明，ChartMoE 在 ChartQA 基准测试中将准确率从 80.48% 提升至 84.64%，验证了 MoE 连接器和初始化策略的有效性。

> Automatic chart understanding is crucial for content comprehension and document parsing. Multimodal large language models (MLLMs) have demonstrated remarkable capabilities in chart understanding through domain-specific alignment and fine-tuning. However, the application of alignment training within the chart domain is still underexplored. To address this, we propose ChartMoE, which employs the mixture of expert (MoE) architecture to replace the traditional linear projector to bridge the modality gap. Specifically, we train multiple linear connectors through distinct alignment tasks, which are utilized as the foundational initialization parameters for different experts. Additionally, we introduce ChartMoE-Align, a dataset with over 900K chart-table-JSON-code quadruples to conduct three alignment tasks (chart-table/JSON/code). Combined with the vanilla connector, we initialize different experts in four distinct ways and adopt high-quality knowledge learning to further refine the MoE connector and LLM parameters. Extensive experiments demonstrate the effectiveness of the MoE connector and our initialization strategy, e.g., ChartMoE improves the accuracy of the previous state-of-the-art from 80.48% to 84.64% on the ChartQA benchmark.

[Arxiv](https://arxiv.org/abs/2409.03277)