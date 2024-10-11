# MolMix：一个简单却高效的多模态分子表示学习基线

发布时间：2024年10月10日

`LLM应用` `生物信息学`

> MolMix: A Simple Yet Effective Baseline for Multimodal Molecular Representation Learning

# 摘要

> 我们提出了一种基于transformer的简单基线方法，用于多模态分子表示学习，整合了SMILES字符串、2D图和3D构象三种模态。关键在于3D构象的聚合，确保模型能处理分子多构象的特性。每种模态的标记通过专用编码器提取，框架灵活，编码器可轻松替换，适应性强。提取的标记合并为统一序列，由下游transformer处理。为高效处理大数据集，我们采用了Flash Attention 2和bfloat16精度。尽管方法简洁，但在多个数据集上表现卓越，成为多模态分子表示学习的坚实基线。

> In this work, we propose a simple transformer-based baseline for multimodal molecular representation learning, integrating three distinct modalities: SMILES strings, 2D graph representations, and 3D conformers of molecules. A key aspect of our approach is the aggregation of 3D conformers, allowing the model to account for the fact that molecules can adopt multiple conformations-an important factor for accurate molecular representation. The tokens for each modality are extracted using modality-specific encoders: a transformer for SMILES strings, a message-passing neural network for 2D graphs, and an equivariant neural network for 3D conformers. The flexibility and modularity of this framework enable easy adaptation and replacement of these encoders, making the model highly versatile for different molecular tasks. The extracted tokens are then combined into a unified multimodal sequence, which is processed by a downstream transformer for prediction tasks. To efficiently scale our model for large multimodal datasets, we utilize Flash Attention 2 and bfloat16 precision. Despite its simplicity, our approach achieves state-of-the-art results across multiple datasets, demonstrating its effectiveness as a strong baseline for multimodal molecular representation learning.

[Arxiv](https://arxiv.org/abs/2410.07981)