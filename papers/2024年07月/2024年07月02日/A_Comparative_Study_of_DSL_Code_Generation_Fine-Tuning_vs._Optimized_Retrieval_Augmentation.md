# 比较 DSL 代码生成的两种方法：微调与优化检索增强

发布时间：2024年07月02日

`RAG` `软件开发` `人工智能`

> A Comparative Study of DSL Code Generation: Fine-Tuning vs. Optimized Retrieval Augmentation

# 摘要

> 近年来，随着大型语言模型（LLM）的发展，自然语言到代码生成取得了显著进步。尽管在C、C++和Python等通用语言的生成方面有了显著提升，LLM在处理特定领域语言（DSL）中的自定义函数名称时仍显不足，导致幻觉率和语法错误增加，尤其是对于那些包含大量自定义函数名称的DSL。此外，函数名称的不断更新也带来了挑战，要求LLM保持最新状态。本文中，我们针对使用检索增强生成（RAG）与LLM进行DSL生成的优化方法进行了探讨，并通过消融研究比较了这些策略的效果。我们创建了一个包含大约700个公共领域API的自动化任务的DSL训练和测试数据集，并使用该训练集对Codex模型进行了微调。结果表明，微调模型在代码相似度指标上表现最佳。通过RAG优化，我们在相似度指标上达到了同等水平。然而，编译率显示两种模型在语法上仍有多次错误，RAG方法略胜一筹。在幻觉率方面，RAG模型在API名称和参数键上稍显落后。最终我们得出结论，经过优化的RAG模型不仅能与微调模型相媲美，还能为处理新的、未见过的API提供优势。

> Natural Language to Code Generation has made significant progress in recent years with the advent of Large Language Models(LLMs). While generation for general-purpose languages like C, C++, and Python has improved significantly, LLMs struggle with custom function names in Domain Specific Languages or DSLs. This leads to higher hallucination rates and syntax errors, specially for DSLs having a high number of custom function names. Additionally, constant updates to function names add to the challenge as LLMs need to stay up-to-date. In this paper, we present optimizations for using Retrieval Augmented Generation (or RAG) with LLMs for DSL generation along with an ablation study comparing these strategies. We generated a train as well as test dataset with a DSL to represent automation tasks across roughly 700 APIs in public domain. We used the training dataset to fine-tune a Codex model for this DSL. Our results showed that the fine-tuned model scored the best on code similarity metric. With our RAG optimizations, we achieved parity for similarity metric. The compilation rate, however, showed that both the models still got the syntax wrong many times, with RAG-based method being 2 pts better. Conversely, hallucination rate for RAG model lagged by 1 pt for API names and by 2 pts for API parameter keys. We conclude that an optimized RAG model can match the quality of fine-tuned models and offer advantages for new, unseen APIs.

![比较 DSL 代码生成的两种方法：微调与优化检索增强](../../../paper_images/2407.02742/x1.png)

[Arxiv](https://arxiv.org/abs/2407.02742)