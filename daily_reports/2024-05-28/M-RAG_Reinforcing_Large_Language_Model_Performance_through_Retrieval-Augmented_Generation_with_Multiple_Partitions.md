# M-RAG：借助多分区检索增强技术，提升大型语言模型的生成性能
发布时间：2024年05月26日

`RAG`
> M-RAG: Reinforcing Large Language Model Performance through Retrieval-Augmented Generation with Multiple Partitions
>
> Retrieval-Augmented Generation (RAG) 通过外部数据库中的相关记忆检索，提升了大型语言模型 (LLMs) 的性能。但现有 RAG 方法往往将所有记忆集中管理，可能导致关键信息被忽视并增加噪声。本文提出了一种多分区 RAG 方法（M-RAG），每个分区独立运作，提高了 RAG 的针对性。我们进一步开发了一个结合多智能体强化学习的框架，专门优化语言生成任务。实验结果显示，M-RAG 在文本摘要、机器翻译和对话生成三类任务中，分别提升了 11%、8% 和 12%，显著超越了其他方法。
>
> https://arxiv.org/abs/2405.16420

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.16420/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.16420/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.16420/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.16420/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.16420/x5.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2405.16420](https://arxiv.org/abs/2405.16420)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886