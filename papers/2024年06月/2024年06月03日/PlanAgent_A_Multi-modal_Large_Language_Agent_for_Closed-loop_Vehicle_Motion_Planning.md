# PlanAgent：专为闭环车辆运动规划设计的多模态大型语言智能代理

发布时间：2024年06月03日

`Agent

理由：这篇论文介绍了一个名为PlanAgent的系统，它是基于多模态大型语言模型（MLLM）的中到中规划系统，专门设计用于车辆运动规划。PlanAgent通过模拟人类认知，将常识推理和可解释性融入闭环规划，这表明它是一个智能代理（Agent），能够自主进行决策和规划。此外，论文中提到的三大核心模块（环境转换模块、推理引擎模块和反射模块）都是为了增强Agent的规划能力，使其在复杂场景中表现出色。因此，这篇论文更适合归类为Agent。` `自动驾驶` `人工智能`

> PlanAgent: A Multi-modal Large Language Agent for Closed-loop Vehicle Motion Planning

# 摘要

> 车辆运动规划是自动驾驶的核心，而现有的基于规则的方法虽在常规场景中表现尚可，但在应对复杂多变的长尾情况时则显得捉襟见肘。学习型方法虽有潜力，但在大规模闭环测试中仍未超越传统方法。为此，我们创新性地推出了PlanAgent，这是首个基于多模态大型语言模型（MLLM）的中到中规划系统，它通过MLLM模拟人类认知，将常识推理和可解释性融入闭环规划。PlanAgent通过三大核心模块发挥MLLM的潜能：环境转换模块构建全景地图与文本描述；推理引擎模块从场景理解到运动指令层层递进，生成规划代码；反射模块则评估并优化规划，降低不确定性。PlanAgent凭借MLLM的强大能力，不仅应对常规场景游刃有余，更在复杂长尾场景中大放异彩。在nuPlan这一大型挑战性基准测试中，PlanAgent的表现超越了所有现有技术，其代码即将公开。

> Vehicle motion planning is an essential component of autonomous driving technology. Current rule-based vehicle motion planning methods perform satisfactorily in common scenarios but struggle to generalize to long-tailed situations. Meanwhile, learning-based methods have yet to achieve superior performance over rule-based approaches in large-scale closed-loop scenarios. To address these issues, we propose PlanAgent, the first mid-to-mid planning system based on a Multi-modal Large Language Model (MLLM). MLLM is used as a cognitive agent to introduce human-like knowledge, interpretability, and common-sense reasoning into the closed-loop planning. Specifically, PlanAgent leverages the power of MLLM through three core modules. First, an Environment Transformation module constructs a Bird's Eye View (BEV) map and a lane-graph-based textual description from the environment as inputs. Second, a Reasoning Engine module introduces a hierarchical chain-of-thought from scene understanding to lateral and longitudinal motion instructions, culminating in planner code generation. Last, a Reflection module is integrated to simulate and evaluate the generated planner for reducing MLLM's uncertainty. PlanAgent is endowed with the common-sense reasoning and generalization capability of MLLM, which empowers it to effectively tackle both common and complex long-tailed scenarios. Our proposed PlanAgent is evaluated on the large-scale and challenging nuPlan benchmarks. A comprehensive set of experiments convincingly demonstrates that PlanAgent outperforms the existing state-of-the-art in the closed-loop motion planning task. Codes will be soon released.

![PlanAgent：专为闭环车辆运动规划设计的多模态大型语言智能代理](../../../paper_images/2406.01587/x1.png)

![PlanAgent：专为闭环车辆运动规划设计的多模态大型语言智能代理](../../../paper_images/2406.01587/x2.png)

![PlanAgent：专为闭环车辆运动规划设计的多模态大型语言智能代理](../../../paper_images/2406.01587/x3.png)

![PlanAgent：专为闭环车辆运动规划设计的多模态大型语言智能代理](../../../paper_images/2406.01587/x4.png)

![PlanAgent：专为闭环车辆运动规划设计的多模态大型语言智能代理](../../../paper_images/2406.01587/x5.png)

![PlanAgent：专为闭环车辆运动规划设计的多模态大型语言智能代理](../../../paper_images/2406.01587/x6.png)

[Arxiv](https://arxiv.org/abs/2406.01587)