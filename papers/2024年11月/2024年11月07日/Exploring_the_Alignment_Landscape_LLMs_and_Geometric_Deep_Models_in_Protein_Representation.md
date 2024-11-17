# 探索对齐态势：蛋白质表示中的大型语言模型与几何深度学习模型

发布时间：2024年11月07日

`LLM应用` `蛋白质` `多模态模型`

> Exploring the Alignment Landscape: LLMs and Geometric Deep Models in Protein Representation

# 摘要

> 潜在表示对齐已成为构建多模态大型语言模型（MLLM）的一项基础技术，它将不同模态的嵌入映射至一个共享空间，且常与大型语言模型（LLM）的嵌入空间对齐，从而实现有效的跨模态理解。尽管初步的聚焦于蛋白质的 MLLM 已现身，但它们主要依赖启发式方法，对跨表示的最优对齐实践缺乏基本理解。在本研究中，我们探究了蛋白质领域中 LLM 与几何深度模型（GDM）之间的多模态表示对齐情况。我们对三个先进的 LLM（Gemma2-2B、LLaMa3.1-8B 和 LLaMa3.1-70B）以及四个针对蛋白质的 GDM（GearNet、GVP、ScanNet、GAT）进行了全面评估。我们的工作从模型和蛋白质两个角度审视了对齐因素，明确了当前对齐方法存在的挑战，并提出了优化对齐过程的策略。我们的关键发现显示，融合了图和 3D 结构信息的 GDM 与 LLM 对齐效果更优，更大的 LLM 展现出更强的对齐能力，蛋白质的稀有程度对对齐性能有显著影响。我们还发现，增加 GDM 嵌入维度、使用两层投影头以及在蛋白质特定数据上微调 LLM 能大幅提升对齐质量。这些策略有望提升蛋白质相关多模态模型的性能。我们的代码和数据可在 https://github.com/Tizzzzy/LLM-GDM-alignment 获取。

> Latent representation alignment has become a foundational technique for constructing multimodal large language models (MLLM) by mapping embeddings from different modalities into a shared space, often aligned with the embedding space of large language models (LLMs) to enable effective cross-modal understanding. While preliminary protein-focused MLLMs have emerged, they have predominantly relied on heuristic approaches, lacking a fundamental understanding of optimal alignment practices across representations. In this study, we explore the alignment of multimodal representations between LLMs and Geometric Deep Models (GDMs) in the protein domain. We comprehensively evaluate three state-of-the-art LLMs (Gemma2-2B, LLaMa3.1-8B, and LLaMa3.1-70B) with four protein-specialized GDMs (GearNet, GVP, ScanNet, GAT). Our work examines alignment factors from both model and protein perspectives, identifying challenges in current alignment methodologies and proposing strategies to improve the alignment process. Our key findings reveal that GDMs incorporating both graph and 3D structural information align better with LLMs, larger LLMs demonstrate improved alignment capabilities, and protein rarity significantly impacts alignment performance. We also find that increasing GDM embedding dimensions, using two-layer projection heads, and fine-tuning LLMs on protein-specific data substantially enhance alignment quality. These strategies offer potential enhancements to the performance of protein-related multimodal models. Our code and data are available at https://github.com/Tizzzzy/LLM-GDM-alignment.

[Arxiv](https://arxiv.org/abs/2411.05316)