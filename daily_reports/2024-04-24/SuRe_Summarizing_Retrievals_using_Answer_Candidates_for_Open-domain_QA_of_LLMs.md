![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/imgs/follow2.gif)
# SuRe：为大型语言模型（LLMs）的开放域问答任务，通过候选答案对检索结果进行精炼总结。
发布时间：2024年04月16日

`应用案例`
> 大型语言模型（LLMs）在自然语言处理的多个领域取得了突破性进展，尤其是在问答（QA）任务上。尽管结合新信息和检索相关内容是提升LLMs QA性能的一条有前景的途径，但现有的技术往往需要额外的微调，这在最新的LLMs中变得不切实际。通过提示来增强检索段落，有望突破这一瓶颈，但这方面的研究还相对有限。为了解决这一问题，我们提出了一个基于总结检索（SuRe）的简洁而高效的框架，用于提升LLMs在开放域问答（ODQA）中的表现。SuRe通过为每个可能的答案构建检索段落的摘要，帮助LLMs更准确地预测问题的答案，这些摘要可视为从检索内容中提取的明确理由。SuRe首先为多个答案候选者生成摘要，然后通过评估这些摘要的准确性和排序来确定最可信的答案。在多个ODQA基准上的实验结果显示，SuRe的性能优于传统提示方法，精确匹配（EM）准确度提升了4.6%，F1分数提升了4.0%。此外，SuRe能够与多种检索方法和LLMs兼容。SuRe生成的摘要还具有额外的优势，它们不仅能够衡量检索内容的重要性，还能作为模型和人类更倾向的理由。

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.13081/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.13081/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.13081/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.13081/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.13081/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.13081/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.13081/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.13081/x8.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.13081/x9.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.13081/x10.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.13081/x11.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.13081/x12.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.13081/x13.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.13081/x14.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.13081/x15.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.13081/x16.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.13081/x17.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.13081/x18.png)


- 论文原文 [https://arxiv.org/abs/2404.13081](https://arxiv.org/abs/2404.13081)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/imgs/qrcode.png)
<img src="https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/imgs/qrcode.png" width="50%" style="margin: auto;" />