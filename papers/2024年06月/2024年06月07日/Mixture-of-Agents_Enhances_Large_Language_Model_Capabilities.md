# 混合代理技术提升了大型语言模型的性能

发布时间：2024年06月07日

`Agent` `人工智能`

> Mixture-of-Agents Enhances Large Language Model Capabilities

# 摘要

> 摘要：随着大型语言模型 (LLM) 在自然语言处理领域的飞速发展，如何整合多模型的集体智慧成为研究热点。我们创新性地采用 Mixture-of-Agents (MoA) 策略，构建了一个多层代理架构，每一层代理相互协作，以前一层的输出为线索，共同提升响应质量。这一方法在 AlpacaEval 2.0、MT-Bench 和 FLASK 等评测中大放异彩，超越了 GPT-4 Omni。特别值得一提的是，仅基于开源 LLM 的 MoA 模型在 AlpacaEval 2.0 中以 65.1% 的高分领跑，显著领先于 GPT-4 Omni 的 57.5%。

> 
Abstract:Recent advances in large language models (LLMs) demonstrate substantial capabilities in natural language understanding and generation tasks. With the growing number of LLMs, how to harness the collective expertise of multiple LLMs is an exciting open direction. Toward this goal, we propose a new approach that leverages the collective strengths of multiple LLMs through a Mixture-of-Agents (MoA) methodology. In our approach, we construct a layered MoA architecture wherein each layer comprises multiple LLM agents. Each agent takes all the outputs from agents in the previous layer as auxiliary information in generating its response. MoA models achieves state-of-art performance on AlpacaEval 2.0, MT-Bench and FLASK, surpassing GPT-4 Omni. For example, our MoA using only open-source LLMs is the leader of AlpacaEval 2.0 by a substantial gap, achieving a score of 65.1% compared to 57.5% by GPT-4 Omni.
    

![混合代理技术提升了大型语言模型的性能](../../../paper_images/2406.04692/x1.png)

![混合代理技术提升了大型语言模型的性能](../../../paper_images/2406.04692/x2.png)

![混合代理技术提升了大型语言模型的性能](../../../paper_images/2406.04692/x3.png)

![混合代理技术提升了大型语言模型的性能](../../../paper_images/2406.04692/x4.png)

![混合代理技术提升了大型语言模型的性能](../../../paper_images/2406.04692/x5.png)

![混合代理技术提升了大型语言模型的性能](../../../paper_images/2406.04692/x6.png)

![混合代理技术提升了大型语言模型的性能](../../../paper_images/2406.04692/x7.png)

![混合代理技术提升了大型语言模型的性能](../../../paper_images/2406.04692/x8.png)

![混合代理技术提升了大型语言模型的性能](../../../paper_images/2406.04692/x9.png)

[Arxiv](https://arxiv.org//pdf/2406.04692)