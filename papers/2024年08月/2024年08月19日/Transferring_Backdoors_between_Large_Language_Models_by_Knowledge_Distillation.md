# 利用知识蒸馏技术，实现大型语言模型间的后门转移

发布时间：2024年08月19日

`LLM应用` `网络安全` `人工智能`

> Transferring Backdoors between Large Language Models by Knowledge Distillation

# 摘要

> 后门攻击对大型语言模型构成了严重威胁。以往的研究仅在特定模型中揭示了这一风险，或在攻击预训练阶段后展示了任务的可转移性。本文探讨了小型 LLM 是否可能在不知情的情况下，通过知识蒸馏被中毒的教师 LLM 传授后门知识。为此，我们提出了 ATBA，一种自适应可转移的后门攻击方法，能在清洁调优过程中有效将后门知识传递给小模型。我们设计了目标触发器生成模块和自适应触发器优化模块，通过影子模型模拟蒸馏过程，实现基于梯度的最优触发器搜索。实验证明，ATBA 不仅能正面指导学生模型，还能隐秘地传递后门知识，转移率高达 80% 以上，旨在唤起对这一安全问题的关注。

> Backdoor Attacks have been a serious vulnerability against Large Language Models (LLMs). However, previous methods only reveal such risk in specific models, or present tasks transferability after attacking the pre-trained phase. So, how risky is the model transferability of a backdoor attack? In this paper, we focus on whether existing mini-LLMs may be unconsciously instructed in backdoor knowledge by poisoned teacher LLMs through knowledge distillation (KD). Specifically, we propose ATBA, an adaptive transferable backdoor attack, which can effectively distill the backdoor of teacher LLMs into small models when only executing clean-tuning. We first propose the Target Trigger Generation (TTG) module that filters out a set of indicative trigger candidates from the token list based on cosine similarity distribution. Then, we exploit a shadow model to imitate the distilling process and introduce an Adaptive Trigger Optimization (ATO) module to realize a gradient-based greedy feedback to search optimal triggers. Extensive experiments show that ATBA generates not only positive guidance for student models but also implicitly transfers backdoor knowledge. Our attack is robust and stealthy, with over 80% backdoor transferability, and hopes the attention of security.

[Arxiv](https://arxiv.org/abs/2408.09878)