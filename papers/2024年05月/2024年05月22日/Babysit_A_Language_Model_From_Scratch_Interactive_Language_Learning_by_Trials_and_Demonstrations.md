# 从零开始培养语言模型：通过反复试验与实例演示，实现交互式语言学习之旅

发布时间：2024年05月22日

`Agent

这篇论文主要探讨了通过交互式学习框架（TnD）来提高语言模型的学习效率，特别是在词汇学习方面。研究通过实验验证了交互中的纠正反馈对神经语言学习的积极影响，并强调了教师示范和学生尝试在语言学习中的重要性。这种研究方向更偏向于Agent的范畴，因为它涉及到了模型的交互式学习和自主学习能力的提升，这与Agent的行为和学习机制紧密相关。` `语言学习` `教育技术`

> Babysit A Language Model From Scratch: Interactive Language Learning by Trials and Demonstrations

# 摘要

> 人类天生擅长语言学习，且具有强烈的社交倾向。我们的语言能力很大程度上是由社会互动塑造的，比如看护者的示范和反馈。相比之下，大型语言模型的最新进展主要依赖于非交互式的训练方法，并通过后续反馈来优化模型。本研究旨在通过一系列精心设计的实验，探究交互中的纠正反馈如何从根本上影响神经语言学习，并评估其是否能提高语言模型的学习效率。我们提出了一种试错与示范（TnD）学习框架，它包括学生尝试、教师示范和基于语言能力发展阶段的不同奖励。实验结果显示，TnD框架能显著加快参数相同或较少的学生模型的词汇学习速度，并强调了尝试和示范的双重作用。此外，我们还发现教师对词汇的选择会直接影响学生特定词汇的学习效率，且频繁的尝试与词汇学习曲线之间存在显著的正相关，验证了“熟能生巧”的效果。这些发现强调了交互式语言学习，即通过教师的示范和学生的尝试，在语言模型中促进高效词汇学习的重要性。

> Humans are efficient language learners and inherently social creatures. Our language development is largely shaped by our social interactions, for example, the demonstration and feedback from caregivers. Contrary to human language learning, recent advancements in large language models have primarily adopted a non-interactive training paradigm, and refined pre-trained models through feedback afterward. In this work, we aim to examine how corrective feedback from interactions influences neural language acquisition from the ground up through systematically controlled experiments, assessing whether it contributes to learning efficiency in language models. We introduce a trial-and-demonstration (TnD) learning framework that incorporates three components: student trials, teacher demonstrations, and a reward conditioned on language competence at various developmental stages. Our experiments reveal that the TnD approach accelerates word acquisition for student models of equal and smaller numbers of parameters, and we highlight the significance of both trials and demonstrations. We further show that the teacher's choices of words influence students' word-specific learning efficiency, and a practice-makes-perfect effect is evident by a strong correlation between the frequency of words in trials and their respective learning curves. Our findings suggest that interactive language learning, with teacher demonstrations and student trials, can facilitate efficient word learning in language models.

[Arxiv](https://arxiv.org/abs/2405.13828)