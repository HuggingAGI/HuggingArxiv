# DPLM-2：一款多模态扩散蛋白语言模型

发布时间：2024年10月17日

`其他` `生物医药` `蛋白质工程`

> DPLM-2: A Multimodal Diffusion Protein Language Model

# 摘要

> 蛋白质的功能由其氨基酸序列决定，进而影响其三维结构。因此，生成蛋白质模型需采用多模态方法，同时处理序列和结构。现有方法通常分别处理各模态，难以捕捉两者间的复杂关系，导致联合生成任务表现不佳。本文提出DPLM-2，一种结合序列和结构的多模态蛋白质模型。通过将3D坐标转换为离散令牌，DPLM-2在实验和合成数据上训练，学习序列和结构的联合分布。此外，通过预热策略，DPLM-2利用进化数据与结构偏差，提升模型性能。实证结果表明，DPLM-2能高效生成兼容的氨基酸序列和3D结构，并在多种条件生成任务中表现优异，为预测任务提供结构感知表示。

> Proteins are essential macromolecules defined by their amino acid sequences, which determine their three-dimensional structures and, consequently, their functions in all living organisms. Therefore, generative protein modeling necessitates a multimodal approach to simultaneously model, understand, and generate both sequences and structures. However, existing methods typically use separate models for each modality, limiting their ability to capture the intricate relationships between sequence and structure. This results in suboptimal performance in tasks that requires joint understanding and generation of both modalities. In this paper, we introduce DPLM-2, a multimodal protein foundation model that extends discrete diffusion protein language model (DPLM) to accommodate both sequences and structures. To enable structural learning with the language model, 3D coordinates are converted to discrete tokens using a lookup-free quantization-based tokenizer. By training on both experimental and high-quality synthetic structures, DPLM-2 learns the joint distribution of sequence and structure, as well as their marginals and conditionals. We also implement an efficient warm-up strategy to exploit the connection between large-scale evolutionary data and structural inductive biases from pre-trained sequence-based protein language models. Empirical evaluation shows that DPLM-2 can simultaneously generate highly compatible amino acid sequences and their corresponding 3D structures eliminating the need for a two-stage generation approach. Moreover, DPLM-2 demonstrates competitive performance in various conditional generation tasks, including folding, inverse folding, and scaffolding with multimodal motif inputs, as well as providing structure-aware representations for predictive tasks.

[Arxiv](https://arxiv.org/abs/2410.13782)