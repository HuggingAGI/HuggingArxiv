# M2oE：多模态协同专家肽模型

发布时间：2024年11月20日

`其他` `药物设计` `肽预测`

> M2oE: Multimodal Collaborative Expert Peptide Model

# 摘要

> 肽是由氨基酸构成的生物分子，在人体中发挥着重要作用。近些年来，肽在药物设计与合成领域备受关注，肽预测任务能帮助我们更有效地探寻功能性肽。一般而言，我们会利用肽的一级序列和结构信息来进行模型编码。然而，近期研究更多聚焦于用于预测的单模态信息（结构或序列），而非多模态方式。我们发现单模态模型难以处理特定模态中信息较少的数据集。所以，本文提出了 M2oE 多模态协同专家肽模型。基于过往工作，通过整合序列和空间结构信息，运用专家模型和交叉注意力机制，使模型的能力得以平衡和提升。实验结果显示，M2oE 模型在复杂任务预测中表现卓越。

> Peptides are biomolecules comprised of amino acids that play an important role in our body. In recent years, peptides have received extensive attention in drug design and synthesis, and peptide prediction tasks help us better search for functional peptides. Typically, we use the primary sequence and structural information of peptides for model encoding. However, recent studies have focused more on single-modal information (structure or sequence) for prediction without multi-modal approaches. We found that single-modal models are not good at handling datasets with less information in that particular modality. Therefore, this paper proposes the M2oE multi-modal collaborative expert peptide model. Based on previous work, by integrating sequence and spatial structural information, employing expert model and Cross-Attention Mechanism, the model's capabilities are balanced and improved. Experimental results indicate that the M2oE model performs excellently in complex task predictions.

[Arxiv](https://arxiv.org/abs/2411.15208)