# 大型语言模型在上下文外知识推理方面存在局限性
发布时间：2024年06月11日

`提示工程`
> Limited Out-of-Context Knowledge Reasoning in Large Language Models
>
> 大型语言模型（LLMs）在知识库和上下文推理方面表现出色，但其在无上下文推理，即从训练数据而非上下文或提示中推断信息的能力上受到质疑。本文聚焦于无上下文知识推理（OCKR），一种结合多源知识推断新知识的能力。我们创建了一个包含七个典型OCKR任务的数据集，用以评估LLMs的OCKR性能。通过此数据集，我们发现LLaMA2-13B-chat模型在OCKR方面的表现不尽人意，无论知识训练方式如何。即使使用完整的推理数据训练，改进也微乎其微。显式知识检索训练仅在一项任务中有所助益，揭示了模型在检索相关知识上的局限性。我们还探讨了跨语言知识转移这一OCKR的特殊形式，并发现模型在此方面同样能力有限。本研究所用数据集已公开，地址为https://github.com/NJUNLP/ID-OCKR。
>
> https://arxiv.org/abs/2406.07393

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.07393/IN_CONTEXT.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.07393/x1.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.07393](https://arxiv.org/abs/2406.07393)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886