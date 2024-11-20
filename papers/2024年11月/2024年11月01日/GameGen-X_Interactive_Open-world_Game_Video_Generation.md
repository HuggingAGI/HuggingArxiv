# GameGen-X：交互式开放世界游戏视频的生成

发布时间：2024年11月01日

`LLM应用` `视频生成`

> GameGen-X: Interactive Open-world Game Video Generation

# 摘要

> 我们推出了 GameGen-X，这是首个专为生成和交互式掌控开放世界游戏视频而打造的扩散变压器模型。此模型通过模拟众多游戏引擎特性，像是创新角色、动态环境、复杂动作以及多样事件，助力实现高质量的开放领域生成。而且，它具备交互可控性，能依据当前片段预测并更改未来内容，进而达成游戏玩法模拟。为达成这一目标，我们起初从零着手收集并构建了一个开放世界视频游戏数据集。这是首个也是规模最大的用于开放世界游戏视频生成与控制的数据集，涵盖了从 150 多款游戏中采样的逾百万个多样的游戏玩法视频片段，还配有来自 GPT-4o 的丰富说明。GameGen-X 历经了两阶段的训练流程，包含基础模型预训练和指令调优。首先，模型通过文本转视频生成和视频延续进行预训练，从而拥有长序列、高质量开放领域游戏视频生成的本领。再者，为实现交互可控性，我们设计了 InstructNet 以整合游戏相关的多模态控制信号专家。这让模型能够依照用户输入调整潜在表征，在视频生成中首次统一了角色交互和场景内容控制。在指令调优期间，仅 InstructNet 得到更新，预训练的基础模型则保持不变，在不折损生成视频内容的多样性和质量的前提下，实现了交互可控性的融合。

> We introduce GameGen-X, the first diffusion transformer model specifically designed for both generating and interactively controlling open-world game videos. This model facilitates high-quality, open-domain generation by simulating an extensive array of game engine features, such as innovative characters, dynamic environments, complex actions, and diverse events. Additionally, it provides interactive controllability, predicting and altering future content based on the current clip, thus allowing for gameplay simulation. To realize this vision, we first collected and built an Open-World Video Game Dataset from scratch. It is the first and largest dataset for open-world game video generation and control, which comprises over a million diverse gameplay video clips sampling from over 150 games with informative captions from GPT-4o. GameGen-X undergoes a two-stage training process, consisting of foundation model pre-training and instruction tuning. Firstly, the model was pre-trained via text-to-video generation and video continuation, endowing it with the capability for long-sequence, high-quality open-domain game video generation. Further, to achieve interactive controllability, we designed InstructNet to incorporate game-related multi-modal control signal experts. This allows the model to adjust latent representations based on user inputs, unifying character interaction and scene content control for the first time in video generation. During instruction tuning, only the InstructNet is updated while the pre-trained foundation model is frozen, enabling the integration of interactive controllability without loss of diversity and quality of generated video content.

[Arxiv](https://arxiv.org/abs/2411.00769)