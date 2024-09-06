# OccLLaMA：一款专为自动驾驶设计的占用-语言-动作生成世界模型，助力智能驾驶的未来。

发布时间：2024年09月05日

`LLM应用` `自动驾驶` `人工智能`

> OccLLaMA: An Occupancy-Language-Action Generative World Model for Autonomous Driving

# 摘要

> 多模态大型语言模型 (MLLM) 在自动驾驶领域的应用日益广泛。然而，现有方法多通过直接映射感知与动作，忽略了世界动态与动作间的复杂关系。相比之下，人类凭借其世界模型，能基于 3D 视觉模拟未来并规划行动。为此，我们推出了 OccLLaMA，一个结合占用、语言与动作的生成世界模型，通过自回归模型统一视觉、语言与动作模态。我们创新性地设计了 VQVAE 类场景标记器，高效处理语义占用场景的稀疏性与类别不平衡。此外，我们构建了视觉、语言与动作的统一词汇表，并强化了 LLaMA 模型，使其能在自动驾驶任务中进行多任务处理。实验结果显示，OccLLaMA 在 4D 占用预测、运动规划及视觉问答等多项任务中表现优异，展现了其在自动驾驶领域的巨大潜力。

> The rise of multi-modal large language models(MLLMs) has spurred their applications in autonomous driving. Recent MLLM-based methods perform action by learning a direct mapping from perception to action, neglecting the dynamics of the world and the relations between action and world dynamics. In contrast, human beings possess world model that enables them to simulate the future states based on 3D internal visual representation and plan actions accordingly. To this end, we propose OccLLaMA, an occupancy-language-action generative world model, which uses semantic occupancy as a general visual representation and unifies vision-language-action(VLA) modalities through an autoregressive model. Specifically, we introduce a novel VQVAE-like scene tokenizer to efficiently discretize and reconstruct semantic occupancy scenes, considering its sparsity and classes imbalance. Then, we build a unified multi-modal vocabulary for vision, language and action. Furthermore, we enhance LLM, specifically LLaMA, to perform the next token/scene prediction on the unified vocabulary to complete multiple tasks in autonomous driving. Extensive experiments demonstrate that OccLLaMA achieves competitive performance across multiple tasks, including 4D occupancy forecasting, motion planning, and visual question answering, showcasing its potential as a foundation model in autonomous driving.

[Arxiv](https://arxiv.org/abs/2409.03272)