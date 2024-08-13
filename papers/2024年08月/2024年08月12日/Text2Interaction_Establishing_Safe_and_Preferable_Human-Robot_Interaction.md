# Text2Interaction：打造安全且受欢迎的人机互动

发布时间：2024年08月12日

`LLM应用` `人工智能` `用户体验`

> Text2Interaction: Establishing Safe and Preferable Human-Robot Interaction

# 摘要

> 为了快速适应新用户和变化，我们提出了Text2Interaction框架，通过大型语言模型生成任务计划和安全控制参数，以零-shot方式整合用户偏好。该框架通过最大化任务完成和用户满意度的综合概率，而非传统的手动平衡奖励，确保了计划的可靠性。实验显示，83%的用户认为其偏好被有效整合，94%的用户更偏爱此框架。消融研究进一步证明，Text2Interaction在保持高成功率的同时，能更好地适应未见过的用户偏好。

> Adjusting robot behavior to human preferences can require intensive human feedback, preventing quick adaptation to new users and changing circumstances. Moreover, current approaches typically treat user preferences as a reward, which requires a manual balance between task success and user satisfaction. To integrate new user preferences in a zero-shot manner, our proposed Text2Interaction framework invokes large language models to generate a task plan, motion preferences as Python code, and parameters of a safe controller. By maximizing the combined probability of task completion and user satisfaction instead of a weighted sum of rewards, we can reliably find plans that fulfill both requirements. We find that 83% of users working with Text2Interaction agree that it integrates their preferences into the robot's plan, and 94% prefer Text2Interaction over the baseline. Our ablation study shows that Text2Interaction aligns better with unseen preferences than other baselines while maintaining a high success rate.

[Arxiv](https://arxiv.org/abs/2408.06105)