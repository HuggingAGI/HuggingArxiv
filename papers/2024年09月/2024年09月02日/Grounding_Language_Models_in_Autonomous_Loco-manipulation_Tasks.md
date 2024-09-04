# 将语言模型锚定于自主定位与操作任务中

发布时间：2024年09月02日

`Agent` `机器人` `人工智能`

> Grounding Language Models in Autonomous Loco-manipulation Tasks

# 摘要

> 人形机器人因其行为自主性，在日常生活中被视为理想的协作伙伴，并代表了具身智能的潜力。与固定机械臂相比，人形机器人虽扩大了操作空间，但也增加了控制和规划的复杂性。尽管通用型人形机器人的发展迅速，但研究多聚焦于移动能力，对全身协调和任务规划的关注不足，限制了其在开放式指令下执行复杂任务的能力。为此，我们提出了一种结合强化学习和全身优化的框架，通过学习、选择和规划行为，生成并存储机器人动作。同时，我们利用大型语言模型的规划和推理能力，构建了一个连接低级执行和高级规划的分层任务图。实验证明，该框架能有效适应新任务，并在非结构化场景中展现出高度的自主性。

> Humanoid robots with behavioral autonomy have consistently been regarded as ideal collaborators in our daily lives and promising representations of embodied intelligence. Compared to fixed-based robotic arms, humanoid robots offer a larger operational space while significantly increasing the difficulty of control and planning. Despite the rapid progress towards general-purpose humanoid robots, most studies remain focused on locomotion ability with few investigations into whole-body coordination and tasks planning, thus limiting the potential to demonstrate long-horizon tasks involving both mobility and manipulation under open-ended verbal instructions. In this work, we propose a novel framework that learns, selects, and plans behaviors based on tasks in different scenarios. We combine reinforcement learning (RL) with whole-body optimization to generate robot motions and store them into a motion library. We further leverage the planning and reasoning features of the large language model (LLM), constructing a hierarchical task graph that comprises a series of motion primitives to bridge lower-level execution with higher-level planning. Experiments in simulation and real-world using the CENTAURO robot show that the language model based planner can efficiently adapt to new loco-manipulation tasks, demonstrating high autonomy from free-text commands in unstructured scenes.

[Arxiv](https://arxiv.org/abs/2409.01326)