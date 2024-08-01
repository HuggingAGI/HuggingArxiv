# 为 RAG 引入新超参数：上下文窗口利用率
发布时间：2024年07月29日

`RAG`
> Introducing a new hyper-parameter for RAG: Context Window Utilization
>
> 本文提出了一种名为“上下文窗口利用率”的新超参数，用于优化检索增强生成（RAG）系统。RAG系统通过整合外部知识库的相关信息，显著提升了生成内容的事实准确性和上下文相关性。本研究聚焦于确定最佳文本块大小，以最大化答案生成的质量。通过一系列实验，我们深入分析了不同块大小对RAG系统效率和效果的影响。研究结果显示，最佳块大小能够在提供充足上下文的同时，有效减少无关信息的干扰。这一发现对于优化RAG系统的设计与实施具有重要意义，强调了选择合适块大小以提升系统性能的关键作用。
>
> https://arxiv.org/abs/2407.19794

**点击公众号菜单加入大语言模型论文讨论**
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)
<hr />

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.19794/Legal_LLAMA3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.19794/Legal_MIXTRAL.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.19794/Research_LLAMA3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.19794/Research_MIXTRAL.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.19794/Wikipedia_LLAMA3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.19794/Wikipedia_MIXTRAL.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.19794/topk.jpg)

<hr />

- 论文原文: [https://arxiv.org/abs/2407.19794](https://arxiv.org/abs/2407.19794)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)