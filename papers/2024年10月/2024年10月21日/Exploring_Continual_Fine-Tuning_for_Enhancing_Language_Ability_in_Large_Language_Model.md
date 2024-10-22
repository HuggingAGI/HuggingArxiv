# 探索持续微调，提升大型语言模型的语言能力

发布时间：2024年10月21日

`LLM理论` `人工智能` `语言处理`

> Exploring Continual Fine-Tuning for Enhancing Language Ability in Large Language Model

# 摘要

> 大型语言模型 (LLM) 面临的一大挑战是如何在学习新语言的同时，不损害其在已熟练掌握的语言（通常是英语）上的表现。持续微调 (CFT) 通过逐步微调 LLM，使其适应数据分布和时间变化多端的下游任务。本文聚焦于通过 CFT 提升 LLM 的语言适应性。我们设计了一个两阶段 CFT 过程：第一阶段主要提升任务能力，LLM 仅使用英语进行端到端微调；第二阶段则侧重于语言能力，LLM 逐步微调于包含新语言任务数据的多语言数据集。我们发现，第二阶段任务与第一阶段的相似性直接影响 LLM 的适应性。若两阶段数据集相似，LLM 在第二阶段后任务能力不减；反之，任务能力则会退化。我们在开源的 \mis\ 和 \llm\ 模型上验证了这一假设，并测试了多个阶段数据集对。为应对任务能力退化，我们探索了两种 CFT 方法的定制变体：层冻结和生成重放。研究结果显示，这些方法在提升 LLM 语言能力的同时，还能有效保持其任务性能，优于传统基线方法。

> A common challenge towards the adaptability of Large Language Models (LLMs) is their ability to learn new languages over time without hampering the model's performance on languages in which the model is already proficient (usually English). Continual fine-tuning (CFT) is the process of sequentially fine-tuning an LLM to enable the model to adapt to downstream tasks with varying data distributions and time shifts. This paper focuses on the language adaptability of LLMs through CFT. We study a two-phase CFT process in which an English-only end-to-end fine-tuned LLM from Phase 1 (predominantly Task Ability) is sequentially fine-tuned on a multilingual dataset -- comprising task data in new languages -- in Phase 2 (predominantly Language Ability). We observe that the ``similarity'' of Phase 2 tasks with Phase 1 determines the LLM's adaptability. For similar phase-wise datasets, the LLM after Phase 2 does not show deterioration in task ability. In contrast, when the phase-wise datasets are not similar, the LLM's task ability deteriorates. We test our hypothesis on the open-source \mis\ and \llm\ models with multiple phase-wise dataset pairs. To address the deterioration, we analyze tailored variants of two CFT methods: layer freezing and generative replay. Our findings demonstrate their effectiveness in enhancing the language ability of LLMs while preserving task performance, in comparison to relevant baselines.

[Arxiv](https://arxiv.org/abs/2410.16006)