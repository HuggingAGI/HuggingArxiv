# SEER：自对齐证据提取，助力检索增强生成

发布时间：2024年10月15日

`RAG` `人工智能`

> SEER: Self-Aligned Evidence Extraction for Retrieval-Augmented Generation

# 摘要

> 近期，RAG 研究尝试从检索段落中提取证据，以降低计算成本并提升性能，但仍面临挑战。现有方法多依赖启发式增强，存在泛化能力差、语义缺失和长度偏斜等问题。为此，我们提出 SEER 框架，通过自对齐学习优化模型，使其具备理想的证据提取能力。实验显示，SEER 显著提升 RAG 性能，增强证据的忠实性、有用性和简洁性，并大幅缩短证据长度。代码即将在 https://github.com/HITsz-TMG/SEER 发布。

> Recent studies in Retrieval-Augmented Generation (RAG) have investigated extracting evidence from retrieved passages to reduce computational costs and enhance the final RAG performance, yet it remains challenging. Existing methods heavily rely on heuristic-based augmentation, encountering several issues: (1) Poor generalization due to hand-crafted context filtering; (2) Semantics deficiency due to rule-based context chunking; (3) Skewed length due to sentence-wise filter learning. To address these issues, we propose a model-based evidence extraction learning framework, SEER, optimizing a vanilla model as an evidence extractor with desired properties through self-aligned learning. Extensive experiments show that our method largely improves the final RAG performance, enhances the faithfulness, helpfulness, and conciseness of the extracted evidence, and reduces the evidence length by 9.25 times. The code will be available at https://github.com/HITsz-TMG/SEER.

[Arxiv](https://arxiv.org/abs/2410.11315)