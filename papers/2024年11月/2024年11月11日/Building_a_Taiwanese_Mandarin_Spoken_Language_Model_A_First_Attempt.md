# 构建一个台湾普通话口语语言模型：首次尝试

发布时间：2024年11月11日

`LLM应用` `语音交互` `语言模型`

> Building a Taiwanese Mandarin Spoken Language Model: A First Attempt

# 摘要

> 这份技术报告展示了我们初步尝试为台湾普通话构建一个口语大型语言模型（LLM），专门用于在多轮对话中实现实时的语音到语音交互。我们的端到端模型采用了仅解码器的 Transformer 架构，旨在实现无缝交互，同时保持对话流程，包括允许同时说话和倾听的全双工能力。本文还详细介绍了训练过程，包括使用合成对话进行数据准备以及针对实时交互的调整。我们还开发了一个平台来评估多轮对话中的会话流畅性和响应连贯性。我们希望报告的发布能够为台湾普通话口语 LLM 的未来发展做出贡献。

> This technical report presents our initial attempt to build a spoken large language model (LLM) for Taiwanese Mandarin, specifically tailored to enable real-time, speech-to-speech interaction in multi-turn conversations. Our end-to-end model incorporates a decoder-only transformer architecture and aims to achieve seamless interaction while preserving the conversational flow, including full-duplex capabilities allowing simultaneous speaking and listening. The paper also details the training process, including data preparation with synthesized dialogues and adjustments for real-time interaction. We also developed a platform to evaluate conversational fluency and response coherence in multi-turn dialogues. We hope the release of the report can contribute to the future development of spoken LLMs in Taiwanese Mandarin.

[Arxiv](https://arxiv.org/abs/2411.07111)