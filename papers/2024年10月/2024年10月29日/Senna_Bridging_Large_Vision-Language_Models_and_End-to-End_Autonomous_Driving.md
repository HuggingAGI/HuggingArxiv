# 塞纳：架起大型视觉语言模型与端到端自动驾驶之间的桥梁

发布时间：2024年10月29日

`LLM应用` `自动驾驶`

> Senna: Bridging Large Vision-Language Models and End-to-End Autonomous Driving

# 摘要

> 端到端自动驾驶依靠大规模数据彰显出强大的规划能力，然而在复杂、罕见的场景中，因常识有限而举步维艰。相较而言，大型视觉语言模型（LVLMs）在场景理解和推理方面表现卓越。未来的方向在于融合二者的优势。此前利用 LVLMs 预测轨迹或控制信号的方法成效欠佳，原因是 LVLMs 不太擅长精确的数值预测。本文介绍了 Senna，这是一个将 LVLM（Senna-VLM）与端到端模型（Senna-E2E）相结合的自动驾驶系统。Senna 把高级规划和低级轨迹预测分离开来。Senna-VLM 用自然语言生成规划决策，Senna-E2E 则预测精确轨迹。Senna-VLM 采用多图像编码方式和多视图提示来实现高效的场景理解。另外，我们引入了面向规划的问答以及三阶段训练策略，在保留常识的同时提升了 Senna-VLM 的规划性能。在两个数据集上开展的大量实验表明，Senna 达成了顶尖的规划性能。特别要指出的是，在大规模数据集 DriveX 上预训练，并在 nuScenes 上微调后，与未预训练的模型相比，Senna 显著降低了平均规划误差 27.12%，碰撞率降低了 33.33%。我们坚信 Senna 的跨场景泛化和可迁移性对于实现完全自动驾驶至关重要。代码和模型将在 https://github.com/hustvl/Senna 发布。

> End-to-end autonomous driving demonstrates strong planning capabilities with large-scale data but still struggles in complex, rare scenarios due to limited commonsense. In contrast, Large Vision-Language Models (LVLMs) excel in scene understanding and reasoning. The path forward lies in merging the strengths of both approaches. Previous methods using LVLMs to predict trajectories or control signals yield suboptimal results, as LVLMs are not well-suited for precise numerical predictions. This paper presents Senna, an autonomous driving system combining an LVLM (Senna-VLM) with an end-to-end model (Senna-E2E). Senna decouples high-level planning from low-level trajectory prediction. Senna-VLM generates planning decisions in natural language, while Senna-E2E predicts precise trajectories. Senna-VLM utilizes a multi-image encoding approach and multi-view prompts for efficient scene understanding. Besides, we introduce planning-oriented QAs alongside a three-stage training strategy, which enhances Senna-VLM's planning performance while preserving commonsense. Extensive experiments on two datasets show that Senna achieves state-of-the-art planning performance. Notably, with pre-training on a large-scale dataset DriveX and fine-tuning on nuScenes, Senna significantly reduces average planning error by 27.12% and collision rate by 33.33% over model without pre-training. We believe Senna's cross-scenario generalization and transferability are essential for achieving fully autonomous driving. Code and models will be released at https://github.com/hustvl/Senna.

[Arxiv](https://arxiv.org/abs/2410.22313)