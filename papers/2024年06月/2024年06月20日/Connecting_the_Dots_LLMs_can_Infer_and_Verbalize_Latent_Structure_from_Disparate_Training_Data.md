# 点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。

发布时间：2024年06月20日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）的一种特定能力，即归纳性超上下文推理（OOCR），这是关于LLMs如何从分散的证据中推断隐含信息并应用于下游任务的理论研究。它不仅展示了LLMs的这种能力，还讨论了这种能力对监控和控制LLMs知识获取的挑战，这属于对LLMs理论特性的深入分析。因此，它更适合归类于LLM理论。` `人工智能`

> Connecting the Dots: LLMs can Infer and Verbalize Latent Structure from Disparate Training Data

# 摘要

> 为了应对大型语言模型（LLMs）的安全风险，一种策略是从训练数据中剔除危险知识。尽管这能清除显性信息，但隐性信息仍可能散布于各训练文档中。LLMs是否能通过整合这些隐性线索，推断出被审查的内容？为此，我们探讨了归纳性超上下文推理（OOCR），这是一种LLMs从分散证据中推断隐含信息并应用于下游任务的能力，无需依赖上下文学习。通过五个任务的系列实验，我们展示了前沿LLMs具备这种能力。例如，我们微调了一个LLM，其训练数据仅包含一个未知城市与其他已知城市的距离。令人惊讶的是，该LLM在没有上下文示例或思维链辅助的情况下，能准确识别出该城市为巴黎，并据此解答后续问题。其他实验也显示，仅基于硬币翻转结果训练的LLMs能判断硬币是否偏倚，而仅基于成对数据$(x,f(x))$训练的LLMs能定义函数$f$并计算其逆。尽管OOCR在多种情境下表现出色，但它对于小型且需学习复杂结构的LLMs来说并不可靠。总体而言，LLMs无需明确上下文学习即能“洞察秋毫”的能力，对监控和控制其知识获取提出了挑战。

> One way to address safety risks from large language models (LLMs) is to censor dangerous knowledge from their training data. While this removes the explicit information, implicit information can remain scattered across various training documents. Could an LLM infer the censored knowledge by piecing together these implicit hints? As a step towards answering this question, we study inductive out-of-context reasoning (OOCR), a type of generalization in which LLMs infer latent information from evidence distributed across training documents and apply it to downstream tasks without in-context learning. Using a suite of five tasks, we demonstrate that frontier LLMs can perform inductive OOCR. In one experiment we finetune an LLM on a corpus consisting only of distances between an unknown city and other known cities. Remarkably, without in-context examples or Chain of Thought, the LLM can verbalize that the unknown city is Paris and use this fact to answer downstream questions. Further experiments show that LLMs trained only on individual coin flip outcomes can verbalize whether the coin is biased, and those trained only on pairs $(x,f(x))$ can articulate a definition of $f$ and compute inverses. While OOCR succeeds in a range of cases, we also show that it is unreliable, particularly for smaller LLMs learning complex structures. Overall, the ability of LLMs to "connect the dots" without explicit in-context learning poses a potential obstacle to monitoring and controlling the knowledge acquired by LLMs.

![点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。](../../../paper_images/2406.14546/x1.png)

![点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。](../../../paper_images/2406.14546/x2.png)

![点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。](../../../paper_images/2406.14546/x3.png)

![点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。](../../../paper_images/2406.14546/x4.png)

![点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。](../../../paper_images/2406.14546/x5.png)

![点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。](../../../paper_images/2406.14546/x6.png)

![点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。](../../../paper_images/2406.14546/x7.png)

![点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。](../../../paper_images/2406.14546/x8.png)

![点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。](../../../paper_images/2406.14546/x9.png)

![点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。](../../../paper_images/2406.14546/x10.png)

![点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。](../../../paper_images/2406.14546/x11.png)

![点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。](../../../paper_images/2406.14546/x12.png)

![点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。](../../../paper_images/2406.14546/x13.png)

![点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。](../../../paper_images/2406.14546/x14.png)

![点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。](../../../paper_images/2406.14546/x15.png)

![点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。](../../../paper_images/2406.14546/x16.png)

![点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。](../../../paper_images/2406.14546/x17.png)

![点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。](../../../paper_images/2406.14546/x18.png)

![点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。](../../../paper_images/2406.14546/x19.png)

![点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。](../../../paper_images/2406.14546/x20.png)

![点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。](../../../paper_images/2406.14546/x21.png)

![点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。](../../../paper_images/2406.14546/x22.png)

![点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。](../../../paper_images/2406.14546/x23.png)

![点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。](../../../paper_images/2406.14546/x24.png)

![点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。](../../../paper_images/2406.14546/x25.png)

![点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。](../../../paper_images/2406.14546/x26.png)

![点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。](../../../paper_images/2406.14546/x27.png)

![点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。](../../../paper_images/2406.14546/x28.png)

![点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。](../../../paper_images/2406.14546/x29.png)

![点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。](../../../paper_images/2406.14546/x30.png)

![点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。](../../../paper_images/2406.14546/x31.png)

![点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。](../../../paper_images/2406.14546/x32.png)

![点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。](../../../paper_images/2406.14546/x33.png)

![点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。](../../../paper_images/2406.14546/x34.png)

![点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。](../../../paper_images/2406.14546/x35.png)

![点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。](../../../paper_images/2406.14546/x36.png)

![点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。](../../../paper_images/2406.14546/x37.png)

![点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。](../../../paper_images/2406.14546/x38.png)

![点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。](../../../paper_images/2406.14546/x39.png)

![点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。](../../../paper_images/2406.14546/x40.png)

![点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。](../../../paper_images/2406.14546/x41.png)

![点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。](../../../paper_images/2406.14546/x42.png)

![点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。](../../../paper_images/2406.14546/x43.png)

![点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。](../../../paper_images/2406.14546/x44.png)

![点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。](../../../paper_images/2406.14546/x45.png)

![点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。](../../../paper_images/2406.14546/x46.png)

![点与点相连：大型语言模型（LLMs）具备从多样训练数据中洞察并阐述隐含结构的能力。](../../../paper_images/2406.14546/x47.png)

[Arxiv](https://arxiv.org/abs/2406.14546)