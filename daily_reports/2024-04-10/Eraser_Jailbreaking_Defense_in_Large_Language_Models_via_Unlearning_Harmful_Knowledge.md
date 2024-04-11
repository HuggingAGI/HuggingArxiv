# Eraser：通过摒弃有害知识，打破大型语言模型的束缚
`模型安全`
> 越狱攻击能助长大型语言模型（LLMs）绕开防护机制，制造恶劣内容。传统的越狱防范策略未能触及问题核心——模型内潜藏的有害信息，从而留下安全隐患。本文提出了一种创新的防御机制，名为“橡皮擦”，旨在抹除有害知识、保留基础常识，并确保安全性。简而言之，LLM若遗忘了回答有害问题的关键信息，便无法再产出有害内容。有趣的是，“橡皮擦”训练过程中，并不需要利用模型原有的有害信息，它通过学习如何回避与有害查询相关的通用回答来提升效果，实现自我净化，无需外部红队的支援。实验数据显示，“橡皮擦”能有效降低各类攻击的成功率，同时保持模型的通用性能不受影响。

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.05880/Motivation.jpg)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.05880/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.05880/combine_acc_asr2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.05880/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.05880/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.05880/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.05880/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.05880/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.05880/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.05880/x8.png)

[https://wx.zsxq.com/dweb2/index/topic_detail/1522421854882852](https://wx.zsxq.com/dweb2/index/topic_detail/1522421854882852)

[https://arxiv.org/abs/2404.05880](https://arxiv.org/abs/2404.05880)