# MotionCharacter：可保持身份且运动可控的人类视频生成

发布时间：2024年11月27日

`其他` `视频生成` `个性化服务`

> MotionCharacter: Identity-Preserving and Motion Controllable Human Video Generation

# 摘要

> 个性化文本到视频（T2V）生成的最新进展凸显了融合角色特定身份与动作的重要性。然而，以往的 T2V 模型在身份一致性和可控运动动态方面遭遇困境，主要归因于有限的细粒度面部及基于动作的文本提示，还有那些忽视关键人类属性和动作的数据集。为应对这些挑战，我们提出了 MotionCharacter，这是一个高效且高保真的人类视频生成框架，专为身份留存和细粒度运动控制而打造。我们引入了身份保留模块，在允许灵活修改属性的同时保持身份的保真度，并进一步整合了身份一致性和区域感知损失机制，极大地增强了身份一致性和细节保真度。此外，我们的方法融入了一个运动控制模块，在维持主题一致性的同时优先考虑与动作相关的文本，还有一个名为 Human-Motion 的数据集，它借助大型语言模型生成详细的运动描述。为在推理时简化用户控制，我们通过单个系数对运动强度进行参数化，便于轻松调节。大量实验彰显了 MotionCharacter 的有效性，表明其在身份留存和高质量视频生成方面有显著提升。

> Recent advancements in personalized Text-to-Video (T2V) generation highlight the importance of integrating character-specific identities and actions. However, previous T2V models struggle with identity consistency and controllable motion dynamics, mainly due to limited fine-grained facial and action-based textual prompts, and datasets that overlook key human attributes and actions. To address these challenges, we propose MotionCharacter, an efficient and high-fidelity human video generation framework designed for identity preservation and fine-grained motion control. We introduce an ID-preserving module to maintain identity fidelity while allowing flexible attribute modifications, and further integrate ID-consistency and region-aware loss mechanisms, significantly enhancing identity consistency and detail fidelity. Additionally, our approach incorporates a motion control module that prioritizes action-related text while maintaining subject consistency, along with a dataset, Human-Motion, which utilizes large language models to generate detailed motion descriptions. For simplify user control during inference, we parameterize motion intensity through a single coefficient, allowing for easy adjustments. Extensive experiments highlight the effectiveness of MotionCharacter, demonstrating significant improvements in ID-preserving, high-quality video generation.

[Arxiv](https://arxiv.org/abs/2411.18281)