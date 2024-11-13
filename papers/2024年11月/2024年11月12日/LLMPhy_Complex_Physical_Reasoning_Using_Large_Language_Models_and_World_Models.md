# LLMPhy：使用大型语言模型和世界模型的复杂物理推理

发布时间：2024年11月12日

`LLM应用` `机器人` `物理推理`

> LLMPhy: Complex Physical Reasoning Using Large Language Models and World Models

# 摘要

> 物理推理是机器人代理在现实世界中操作时所需的一项重要技能。然而，解决此类推理问题通常涉及在众多物理力的作用下假设和思考复杂的多体相互作用，因此学习所有这些相互作用对包括大型语言模型（LLM）在内的最先进机器学习框架构成了重大障碍。为了研究这个问题，我们提出了一个新的物理推理任务和一个数据集，称为 TraySim。我们的任务涉及预测在受到外部冲击的托盘上的几个物体的动态——随之而来的物体相互作用的多米诺效应及其动态，从而提供了一个具有挑战性但可控的设置，推理的目标是推断冲击后物体的稳定性。为了解决这个复杂的物理推理任务，我们提出了 LLMPhy，这是一个零样本黑箱优化框架，它利用了 LLM 的物理知识和程序综合能力，并将这些能力与现代物理引擎中内置的世界模型协同起来。具体来说，LLMPhy 使用 LLM 生成代码，通过一个（不可微的）模拟器在循环中使用隐式的分析合成方法迭代估计系统的物理超参数（摩擦、阻尼、布局等），并使用推断的参数来想象场景的动态以解决推理任务。为了展示 LLMPhy 的有效性，我们在我们的 TraySim 数据集上进行了实验，以预测物体的稳态姿势。我们的结果表明，LLM 和物理引擎的结合导致了最先进的零样本物理推理性能，同时展示了对标准黑箱优化方法的优越收敛性和对物理参数的更好估计。

> Physical reasoning is an important skill needed for robotic agents when operating in the real world. However, solving such reasoning problems often involves hypothesizing and reflecting over complex multi-body interactions under the effect of a multitude of physical forces and thus learning all such interactions poses a significant hurdle for state-of-the-art machine learning frameworks, including large language models (LLMs). To study this problem, we propose a new physical reasoning task and a dataset, dubbed TraySim. Our task involves predicting the dynamics of several objects on a tray that is given an external impact -- the domino effect of the ensued object interactions and their dynamics thus offering a challenging yet controlled setup, with the goal of reasoning being to infer the stability of the objects after the impact. To solve this complex physical reasoning task, we present LLMPhy, a zero-shot black-box optimization framework that leverages the physics knowledge and program synthesis abilities of LLMs, and synergizes these abilities with the world models built into modern physics engines. Specifically, LLMPhy uses an LLM to generate code to iteratively estimate the physical hyperparameters of the system (friction, damping, layout, etc.) via an implicit analysis-by-synthesis approach using a (non-differentiable) simulator in the loop and uses the inferred parameters to imagine the dynamics of the scene towards solving the reasoning task. To show the effectiveness of LLMPhy, we present experiments on our TraySim dataset to predict the steady-state poses of the objects. Our results show that the combination of the LLM and the physics engine leads to state-of-the-art zero-shot physical reasoning performance, while demonstrating superior convergence against standard black-box optimization methods and better estimation of the physical parameters.

[Arxiv](https://arxiv.org/abs/2411.08027)