# GLOVER：用于面向任务抓取的可泛化开放词汇可供性推理

发布时间：2024年11月19日

`LLM应用` `机器人` `抓取规划`

> GLOVER: Generalizable Open-Vocabulary Affordance Reasoning for Task-Oriented Grasping

# 摘要

> 依据人类的规定来推断任意物体的可承受（即能抓取）部分，这对于机器人朝着开放词汇操作发展至关重要。然而，当下的抓取规划器因有限的视觉语言理解能力以及耗时的 3D 辐射建模而受阻，限制了与物体的实时、开放词汇交互。为应对这些局限，我们提出了 GLOVER，一个统一的通用开放词汇可供性推理框架，它对大型语言模型（LLMs）进行微调，以在 RGB 特征空间内预测可抓取物体部分的视觉可供性。我们整理了一个包含超过 10,000 张来自人与物体交互图像的数据集，并标注了统一的视觉和语言可供性标签，以实现多模态微调。GLOVER 从 LLMs 继承了世界知识和常识推理，有助于更精细的物体理解以及复杂的工具使用推理。为实现有效的实际应用，我们提出了可供性感知抓取估计（AGE），这是一种非参数抓取规划器，能使抓取器姿态与从可供性数据导出的超二次曲面相匹配。在 30 个真实场景的评估中，GLOVER 在部分识别方面的成功率达 86.0％，在抓取方面的成功率为 76.3％，在可供性推理方面的速度比之前的最先进技术快约 330 倍，在抓取姿态估计方面的速度快约 40 倍。

> Inferring affordable (i.e., graspable) parts of arbitrary objects based on human specifications is essential for robots advancing toward open-vocabulary manipulation. Current grasp planners, however, are hindered by limited vision-language comprehension and time-consuming 3D radiance modeling, restricting real-time, open-vocabulary interactions with objects. To address these limitations, we propose GLOVER, a unified Generalizable Open-Vocabulary Affordance Reasoning framework, which fine-tunes the Large Language Models (LLMs) to predict visual affordance of graspable object parts within RGB feature space. We compile a dataset of over 10,000 images from human-object interactions, annotated with unified visual and linguistic affordance labels, to enable multi-modal fine-tuning. GLOVER inherits world knowledge and common-sense reasoning from LLMs, facilitating more fine-grained object understanding and sophisticated tool-use reasoning. To enable effective real-world deployment, we present Affordance-Aware Grasping Estimation (AGE), a non-parametric grasp planner that aligns the gripper pose with a superquadric surface derived from affordance data. In evaluations across 30 real-world scenes, GLOVER achieves success rates of 86.0% in part identification and 76.3% in grasping, with speeds approximately 330 times faster in affordance reasoning and 40 times faster in grasping pose estimation than the previous state-of-the-art.

[Arxiv](https://arxiv.org/abs/2411.12286)