# 借助声学适应与视觉对齐，提升多模态情感识别的精准度。

发布时间：2024年09月08日

`LLM应用` `情感识别` `人工智能`

> Improving Multimodal Emotion Recognition by Leveraging Acoustic Adaptation and Visual Alignment

# 摘要

> 多模态情感识别 (MER) 旨在通过整合多模态信息自动识别和理解人类情感。然而，标注数据的稀缺性严重制约了这一领域的发展。本文针对 MER 2024 的 MER-SEMI 子挑战，提出了一套解决方案。首先，我们通过实验评估预训练语音模型 HuBERT 各层在情感识别中的贡献，并对其最有效的层进行参数高效微调 (PEFT)，以最少参数实现最佳情感识别效果。其次，我们提出一种特征对齐预训练方法，利用大规模未标注数据训练视觉编码器，促进声学特征空间内视觉特征的语义对齐。最后，结合适应的声学特征、对齐的视觉特征和词汇特征，采用注意力机制进行特征融合。在 MER2024-SEMI 测试集上，我们的方法以 88.90% 的加权 F1 分数位列第四，充分验证了其有效性。

> Multimodal Emotion Recognition (MER) aims to automatically identify and understand human emotional states by integrating information from various modalities. However, the scarcity of annotated multimodal data significantly hinders the advancement of this research field. This paper presents our solution for the MER-SEMI sub-challenge of MER 2024. First, to better adapt acoustic modality features for the MER task, we experimentally evaluate the contributions of different layers of the pre-trained speech model HuBERT in emotion recognition. Based on these observations, we perform Parameter-Efficient Fine-Tuning (PEFT) on the layers identified as most effective for emotion recognition tasks, thereby achieving optimal adaptation for emotion recognition with a minimal number of learnable parameters. Second, leveraging the strengths of the acoustic modality, we propose a feature alignment pre-training method. This approach uses large-scale unlabeled data to train a visual encoder, thereby promoting the semantic alignment of visual features within the acoustic feature space. Finally, using the adapted acoustic features, aligned visual features, and lexical features, we employ an attention mechanism for feature fusion. On the MER2024-SEMI test set, the proposed method achieves a weighted F1 score of 88.90%, ranking fourth among all participating teams, validating the effectiveness of our approach.

[Arxiv](https://arxiv.org/abs/2409.05015)