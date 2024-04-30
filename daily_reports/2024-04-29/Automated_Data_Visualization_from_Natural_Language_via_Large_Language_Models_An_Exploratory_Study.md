![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/imgs/follow2.gif)
# 本研究探索了利用大型语言模型将自然语言自动转换为数据可视化的过程。
发布时间：2024年04月25日

`应用案例`
> 自然语言到可视化（NL2Vis）任务致力于将自然语言描述转换成可视化的表格数据，以便用户能从海量数据中洞察信息。尽管基于深度学习的多种方法已应运而生，但在将未见数据库或跨多表的数据可视化时，仍面临挑战。本文借鉴大型语言模型（LLMs）的卓越生成能力，通过实证研究来评估其在创建可视化方面的能力，并探讨使用上下文学习提示来提升任务效果的可能性。我们首先研究了如何将结构化表格数据转化为连续文本提示，以便输入LLMs，并分析了哪些表格内容对NL2Vis最为关键。研究结果显示，将表格数据转化为程序文本是有效的，同时在构建提示时考虑表格结构是必要的。我们还对比了两种LLMs：经过微调的模型（如T5-Small）和仅限推理的模型（如GPT-3.5），并与现有最先进方法进行了比较。实验结果显示，LLMs在性能上超越了基线，尤其是仅限推理模型在上下文学习中通过少量示例的引导，有时甚至能超越微调模型。最后，我们深入分析了LLMs在NL2Vis中的不足，并提出了通过链式思考、角色扮演和代码解释等策略来迭代优化结果。实验结果证明了迭代更新策略的有效性，并为未来的研究开辟了新的可能性。

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.17136/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.17136/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.17136/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.17136/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.17136/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.17136/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.17136/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.17136/x8.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.17136/x9.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.17136/x10.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.17136/x11.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.17136/x12.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.17136/x13.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.17136/x14.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.17136/x15.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.17136/x16.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.17136/x17.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.17136/x18.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.17136/x19.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.17136/x20.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.17136/x21.png)


- 论文原文 [https://arxiv.org/abs/2404.17136](https://arxiv.org/abs/2404.17136)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/imgs/qrcode.png)