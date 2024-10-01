# 多模态跨域自监督预训练：融合 fMRI 与 EEG

发布时间：2024年09月27日

`LLM应用` `神经科学`

> Multi-modal Cross-domain Self-supervised Pre-training for fMRI and EEG Fusion

# 摘要

> 神经影像技术如 fMRI 和 EEG 在检测脑功能异常方面表现出色。然而，现有研究多聚焦于单一领域，忽略了 fMRI 和 EEG 多领域互补信息的重要性。为解决这一问题，我们提出了多模态跨领域自监督预训练模型 (MCSP)，通过自监督学习整合多模态信息，跨越空间、时间和频谱领域。MCSP 采用跨领域自监督损失，通过数据增强和对比损失弥合领域差异，提升特征辨别力。同时，引入跨模态自监督损失，利用 fMRI 和 EEG 的互补信息，促进知识蒸馏和跨模态特征融合。我们构建了大规模预训练数据集，通过自监督范式预训练 MCSP 模型，全面利用多模态神经影像数据。实验证明，MCSP 在多个分类任务中表现优异且具有广泛适用性。本研究在 fMRI 和 EEG 融合方面取得重要进展，为神经影像研究，特别是精神疾病研究，开辟了新路径。

> Neuroimaging techniques including functional magnetic resonance imaging (fMRI) and electroencephalogram (EEG) have shown promise in detecting functional abnormalities in various brain disorders. However, existing studies often focus on a single domain or modality, neglecting the valuable complementary information offered by multiple domains from both fMRI and EEG, which is crucial for a comprehensive representation of disorder pathology. This limitation poses a challenge in effectively leveraging the synergistic information derived from these modalities. To address this, we propose a Multi-modal Cross-domain Self-supervised Pre-training Model (MCSP), a novel approach that leverages self-supervised learning to synergize multi-modal information across spatial, temporal, and spectral domains. Our model employs cross-domain self-supervised loss that bridges domain differences by implementing domain-specific data augmentation and contrastive loss, enhancing feature discrimination. Furthermore, MCSP introduces cross-modal self-supervised loss to capitalize on the complementary information of fMRI and EEG, facilitating knowledge distillation within domains and maximizing cross-modal feature convergence. We constructed a large-scale pre-training dataset and pretrained MCSP model by leveraging proposed self-supervised paradigms to fully harness multimodal neuroimaging data. Through comprehensive experiments, we have demonstrated the superior performance and generalizability of our model on multiple classification tasks. Our study contributes a significant advancement in the fusion of fMRI and EEG, marking a novel integration of cross-domain features, which enriches the existing landscape of neuroimaging research, particularly within the context of mental disorder studies.

[Arxiv](https://arxiv.org/abs/2409.19130)