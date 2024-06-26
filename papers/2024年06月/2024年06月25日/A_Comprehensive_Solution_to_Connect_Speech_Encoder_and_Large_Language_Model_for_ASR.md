# 全面解决方案：构建语音编码器与大型语言模型的桥梁，助力自动语音识别（ASR）。

发布时间：2024年06月25日

`LLM应用

这篇论文主要探讨了将语音编码器与大型语言模型（LLMs）结合用于语音识别的应用问题，并提出了解决方案。它涉及了微调策略、模态对齐机制以及训练和推理技术的改进，这些都是针对LLM在语音识别领域的具体应用问题。因此，这篇论文应归类于LLM应用。` `语音识别`

> A Comprehensive Solution to Connect Speech Encoder and Large Language Model for ASR

# 摘要

> 近期研究显示，将语音编码器与大型语言模型（LLMs）结合用于语音识别已取得显著进展，但仍面临挑战，如微调选项有限、缺乏语音与文本对齐机制，以及在领域不匹配时插入错误率高。本文提出了一套综合方案应对这些挑战。首先，我们深入探讨了更精细的微调策略。其次，引入了一种匹配损失以加强不同模态间的对齐。最后，我们开发了新的训练和推理技术以大幅降低插入错误。实验在Librispeech语料库上进行，结果显示，采用LoRA等参数高效方法部分微调编码器和LLM，不仅成本效益高，而且通过匹配损失提升了模态对齐，显著提高了性能。

> Recent works have shown promising results in connecting speech encoders to large language models (LLMs) for speech recognition. However, several limitations persist, including limited fine-tuning options, a lack of mechanisms to enforce speech-text alignment, and high insertion errors especially in domain mismatch conditions. This paper presents a comprehensive solution to address these issues. We begin by investigating more thoughtful fine-tuning schemes. Next, we propose a matching loss to enhance alignment between modalities. Finally, we explore training and inference methods to mitigate high insertion errors. Experimental results on the Librispeech corpus demonstrate that partially fine-tuning the encoder and LLM using parameter-efficient methods, such as LoRA, is the most cost-effective approach. Additionally, the matching loss improves modality alignment, enhancing performance. The proposed training and inference methods significantly reduce insertion errors.

[Arxiv](https://arxiv.org/abs/2406.17272)