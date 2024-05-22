# 单图遗忘术：多模态大语言模型中的高效遗忘机制

发布时间：2024年05月21日

`LLM应用

理由：这篇论文主要探讨了在多模态大型语言模型（MLLMs）中实现机器遗忘的技术，特别是针对视觉数据的遗忘。它提出了一种新的方法——单图像遗忘（SIU），并构建了一个新的基准MMUBench来评估这种技术。这些内容涉及到LLM的具体应用，即如何处理和保护模型中的敏感信息，而不是探讨LLM的理论基础或Agent的设计与应用，也不是关于检索增强生成（RAG）的研究。因此，它最适合归类为LLM应用。` `机器学习` `隐私保护`

> Single Image Unlearning: Efficient Machine Unlearning in Multimodal Large Language Models

# 摘要

> 机器遗忘技术赋予了个人“被遗忘权”，即从机器学习模型中移除其私人或敏感信息。但在多模态大型语言模型（MLLMs）中，尤其是在需要遗忘视觉数据泄露的情况下，机器遗忘的有效性尚不明确。为此，我们提出了一种名为单图像遗忘（SIU）的高效方法，通过微调单张相关图像的几个步骤，实现对特定概念的视觉识别的遗忘。SIU方法包含两个核心要素：一是构建多面向的微调数据，我们依据四个目标为需遗忘的概念定制微调数据；二是采用联合训练损失，通过创新的双掩码KL散度损失结合交叉熵损失，同步实现概念视觉识别的遗忘并保持MLLMs的实用性。此外，我们还推出了MMUBench，一个针对MLLMs中机器遗忘的新基准，并配套了一系列评估指标。实验结果表明，SIU在MMUBench上的表现远超现有方法，并意外地发现它能有效防御成员推理攻击和越狱攻击。作为首个探索MLLMs中机器遗忘的研究，我们计划不久后公开代码和基准。

> Machine unlearning empowers individuals with the `right to be forgotten' by removing their private or sensitive information encoded in machine learning models. However, it remains uncertain whether MU can be effectively applied to Multimodal Large Language Models (MLLMs), particularly in scenarios of forgetting the leaked visual data of concepts. To overcome the challenge, we propose an efficient method, Single Image Unlearning (SIU), to unlearn the visual recognition of a concept by fine-tuning a single associated image for few steps. SIU consists of two key aspects: (i) Constructing Multifaceted fine-tuning data. We introduce four targets, based on which we construct fine-tuning data for the concepts to be forgotten; (ii) Jointly training loss. To synchronously forget the visual recognition of concepts and preserve the utility of MLLMs, we fine-tune MLLMs through a novel Dual Masked KL-divergence Loss combined with Cross Entropy loss. Alongside our method, we establish MMUBench, a new benchmark for MU in MLLMs and introduce a collection of metrics for its evaluation. Experimental results on MMUBench show that SIU completely surpasses the performance of existing methods. Furthermore, we surprisingly find that SIU can avoid invasive membership inference attacks and jailbreak attacks. To the best of our knowledge, we are the first to explore MU in MLLMs. We will release the code and benchmark in the near future.

[Arxiv](https://arxiv.org/abs/2405.12523)