# SZTU-CMU 在 MER2024 提出：利用 Conv-Attention 技术优化 Emotion-LLaMA，提升多模态情感识别能力。

发布时间：2024年08月21日

`LLM应用` `情感识别` `多模态技术`

> SZTU-CMU at MER2024: Improving Emotion-LLaMA with Conv-Attention for Multimodal Emotion Recognition

# 摘要

> 本文展示了我们在MER2024挑战赛多模态情感识别任务中的夺冠方案，涵盖MER-NOISE和MER-OV赛道。我们采用Emotion-LLaMA的高级情感理解技术，为未标记样本生成优质注释，有效应对标记数据不足的挑战。同时，我们创新性地引入了Conv-Attention轻量高效混合框架，以提升多模态融合并降低模态噪声。实验结果表明，我们的方法在MER-NOISE赛道以85.30%的加权平均F分数领先，分别超越亚军和季军1.47%和1.65%。在MER-OV赛道，通过Emotion-LLaMA进行开放词汇注释，我们的平均准确率和召回率较GPT-4V提升8.52%，位居所有大型多模态模型之首。Emotion-LLaMA的代码和模型已公开于https://github.com/ZebangCheng/Emotion-LLaMA。

> This paper presents our winning approach for the MER-NOISE and MER-OV tracks of the MER2024 Challenge on multimodal emotion recognition. Our system leverages the advanced emotional understanding capabilities of Emotion-LLaMA to generate high-quality annotations for unlabeled samples, addressing the challenge of limited labeled data. To enhance multimodal fusion while mitigating modality-specific noise, we introduce Conv-Attention, a lightweight and efficient hybrid framework. Extensive experimentation vali-dates the effectiveness of our approach. In the MER-NOISE track, our system achieves a state-of-the-art weighted average F-score of 85.30%, surpassing the second and third-place teams by 1.47% and 1.65%, respectively. For the MER-OV track, our utilization of Emotion-LLaMA for open-vocabulary annotation yields an 8.52% improvement in average accuracy and recall compared to GPT-4V, securing the highest score among all participating large multimodal models. The code and model for Emotion-LLaMA are available at https://github.com/ZebangCheng/Emotion-LLaMA.

[Arxiv](https://arxiv.org/abs/2408.10500)