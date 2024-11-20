# NeuMaDiff：借助超扩散实现神经材料合成

发布时间：2024年11月18日

`其他` `材料科学` `数字场景`

> NeuMaDiff: Neural Material Synthesis via Hyperdiffusion

# 摘要

> 高质量的材料合成对于复制复杂表面特性以打造逼真数字场景极为关键。然而，现有的方法常常存在时间和内存效率低的问题，需要专业领域知识，或者依赖大量训练数据，高维材料数据更是进一步制约了性能。另外，多数方法缺少多模态引导能力和标准化评估指标，限制了合成任务中的掌控和可对比性。为克服这些局限，我们提出了NeuMaDiff，这是一个借助超扩散的新型神经材料合成框架。我们的方法将神经场用作低维表示，并融入多模态条件超扩散模型来学习材料权重的分布。这通过诸如材料类型、文本描述或参考图像等输入实现了灵活引导，为合成提供了更强的掌控力。为助力未来研究，我们贡献了两个新的材料数据集，并引入了两个BRDF分布指标用于更严格的评估。我们通过大量实验证明了NeuMaDiff的有效性，其中包括一种基于统计的新型约束合成方法，能够生成期望类别的材料。

> High-quality material synthesis is essential for replicating complex surface properties to create realistic digital scenes. However, existing methods often suffer from inefficiencies in time and memory, require domain expertise, or demand extensive training data, with high-dimensional material data further constraining performance. Additionally, most approaches lack multi-modal guidance capabilities and standardized evaluation metrics, limiting control and comparability in synthesis tasks. To address these limitations, we propose NeuMaDiff, a novel neural material synthesis framework utilizing hyperdiffusion. Our method employs neural fields as a low-dimensional representation and incorporates a multi-modal conditional hyperdiffusion model to learn the distribution over material weights. This enables flexible guidance through inputs such as material type, text descriptions, or reference images, providing greater control over synthesis. To support future research, we contribute two new material datasets and introduce two BRDF distributional metrics for more rigorous evaluation. We demonstrate the effectiveness of NeuMaDiff through extensive experiments, including a novel statistics-based constrained synthesis approach, which enables the generation of materials of desired categories.

[Arxiv](https://arxiv.org/abs/2411.12015)