# 协同事件理解：借助大型语言模型，探索跨文档事件共指消解的协作新途径

发布时间：2024年06月04日

`RAG

理由：这篇论文提出了一种结合通用大型语言模型（LLM）和任务特定小型语言模型（SLM）的协作方法来解决跨文档事件共指消解（CDECR）问题。这种方法利用LLM的强大上下文理解能力来精准全面地总结事件，同时利用SLM在特定任务上的优化能力来改善事件表示学习。这种结合了LLM和SLM优势的方法，类似于RAG（Retrieval-Augmented Generation）框架，其中LLM提供广泛的上下文理解，而SLM则提供任务特定的优化。因此，这篇论文更适合归类为RAG。` `信息抽取`

> Synergetic Event Understanding: A Collaborative Approach to Cross-Document Event Coreference Resolution with Large Language Models

# 摘要

> 跨文档事件共指消解（CDECR）旨在将多个文档中提及的同一现实世界事件的事件提及进行聚类。现有技术通过微调BERT等小型语言模型（SLMs）来处理事件提及间的上下文兼容性，但常陷入简单共现的学习。近期，ChatGPT等大型语言模型（LLMs）虽在上下文理解上表现出色，却难以适应特定的信息抽取（IE）任务。本文提出了一种CDECR的协作方法，结合了通用LLM与任务特定SLM的优势。首先，LLM通过提示精准全面地总结事件；随后，SLM基于这些总结在微调中优化事件表示学习。实验证明，此方法在性能上超越了单独使用LLM和SLM，形成了互补优势，并在多个数据集上达到了最先进水平，展现了其在多样场景中的高效性。

> Cross-document event coreference resolution (CDECR) involves clustering event mentions across multiple documents that refer to the same real-world events. Existing approaches utilize fine-tuning of small language models (SLMs) like BERT to address the compatibility among the contexts of event mentions. However, due to the complexity and diversity of contexts, these models are prone to learning simple co-occurrences. Recently, large language models (LLMs) like ChatGPT have demonstrated impressive contextual understanding, yet they encounter challenges in adapting to specific information extraction (IE) tasks. In this paper, we propose a collaborative approach for CDECR, leveraging the capabilities of both a universally capable LLM and a task-specific SLM. The collaborative strategy begins with the LLM accurately and comprehensively summarizing events through prompting. Then, the SLM refines its learning of event representations based on these insights during fine-tuning. Experimental results demonstrate that our approach surpasses the performance of both the large and small language models individually, forming a complementary advantage. Across various datasets, our approach achieves state-of-the-art performance, underscoring its effectiveness in diverse scenarios.

![协同事件理解：借助大型语言模型，探索跨文档事件共指消解的协作新途径](../../../paper_images/2406.02148/intro_slm.jpg)

![协同事件理解：借助大型语言模型，探索跨文档事件共指消解的协作新途径](../../../paper_images/2406.02148/intro_llm.jpg)

![协同事件理解：借助大型语言模型，探索跨文档事件共指消解的协作新途径](../../../paper_images/2406.02148/paraphrase_f1.png)

![协同事件理解：借助大型语言模型，探索跨文档事件共指消解的协作新途径](../../../paper_images/2406.02148/multi-step_f1.png)

![协同事件理解：借助大型语言模型，探索跨文档事件共指消解的协作新途径](../../../paper_images/2406.02148/multi-step_errors.png)

![协同事件理解：借助大型语言模型，探索跨文档事件共指消解的协作新途径](../../../paper_images/2406.02148/len_ratio.png)

![协同事件理解：借助大型语言模型，探索跨文档事件共指消解的协作新途径](../../../paper_images/2406.02148/demo_num_impact.png)

[Arxiv](https://arxiv.org/abs/2406.02148)