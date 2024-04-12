# 在大规模在线开放课程（MOOC）的学习环境中，通过整合视频中的语义信息，实现对学习者情感的多维度识别。

发布时间：2024年04月11日

`LLM应用` `情感计算`

> Multimodal Emotion Recognition by Fusing Video Semantic in MOOC Learning Scenarios

# 摘要

> 在MOOC学习环境中，教学视频的深层含义对学习者情绪的影响至关重要。学习者主要通过观看视频来吸收知识，视频内容的深层含义直接作用于他们的情绪。尽管如此，目前对于教学视频语义如何影响学习者情绪的研究仍相对匮乏。本研究独树一帜，提出了一种新颖的多模态情绪识别技术，通过结合视频内容的语义信息和生理信号来分析学习者的情绪变化。我们利用预训练的大型语言模型生成视频摘要，捕捉视频的深层语义。通过交叉注意力机制，将这些语义信息与眼动和PPG信号相结合，提取出包含关键情绪特征的信息。借助情绪分类器，我们实现了对学习者情绪的精确识别。实验数据显示，这种方法显著提升了情绪识别的准确度，为MOOC环境下的情绪研究开辟了新的路径和高效的解决方案。本研究不仅深化了我们对教学视频如何影响学习者情绪的认识，也为未来相关领域的研究提供了宝贵的参考。

> In the Massive Open Online Courses (MOOC) learning scenario, the semantic information of instructional videos has a crucial impact on learners' emotional state. Learners mainly acquire knowledge by watching instructional videos, and the semantic information in the videos directly affects learners' emotional states. However, few studies have paid attention to the potential influence of the semantic information of instructional videos on learners' emotional states. To deeply explore the impact of video semantic information on learners' emotions, this paper innovatively proposes a multimodal emotion recognition method by fusing video semantic information and physiological signals. We generate video descriptions through a pre-trained large language model (LLM) to obtain high-level semantic information about instructional videos. Using the cross-attention mechanism for modal interaction, the semantic information is fused with the eye movement and PhotoPlethysmoGraphy (PPG) signals to obtain the features containing the critical information of the three modes. The accurate recognition of learners' emotional states is realized through the emotion classifier. The experimental results show that our method has significantly improved emotion recognition performance, providing a new perspective and efficient method for emotion recognition research in MOOC learning scenarios. The method proposed in this paper not only contributes to a deeper understanding of the impact of instructional videos on learners' emotional states but also provides a beneficial reference for future research on emotion recognition in MOOC learning scenarios.

[Arxiv](https://arxiv.org/abs/2404.07484)