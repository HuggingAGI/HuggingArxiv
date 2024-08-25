# 利用 RAG 和 LLM 进行少量样本上下文学习，实现基于证据的事实核查
发布时间：2024年08月21日

`RAG`
> Evidence-backed Fact Checking using RAG and Few-Shot In-Context Learning with LLMs
>
> 社交媒体上的错误信息泛滥，使得在线声明的事实核查变得至关重要。手动验证每条声明极为困难，因此我们设计了一个自动化系统来应对这一挑战。该系统利用 Averitec 数据集评估声明的真实性，并提供支持证据。通过 Retrieve and Generate (RAG) 流程，我们从知识库中提取相关证据，结合声明输入 LLM 进行分类。此外，我们还评估了 LLM 的少量样本 In-Context Learning (ICL) 能力。我们的系统在 'Averitec' 评分上比基线提升了 22%，所有代码将在 GitHub 上公开。
>
> https://arxiv.org/abs/2408.12060

**点击公众号菜单加入大语言模型论文讨论**
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)
<hr />

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.12060/claim_word_cloud.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.12060/x1.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2408.12060](https://arxiv.org/abs/2408.12060)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)