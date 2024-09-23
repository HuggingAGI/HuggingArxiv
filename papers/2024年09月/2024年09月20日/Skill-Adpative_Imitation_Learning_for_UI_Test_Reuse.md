# UI 测试重用的技能适应性模仿学习

发布时间：2024年09月20日

`LLM应用` `软件测试` `移动应用`

> Skill-Adpative Imitation Learning for UI Test Reuse

# 摘要

> 为了降低手动创建 UI 测试用例的高昂成本，UI 测试迁移通过调整相似功能源应用的测试用例，自动为目标移动应用生成测试用例。传统上，这一过程被视为基于文本描述的源应用与目标应用事件映射问题。尽管大型语言模型 (LLM) 的 NLP 能力强大，但研究表明，LLM 的高精度事件映射仍无法解决源应用与目标应用间的实现差异，从而影响 LLM 驱动的 UI 测试迁移效果。为此，本文提出 SAIL，一个技能自适应模仿学习框架，通过两个关键设计提升 UI 测试迁移效果。首先，SAIL 利用源测试用例作为演示，通过多层次抽象提取测试信息，构建目标应用测试生成的知识库。其次，SAIL 选择性重用学习技能，结合上下文和历史感知，指导目标应用测试用例生成。SAIL 可与任何模仿学习技术结合，本文利用 LLM 的上下文学习能力实例化 SAIL。评估显示，SAIL 使 UI 测试迁移成功率比最先进方法提升 149%。

> To alleviate the substantial cost of manually crafting user interface (UI) test cases, UI test migration aims to automatically generate test cases for a target mobile application (app) by adapting those from a source app that shares similar functionalities. Traditionally, this process has been approached as a sequential UI-event-mapping problem, where events in the source app are mapped to those in the target one based on their textual descriptions. Prior research has extensively focused on enhancing the event-mapping accuracy of NLP models. Although the advent of large language models (LLMs) with impressive NLP capabilities suggests the potential for near-perfect event-mapping, our study demonstrates that even the highly accurate event-mapping of LLMs is insufficient to address the implementation discrepancies between the source and the target apps, reducing the overall effectiveness of LLM-driven solutions for UI test migration.
  To address this challenge, in this paper, we propose SAIL, a skill-adaptive imitation learning framework designed to enhance the effectiveness of UI test migration through two key designs. First, SAIL leverages the source test cases as demonstrations and employs a multi-level abstraction of test cases' underlying skills, so as to extract the testing information from source test cases as the knowledge base for the subsequent test generation on the target app. Second, SAIL selectively reuses a subset of the learned skills to guide the generation of test cases for the target app with its novel context- and history-aware skill adaptation. While SAIL can be instantiated with any imitation learning techniques, we utilize the in-context learning capabilities of LLMs to instantiate SAIL. Evaluations results show that SAIL substantially improves the effectiveness of UI test migration, with 149\% higher success rate than state-of-the-art approaches.

[Arxiv](https://arxiv.org/abs/2409.13311)