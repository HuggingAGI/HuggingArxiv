# InstructRAG：借助显式去噪技术，指导检索增强生成过程
发布时间：2024年06月19日

`RAG`
> InstructRAG: Instructing Retrieval-Augmented Generation with Explicit Denoising
>
> 检索增强生成（RAG）展现出提升语言模型准确性和事实性的潜力，但检索器的不完善或数据集的噪声可能引入误导性信息，影响生成质量。现有方法虽能直接预测答案，但去噪过程难以解释和验证。为此，我们提出InstructRAG，通过让模型自我解释如何从检索文档中得出正确答案，实现显式去噪学习。这种方法无需额外监督，简化了验证过程，并显著提升了生成准确性。实验证明，InstructRAG在多个知识密集型任务中超越了现有方法，平均提升了8.3%。此外，它展现出良好的扩展性和强大的泛化能力，即使在域外数据集上也能有效去噪。
>
> https://arxiv.org/abs/2406.13629

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.13629/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.13629/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.13629/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.13629/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.13629/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.13629/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.13629/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.13629/x8.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.13629/x9.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.13629/x10.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.13629/x11.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.13629](https://arxiv.org/abs/2406.13629)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 最新论文订阅体验：公众号号菜单回复1
- 最新论文订阅新人：公众号号菜单回复2