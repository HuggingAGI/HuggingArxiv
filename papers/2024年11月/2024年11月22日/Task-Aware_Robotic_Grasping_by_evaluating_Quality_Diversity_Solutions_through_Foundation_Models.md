# 借助基础模型对质量多样性解决方案进行评估，实现任务感知的机器人抓取

发布时间：2024年11月22日

`LLM应用` `机器人` `抓取技术`

> Task-Aware Robotic Grasping by evaluating Quality Diversity Solutions through Foundation Models

# 摘要

> 任务感知型机器人抓取是个颇具挑战的难题，它要求融合语义理解与几何推理。传统的抓取规划方式着重于稳定或可行的抓取，常常忽视机器人需完成的特定任务。此文提出了一个全新的框架，借助大型语言模型（LLMs）和质量多样性（QD）算法，达成零样本任务条件下的抓取选择。该框架把对象分割成有意义的子部分，并给每个子部分进行语义标注，构建出能用于提示LLM的结构化表述。通过将对象结构的语义和几何表示相耦合，LLM有关任务以及抓取哪些部分的知识能够应用于现实世界。QD生成的抓取档案提供了一系列多样化的抓取方式，让我们能依据任务选出最适宜的抓取。我们在YCB数据集的一个子集上对所提方法进行了评估，其中一个Franka Emika机器人被安排依据对象特定的任务要求执行各类动作。我们通过对六位参与者展开调查来确立一个基本事实，依照人类直觉确定每个任务 - 对象组合的最佳抓取区域。该模型针对12个不同对象的4至7个对象特定任务进行了评估，与调查数据相比，实现了76.4％的加权交并比（IoU）。

> Task-aware robotic grasping is a challenging problem that requires the integration of semantic understanding and geometric reasoning. Traditional grasp planning approaches focus on stable or feasible grasps, often disregarding the specific tasks the robot needs to accomplish. This paper proposes a novel framework that leverages Large Language Models (LLMs) and Quality Diversity (QD) algorithms to enable zero-shot task-conditioned grasp selection. The framework segments objects into meaningful subparts and labels each subpart semantically, creating structured representations that can be used to prompt an LLM. By coupling semantic and geometric representations of an object's structure, the LLM's knowledge about tasks and which parts to grasp can be applied in the physical world. The QD-generated grasp archive provides a diverse set of grasps, allowing us to select the most suitable grasp based on the task. We evaluate the proposed method on a subset of the YCB dataset, where a Franka Emika robot is assigned to perform various actions based on object-specific task requirements. We created a ground truth by conducting a survey with six participants to determine the best grasp region for each task-object combination according to human intuition. The model was evaluated on 12 different objects across 4--7 object-specific tasks, achieving a weighted intersection over union (IoU) of 76.4% when compared to the survey data.

[Arxiv](https://arxiv.org/abs/2411.14917)