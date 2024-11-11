# 一个能够模仿角色语言风格的多任务角色扮演代理

发布时间：2024年11月03日

`Agent` `角色扮演`

> A Multi-Task Role-Playing Agent Capable of Imitating Character Linguistic Styles

# 摘要

> 大型语言模型（LLMs）的出现极大地推动了角色扮演代理（RPAs）的发展。然而，当前的角色扮演代理主要侧重于模仿角色的基本属性，而忽略了语言风格的复制，并且在执行多轮对话之外的任务时无法有效地复制角色，这导致生成的响应缺乏真实性。当前 RPAs 缺乏此能力的原因是由于现有角色数据集的性质，这些数据集缺乏角色引语的收集并且仅限于多轮对话任务，限制了 RPA 在其他任务领域的性能并且无法模仿角色的语言风格。为了解决这一差距，我们开发了一个名为 MRstyle 的多任务角色扮演数据集，其中包含大量真实个体及其引语，并涵盖七个不同的任务。在此基础上，我们开发了 StyleRPA，这是一种多任务角色扮演代理（MRPA），在包括对话、词典、作文、故事生成、产品描述、音乐评论和开放式问答在内的 7 项任务上显著优于最近的开源 LLMs 和 RPAs 基线。代码和数据将被发布。

> The advent of large language models (LLMs) has significantly propelled the advancement of Role-Playing Agents (RPAs). However, current Role-Playing Agents predominantly focus on mimicking a character's fundamental attributes while neglecting the replication of linguistic style, and they are incapable of effectively replicating characters when performing tasks beyond multi-turn dialogues, which results in generated responses that lack authenticity. The reason current RPAs lack this capability is due to the nature of existing character datasets, which lack collections of character quotations and are limited to multi-turn dialogue tasks, constraining the RPA's performance across other task domains and failing to mimic a character's linguistic style. To address this gap, we developed a multi-task role-playing dataset named MRstyle, which encompasses a substantial number of real individuals along with their quotations and covers seven different tasks. On this basis, we develop StyleRPA, a Multi-Task Role-Playing Agent (MRPA) that significantly outperforms recent open-source LLMs and RPAs baselines on 7 tasks including Dialogue, Dictionary, Composition, Story Generation, Product Description, Music Commentary, and Open Question Answering. The code and data will be released.

[Arxiv](https://arxiv.org/abs/2411.02457)