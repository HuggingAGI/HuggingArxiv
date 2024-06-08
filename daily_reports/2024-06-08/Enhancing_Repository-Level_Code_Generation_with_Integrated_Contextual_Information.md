# 集成上下文信息，提升仓库级代码生成能力
发布时间：2024年06月05日

`代码编写`
> Enhancing Repository-Level Code Generation with Integrated Contextual Information
>
> 大型语言模型（LLMs）在代码生成领域表现出色，但仓库级别的代码生成因其涉及跨文件信息的复杂性而面临挑战。现有基于检索的方法在深入理解仓库上下文方面存在不足。为此，我们推出了CatCoder，一个专为静态类型语言设计的创新代码生成框架。CatCoder通过结合类型分析与代码检索，为LLMs提供丰富的上下文提示，显著提升了仓库级代码生成的质量。我们通过包含199个Java任务和90个Rust任务的基准测试，证明了CatCoder在pass@k评分上超越了基线RepoCoder达17.35%。此外，CatCoder在多种LLMs上的广泛适用性也得到了验证，无论是专精于代码的模型还是通用模型，均显示出一致的性能提升，凸显了CatCoder的实际应用价值。
>
> https://arxiv.org/abs/2406.03283

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.03283/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.03283/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.03283/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.03283/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.03283/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.03283/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.03283/x7.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.03283](https://arxiv.org/abs/2406.03283)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886