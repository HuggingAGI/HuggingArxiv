# FPT，即特征提示调整技术，旨在提升少样本情境下的文本可读性评估效果。
`应用案例`
> 在少量样本文本分类任务中，基于提示的方法已取得显著成果。但在可读性评估方面，传统方法缺少必要的语言知识。以往的研究也显示，在少量样本环境下，单纯依赖语言特征的表现并不稳定，有时甚至会影响模型效能。为应对这些挑战，我们引入了一种创新的基于提示的调整框架——特征提示调整（FPT），它融合了丰富的语言知识。我们通过提取文本的语言特征并将其嵌入可训练的柔性提示中，同时设计了一种新的损失函数来优化类别间的相似度排序。实验证明，FPT方法不仅在性能上大幅超越了以往的提示调整技术，也包括那些融合了语言特征的先进方法。此外，我们的模型在多数情况下的表现甚至超过了大型语言模型gpt-3.5-turbo-16k。这一新架构为提示调整开辟了新天地，展示了如何将语言特征轻松应用于与语言相关的任务中。

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.02772/figure1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.02772/figure2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.02772/figure3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.02772/LLM_prompt.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.02772/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.02772/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.02772/blank.jpg)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.02772/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.02772/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.02772/colorBar.png)

[https://wx.zsxq.com/dweb2/index/topic_detail/2855814415548811](https://wx.zsxq.com/dweb2/index/topic_detail/2855814415548811)

[https://arxiv.org/abs/2404.02772](https://arxiv.org/abs/2404.02772)