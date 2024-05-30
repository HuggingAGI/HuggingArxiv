# CtrlA：利用探针引导控制实现自适应检索增强生成

发布时间：2024年05月28日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）框架的改进，特别是通过引入新的探针引导的自适应RAG框架CtrlA来优化大型语言模型（LLMs）的性能和可靠性。论文的核心贡献在于提出了一种新的方法来动态评估和优化LLMs中的检索需求，这是RAG技术的一个关键方面。因此，这篇论文属于RAG分类。` `知识检索`

> CtrlA: Adaptive Retrieval-Augmented Generation via Probe-Guided Control

# 摘要

> 检索增强生成（RAG）作为一种解决方案，有效缓解了大型语言模型（LLMs）中的幻觉问题，通过引入外部知识检索。自适应RAG通过动态评估检索需求，优化了外部与内部知识的平衡。然而，现有方法多依赖于LLMs的表面反馈或概率反馈，或通过特定数据集微调模型，导致检索决策不可靠，成本增加，且生成结果不尽人意。我们提出了一种新的探针引导的自适应RAG框架CtrlA，首次深入LLMs内部状态，以解决这些问题。CtrlA通过诚实探针调整LLM行为，增强其诚实度，同时利用信心探针监控模型状态，评估信心水平，以确定生成时的检索需求。实验证明，CtrlA在多任务中表现优于现有方法，诚实控制显著提升了LLMs的可靠性，信心监控成为检索触发的重要指标。代码已公开于https://github.com/HSLiu-Initial/CtrlA.git。

> Retrieval-augmented generation (RAG) has emerged as a promising solution for mitigating hallucinations of large language models (LLMs) with retrieved external knowledge. Adaptive RAG enhances this approach by dynamically assessing the retrieval necessity, aiming to balance external and internal knowledge usage. However, existing adaptive RAG methods primarily realize retrieval on demand by relying on superficially verbalize-based or probability-based feedback of LLMs, or directly fine-tuning LLMs via carefully crafted datasets, resulting in unreliable retrieval necessity decisions, heavy extra costs, and sub-optimal response generation. We present the first attempts to delve into the internal states of LLMs to mitigate such issues by introducing an effective probe-guided adaptive RAG framework, termed CtrlA. Specifically, CtrlA employs an honesty probe to regulate the LLM's behavior by manipulating its representations for increased honesty, and a confidence probe to monitor the internal states of LLM and assess confidence levels, determining the retrieval necessity during generation. Experiments show that CtrlA is superior to existing adaptive RAG methods on a diverse set of tasks, the honesty control can effectively make LLMs more honest and confidence monitoring is proven to be a promising indicator of retrieval trigger. Our codes are available at https://github.com/HSLiu-Initial/CtrlA.git.

[Arxiv](https://arxiv.org/abs/2405.18727)