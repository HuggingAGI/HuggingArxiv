# CtrlA：利用探针引导控制实现自适应检索增强生成

发布时间：2024年05月28日

`RAG

理由：这篇论文主要探讨了检索增强生成（RAG）框架的改进，特别是通过引入名为CtrlA的自适应RAG框架来优化大型语言模型（LLMs）的检索决策和响应质量。论文的核心贡献在于通过内部状态的探索和探针引导的方式，提高了LLMs的诚实度和信心水平监控，从而优化了外部知识检索的效率和准确性。这与RAG技术的核心目标紧密相关，即通过增强检索过程来改善生成模型的性能，因此归类为RAG。` `人工智能`

> CtrlA: Adaptive Retrieval-Augmented Generation via Probe-Guided Control

# 摘要

> 检索增强生成（RAG）作为一种解决方案，有效减轻了大型语言模型（LLMs）因外部知识检索而产生的幻觉问题。自适应RAG通过动态评估检索需求，优化了外部与内部知识的平衡使用。然而，现有方法多依赖于LLMs的表面反馈或通过特定数据集微调，导致检索决策不可靠，成本高且响应质量次优。我们首次探索了LLMs的内部状态，并引入了名为CtrlA的有效探针引导的自适应RAG框架。CtrlA通过诚实探针调整LLM行为，增强其诚实度，并通过信心探针监控并评估LLM的信心水平，以确定检索的必要性。实验证明，CtrlA在多种任务上表现优于现有方法，诚实控制显著提升了LLMs的可靠性，信心监控成为检索触发的重要指标。相关代码已公开于https://github.com/HSLiu-Initial/CtrlA.git。

> Retrieval-augmented generation (RAG) has emerged as a promising solution for mitigating hallucinations of large language models (LLMs) with retrieved external knowledge. Adaptive RAG enhances this approach by dynamically assessing the retrieval necessity, aiming to balance external and internal knowledge usage. However, existing adaptive RAG methods primarily realize retrieval on demand by relying on superficially verbalize-based or probability-based feedback of LLMs, or directly fine-tuning LLMs via carefully crafted datasets, resulting in unreliable retrieval necessity decisions, heavy extra costs, and sub-optimal response generation. We present the first attempts to delve into the internal states of LLMs to mitigate such issues by introducing an effective probe-guided adaptive RAG framework, termed CtrlA. Specifically, CtrlA employs an honesty probe to regulate the LLM's behavior by manipulating its representations for increased honesty, and a confidence probe to monitor the internal states of LLM and assess confidence levels, determining the retrieval necessity during generation. Experiments show that CtrlA is superior to existing adaptive RAG methods on a diverse set of tasks, the honesty control can effectively make LLMs more honest and confidence monitoring is proven to be a promising indicator of retrieval trigger. Our codes are available at https://github.com/HSLiu-Initial/CtrlA.git.

[Arxiv](https://arxiv.org/abs/2405.18727)