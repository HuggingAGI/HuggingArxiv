# 迈向忠实的思维链：大型语言模型正成为推理者间的桥梁

发布时间：2024年05月29日

`LLM理论

这篇论文主要探讨了大型语言模型（LLMs）中的思维链（CoT）不忠实问题，并从CoT步骤的细节入手，分析了两种推理模式——集中式与分布式推理，以及它们与忠实性的关联。此外，论文还研究了推理过程中上下文、CoT与答案间的因果联系，并提出了推理桥接策略来提升CoT的忠实度。这些内容主要涉及LLM的理论分析和改进方法，因此归类为LLM理论。` `人工智能`

> Towards Faithful Chain-of-Thought: Large Language Models are Bridging Reasoners

# 摘要

> 大型语言模型（LLMs）面临思维链（CoT）不忠实问题的严重挑战。尽管先前的研究尝试对此进行量化和解释，但未能深入分析CoT内部机制，也未全面考虑推理组件间的互动。本文首次从CoT步骤的细节入手，揭示了两种推理模式——集中式与分布式推理，并探讨了它们与忠实性的关联。接着，我们综合分析了推理过程中上下文、CoT与答案间的因果联系。研究发现，LLMs在预测答案时，能从上下文中提取CoT遗漏的正确信息，从而引发不忠实问题。为此，我们提出了推理桥接策略，通过归因技术提取关键信息作为CoT生成的线索，并依据语义一致性与归因评分筛选出高质量的CoT。实验结果显示，该策略显著提升了CoT的忠实度。

> Large language models (LLMs) suffer from serious unfaithful chain-of-thought (CoT) issues. Previous work attempts to measure and explain it but lacks in-depth analysis within CoTs and does not consider the interactions among all reasoning components jointly. In this paper, we first study the CoT faithfulness issue at the granularity of CoT steps, identify two reasoning paradigms: centralized reasoning and distributed reasoning, and find their relationship with faithfulness. Subsequently, we conduct a joint analysis of the causal relevance among the context, CoT, and answer during reasoning. The result proves that, when the LLM predicts answers, it can recall correct information missing in the CoT from the context, leading to unfaithfulness issues. Finally, we propose the inferential bridging method to mitigate this issue, in which we use the attribution method to recall information as hints for CoT generation and filter out noisy CoTs based on their semantic consistency and attribution scores. Extensive experiments demonstrate that our approach effectively alleviates the unfaithful CoT problem.

![迈向忠实的思维链：大型语言模型正成为推理者间的桥梁](../../../paper_images/2405.18915/x1.png)

![迈向忠实的思维链：大型语言模型正成为推理者间的桥梁](../../../paper_images/2405.18915/x2.png)

![迈向忠实的思维链：大型语言模型正成为推理者间的桥梁](../../../paper_images/2405.18915/x3.png)

![迈向忠实的思维链：大型语言模型正成为推理者间的桥梁](../../../paper_images/2405.18915/x4.png)

![迈向忠实的思维链：大型语言模型正成为推理者间的桥梁](../../../paper_images/2405.18915/x5.png)

![迈向忠实的思维链：大型语言模型正成为推理者间的桥梁](../../../paper_images/2405.18915/x6.png)

![迈向忠实的思维链：大型语言模型正成为推理者间的桥梁](../../../paper_images/2405.18915/x7.png)

![迈向忠实的思维链：大型语言模型正成为推理者间的桥梁](../../../paper_images/2405.18915/x8.png)

![迈向忠实的思维链：大型语言模型正成为推理者间的桥梁](../../../paper_images/2405.18915/x9.png)

![迈向忠实的思维链：大型语言模型正成为推理者间的桥梁](../../../paper_images/2405.18915/x10.png)

![迈向忠实的思维链：大型语言模型正成为推理者间的桥梁](../../../paper_images/2405.18915/x11.png)

![迈向忠实的思维链：大型语言模型正成为推理者间的桥梁](../../../paper_images/2405.18915/x12.png)

![迈向忠实的思维链：大型语言模型正成为推理者间的桥梁](../../../paper_images/2405.18915/x13.png)

![迈向忠实的思维链：大型语言模型正成为推理者间的桥梁](../../../paper_images/2405.18915/x14.png)

![迈向忠实的思维链：大型语言模型正成为推理者间的桥梁](../../../paper_images/2405.18915/x15.png)

![迈向忠实的思维链：大型语言模型正成为推理者间的桥梁](../../../paper_images/2405.18915/x16.png)

![迈向忠实的思维链：大型语言模型正成为推理者间的桥梁](../../../paper_images/2405.18915/x17.png)

![迈向忠实的思维链：大型语言模型正成为推理者间的桥梁](../../../paper_images/2405.18915/x18.png)

![迈向忠实的思维链：大型语言模型正成为推理者间的桥梁](../../../paper_images/2405.18915/x19.png)

![迈向忠实的思维链：大型语言模型正成为推理者间的桥梁](../../../paper_images/2405.18915/x20.png)

![迈向忠实的思维链：大型语言模型正成为推理者间的桥梁](../../../paper_images/2405.18915/x21.png)

![迈向忠实的思维链：大型语言模型正成为推理者间的桥梁](../../../paper_images/2405.18915/x22.png)

![迈向忠实的思维链：大型语言模型正成为推理者间的桥梁](../../../paper_images/2405.18915/x23.png)

![迈向忠实的思维链：大型语言模型正成为推理者间的桥梁](../../../paper_images/2405.18915/x24.png)

![迈向忠实的思维链：大型语言模型正成为推理者间的桥梁](../../../paper_images/2405.18915/x25.png)

![迈向忠实的思维链：大型语言模型正成为推理者间的桥梁](../../../paper_images/2405.18915/x26.png)

![迈向忠实的思维链：大型语言模型正成为推理者间的桥梁](../../../paper_images/2405.18915/x27.png)

![迈向忠实的思维链：大型语言模型正成为推理者间的桥梁](../../../paper_images/2405.18915/x28.png)

![迈向忠实的思维链：大型语言模型正成为推理者间的桥梁](../../../paper_images/2405.18915/x30.png)

![迈向忠实的思维链：大型语言模型正成为推理者间的桥梁](../../../paper_images/2405.18915/x31.png)

![迈向忠实的思维链：大型语言模型正成为推理者间的桥梁](../../../paper_images/2405.18915/x32.png)

[Arxiv](https://arxiv.org/abs/2405.18915)