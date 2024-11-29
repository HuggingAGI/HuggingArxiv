# 一种能够增强大型语言模型中空间推理能力的神经符号集成管线

发布时间：2024年11月27日

`LLM应用` `空间推理` `人工智能`

> A Pipeline of Neural-Symbolic Integration to Enhance Spatial Reasoning in Large Language Models

# 摘要

> 大型语言模型（LLMs）在各类任务中展现出了非凡的能力。但 LLMs 在空间推理方面常显薄弱，空间推理作为推理和推断的关键一环，需要理解空间中物体间的复杂关系。此文提出了一种全新的神经符号框架，用以增强 LLMs 的空间推理能力。我们在两个基准数据集——StepGame 和 SparQA 上对该方法进行了评估，并采用了三种不同策略：（1）基于答案集编程（ASP）的符号推理；（2）运用 DSPy 的 LLM + ASP 管道；（3）事实 + 逻辑规则。实验表明，相比基线提示方法，有了显著的改进，在 StepGame 数据集上准确率提升了 40 - 50％，在更为复杂的 SparQA 数据集上提高了 3 - 13％。“LLM + ASP”管道在寻找关系（FR）和寻找块（FB）问题的任务中成果斐然，不过不同问题类型的表现有所差异。出色的结果显示，尽管神经符号方法为提升 LLMs 的空间推理能力指明了充满希望的方向，但其有效性在很大程度上取决于特定的任务特点和实施策略。我们提出了一套融合的、简洁却有效的策略，通过神经符号管道来增强 LLMs 的空间推理能力。该管道及其策略在 LLMs 的其他推理领域，如时间推理、演绎推理等方面，展现出了强大且更广泛的适用性。

> Large Language Models (LLMs) have demonstrated impressive capabilities across various tasks. However, LLMs often struggle with spatial reasoning which is one essential part of reasoning and inference and requires understanding complex relationships between objects in space. This paper proposes a novel neural-symbolic framework that enhances LLMs' spatial reasoning abilities. We evaluate our approach on two benchmark datasets: StepGame and SparQA, implementing three distinct strategies: (1) ASP (Answer Set Programming)-based symbolic reasoning, (2) LLM + ASP pipeline using DSPy, and (3) Fact + Logical rules. Our experiments demonstrate significant improvements over the baseline prompting methods, with accuracy increases of 40-50% on StepGame} dataset and 3-13% on the more complex SparQA dataset. The "LLM + ASP" pipeline achieves particularly strong results on the tasks of Finding Relations (FR) and Finding Block (FB) questions, though performance varies across different question types. The impressive results suggest that while neural-symbolic approaches offer promising directions for enhancing spatial reasoning in LLMs, their effectiveness depends heavily on the specific task characteristics and implementation strategies. We propose an integrated, simple yet effective set of strategies using a neural-symbolic pipeline to boost spatial reasoning abilities in LLMs. This pipeline and its strategies demonstrate strong and broader applicability to other reasoning domains in LLMs, such as temporal reasoning, deductive inference etc.

[Arxiv](https://arxiv.org/abs/2411.18564)