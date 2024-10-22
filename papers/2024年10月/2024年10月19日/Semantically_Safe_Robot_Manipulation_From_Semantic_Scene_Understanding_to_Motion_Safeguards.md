# 机器人操作的语义安全：从场景理解到运动保护

发布时间：2024年10月19日

`Agent` `机器人` `计算机视觉`

> Semantically Safe Robot Manipulation: From Semantic Scene Understanding to Motion Safeguards

# 摘要

> 在以人为中心的环境中，机器人需理解并遵循人类的“常识”约束，如“勿将水杯置于电脑上方”或“旋转水杯易导致倾倒”。计算机视觉与机器学习的进步使机器人能理解并推理其操作环境。尽管安全决策文献丰富，但语义理解常被忽视。我们提出语义安全过滤器框架，结合语义与几何约束认证机器人输入。通过构建3D环境语义地图，并利用大型语言模型推断不安全条件，再将其转化为安全动作。实验证明，该方法在远程操作与拾取放置任务中，有效提升机器人安全操作，超越单纯碰撞避免。

> Ensuring safe interactions in human-centric environments requires robots to understand and adhere to constraints recognized by humans as "common sense" (e.g., "moving a cup of water above a laptop is unsafe as the water may spill" or "rotating a cup of water is unsafe as it can lead to pouring its content"). Recent advances in computer vision and machine learning have enabled robots to acquire a semantic understanding of and reason about their operating environments. While extensive literature on safe robot decision-making exists, semantic understanding is rarely integrated into these formulations. In this work, we propose a semantic safety filter framework to certify robot inputs with respect to semantically defined constraints (e.g., unsafe spatial relationships, behaviours, and poses) and geometrically defined constraints (e.g., environment-collision and self-collision constraints). In our proposed approach, given perception inputs, we build a semantic map of the 3D environment and leverage the contextual reasoning capabilities of large language models to infer semantically unsafe conditions. These semantically unsafe conditions are then mapped to safe actions through a control barrier certification formulation. We evaluated our semantic safety filter approach in teleoperated tabletop manipulation tasks and pick-and-place tasks, demonstrating its effectiveness in incorporating semantic constraints to ensure safe robot operation beyond collision avoidance.

[Arxiv](https://arxiv.org/abs/2410.15185)