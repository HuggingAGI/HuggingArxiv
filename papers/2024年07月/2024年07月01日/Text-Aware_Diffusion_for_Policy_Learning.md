# 文本感知扩散在政策学习中的应用

发布时间：2024年07月01日

`Agent` `机器人` `人工智能`

> Text-Aware Diffusion for Policy Learning

# 摘要

> 通过强化学习训练代理实现特定目标或行为，尤其是在缺乏专家演示时，通常需要临时设计奖励函数，这很快变得复杂。为此，我们引入了文本感知扩散策略学习（TADPoLe），利用预训练的文本条件扩散模型生成零-shot奖励信号，促进文本对齐策略的学习。我们相信，大规模预训练模型蕴含的丰富先验知识，不仅能指导策略与文本一致，还能与互联网数据中提炼的自然性相契合。实验证明，TADPoLe能在不同环境中，无需真实奖励或专家演示，零-shot学习自然语言描述的新目标和连续运动行为，且在人类评估中表现更自然。此外，TADPoLe在机器人操作任务中也展现出竞争力。

> Training an agent to achieve particular goals or perform desired behaviors is often accomplished through reinforcement learning, especially in the absence of expert demonstrations. However, supporting novel goals or behaviors through reinforcement learning requires the ad-hoc design of appropriate reward functions, which quickly becomes intractable. To address this challenge, we propose Text-Aware Diffusion for Policy Learning (TADPoLe), which uses a pretrained, frozen text-conditioned diffusion model to compute dense zero-shot reward signals for text-aligned policy learning. We hypothesize that large-scale pretrained generative models encode rich priors that can supervise a policy to behave not only in a text-aligned manner, but also in alignment with a notion of naturalness summarized from internet-scale training data. In our experiments, we demonstrate that TADPoLe is able to learn policies for novel goal-achievement and continuous locomotion behaviors specified by natural language, in both Humanoid and Dog environments. The behaviors are learned zero-shot without ground-truth rewards or expert demonstrations, and are qualitatively more natural according to human evaluation. We further show that TADPoLe performs competitively when applied to robotic manipulation tasks in the Meta-World environment.

[Arxiv](https://arxiv.org/abs/2407.01903)