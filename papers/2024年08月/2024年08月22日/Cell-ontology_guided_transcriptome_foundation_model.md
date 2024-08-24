# 基于细胞本体的转录组基础模型

发布时间：2024年08月22日

`LLM应用` `生物技术`

> Cell-ontology guided transcriptome foundation model

# 摘要

> 转录组基础模型（TFMs）通过自我监督学习，有望解码细胞功能的转录组语言，并揭示人类疾病的复杂机制。然而，现有TFMs忽略了细胞类型间的分类关系。我们提出scCello，通过引入细胞类型一致性损失和本体对齐损失，优化基因共表达模式学习，同时保持其通用性。在2200万个细胞上预训练的scCello，在识别新细胞类型、预测标记基因和药物反应等任务上，表现卓越。

> Transcriptome foundation models TFMs hold great promises of deciphering the transcriptomic language that dictate diverse cell functions by self-supervised learning on large-scale single-cell gene expression data, and ultimately unraveling the complex mechanisms of human diseases. However, current TFMs treat cells as independent samples and ignore the taxonomic relationships between cell types, which are available in cell ontology graphs. We argue that effectively leveraging this ontology information during the TFM pre-training can improve learning biologically meaningful gene co-expression patterns while preserving TFM as a general purpose foundation model for downstream zero-shot and fine-tuning tasks. To this end, we present \textbf{s}ingle \textbf{c}ell, \textbf{Cell}-\textbf{o}ntology guided TFM scCello. We introduce cell-type coherence loss and ontology alignment loss, which are minimized along with the masked gene expression prediction loss during the pre-training. The novel loss component guide scCello to learn the cell-type-specific representation and the structural relation between cell types from the cell ontology graph, respectively. We pre-trained scCello on 22 million cells from CellxGene database leveraging their cell-type labels mapped to the cell ontology graph from Open Biological and Biomedical Ontology Foundry. Our TFM demonstrates competitive generalization and transferability performance over the existing TFMs on biologically important tasks including identifying novel cell types of unseen cells, prediction of cell-type-specific marker genes, and cancer drug responses.

[Arxiv](https://arxiv.org/abs/2408.12373)