# SuRe：为大型语言模型（LLMs）的开放域问答任务，通过候选答案对检索结果进行精炼总结。
发布时间：2024年04月16日
`应用案例`
> 大型语言模型（LLMs）在自然语言处理的多个任务上取得了突破性进展，尤其是在问答（QA）领域。尽管将新信息与相关文段检索相结合是提升LLMs QA性能的一个有前景的途径，但现有技术往往需要额外的微调步骤，这在最新型号的LLMs中变得不太可行。通过提示来增强检索文段，有望突破这一局限，但这方面的研究还不多见。为了解决这一问题，我们提出了一个既简洁又高效的框架，利用总结检索（SuRe）技术来提升LLMs在开放域问答（ODQA）任务中的表现。SuRe通过为每个可能的答案构建检索文段的摘要，帮助LLMs更准确地预测问题的答案，这些摘要可视为从检索文段中提取的明确理由。SuRe首先为每个答案候选生成检索文段的摘要，然后通过评估这些摘要的有效性和排序来确定最可信的答案。在多个ODQA基准上的实验结果显示，SuRe的性能优于传统的提示方法，精确匹配（EM）准确度提升了4.6%，F1分数提高了4.0%。此外，SuRe还能与多种检索方法和LLMs兼容。SuRe生成的摘要不仅有助于衡量检索文段的重要性，也为模型和人类提供了更优的理由。

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

[https://wx.zsxq.com/dweb2/index/topic_detail/5122514148522414](https://wx.zsxq.com/dweb2/index/topic_detail/5122514148522414)

[https://arxiv.org/abs/2404.13081](https://arxiv.org/abs/2404.13081)