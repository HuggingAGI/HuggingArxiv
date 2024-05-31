# 条件性蛋白质骨架生成中的序列增强SE(3)-流匹配

发布时间：2024年05月30日

`LLM应用

这篇论文介绍了一种名为FoldFlow-2的创新模型，该模型专门用于蛋白质结构的生成。它利用了大型语言模型来编码蛋白质序列，并结合了多模态融合主干和基于几何变换器的解码器。此外，论文还提到了使用大规模数据集进行训练，并通过强化微调（ReFT）目标来优化模型，以增加二级结构的多样性。这些特性表明，FoldFlow-2是一个应用了大型语言模型（LLM）技术的具体应用案例，特别是在生物信息学和蛋白质工程领域。因此，将其归类为LLM应用是合适的。` `生物信息学` `蛋白质工程`

> Sequence-Augmented SE(3)-Flow Matching For Conditional Protein Backbone Generation

# 摘要

> 蛋白质的复杂3D结构由其氨基酸序列决定，赋予了它们在生物过程中的多样功能。本文推出的FoldFlow-2，是一种创新的序列条件SE(3)-等变流匹配模型，专为蛋白质结构生成设计。它在原有FoldFlow系列模型上进行了重大架构升级，包括使用蛋白质大型语言模型编码序列、结合结构与序列表示的新型多模态融合主干，以及基于几何变换器的解码器。为了提升生成样本的多样性和新颖性，我们大规模训练了FoldFlow-2，使用了一个比以往PDB数据集大一个数量级的新数据集，涵盖了PDB中的已知蛋白质和高质量的合成结构。通过强化微调（ReFT）目标，FoldFlow-2能够针对特定奖励（如增加二级结构多样性）进行优化。实证结果显示，FoldFlow-2在设计性、多样性和新颖性等所有指标上超越了RFDiffusion，并在平衡构象采样任务上展现了出色的泛化能力。此外，经过微调的FoldFlow-2在设计VHH纳米体支架等复杂条件设计任务上取得了显著进展。

> Proteins are essential for almost all biological processes and derive their diverse functions from complex 3D structures, which are in turn determined by their amino acid sequences. In this paper, we exploit the rich biological inductive bias of amino acid sequences and introduce FoldFlow-2, a novel sequence-conditioned SE(3)-equivariant flow matching model for protein structure generation. FoldFlow-2 presents substantial new architectural features over the previous FoldFlow family of models including a protein large language model to encode sequence, a new multi-modal fusion trunk that combines structure and sequence representations, and a geometric transformer based decoder. To increase diversity and novelty of generated samples -- crucial for de-novo drug design -- we train FoldFlow-2 at scale on a new dataset that is an order of magnitude larger than PDB datasets of prior works, containing both known proteins in PDB and high-quality synthetic structures achieved through filtering. We further demonstrate the ability to align FoldFlow-2 to arbitrary rewards, e.g. increasing secondary structures diversity, by introducing a Reinforced Finetuning (ReFT) objective. We empirically observe that FoldFlow-2 outperforms previous state-of-the-art protein structure-based generative models, improving over RFDiffusion in terms of unconditional generation across all metrics including designability, diversity, and novelty across all protein lengths, as well as exhibiting generalization on the task of equilibrium conformation sampling. Finally, we demonstrate that a fine-tuned FoldFlow-2 makes progress on challenging conditional design tasks such as designing scaffolds for the VHH nanobody.

![条件性蛋白质骨架生成中的序列增强SE(3)-流匹配](../../../paper_images/2405.20313/main_v4.png)

![条件性蛋白质骨架生成中的序列增强SE(3)-流匹配](../../../paper_images/2405.20313/seq2trunk_v2.png)

![条件性蛋白质骨架生成中的序列增强SE(3)-流匹配](../../../paper_images/2405.20313/combiner_v2.png)

![条件性蛋白质骨架生成中的序列增强SE(3)-流匹配](../../../paper_images/2405.20313/legend_v2.png)

![条件性蛋白质骨架生成中的序列增强SE(3)-流匹配](../../../paper_images/2405.20313/length_100_named_v2.png)

![条件性蛋白质骨架生成中的序列增强SE(3)-流匹配](../../../paper_images/2405.20313/secondary_structure_plot.png)

![条件性蛋白质骨架生成中的序列增强SE(3)-流匹配](../../../paper_images/2405.20313/secondary_structure_plot.png)

![条件性蛋白质骨架生成中的序列增强SE(3)-流匹配](../../../paper_images/2405.20313/secondary_structure_plot.png)

![条件性蛋白质骨架生成中的序列增强SE(3)-流匹配](../../../paper_images/2405.20313/secondary_structure_plot.png)

![条件性蛋白质骨架生成中的序列增强SE(3)-流匹配](../../../paper_images/2405.20313/training_triangle.png)

![条件性蛋白质骨架生成中的序列增强SE(3)-流匹配](../../../paper_images/2405.20313/x1.png)

![条件性蛋白质骨架生成中的序列增强SE(3)-流匹配](../../../paper_images/2405.20313/x2.png)

![条件性蛋白质骨架生成中的序列增强SE(3)-流匹配](../../../paper_images/2405.20313/cummulative_pLDDT.png)

![条件性蛋白质骨架生成中的序列增强SE(3)-流匹配](../../../paper_images/2405.20313/pLDDT_filtering.png)

![条件性蛋白质骨架生成中的序列增强SE(3)-流匹配](../../../paper_images/2405.20313/bad_A4FZT8.png)

![条件性蛋白质骨架生成中的序列增强SE(3)-流匹配](../../../paper_images/2405.20313/bad_Q0SNQ5.png)

![条件性蛋白质骨架生成中的序列增强SE(3)-流匹配](../../../paper_images/2405.20313/legend.png)

![条件性蛋白质骨架生成中的序列增强SE(3)-流匹配](../../../paper_images/2405.20313/refold_schematic_v2.png)

![条件性蛋白质骨架生成中的序列增强SE(3)-流匹配](../../../paper_images/2405.20313/7MRX_med.png)

![条件性蛋白质骨架生成中的序列增强SE(3)-流匹配](../../../paper_images/2405.20313/4JHW.png)

![条件性蛋白质骨架生成中的序列增强SE(3)-流匹配](../../../paper_images/2405.20313/5IUS.png)

![条件性蛋白质骨架生成中的序列增强SE(3)-流匹配](../../../paper_images/2405.20313/5WN9.png)

![条件性蛋白质骨架生成中的序列增强SE(3)-流匹配](../../../paper_images/2405.20313/1BCF.png)

![条件性蛋白质骨架生成中的序列增强SE(3)-流匹配](../../../paper_images/2405.20313/2KL8.png)

![条件性蛋白质骨架生成中的序列增强SE(3)-流匹配](../../../paper_images/2405.20313/vhh1.png)

![条件性蛋白质骨架生成中的序列增强SE(3)-流匹配](../../../paper_images/2405.20313/vhh2.png)

![条件性蛋白质骨架生成中的序列增强SE(3)-流匹配](../../../paper_images/2405.20313/vhh3.png)

![条件性蛋白质骨架生成中的序列增强SE(3)-流匹配](../../../paper_images/2405.20313/vhh4.png)

![条件性蛋白质骨架生成中的序列增强SE(3)-流匹配](../../../paper_images/2405.20313/x3.png)

![条件性蛋白质骨架生成中的序列增强SE(3)-流匹配](../../../paper_images/2405.20313/x4.png)

![条件性蛋白质骨架生成中的序列增强SE(3)-流匹配](../../../paper_images/2405.20313/x5.png)

![条件性蛋白质骨架生成中的序列增强SE(3)-流匹配](../../../paper_images/2405.20313/secondary_structure_plot.png)

![条件性蛋白质骨架生成中的序列增强SE(3)-流匹配](../../../paper_images/2405.20313/secondary_structure_plot.png)

![条件性蛋白质骨架生成中的序列增强SE(3)-流匹配](../../../paper_images/2405.20313/secondary_structure_plot.png)

![条件性蛋白质骨架生成中的序列增强SE(3)-流匹配](../../../paper_images/2405.20313/training_triangle.png)

[Arxiv](https://arxiv.org/abs/2405.20313)