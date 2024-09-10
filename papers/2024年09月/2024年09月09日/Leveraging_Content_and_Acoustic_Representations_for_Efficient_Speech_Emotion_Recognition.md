# 结合内容与声学特征，实现高效的语音情感识别

发布时间：2024年09月09日

`LLM应用` `语音识别` `情感分析`

> Leveraging Content and Acoustic Representations for Efficient Speech Emotion Recognition

# 摘要

> 语音情感识别 (SER) 因从语音中提取情感特征的难度而充满挑战，且大型标注数据集的稀缺性更易导致模型过拟合。为此，我们提出了 CARE（情感的内容和声学表示），通过双编码方案强调语音的语义和声学特征。语义编码器通过话语级文本表示模型的蒸馏训练，声学编码器则预测语音信号的低级逐帧特征。CARE 模型仅在无监督原始语音上训练，结合轻量级分类模型，在多种任务上展现了出色的情感识别能力。与多种自监督模型及大型语言模型方法相比，CARE 在 8 个多样化数据集上的平均表现最为优异。此外，我们还通过消融研究深入分析了各设计选择的重要性。

> Speech emotion recognition (SER), the task of identifying the expression of emotion from spoken content, is challenging due to the difficulty in extracting representations that capture emotional attributes from speech. The scarcity of large labeled datasets further complicates the challenge where large models are prone to over-fitting. In this paper, we propose CARE (Content and Acoustic Representations of Emotions), where we design a dual encoding scheme which emphasizes semantic and acoustic factors of speech. While the semantic encoder is trained with the distillation of utterance-level text representation model, the acoustic encoder is trained to predict low-level frame-wise features of the speech signal. The proposed dual encoding scheme is a base-sized model trained only on unsupervised raw speech. With a simple light-weight classification model trained on the downstream task, we show that the CARE embeddings provide effective emotion recognition on a variety of tasks. We compare the proposal with several other self-supervised models as well as recent large-language model based approaches. In these evaluations, the proposed CARE model is shown to be the best performing model based on average performance across 8 diverse datasets. We also conduct several ablation studies to analyze the importance of various design choices.

[Arxiv](https://arxiv.org/abs/2409.05566)