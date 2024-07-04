# 比较 DSL 代码生成的两种方法：微调与优化检索增强
发布时间：2024年07月02日

`代码编写`
> A Comparative Study of DSL Code Generation: Fine-Tuning vs. Optimized Retrieval Augmentation
>
> 近年来，随着大型语言模型（LLM）的发展，自然语言到代码生成取得了显著进步。尽管在C、C++和Python等通用语言的生成方面有了显著提升，LLM在处理特定领域语言（DSL）中的自定义函数名称时仍显不足，导致幻觉率和语法错误增加，尤其是对于那些包含大量自定义函数名称的DSL。此外，函数名称的不断更新也带来了挑战，要求LLM保持最新状态。本文中，我们针对使用检索增强生成（RAG）与LLM进行DSL生成的优化方法进行了探讨，并通过消融研究比较了这些策略的效果。我们创建了一个包含大约700个公共领域API的自动化任务的DSL训练和测试数据集，并使用该训练集对Codex模型进行了微调。结果表明，微调模型在代码相似度指标上表现最佳。通过RAG优化，我们在相似度指标上达到了同等水平。然而，编译率显示两种模型在语法上仍有多次错误，RAG方法略胜一筹。在幻觉率方面，RAG模型在API名称和参数键上稍显落后。最终我们得出结论，经过优化的RAG模型不仅能与微调模型相媲美，还能为处理新的、未见过的API提供优势。
>
> https://arxiv.org/abs/2407.02742

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.02742/x1.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2407.02742](https://arxiv.org/abs/2407.02742)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 加入社群，公众号回复LLM
- 最新论文订阅体验：公众号号菜单回复1