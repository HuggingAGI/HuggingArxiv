# GravMAD：以空间价值地图为基石，引导动作在 3D 空间中自由扩散，实现广义操作。

发布时间：2024年09月30日

`Agent` `机器人` `人工智能`

> GravMAD: Grounded Spatial Value Maps Guided Action Diffusion for Generalized 3D Manipulation

# 摘要

> 机器人能否遵循语言指令执行多样化的3D任务，是机器人学习中的关键。传统模仿学习虽在已知任务上表现出色，但面对新颖任务时却因多样性而力不从心。近期，借助大型基础模型理解新任务的方法虽有所缓解，但仍缺乏任务特定学习，导致3D环境理解不准确，执行时常失败。为此，我们推出了GravMAD，一种结合模仿学习与基础模型优势的子目标驱动语言条件动作扩散框架。该框架根据语言指令将任务细分为子目标，训练与推理皆有辅助指导。训练时，通过子目标关键姿态发现识别关键子目标；推理时，则依赖预训练基础模型填补空白，识别当前任务子目标。两阶段均生成GravMaps，提供比固定3D位置更灵活的空间指导。在RLBench上的实证评估表明，GravMAD在新任务上提升28.63%，在训练任务上提升13.36%，显著超越现有技术。这充分展现了GravMAD在3D操作中的卓越多任务学习和泛化能力。视频演示详见：https://gravmad.github.io。

> Robots' ability to follow language instructions and execute diverse 3D tasks is vital in robot learning. Traditional imitation learning-based methods perform well on seen tasks but struggle with novel, unseen ones due to variability. Recent approaches leverage large foundation models to assist in understanding novel tasks, thereby mitigating this issue. However, these methods lack a task-specific learning process, which is essential for an accurate understanding of 3D environments, often leading to execution failures. In this paper, we introduce GravMAD, a sub-goal-driven, language-conditioned action diffusion framework that combines the strengths of imitation learning and foundation models. Our approach breaks tasks into sub-goals based on language instructions, allowing auxiliary guidance during both training and inference. During training, we introduce Sub-goal Keypose Discovery to identify key sub-goals from demonstrations. Inference differs from training, as there are no demonstrations available, so we use pre-trained foundation models to bridge the gap and identify sub-goals for the current task. In both phases, GravMaps are generated from sub-goals, providing flexible 3D spatial guidance compared to fixed 3D positions. Empirical evaluations on RLBench show that GravMAD significantly outperforms state-of-the-art methods, with a 28.63% improvement on novel tasks and a 13.36% gain on tasks encountered during training. These results demonstrate GravMAD's strong multi-task learning and generalization in 3D manipulation. Video demonstrations are available at: https://gravmad.github.io.

[Arxiv](https://arxiv.org/abs/2409.20154)