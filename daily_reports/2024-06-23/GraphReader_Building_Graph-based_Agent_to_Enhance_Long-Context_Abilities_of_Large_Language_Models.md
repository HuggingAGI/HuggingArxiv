# GraphReader：打造基于图的智能体，提升大型语言模型处理长上下文的能力
发布时间：2024年06月20日

`Agent应用`
> GraphReader: Building Graph-based Agent to Enhance Long-Context Abilities of Large Language Models
>
> 大型语言模型（LLMs）要想应对复杂且长输入的任务，必须具备强大的长上下文处理能力。尽管业界已付出诸多努力优化LLMs以适应长上下文，但稳健地处理长输入依旧是一大挑战。本文中，我们推出了GraphReader，一种基于图的代理系统，它通过将文本转化为图结构，并利用代理自主探索图来应对长文本挑战。当接收到问题时，代理会进行细致分析并制定合理计划，随后调用预设功能，逐层深入地探索图中的节点与邻居。在探索过程中，代理不断汲取新知，并根据当前情况调整策略，直至收集到足够信息以生成答案。实验结果表明，在LV-Eval数据集上，使用4k上下文窗口的GraphReader在16k至256k的上下文长度范围内，均显著超越GPT-4-128k。此外，我们的方法在四个高难度的单跳和多跳基准测试中也展现了卓越性能。
>
> https://arxiv.org/abs/2406.14550

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.14550/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.14550/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.14550/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.14550/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.14550/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.14550/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.14550/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.14550/x8.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.14550](https://arxiv.org/abs/2406.14550)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 最新论文订阅体验：公众号号菜单回复1
- 最新论文订阅新人：公众号号菜单回复2