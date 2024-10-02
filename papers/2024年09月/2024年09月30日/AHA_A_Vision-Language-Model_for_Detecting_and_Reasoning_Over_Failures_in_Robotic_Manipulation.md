# AHA：一款专为机器人操作故障检测与推理而设计的视觉-语言模型

发布时间：2024年09月30日

`Agent` `机器人` `人工智能`

> AHA: A Vision-Language-Model for Detecting and Reasoning Over Failures in Robotic Manipulation

# 摘要

> 在开放世界中进行机器人操作，不仅需要执行任务，还需具备检测和从失败中学习的能力。尽管视觉语言模型（VLM）和大型语言模型（LLM）的进步提升了机器人的空间推理和问题解决能力，但在失败识别方面仍有不足，限制了其在现实中的应用。为此，我们推出了AHA，一个开源的VLM，专门用于使用自然语言检测和分析机器人操作中的失败。通过将失败检测视为自由形式的推理任务，AHA能够识别失败并提供详尽且适应性强的解释，适用于各种机器人、任务和环境。我们利用FailGen框架对AHA进行了微调，该框架生成了首个大规模的机器人失败轨迹数据集——AHA数据集。尽管仅基于AHA数据集训练，AHA仍能有效应用于现实世界的失败场景、机器人系统和未见过的任务，表现优于GPT-4o等模型。我们将AHA整合到三个操作框架中，通过优化奖励函数、任务规划和子任务验证，显著提升了任务成功率，平均提高了21.4%。

> Robotic manipulation in open-world settings requires not only task execution but also the ability to detect and learn from failures. While recent advances in vision-language models (VLMs) and large language models (LLMs) have improved robots' spatial reasoning and problem-solving abilities, they still struggle with failure recognition, limiting their real-world applicability. We introduce AHA, an open-source VLM designed to detect and reason about failures in robotic manipulation using natural language. By framing failure detection as a free-form reasoning task, AHA identifies failures and provides detailed, adaptable explanations across different robots, tasks, and environments. We fine-tuned AHA using FailGen, a scalable framework that generates the first large-scale dataset of robotic failure trajectories, the AHA dataset. FailGen achieves this by procedurally perturbing successful demonstrations from simulation. Despite being trained solely on the AHA dataset, AHA generalizes effectively to real-world failure datasets, robotic systems, and unseen tasks. It surpasses the second-best model (GPT-4o in-context learning) by 10.3% and exceeds the average performance of six compared models including five state-of-the-art VLMs by 35.3% across multiple metrics and datasets. We integrate AHA into three manipulation frameworks that utilize LLMs/VLMs for reinforcement learning, task and motion planning, and zero-shot trajectory generation. AHA's failure feedback enhances these policies' performances by refining dense reward functions, optimizing task planning, and improving sub-task verification, boosting task success rates by an average of 21.4% across all three tasks compared to GPT-4 models.

[Arxiv](https://arxiv.org/abs/2410.00371)