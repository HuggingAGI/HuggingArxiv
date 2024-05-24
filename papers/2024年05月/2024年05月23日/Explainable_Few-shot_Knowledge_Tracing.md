# 可解释的少量样本知识追踪研究

发布时间：2024年05月23日

`Agent

这篇论文主要关注的是知识追踪（KT）任务，并提出了一种新的方法，该方法利用大型语言模型（LLMs）的推理和生成能力来构建一个认知引导框架。这个框架不仅能够从少量的学生练习记录中追踪学生的知识状态，还能够提供自然语言解释。这种方法强调了在教育评估中使用LLMs的潜力，特别是在处理少量样本和提供解释性反馈方面。因此，这篇论文更符合Agent分类，因为它涉及使用LLMs作为智能代理来解决特定的教育问题。` `人工智能`

> Explainable Few-shot Knowledge Tracing

# 摘要

> 知识追踪（KT）是教育评估的核心，旨在通过分析学生的练习记录来预测其未来测试的表现。尽管深度学习技术带来了显著进展，但现有方法与实际教学环境仍有差距，主要依赖大量数据和数值预测，而非教师基于有限练习给出的解释性反馈。为此，我们提出了“可解释的少量样本知识追踪”新任务，借助LLMs的强大推理和生成能力，构建了一个认知引导框架，不仅能从少量记录中追踪学生知识，还能提供自然语言解释。实验表明，LLMs在多个数据集上的表现不逊于甚至超越了现有的深度知识追踪方法。我们探讨了未来的研究方向，并期待在相关领域取得更多进展。

> Knowledge tracing (KT), aiming to mine students' mastery of knowledge by their exercise records and predict their performance on future test questions, is a critical task in educational assessment. While researchers achieved tremendous success with the rapid development of deep learning techniques, current knowledge tracing tasks fall into the cracks from real-world teaching scenarios. Relying heavily on extensive student data and solely predicting numerical performances differs from the settings where teachers assess students' knowledge state from limited practices and provide explanatory feedback. To fill this gap, we explore a new task formulation: Explainable Few-shot Knowledge Tracing. By leveraging the powerful reasoning and generation abilities of large language models (LLMs), we then propose a cognition-guided framework that can track the student knowledge from a few student records while providing natural language explanations. Experimental results from three widely used datasets show that LLMs can perform comparable or superior to competitive deep knowledge tracing methods. We also discuss potential directions and call for future improvements in relevant topics.

[Arxiv](https://arxiv.org/abs/2405.14391)