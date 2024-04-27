# 利用检索增强生成技术，有效降低结构化输出中的幻觉问题。

发布时间：2024年04月11日

`分类：RAG

这篇论文讨论了在生成性AI（GenAI）中，如何通过使用检索增强生成（RAG）技术来减少误导性信息的产生。论文中提到，RAG技术显著提升了生成工作流程的结构化输出质量，降低了输出中的幻觉现象，并增强了LLM在新领域中的泛化性能。这些内容都与RAG技术的应用和效果相关，因此将这篇论文归类为RAG。` `企业应用` `人工智能`

> Reducing hallucination in structured outputs via Retrieval-Augmented Generation

# 摘要

> 生成性AI（GenAI）普遍面临的一个基本问题是其容易产生误导性信息。尽管大型语言模型（LLM）在全球掀起了波澜，但如果不能有效减少幻觉现象，GenAI在现实世界的应用可能会遭遇用户接受度的难题。在开发一个根据自然语言需求生成工作流程的企业级应用时，我们构建了一个系统，该系统采用了检索增强生成（RAG）技术，显著提升了所生成工作流程的结构化输出质量。得益于RAG的引入，我们的系统显著降低了输出中的幻觉现象，并增强了LLM在新领域中的泛化性能。此外，我们还发现，采用一个小型但训练精良的检索器编码器，可以减小与之配合使用的LLM的规模，从而降低了部署基于LLM的系统的资源消耗。

> A common and fundamental limitation of Generative AI (GenAI) is its propensity to hallucinate. While large language models (LLM) have taken the world by storm, without eliminating or at least reducing hallucinations, real-world GenAI systems may face challenges in user adoption. In the process of deploying an enterprise application that produces workflows based on natural language requirements, we devised a system leveraging Retrieval Augmented Generation (RAG) to greatly improve the quality of the structured output that represents such workflows. Thanks to our implementation of RAG, our proposed system significantly reduces hallucinations in the output and improves the generalization of our LLM in out-of-domain settings. In addition, we show that using a small, well-trained retriever encoder can reduce the size of the accompanying LLM, thereby making deployments of LLM-based systems less resource-intensive.

![利用检索增强生成技术，有效降低结构化输出中的幻觉问题。](../../../paper_images/2404.08189/x1.png)

![利用检索增强生成技术，有效降低结构化输出中的幻觉问题。](../../../paper_images/2404.08189/t2f_architecture.jpg)

![利用检索增强生成技术，有效降低结构化输出中的幻觉问题。](../../../paper_images/2404.08189/t2f_input_output_example.jpg)

![利用检索增强生成技术，有效降低结构化输出中的幻觉问题。](../../../paper_images/2404.08189/x2.png)

![利用检索增强生成技术，有效降低结构化输出中的幻觉问题。](../../../paper_images/2404.08189/x3.png)

![利用检索增强生成技术，有效降低结构化输出中的幻觉问题。](../../../paper_images/2404.08189/x4.png)

[Arxiv](https://arxiv.org/abs/2404.08189)