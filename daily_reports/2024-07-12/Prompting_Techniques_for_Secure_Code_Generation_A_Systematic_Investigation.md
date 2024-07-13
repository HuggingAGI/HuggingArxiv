# 探索安全代码生成的提示技术：系统性研究
发布时间：2024年07月09日

`代码编写`
> Prompting Techniques for Secure Code Generation: A Systematic Investigation
>
> 随着提示驱动编程的兴起，大型语言模型 (LLM) 在软件开发领域日益受到关注，使开发者能够通过自然语言指令编写代码。然而，这些模型生成安全代码的能力受到质疑，进而影响了提示生成软件的质量。为此，多种精心设计的提示技术应运而生，旨在从 LLM 中获取最佳响应。尽管如此，这些提示策略与安全代码生成之间的关系仍待深入探索。本研究旨在探讨不同提示技术对 LLM 生成的代码安全性的影响。我们首先进行了系统的文献回顾，筛选出适用于代码生成任务的提示技术，并在 GPT-3、GPT-3.5 和 GPT-4 模型上对其进行安全代码生成的评估。通过使用包含 150 个与安全相关的自然语言代码生成提示的数据集，我们的研究发现，通过分类和评估一系列提示技术，特别是在采用递归批评与改进 (RCI) 技术后，显著减少了测试 LLM 中的安全弱点，为 LLM 生成代码安全性的研究提供了重要见解。
>
> https://arxiv.org/abs/2407.07064

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.07064/slr.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.07064/taxonomy.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.07064/zero-and-few-shot.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.07064/rci-and-progressive-hint.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.07064/least-to-most-1-and-2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.07064/self-planning-1-and-2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.07064/zero-and-cot.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.07064/self-consistency-and-explanation.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.07064/persona-narrow.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.07064/methodology.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.07064/heat_map-gpt3-blue.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.07064/heat_map-gpt3_5-blue.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.07064/heat_map-gpt4-blue.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2407.07064](https://arxiv.org/abs/2407.07064)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 加入社群，公众号回复LLM
- 最新论文订阅体验：公众号号菜单回复1