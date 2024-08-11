# 语言模型边说边听，功能非凡。

发布时间：2024年08月05日

`Agent` `人工智能`

> Language Model Can Listen While Speaking

# 摘要

> 摘要：对话是人类与计算机交互的自然方式。尽管语音语言模型的进步提升了对话AI，但现有模型仍受限于轮流对话，无法在实时口语场景中灵活互动，如在生成内容不佳时被打断。为此，我们探索了交互式语音模型中的全双工建模，重点提升实时交互能力，特别是打断处理。我们设计了边听边说模型（LSLM），这是一个集听与说于一体的端到端系统。LSLM通过基于令牌的TTS生成语音，并利用流式自监督学习编码器处理实时音频。它融合听与说通道，实时自回归生成并检测对话轮换。我们测试了三种融合策略，中期融合在语音生成与实时交互间取得最佳平衡。实验显示，LSLM在噪声环境下稳健，对多样指令敏感。研究结果表明，LSLM能有效实现双工通信，对现有系统影响甚微。本研究旨在推动交互式语音对话系统的发展，提升其在现实应用中的实用性。

> 
Abstract:Dialogue serves as the most natural manner of human-computer interaction (HCI). Recent advancements in speech language models (SLM) have significantly enhanced speech-based conversational AI. However, these models are limited to turn-based conversation, lacking the ability to interact with humans in real-time spoken scenarios, for example, being interrupted when the generated content is not satisfactory. To address these limitations, we explore full duplex modeling (FDM) in interactive speech language models (iSLM), focusing on enhancing real-time interaction and, more explicitly, exploring the quintessential ability of interruption. We introduce a novel model design, namely listening-while-speaking language model (LSLM), an end-to-end system equipped with both listening and speaking channels. Our LSLM employs a token-based decoder-only TTS for speech generation and a streaming self-supervised learning (SSL) encoder for real-time audio input. LSLM fuses both channels for autoregressive generation and detects turn-taking in real time. Three fusion strategies -- early fusion, middle fusion, and late fusion -- are explored, with middle fusion achieving an optimal balance between speech generation and real-time interaction. Two experimental settings, command-based FDM and voice-based FDM, demonstrate LSLM's robustness to noise and sensitivity to diverse instructions. Our results highlight LSLM's capability to achieve duplex communication with minimal impact on existing systems. This study aims to advance the development of interactive speech dialogue systems, enhancing their applicability in real-world contexts.
    

[Arxiv](https://arxiv.org/pdf/2408.02622)