# D-Flow：用于 D 肽设计的多模态流匹配方案

发布时间：2024年11月15日

`其他` `生物制药` `蛋白质设计`

> D-Flow: Multi-modality Flow Matching for D-peptide Design

# 摘要

> 蛋白质在生物进程中扮演着关键角色，治疗性肽作为颇具前景的药物制剂崭露头角。它们为利用此前难以成药的靶结合位点创造了新契机。尽管深度学习（DL）推动了肽的发现进程，但由于天然实例稀缺，生成由D-氨基酸构成的D-蛋白仍困难重重。本文提出了D-Flow，这是一个用于全新D-肽设计的全原子流框架。D-Flow 以受体结合为条件，采用了肽结构的综合表征，涵盖骨架框架、侧链角度以及离散的氨基酸类型。还实施了一种镜像算法以应对D-蛋白训练数据的匮乏，该算法能转换L-受体的手性。此外，我们通过一个轻量级结构适配器将具备结构意识的大型蛋白质语言模型（PLMs）融入D-Flow，从而增强其能力。一个两阶段的训练流程和一个控制工具包也使D-Flow能够在保留预训练知识的同时，从一般的蛋白质设计转向有针对性的结合剂设计。
在PepMerge基准上的众多实验结果彰显了D-Flow的有效性，尤其在开发全D残基的肽方面。此方法在计算D-肽设计领域取得了重大突破，为生物正交和稳定的分子工具及诊断提供了独特机遇。代码可在~url{https://github.com/smiles724/PeptideDesign}获取。

> Proteins play crucial roles in biological processes, with therapeutic peptides emerging as promising pharmaceutical agents. They allow new possibilities to leverage target binding sites that were previously undruggable. While deep learning (DL) has advanced peptide discovery, generating D-proteins composed of D-amino acids remains challenging due to the scarcity of natural examples. This paper proposes D-Flow, a full-atom flow-based framework for {de novo} D-peptide design. D-Flow is conditioned on receptor binding and utilizes a comprehensive representation of peptide structure, incorporating backbone frames, side-chain angles, and discrete amino acid types. A mirror-image algorithm is implemented to address the lack of training data for D-proteins, which converts L-receptors' chirality. Furthermore, we enhance D-Flow's capacity by integrating large protein language models (PLMs) with structural awareness through a lightweight structural adapter. A two-stage training pipeline and a controlling toolkit also enable D-Flow to transition from general protein design to targeted binder design while preserving pretraining knowledge.
  Extensive experimental results on the PepMerge benchmark demonstrate D-Flow's effectiveness, particularly in developing peptides with entire D-residues. This approach represents a significant advancement in computational D-peptide design, offering unique opportunities for bioorthogonal and stable molecular tools and diagnostics. The code is available in~url{https://github.com/smiles724/PeptideDesign}.

[Arxiv](https://arxiv.org/abs/2411.10618)