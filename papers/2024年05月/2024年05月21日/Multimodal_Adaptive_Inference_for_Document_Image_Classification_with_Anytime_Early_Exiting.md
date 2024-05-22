# 文档图像分类中的多模态自适应推理：随时早期退出策略的应用

发布时间：2024年05月21日

`RAG

理由：这篇论文主要关注的是视觉丰富文档理解（VDU）任务中的性能与效率平衡问题，并提出了一种多模态早期退出（EE）模型。这种模型设计涉及到多模态数据的处理和优化，与RAG（Retrieval-Augmented Generation）模型中的多模态处理和效率优化有相似之处。虽然论文中没有直接提到RAG，但其研究内容和目标与RAG模型中对多模态数据处理和模型效率的关注相吻合。因此，将其归类为RAG是合适的。` `文档理解` `多模态处理`

> Multimodal Adaptive Inference for Document Image Classification with Anytime Early Exiting

# 摘要

> 本研究针对视觉丰富文档理解（VDU）任务在可扩展生产环境中，性能与效率的平衡问题提出了解决方案。当前，大型文档基础模型虽功能强大，但计算成本高昂。为此，我们设计了一种多模态早期退出（EE）模型，融合了多种训练策略和退出层配置。旨在为多模态文档图像分类找到性能与效率的帕累托最优解。实验对比传统策略，展示了我们方法在性能与效率上的优越权衡。该设计不仅保持了预测精度，还通过减少20%以上的延迟提升了处理速度。这是VDU领域首次探索多模态EE设计，并验证了校准在提升不同层退出置信度上的效果。研究成果提升了VDU应用的实际效能，兼顾了性能与效率。

> This work addresses the need for a balanced approach between performance and efficiency in scalable production environments for visually-rich document understanding (VDU) tasks. Currently, there is a reliance on large document foundation models that offer advanced capabilities but come with a heavy computational burden. In this paper, we propose a multimodal early exit (EE) model design that incorporates various training strategies, exit layer types and placements. Our goal is to achieve a Pareto-optimal balance between predictive performance and efficiency for multimodal document image classification. Through a comprehensive set of experiments, we compare our approach with traditional exit policies and showcase an improved performance-efficiency trade-off. Our multimodal EE design preserves the model's predictive capabilities, enhancing both speed and latency. This is achieved through a reduction of over 20% in latency, while fully retaining the baseline accuracy. This research represents the first exploration of multimodal EE design within the VDU community, highlighting as well the effectiveness of calibration in improving confidence scores for exiting at different layers. Overall, our findings contribute to practical VDU applications by enhancing both performance and efficiency.

[Arxiv](https://arxiv.org/abs/2405.12705)