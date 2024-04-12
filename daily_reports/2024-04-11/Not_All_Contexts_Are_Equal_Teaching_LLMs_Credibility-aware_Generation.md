# 上下文并非一视同仁：引导大型语言模型（LLM）进行可信度敏感的内容生成。
`RAG`
> 随着大型语言模型迅猛发展，检索增强生成（RAG）技术应运而生，它通过融合外部知识来解决知识匮乏问题并减少生成内容的失真。然而，RAG在实际应用中常受到检索过程中错误信息的干扰，影响生成结果的可靠性和准确性。本文提出了一种新颖的框架——可信度感知生成（CAG），它能够减轻RAG中错误信息的负面影响。CAG的核心在于赋予模型识别和处理信息可信度的能力。我们设计了一种创新的数据转换方法，根据信息的可信度生成数据，使模型具备CAG的能力。为了全面评估模型的CAG性能，我们构建了一个包含三个真实世界场景的综合基准测试。实验结果显示，我们的模型能够高效地理解和运用信息的可信度，相较于其他增强检索模型，其生成效果显著提升，且在面对噪声文档的干扰时表现出强大的抗扰性，确保了生成结果的稳定性。此外，模型还支持定制化可信度设置，拓展了其应用范围。

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.06809/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.06809/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.06809/noise.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.06809/discard.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.06809/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.06809/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.06809/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.06809/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.06809/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.06809/x8.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.06809/x9.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.06809/x10.png)

[https://wx.zsxq.com/dweb2/index/topic_detail/5122528252558524](https://wx.zsxq.com/dweb2/index/topic_detail/5122528252558524)

[https://arxiv.org/abs/2404.06809](https://arxiv.org/abs/2404.06809)