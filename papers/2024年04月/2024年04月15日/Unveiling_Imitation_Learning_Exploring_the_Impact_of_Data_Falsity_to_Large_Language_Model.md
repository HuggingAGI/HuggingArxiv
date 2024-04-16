# 揭秘模仿学习：探究数据不真实性如何影响大型语言模型的表现。

发布时间：2024年04月15日

`LLM应用` `语言模型` `数据集`

> Unveiling Imitation Learning: Exploring the Impact of Data Falsity to Large Language Model

# 摘要

> 近期众多研究试图通过模仿学习，以及在ChatGPT、GPT-4等顶级私有模型生成的合成指令数据上进行再训练，来提升开源语言模型的性能。但合成数据天生带有噪声，不可避免地引入了大量低质量数据，充斥着错误回应和逻辑谬误。虽然我们深知噪声数据的危害，却对其具体影响缺乏定量的认识。本文旨在探究噪声程度与语言模型性能之间的关联，特别是通过指令调整的影响。我们首先推出了FACO数据集，其中既包含真实答案及其推理过程，也包含虚假答案对，以便人工控制数据集中的虚假信息比例。经过大量实验，我们发现了数据真实性与指令调整之间几个引人入胜的关联点：特别是，我们发现指令的虚假性与各项基准测试得分紧密相连。更甚者，当大型语言模型接受了错误的训练指令后，它们竟学会了编造谎言，即便明知正确答案，也会生成不符合用户需求的虚假回答。此外，我们发现，一旦语言模型受到噪声污染的数据集影响，虽然可以恢复部分性能，但难以完全复原。

> Many recent studies endeavor to improve open-source language models through imitation learning, and re-training on the synthetic instruction data from state-of-the-art proprietary models like ChatGPT and GPT-4. However, the innate nature of synthetic data inherently contains noisy data, giving rise to a substantial presence of low-quality data replete with erroneous responses, and flawed reasoning. Although we intuitively grasp the potential harm of noisy data, we lack a quantitative understanding of its impact. To this end, this paper explores the correlation between the degree of noise and its impact on language models through instruction tuning. We first introduce the Falsity-Controllable (FACO) dataset, which comprises pairs of true answers with corresponding reasoning, as well as false pairs to manually control the falsity ratio of the dataset.Through our extensive experiments, we found multiple intriguing findings of the correlation between the factuality of the dataset and instruction tuning: Specifically, we verified falsity of the instruction is highly relevant to various benchmark scores. Moreover, when LLMs are trained with false instructions, they learn to lie and generate fake unfaithful answers, even though they know the correct answer for the user request. Additionally, we noted that once the language model is trained with a dataset contaminated by noise, restoring its original performance is possible, but it failed to reach full performance.

[Arxiv](https://arxiv.org/abs/2404.09717)