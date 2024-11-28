# SALMONN-omni：一款用于全双工语音理解与生成的无编解码器大语言模型

发布时间：2024年11月27日

`LLM应用` `会话 AI`

> SALMONN-omni: A Codec-free LLM for Full-duplex Speech Understanding and Generation

# 摘要

> 全双工多模态大型语言模型（LLMs）为各类语音理解与生成任务提供了统一框架，使人机对话更自然、无缝。传统的模块化会话 AI 系统将语音识别、理解及文本转语音生成等分为不同组件，而多模态 LLMs 则作为单个端到端模型运作。这种精简设计消除了组件间的错误传播，充分利用了输入语音信号中丰富的非语言信息。我们推出了 SALMONN-omni，这是一款无编解码器的全双工语音理解与生成模型，能在说话时同步监听自身生成的语音及背景声。为支持此功能，我们提出了一种新颖的双工口语对话框架，其中融入了一种“思考”机制，有助于基于嵌入而非编解码器（量化语音和音频令牌）实现异步文本和语音生成。实验结果显示，SALMONN-omni 在包括语音识别、语音增强和口语问答等众多流式语音任务中展现出多面性。此外，SALMONN-omni 在处理轮流发言、插话和回声消除等场景时表现卓越，彰显了其作为全双工会话 AI 系统强大原型的潜力。据我们所知，SALMONN-omni 是此类中首个无编解码器的模型。完整的技术报告及模型检查点即将发布。

> Full-duplex multimodal large language models (LLMs) provide a unified framework for addressing diverse speech understanding and generation tasks, enabling more natural and seamless human-machine conversations. Unlike traditional modularised conversational AI systems, which separate speech recognition, understanding, and text-to-speech generation into distinct components, multimodal LLMs operate as single end-to-end models. This streamlined design eliminates error propagation across components and fully leverages the rich non-verbal information embedded in input speech signals. We introduce SALMONN-omni, a codec-free, full-duplex speech understanding and generation model capable of simultaneously listening to its own generated speech and background sounds while speaking. To support this capability, we propose a novel duplex spoken dialogue framework incorporating a ``thinking'' mechanism that facilitates asynchronous text and speech generation relying on embeddings instead of codecs (quantized speech and audio tokens). Experimental results demonstrate SALMONN-omni's versatility across a broad range of streaming speech tasks, including speech recognition, speech enhancement, and spoken question answering. Additionally, SALMONN-omni excels at managing turn-taking, barge-in, and echo cancellation scenarios, establishing its potential as a robust prototype for full-duplex conversational AI systems. To the best of our knowledge, SALMONN-omni is the first codec-free model of its kind. A full technical report along with model checkpoints will be released soon.

[Arxiv](https://arxiv.org/abs/2411.18138)