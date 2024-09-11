# MoWE-Audio：融合弱编码器的多任务音频LLMs

发布时间：2024年09月10日

`LLM应用` `音频处理` `人工智能`

> MoWE-Audio: Multitask AudioLLMs with Mixture of Weak Encoders

# 摘要

> 随着 LLM 的飞速进步，自然语言处理能力大幅提升，催生了能够处理语音和音频的 AudioLLMs。现有 AudioLLMs 通常结合预训练的音频编码器和 LLM，并在特定音频任务上微调。然而，预训练编码器在捕捉新任务特征方面能力有限。为此，我们引入“弱”编码器混合 (MoWE) 到 AudioLLM 框架中。MoWE 通过一组轻量级编码器补充基础编码器，根据音频输入选择性激活，增强特征提取而不显著增加模型大小。实证结果显示，MoWE 有效提升多任务性能，扩展了 AudioLLMs 在多样化音频任务中的应用。

> The rapid advancements in large language models (LLMs) have significantly enhanced natural language processing capabilities, facilitating the development of AudioLLMs that process and understand speech and audio inputs alongside text. Existing AudioLLMs typically combine a pre-trained audio encoder with a pre-trained LLM, which are subsequently finetuned on specific audio tasks. However, the pre-trained audio encoder has constrained capacity to capture features for new tasks and datasets. To address this, we propose to incorporate mixtures of `weak' encoders (MoWE) into the AudioLLM framework. MoWE supplements a base encoder with a pool of relatively light weight encoders, selectively activated based on the audio input to enhance feature extraction without significantly increasing model size. Our empirical results demonstrate that MoWE effectively improves multi-task performance, broadening the applicability of AudioLLMs to more diverse audio tasks.

[Arxiv](https://arxiv.org/abs/2409.06635)