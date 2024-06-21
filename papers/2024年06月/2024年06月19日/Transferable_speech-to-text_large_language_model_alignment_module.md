# 语音转文字大型语言模型的可迁移对齐模块

发布时间：2024年06月19日

`LLM应用

这篇论文摘要描述了利用大型语言模型（LLMs）和语音基础模型来开发一种新的语音-文本双模态技术，该技术能够处理口语翻译和问答等复杂任务。研究中使用了特定的编码器和预训练模型，并通过实验展示了模态对齐的有效性。此外，研究还探讨了模型的推理阶段和未来的扩展可能性。这些内容表明该论文是在应用层面探讨LLM技术的实际应用和效果，因此属于LLM应用分类。` `语音识别` `机器翻译`

> Transferable speech-to-text large language model alignment module

# 摘要

> 借助大型语言模型（LLMs）和语音基础模型的强大功能，最新的语音-文本双模态技术已能以更简洁的架构，同时处理口语翻译（ST）和问答（SQA）等复杂任务。本研究中，我们运用了Whisper编码器及预训练的Yi-6B，实验结果表明，仅需单层模块和数百小时的语音-文本多任务数据，即可实现模态对齐。我们还尝试在推理阶段将Yi-6B替换为与人类偏好对齐的Yi-6B-Chat，发现其对齐能力同样有效。此外，通过奇异值分解（SVD）分析，我们发现线性对齐子空间具有稀疏性，这为未来添加声纹或视频等其他特征以扩展模态提供了可能。

> By leveraging the power of Large Language Models(LLMs) and speech foundation models, state of the art speech-text bimodal works can achieve challenging tasks like spoken translation(ST) and question answering(SQA) altogether with much simpler architectures. In this paper, we utilize the capability of Whisper encoder and pre-trained Yi-6B. Empirical results reveal that modal alignment can be achieved with one layer module and hundred hours of speech-text multitask corpus. We further swap the Yi-6B with human preferences aligned version of Yi-6B-Chat during inference, and discover that the alignment capability is applicable as well. In addition, the alignment subspace revealed by singular value decomposition(SVD) also implies linear alignment subspace is sparse, which leaves the possibility to concatenate other features like voice-print or video to expand modality.

![语音转文字大型语言模型的可迁移对齐模块](../../../paper_images/2406.13357/Model2.png)

![语音转文字大型语言模型的可迁移对齐模块](../../../paper_images/2406.13357/cases.png)

[Arxiv](https://arxiv.org/abs/2406.13357)