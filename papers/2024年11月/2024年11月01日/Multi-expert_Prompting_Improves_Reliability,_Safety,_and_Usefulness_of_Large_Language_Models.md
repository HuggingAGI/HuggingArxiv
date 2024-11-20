# 多专家提示提升了大型语言模型的可靠性、安全性及有用性

发布时间：2024年11月01日

`LLM应用` `语言模型` `决策框架`

> Multi-expert Prompting Improves Reliability, Safety, and Usefulness of Large Language Models

# 摘要

> 我们推出了多专家提示，这是对 ExpertPrompting（Xu 等人，2023）的创新增强，旨在优化大型语言模型（LLM）的生成效果。具体而言，它通过模拟多位专家，汇总他们的回应，并从个体和汇总的回应中选出最优者，来引导 LLM 完成输入指令。这一过程借助我们依据名义小组技术（Ven 和 Delbecq，1974）精心设计的七个子任务，在单一的思维链条中得以实现，该技术是一个成熟的决策框架。我们的评估显示，多专家提示在提升回应的真实性、事实性、信息量和有用性，以及降低毒性和伤害性方面，明显优于 ExpertPrompting 及同类基线。它还以超越 ChatGPT 最佳基线 8.69%的成绩，进一步达成了最前沿的真实性。多专家提示高效、可解释，对各类场景适应性强，无需人工构建提示。

> We present Multi-expert Prompting, a novel enhancement of ExpertPrompting (Xu et al., 2023), designed to improve the large language model (LLM) generation. Specifically, it guides an LLM to fulfill an input instruction by simulating multiple experts, aggregating their responses, and selecting the best among individual and aggregated responses. This process is performed in a single chain of thoughts through our seven carefully designed subtasks derived from the Nominal Group Technique (Ven and Delbecq, 1974), a well-established decision-making framework. Our evaluations demonstrate that Multi-expert Prompting significantly outperforms ExpertPrompting and comparable baselines in enhancing the truthfulness, factuality, informativeness, and usefulness of responses while reducing toxicity and hurtfulness. It further achieves state-of-the-art truthfulness by outperforming the best baseline by 8.69% with ChatGPT. Multi-expert Prompting is efficient, explainable, and highly adaptable to diverse scenarios, eliminating the need for manual prompt construction.

[Arxiv](https://arxiv.org/abs/2411.00492)