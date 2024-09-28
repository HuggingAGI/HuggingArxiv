# 乳腺摄影中的对比语言-图像预训练：多视图与多尺度的精准对齐

发布时间：2024年09月26日

`LLM应用` `图像分析`

> Multi-View and Multi-Scale Alignment for Contrastive Language-Image Pre-training in Mammography

# 摘要

> CLIP 在医学图像分析中潜力巨大，但需要大量数据和计算资源。现有应用多集中在胸部 X 光等数据丰富的模态，而其他重要模态则鲜有涉足。我们首次将 CLIP 完整模型应用于乳腺摄影，克服了标签数据稀缺、高分辨率图像细节复杂及数据不平衡等挑战。我们设计了多视角监督框架和对称局部对齐模块，并采用参数高效的微调方法，使我们的 MaMA 方法在 EMBED 和 RSNA-Mammo 数据集上的三个任务中，以仅 52% 的模型大小超越了最先进基线。

> Contrastive Language-Image Pre-training (CLIP) shows promise in medical image analysis but requires substantial data and computational resources. Due to these restrictions, existing CLIP applications in medical imaging focus mainly on modalities like chest X-rays that have abundant image-report data available, leaving many other important modalities under-explored. Here, we propose the first adaptation of the full CLIP model to mammography, which presents significant challenges due to labeled data scarcity, high-resolution images with small regions of interest, and data imbalance. We first develop a specialized supervision framework for mammography that leverages its multi-view nature. Furthermore, we design a symmetric local alignment module to better focus on detailed features in high-resolution images. Lastly, we incorporate a parameter-efficient fine-tuning approach for large language models pre-trained with medical knowledge to address data limitations. Our multi-view and multi-scale alignment (MaMA) method outperforms state-of-the-art baselines for three different tasks on two large real-world mammography datasets, EMBED and RSNA-Mammo, with only 52% model size compared with the largest baseline.

[Arxiv](https://arxiv.org/abs/2409.18119)