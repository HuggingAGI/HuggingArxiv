# 探讨大规模语言模型中注意力头在安全性方面的作用

发布时间：2024年10月17日

`LLM理论` `人工智能` `网络安全`

> On the Role of Attention Heads in Large Language Model Safety

# 摘要

> 大型语言模型 (LLM) 在多项任务中表现卓越，但其安全防护有时会被绕过，导致有害输出。近期研究揭示，抑制安全组件会削弱 LLM 的安全性能。然而，现有研究常忽略多头注意力机制对安全性的影响，尽管其在模型功能中至关重要。本文探讨了标准注意力机制与安全能力的关系，填补了安全机制解释性的空白。我们提出了安全头重要性评分 (Ships)，用于评估多头注意力中各头对安全性的贡献。基于此，我们推广了 Ships 至数据集级别，并引入了安全注意力头归因算法 (Sahara)，以识别模型中的关键安全头。研究发现，特定注意力头对安全影响显著。消除单个安全头可使对齐模型响应更多有害查询，且仅修改极少参数。此外，我们证明注意力头主要作为安全特征提取器，且从同一基础模型微调的模型具有重叠的安全头。这些发现为理解大型模型中的安全机制提供了新视角。

> Large language models (LLMs) achieve state-of-the-art performance on multiple language tasks, yet their safety guardrails can be circumvented, leading to harmful generations. In light of this, recent research on safety mechanisms has emerged, revealing that when safety representations or component are suppressed, the safety capability of LLMs are compromised. However, existing research tends to overlook the safety impact of multi-head attention mechanisms, despite their crucial role in various model functionalities. Hence, in this paper, we aim to explore the connection between standard attention mechanisms and safety capability to fill this gap in the safety-related mechanistic interpretability. We propose a novel metric which tailored for multi-head attention, the Safety Head ImPortant Score (Ships), to assess the individual heads' contributions to model safety. Based on this, we generalize Ships to the dataset level and further introduce the Safety Attention Head AttRibution Algorithm (Sahara) to attribute the critical safety attention heads inside the model. Our findings show that the special attention head has a significant impact on safety. Ablating a single safety head allows aligned model (e.g., Llama-2-7b-chat) to respond to 16 times more harmful queries, while only modifying 0.006% of the parameters, in contrast to the ~ 5% modification required in previous studies. More importantly, we demonstrate that attention heads primarily function as feature extractors for safety and models fine-tuned from the same base model exhibit overlapping safety heads through comprehensive experiments. Together, our attribution approach and findings provide a novel perspective for unpacking the black box of safety mechanisms within large models.

[Arxiv](https://arxiv.org/abs/2410.13708)