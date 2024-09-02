# 编解码器不容小觑：揭秘音频语言模型中编解码器的语义短板

发布时间：2024年08月30日

`LLM应用` `音频处理`

> Codec Does Matter: Exploring the Semantic Shortcoming of Codec for Audio Language Model

# 摘要

> 音频生成的进步得益于大型语言模型（LLM）的强大能力。当前研究主要提升音频模型的架构和数据规模，常用EnCodec等声学编解码器进行音频标记化。然而，这些编解码器原本用于音频压缩，可能影响音频LLM性能。我们的研究针对现有音频LLM编解码器的不足，特别是生成音频时语义完整性的挑战。例如，VALL-E等方法因声学标记的语义误解，常导致内容不准确和单词错误率（WER）升高。为此，我们提出X-Codec方法，在RVQ前后结合语义特征和重建损失，显著降低WER，并扩展到音乐和声音生成等非语音应用。实验显示，整合语义信息大幅提升音频生成性能。相关代码和演示已公开（演示：https://x-codec-audio.github.io 代码：https://github.com/zhenye234/xcodec）。

> Recent advancements in audio generation have been significantly propelled by the capabilities of Large Language Models (LLMs). The existing research on audio LLM has primarily focused on enhancing the architecture and scale of audio language models, as well as leveraging larger datasets, and generally, acoustic codecs, such as EnCodec, are used for audio tokenization. However, these codecs were originally designed for audio compression, which may lead to suboptimal performance in the context of audio LLM. Our research aims to address the shortcomings of current audio LLM codecs, particularly their challenges in maintaining semantic integrity in generated audio. For instance, existing methods like VALL-E, which condition acoustic token generation on text transcriptions, often suffer from content inaccuracies and elevated word error rates (WER) due to semantic misinterpretations of acoustic tokens, resulting in word skipping and errors. To overcome these issues, we propose a straightforward yet effective approach called X-Codec. X-Codec incorporates semantic features from a pre-trained semantic encoder before the Residual Vector Quantization (RVQ) stage and introduces a semantic reconstruction loss after RVQ. By enhancing the semantic ability of the codec, X-Codec significantly reduces WER in speech synthesis tasks and extends these benefits to non-speech applications, including music and sound generation. Our experiments in text-to-speech, music continuation, and text-to-sound tasks demonstrate that integrating semantic information substantially improves the overall performance of language models in audio generation. Our code and demo are available (Demo: https://x-codec-audio.github.io Code: https://github.com/zhenye234/xcodec)

[Arxiv](https://arxiv.org/abs/2408.17175)