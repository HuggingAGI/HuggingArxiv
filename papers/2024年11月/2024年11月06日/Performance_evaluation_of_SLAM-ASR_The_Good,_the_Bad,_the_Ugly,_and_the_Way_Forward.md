# SLAM-ASR 的性能评估：好的、坏的、丑的和前进的道路

发布时间：2024年11月06日

`LLM应用` `语音识别` `模型架构`

> Performance evaluation of SLAM-ASR: The Good, the Bad, the Ugly, and the Way Forward

# 摘要

> 最近的研究表明，在语音基础编码器和大型语言模型（LLM）之间训练一个线性连接器使这种架构能够实现强大的 ASR 能力。尽管结果令人印象深刻，但仍不清楚这些简单的方法在不同的场景和语音条件下是否足够强大，例如领域转移和不同的语音干扰。在本文中，我们通过使用一种最近且广泛采用的称为 SLAM-ASR 的方法进行各种消融实验来解决这些问题。我们提出了新的实证发现，为如何在广泛的设置中有效利用 SLAM-ASR 架构提供了见解。我们的主要发现表明，SLAM-ASR 在跨域评估设置中表现不佳。此外，域内数据中的语音干扰，例如速度变化或存在附加噪声，会显著影响性能。我们的发现为针对不同数据特征和计算资源微调并配置强大的基于 LLM 的 ASR 模型提供了关键见解。

> Recent research has demonstrated that training a linear connector between speech foundation encoders and large language models (LLMs) enables this architecture to achieve strong ASR capabilities. Despite the impressive results, it remains unclear whether these simple approaches are robust enough across different scenarios and speech conditions, such as domain shifts and different speech perturbations. In this paper, we address these questions by conducting various ablation experiments using a recent and widely adopted approach called SLAM-ASR. We present novel empirical findings that offer insights on how to effectively utilize the SLAM-ASR architecture across a wide range of settings. Our main findings indicate that the SLAM-ASR exhibits poor performance in cross-domain evaluation settings. Additionally, speech perturbations within in-domain data, such as changes in speed or the presence of additive noise, can significantly impact performance. Our findings offer critical insights for fine-tuning and configuring robust LLM-based ASR models, tailored to different data characteristics and computational resources.

[Arxiv](https://arxiv.org/abs/2411.03866)