# 利用关键词驱动检索增强的大型语言模型，为冷启动用户提供精准推荐
发布时间：2024年05月29日

`RAG`
> Keyword-driven Retrieval-Augmented Large Language Models for Cold-start User Recommendations
>
> 大型语言模型（LLMs）的进步已经极大地提升了推荐系统的潜力，但面对用户缺乏历史数据的冷启动问题，仍是一大挑战。为此，我们提出了KALM4Rec框架，专为解决冷启动用户在餐厅推荐中的问题而设计，仅需用户提供少量关键词。该框架分为两个主要阶段：候选检索和基于LLM的重新排序。首先，通过关键词驱动的检索模型筛选潜在候选，克服了LLMs处理大量数据的局限，并降低了误导信息的风险。其次，利用LLMs结合零-shot和few-shot等提示策略，将多例直接融入提示中，对候选进行重新排序。我们基于Yelp餐厅数据集的评估显示，KALM4Rec显著提升了推荐质量，尤其是通过LLMs的上下文指令进行重新排序，大幅增强了冷启动用户推荐系统的性能。
>
> https://arxiv.org/abs/2405.19612

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19612/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19612/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19612/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19612/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19612/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19612/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19612/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19612/x8.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19612/x9.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19612/x10.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19612/x11.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19612/x12.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19612/x13.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19612/x14.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19612/x15.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19612/x16.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19612/x17.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19612/x18.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19612/x19.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2405.19612](https://arxiv.org/abs/2405.19612)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886