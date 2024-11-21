# JEMA：一个用于实现多模态对齐的可扩展协同学习的联合嵌入框架

发布时间：2024年10月31日

`其他` `工业制造` `过程监控`

> JEMA: A Joint Embedding Framework for Scalable Co-Learning with Multimodal Alignment

# 摘要

> 此项工作引入了 JEMA（具有多模态对齐的联合嵌入），这一专为激光金属沉积（LMD）打造的新型协同学习框架，而 LMD 是金属增材制造的关键流程。随着工业 5.0 在工业应用中渐成趋势，高效的过程监控愈发关键。然而，数据有限以及人工智能的不透明性给其在工业场景中的应用带来难题。JEMA 借助多模态数据，涵盖多视图图像和诸如工艺参数之类的元数据，来学习可迁移的语义表征，以此应对这些挑战。通过采用有监督的对比损失函数，JEMA 仅依靠主要模态就能达成强大的学习以及后续的过程监控，降低了硬件要求和计算开销。我们探究了 JEMA 在 LMD 过程监控中的成效，尤其聚焦于它对诸如熔池几何形状预测等下游任务的泛化能力，无需大量微调即可达成。我们的实证评估显示，JEMA 具有出色的可扩展性和性能，特别是与视觉 Transformer 模型相结合时。相较于有监督的对比学习，我们报告称在多模态设置中性能提升 8%，在单模态设置中提升 1%。此外，所学到的嵌入表征能够预测元数据，增强了可解释性，并能够评估所添加元数据的贡献。我们的框架为多传感器数据与元数据的整合奠定了基础，能够在 LMD 领域及其他领域实现各类下游任务。

> This work introduces JEMA (Joint Embedding with Multimodal Alignment), a novel co-learning framework tailored for laser metal deposition (LMD), a pivotal process in metal additive manufacturing. As Industry 5.0 gains traction in industrial applications, efficient process monitoring becomes increasingly crucial. However, limited data and the opaque nature of AI present challenges for its application in an industrial setting. JEMA addresses this challenges by leveraging multimodal data, including multi-view images and metadata such as process parameters, to learn transferable semantic representations. By applying a supervised contrastive loss function, JEMA enables robust learning and subsequent process monitoring using only the primary modality, simplifying hardware requirements and computational overhead. We investigate the effectiveness of JEMA in LMD process monitoring, focusing specifically on its generalization to downstream tasks such as melt pool geometry prediction, achieved without extensive fine-tuning. Our empirical evaluation demonstrates the high scalability and performance of JEMA, particularly when combined with Vision Transformer models. We report an 8% increase in performance in multimodal settings and a 1% improvement in unimodal settings compared to supervised contrastive learning. Additionally, the learned embedding representation enables the prediction of metadata, enhancing interpretability and making possible the assessment of the added metadata's contributions. Our framework lays the foundation for integrating multisensor data with metadata, enabling diverse downstream tasks within the LMD domain and beyond.

[Arxiv](https://arxiv.org/abs/2410.23988)