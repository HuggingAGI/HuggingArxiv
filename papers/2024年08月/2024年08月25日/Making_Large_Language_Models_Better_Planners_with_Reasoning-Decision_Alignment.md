# 通过推理与决策的精准对齐，我们能够让大型语言模型在规划领域表现更出色。

发布时间：2024年08月25日

`LLM应用` `自动驾驶`

> Making Large Language Models Better Planners with Reasoning-Decision Alignment

# 摘要

> 过去十年，自动驾驶领域广泛采用数据驱动方法，但存在数据偏差和解释性不足的问题。受人类驾驶知识驱动启发，近期研究利用大型语言模型（LLM）提升交通场景中的理解和决策能力。研究发现，结合链式思维（CoT）推理的预训练-微调模式能增强解释性和场景理解。然而，这种策略存在CoT设计与决策不一致的问题，先前方法未解决。为此，我们提出基于多模态LLM的端到端决策模型，同时进行CoT推理和规划，并引入推理-决策对齐约束，确保推理与决策的一致性。我们还重新设计CoT，增强模型对复杂场景的理解和决策性能。我们将这一新模型命名为RDA-Driver。实验显示，RDA-Driver在nuScenes和DriveLM-nuScenes基准上显著提升了端到端自动驾驶系统的性能，实现了行业领先的规划效果。

> Data-driven approaches for autonomous driving (AD) have been widely adopted in the past decade but are confronted with dataset bias and uninterpretability. Inspired by the knowledge-driven nature of human driving, recent approaches explore the potential of large language models (LLMs) to improve understanding and decision-making in traffic scenarios. They find that the pretrain-finetune paradigm of LLMs on downstream data with the Chain-of-Thought (CoT) reasoning process can enhance explainability and scene understanding. However, such a popular strategy proves to suffer from the notorious problems of misalignment between the crafted CoTs against the consequent decision-making, which remains untouched by previous LLM-based AD methods. To address this problem, we motivate an end-to-end decision-making model based on multimodality-augmented LLM, which simultaneously executes CoT reasoning and carries out planning results. Furthermore, we propose a reasoning-decision alignment constraint between the paired CoTs and planning results, imposing the correspondence between reasoning and decision-making. Moreover, we redesign the CoTs to enable the model to comprehend complex scenarios and enhance decision-making performance. We dub our proposed large language planners with reasoning-decision alignment as RDA-Driver. Experimental evaluations on the nuScenes and DriveLM-nuScenes benchmarks demonstrate the effectiveness of our RDA-Driver in enhancing the performance of end-to-end AD systems. Specifically, our RDA-Driver achieves state-of-the-art planning performance on the nuScenes dataset with 0.80 L2 error and 0.32 collision rate, and also achieves leading results on challenging DriveLM-nuScenes benchmarks with 0.82 L2 error and 0.38 collision rate.

[Arxiv](https://arxiv.org/abs/2408.13890)