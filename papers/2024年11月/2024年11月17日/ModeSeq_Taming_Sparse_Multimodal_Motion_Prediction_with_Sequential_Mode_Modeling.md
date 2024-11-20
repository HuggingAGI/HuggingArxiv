# ModeSeq：以顺序模式建模来驾驭稀疏多模态运动预测

发布时间：2024年11月17日

`其他` `自动驾驶`

> ModeSeq: Taming Sparse Multimodal Motion Prediction with Sequential Mode Modeling

# 摘要

> 预测未来事件的多模态性，为安全的自动驾驶筑牢根基。然而，由于缺乏多模态的真实数据，交通主体的多模态运动预测困难重重。现有的工作大多采用赢家通吃的训练策略来应对此挑战，可仍存在轨迹多样性不足和模式置信度不匹配的问题。有些方法虽通过生成大量轨迹候选来解决这些限制，但还需后处理阶段来甄别最具代表性的模式，此过程缺乏通用准则，还会影响轨迹的精准度。于是，我们积极引入 ModeSeq，这是一种将模式构建为序列的全新多模态预测范式。和一次性解码多个合理轨迹的常规做法不同，ModeSeq 要求运动解码器逐步推断下一个模式，从而更清晰地捕捉模式间的关联，显著增强对多模态的推理能力。借助顺序模式预测的归纳偏差，我们还提出了早期匹配全取（EMTA）训练策略，进一步让轨迹丰富多样。无需依赖密集模式预测或基于规则的轨迹选择，ModeSeq 大幅提升了多模态输出的多样性，同时收获了令人满意的轨迹准确性，在运动预测基准测试中达成了均衡的性能表现。此外，ModeSeq 天然具备模式外推的能力，能够在未来高度不确定时预测更多的行为模式。

> Anticipating the multimodality of future events lays the foundation for safe autonomous driving. However, multimodal motion prediction for traffic agents has been clouded by the lack of multimodal ground truth. Existing works predominantly adopt the winner-take-all training strategy to tackle this challenge, yet still suffer from limited trajectory diversity and misaligned mode confidence. While some approaches address these limitations by generating excessive trajectory candidates, they necessitate a post-processing stage to identify the most representative modes, a process lacking universal principles and compromising trajectory accuracy. We are thus motivated to introduce ModeSeq, a new multimodal prediction paradigm that models modes as sequences. Unlike the common practice of decoding multiple plausible trajectories in one shot, ModeSeq requires motion decoders to infer the next mode step by step, thereby more explicitly capturing the correlation between modes and significantly enhancing the ability to reason about multimodality. Leveraging the inductive bias of sequential mode prediction, we also propose the Early-Match-Take-All (EMTA) training strategy to diversify the trajectories further. Without relying on dense mode prediction or rule-based trajectory selection, ModeSeq considerably improves the diversity of multimodal output while attaining satisfactory trajectory accuracy, resulting in balanced performance on motion prediction benchmarks. Moreover, ModeSeq naturally emerges with the capability of mode extrapolation, which supports forecasting more behavior modes when the future is highly uncertain.

[Arxiv](https://arxiv.org/abs/2411.11911)