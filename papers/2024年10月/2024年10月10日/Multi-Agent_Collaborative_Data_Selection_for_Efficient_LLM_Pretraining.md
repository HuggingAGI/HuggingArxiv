# 多代理协作数据选择：高效 LLM 预训练的关键

发布时间：2024年10月10日

`Agent` `人工智能` `数据科学`

> Multi-Agent Collaborative Data Selection for Efficient LLM Pretraining

# 摘要

> 加速 LLM 预训练的关键在于高效的数据选择。虽然已有多种方法提升数据效率，但如何调和这些方法间的内在冲突，实现最佳数据选择，仍鲜有研究。为此，我们创新性地提出了多代理协作数据选择机制。在此框架下，每种数据选择方法作为独立代理，并通过代理控制台动态整合信息。实证研究显示，该方法不仅显著提升数据效率，加速训练收敛，还在多项基准测试中超越现有技术，平均性能提升达 10.5%。

> Efficient data selection is crucial to accelerate the pretraining of large language models (LLMs). While various methods have been proposed to enhance data efficiency, limited research has addressed the inherent conflicts between these approaches to achieve optimal data selection for LLM pretraining. To tackle this problem, we propose a novel multi-agent collaborative data selection mechanism. In this framework, each data selection method serves as an independent agent, and an agent console is designed to dynamically integrate the information from all agents throughout the LLM training process. We conduct extensive empirical studies to evaluate our multi-agent framework. The experimental results demonstrate that our approach significantly improves data efficiency, accelerates convergence in LLM training, and achieves an average performance gain of 10.5% across multiple language model benchmarks compared to the state-of-the-art methods.

[Arxiv](https://arxiv.org/abs/2410.08102)