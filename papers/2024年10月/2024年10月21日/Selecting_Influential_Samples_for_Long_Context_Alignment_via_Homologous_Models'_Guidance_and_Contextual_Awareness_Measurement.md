# 借助同源模型的引导和上下文感知评估，精选长上下文对齐的关键样本。

发布时间：2024年10月21日

`LLM理论` `人工智能`

> Selecting Influential Samples for Long Context Alignment via Homologous Models' Guidance and Contextual Awareness Measurement

# 摘要

> 大型语言模型在处理极长上下文指令方面的能力尚未完全探索。核心难题在于构建一个高质量的长上下文对齐指令数据集。现有研究尝试通过合成长指令样本来扩充数据量，但缺乏明确的质量策略可能导致低质量样本，限制最终性能。为此，我们聚焦于长上下文对齐的挑战，提出GATEAU框架，通过同源模型引导（HMG）和上下文感知测量（CAM）识别高影响力样本。HMG利用困惑度分数评估长程依赖下的响应难度，CAM则通过注意力集中度评估长输入的理解难度。基于此，我们精选最具挑战性的样本，有效构建长程依赖，提升LLM性能。实验证明，GATEAU能精准识别长程依赖样本，训练后的模型在指令遵循和长上下文理解上表现更佳。

> The expansion of large language models to effectively handle instructions with extremely long contexts has yet to be fully investigated. The primary obstacle lies in constructing a high-quality long instruction-following dataset devised for long context alignment. Existing studies have attempted to scale up the available data volume by synthesizing long instruction-following samples. However, indiscriminately increasing the quantity of data without a well-defined strategy for ensuring data quality may introduce low-quality samples and restrict the final performance. To bridge this gap, we aim to address the unique challenge of long-context alignment, i.e., modeling the long-range dependencies for handling instructions and lengthy input contexts. We propose GATEAU, a novel framework designed to identify the influential and high-quality samples enriched with long-range dependency relations by utilizing crafted Homologous Models' Guidance (HMG) and Contextual Awareness Measurement (CAM). Specifically, HMG attempts to measure the difficulty of generating corresponding responses due to the long-range dependencies, using the perplexity scores of the response from two homologous models with different context windows. Also, the role of CAM is to measure the difficulty of understanding the long input contexts due to long-range dependencies by evaluating whether the model's attention is focused on important segments. Built upon both proposed methods, we select the most challenging samples as the influential data to effectively frame the long-range dependencies, thereby achieving better performance of LLMs. Comprehensive experiments indicate that GATEAU effectively identifies samples enriched with long-range dependency relations and the model trained on these selected samples exhibits better instruction-following and long-context understanding capabilities.

[Arxiv](https://arxiv.org/abs/2410.15633)