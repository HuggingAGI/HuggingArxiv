# 通过针对特定领域的精细调整和循环推理，提升问答系统的性能：一项对比分析研究

发布时间：2024年04月17日

`分类：RAG` `问答系统`

> Enhancing Q&A with Domain-Specific Fine-Tuning and Iterative Reasoning: A Comparative Study

# 摘要

> 本研究深入探讨了特定领域模型微调和推理机制对基于大型语言模型（LLMs）和增强检索生成（RAG）技术的问答（Q&A）系统性能的影响。通过FinanceBench SEC财务文件数据集的分析，我们发现，对于RAG系统而言，将经过微调的嵌入模型与LLM相结合，能够比通用模型获得更高的准确度，尤其是微调的嵌入模型贡献了更多的性能提升。此外，引入RAG之上的推理迭代机制，能够显著提升系统性能，使Q&A系统的表现更趋近于人类专家水平。文章还讨论了这些发现的意义，提出了一个包含Q&A AI主要技术组件的结构化技术设计框架，并为这些组件的技术选择提供了建议。我们将继续这项工作，为AI团队提供实用的指导，并进一步探索特定领域增强在RAG中的作用以及代理AI的高级规划和推理能力。

> This paper investigates the impact of domain-specific model fine-tuning and of reasoning mechanisms on the performance of question-answering (Q&A) systems powered by large language models (LLMs) and Retrieval-Augmented Generation (RAG). Using the FinanceBench SEC financial filings dataset, we observe that, for RAG, combining a fine-tuned embedding model with a fine-tuned LLM achieves better accuracy than generic models, with relatively greater gains attributable to fine-tuned embedding models. Additionally, employing reasoning iterations on top of RAG delivers an even bigger jump in performance, enabling the Q&A systems to get closer to human-expert quality. We discuss the implications of such findings, propose a structured technical design space capturing major technical components of Q&A AI, and provide recommendations for making high-impact technical choices for such components. We plan to follow up on this work with actionable guides for AI teams and further investigations into the impact of domain-specific augmentation in RAG and into agentic AI capabilities such as advanced planning and reasoning.

![通过针对特定领域的精细调整和循环推理，提升问答系统的性能：一项对比分析研究](../../../paper_images/2404.11792/ooda.png)

![通过针对特定领域的精细调整和循环推理，提升问答系统的性能：一项对比分析研究](../../../paper_images/2404.11792/ooda-rag.png)

![通过针对特定领域的精细调整和循环推理，提升问答系统的性能：一项对比分析研究](../../../paper_images/2404.11792/ooda-financebench.png)

![通过针对特定领域的精细调整和循环推理，提升问答系统的性能：一项对比分析研究](../../../paper_images/2404.11792/design-space.png)

![通过针对特定领域的精细调整和循环推理，提升问答系统的性能：一项对比分析研究](../../../paper_images/2404.11792/financebench-categories.png)

[Arxiv](https://arxiv.org/abs/2404.11792)