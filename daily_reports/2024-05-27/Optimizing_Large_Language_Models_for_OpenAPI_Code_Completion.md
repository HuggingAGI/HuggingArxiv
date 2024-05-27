# 精调大型语言模型，助力OpenAPI代码自动补全
发布时间：2024年05月24日

`动手训练`
> Optimizing Large Language Models for OpenAPI Code Completion
>
> 大型语言模型（LLMs）的最新进展及其在代码生成中的应用，已深刻重塑了软件开发领域。尽管主流编程语言的代码补全工具表现出色，但在处理OpenAPI等非主流格式时，性能却有所不足。本研究对GitHub Copilot在OpenAPI补全任务上的表现进行了评估，并借助Meta的开源模型Code Llama提出了一系列针对性优化。通过本研究提出的语义感知OpenAPI补全基准，我们进行了一系列实验，深入分析了提示工程和微调技术对Code Llama性能的影响。结果显示，尽管参数数量仅为商业解决方案的1/25，微调后的Code Llama模型在正确性上超越了GitHub Copilot，提升了55.2%。此外，本研究还针对代码填充训练技术提出了一项改进，有效解决了模型在提示上下文小于训练时所用大小时的性能问题。
>
> https://arxiv.org/abs/2405.15729

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.15729/benchmark-pipeline.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.15729/code-llama-family.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.15729/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.15729/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.15729/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.15729/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.15729/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.15729/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.15729/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.15729/x8.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.15729/x9.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2405.15729](https://arxiv.org/abs/2405.15729)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886