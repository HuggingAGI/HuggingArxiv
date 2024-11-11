# RT-Affordance：可供性是用于机器人操作的通用中间表示。

发布时间：2024年11月04日

`Agent` `机器人` `互联网`

> RT-Affordance: Affordances are Versatile Intermediate Representations for Robot Manipulation

# 摘要

> 我们探讨了中间策略表示如何通过提供如何执行操作任务的指导来促进泛化。现有的表示，如语言、目标图像和轨迹草图已被证明是有帮助的，但这些表示要么没有提供足够的上下文，要么提供了过度指定的上下文，导致策略不够稳健。我们提出以可供性为条件制定策略，它捕获了机器人在任务关键阶段的姿态。可供性提供了富有表现力但轻量级的抽象，易于用户指定，并通过从大型互联网数据集中转移知识促进高效学习。我们的方法，RT-Affordance，是一个分层模型，首先根据任务语言提出一个可供性计划，然后根据这个可供性计划制定策略来执行操作。我们的模型可以灵活地连接包括大型网络数据集和机器人轨迹在内的异构监督源。我们还在易于收集的域内可供性图像上训练我们的模型，使我们能够在不收集任何额外昂贵的机器人轨迹的情况下学习新任务。我们在一系列不同的新任务上展示了 RT-Affordance 如何超过现有方法 50%以上的性能，并且我们通过实验证明了可供性对新设置具有鲁棒性。视频可在 https://snasiriany.me/rt-affordance 查看。

> We explore how intermediate policy representations can facilitate generalization by providing guidance on how to perform manipulation tasks. Existing representations such as language, goal images, and trajectory sketches have been shown to be helpful, but these representations either do not provide enough context or provide over-specified context that yields less robust policies. We propose conditioning policies on affordances, which capture the pose of the robot at key stages of the task. Affordances offer expressive yet lightweight abstractions, are easy for users to specify, and facilitate efficient learning by transferring knowledge from large internet datasets. Our method, RT-Affordance, is a hierarchical model that first proposes an affordance plan given the task language, and then conditions the policy on this affordance plan to perform manipulation. Our model can flexibly bridge heterogeneous sources of supervision including large web datasets and robot trajectories. We additionally train our model on cheap-to-collect in-domain affordance images, allowing us to learn new tasks without collecting any additional costly robot trajectories. We show on a diverse set of novel tasks how RT-Affordance exceeds the performance of existing methods by over 50%, and we empirically demonstrate that affordances are robust to novel settings. Videos available at https://snasiriany.me/rt-affordance

[Arxiv](https://arxiv.org/abs/2411.02704)