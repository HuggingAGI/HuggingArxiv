# 揭秘检索增强生成技术的双重奥秘：理论剖析与实践指南
发布时间：2024年06月02日

`RAG`
> Unveil the Duality of Retrieval-Augmented Generation: Theoretical Analysis and Practical Solution
>
> 检索增强生成（RAG）通过利用检索文本来提升大型语言模型（LLMs）的性能，但研究发现，RAG的效果并不稳定，有时甚至因检索到的文本质量不佳而误导模型。这揭示了RAG的双重性质——既有利也有弊。尽管已有多种方法尝试解决这一问题，但缺乏对RAG双重性的理论解释。这种双重性中的利弊仍是一个难以量化和解释的谜。本文首次从理论上阐释了RAG中的利弊：（1）从RAG预测中分离并形式化它们，（2）通过表示相似性估算它们之间的价值差异，（3）建立它们之间的权衡机制，使其可解释、可量化和可比较。我们发现，检索文本与LLMs知识间的分布差异既是助力也是阻力。我们还证实了RAG的实际效果可在令牌级别上预见。基于此理论，我们提出了X-RAG方法，该方法在令牌级别上实现了纯LLM与RAG的协同生成，旨在最大化益处并最小化损害。实验结果显示，我们的方法在包括OPT、LLaMA-2和Mistral在内的LLMs上表现出色，验证了我们的理论。
>
> https://arxiv.org/abs/2406.00944

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.00944/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.00944/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.00944/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.00944/x4.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.00944](https://arxiv.org/abs/2406.00944)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886