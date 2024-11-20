# Fish-Speech：借助大型语言模型实现高级多语言文本到语音的合成

发布时间：2024年11月02日

`LLM应用` `人工智能` `语音合成`

> Fish-Speech: Leveraging Large Language Models for Advanced Multilingual Text-to-Speech Synthesis

# 摘要

> 文本到语音（TTS）系统在处理复杂语言特征、应对复音表达以及生成自然的多语言语音等方面持续面临挑战，而这些能力对未来的人工智能应用至关重要。在本文中，我们推出了 Fish-Speech 这一全新框架，它采用了串行的快速-慢速双自回归（Dual-AR）架构，增强了分组有限标量矢量量化（GFSQ）在序列生成任务中的稳定性。此架构在保持高保真输出的同时，提高了码本处理效率，对人工智能交互和语音克隆极为有效。
  Fish-Speech 借助大型语言模型（LLMs）进行语言特征提取，无需传统的字素到音素（G2P）转换，从而精简了合成流程，加强了多语言支持。另外，我们通过 GFSQ 开发了 FF-GAN，实现了出色的压缩比和近乎 100％的码本利用率。
  我们的方法解决了当下 TTS 系统的关键局限，为更复杂、具有上下文感知能力的语音合成奠定了基础。实验结果显示，Fish-Speech 在处理复杂语言场景和语音克隆任务时，显著优于基线模型，展现出其在人工智能应用中推动 TTS 技术发展的潜力。该实现的开源地址为 \href{https://github.com/fishaudio/fish-speech}{https://github.com/fishaudio/fish-speech}。

> Text-to-Speech (TTS) systems face ongoing challenges in processing complex linguistic features, handling polyphonic expressions, and producing natural-sounding multilingual speech - capabilities that are crucial for future AI applications. In this paper, we present Fish-Speech, a novel framework that implements a serial fast-slow Dual Autoregressive (Dual-AR) architecture to enhance the stability of Grouped Finite Scalar Vector Quantization (GFSQ) in sequence generation tasks. This architecture improves codebook processing efficiency while maintaining high-fidelity outputs, making it particularly effective for AI interactions and voice cloning.
  Fish-Speech leverages Large Language Models (LLMs) for linguistic feature extraction, eliminating the need for traditional grapheme-to-phoneme (G2P) conversion and thereby streamlining the synthesis pipeline and enhancing multilingual support. Additionally, we developed FF-GAN through GFSQ to achieve superior compression ratios and near 100\% codebook utilization.
  Our approach addresses key limitations of current TTS systems while providing a foundation for more sophisticated, context-aware speech synthesis. Experimental results show that Fish-Speech significantly outperforms baseline models in handling complex linguistic scenarios and voice cloning tasks, demonstrating its potential to advance TTS technology in AI applications. The implementation is open source at \href{https://github.com/fishaudio/fish-speech}{https://github.com/fishaudio/fish-speech}.

[Arxiv](https://arxiv.org/abs/2411.01156)