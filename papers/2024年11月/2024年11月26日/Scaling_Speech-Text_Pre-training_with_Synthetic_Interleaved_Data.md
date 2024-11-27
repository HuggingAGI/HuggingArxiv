# 利用合成交错数据进行语音 - 文本预训练的规模扩展

发布时间：2024年11月26日

`LLM应用` `语音交互` `人机交互`

> Scaling Speech-Text Pre-training with Synthetic Interleaved Data

# 摘要

> 语音语言模型（SpeechLMs）能接收语音输入并生成语音输出，相比基于文本的大型语言模型（LLMs），实现了更自然的人机交互。传统开发 SpeechLMs 的方法，因无监督语音数据和并行语音-文本数据的有限可用性而受限，这些数据远不如文本预训练数据丰富，限制了其作为 LLMs 的可扩展性。我们提出一种新方法，借助从文本语料库衍生的大规模合成交错数据来拓展语音-文本预训练，无需并行语音-文本数据集。我们的方法从现有文本语料库采样文本跨度，并用文本到标记模型合成相应语音跨度，高效构建语音-文本交错数据，无需生成真实语音。我们还通过在编码器中引入向量量化瓶颈，采用来自自动语音识别（ASR）模型的监督语音标记器。这种监督训练方式即便在较低采样率（如 12.5Hz）下，也能生成语义保留强的离散语音标记，同时保持语音重建质量。从预训练语言模型起步，将预训练拓展到 1 万亿个标记（含 6000 亿合成交错语音-文本数据），我们在语音语言建模和口语问答中取得了顶尖性能，将口语问题任务的性能从之前的 SOTA（Moshi）的 13%提升至 31%。我们进一步表明，通过用语音对话数据对预训练模型微调，能开发出一个端到端的口语聊天机器人，在对话能力和语音质量方面均可与现有基线媲美，甚至能完全在语音领域运作。

> Speech language models (SpeechLMs) accept speech input and produce speech output, allowing for more natural human-computer interaction compared to text-based large language models (LLMs). Traditional approaches for developing SpeechLMs are constrained by the limited availability of unsupervised speech data and parallel speech-text data, which are significantly less abundant than text pre-training data, thereby limiting their scalability as LLMs. We propose a novel approach to scaling speech-text pre-training by leveraging large-scale synthetic interleaved data derived from text corpora, eliminating the need for parallel speech-text datasets. Our method efficiently constructs speech-text interleaved data by sampling text spans from existing text corpora and synthesizing corresponding speech spans using a text-to-token model, bypassing the need to generate actual speech. We also employ a supervised speech tokenizer derived from an automatic speech recognition (ASR) model by incorporating a vector-quantized bottleneck into the encoder. This supervised training approach results in discrete speech tokens with strong semantic preservation even at lower sampling rates (e.g. 12.5Hz), while still maintaining speech reconstruction quality. Starting from a pre-trained language model and scaling our pre-training to 1 trillion tokens (with 600B synthetic interleaved speech-text data), we achieve state-of-the-art performance in speech language modeling and spoken question answering, improving performance on spoken questions tasks from the previous SOTA of 13% (Moshi) to 31%. We further demonstrate that by fine-tuning the pre-trained model with speech dialogue data, we can develop an end-to-end spoken chatbot that achieves competitive performance comparable to existing baselines in both conversational abilities and speech quality, even operating exclusively in the speech domain.

[Arxiv](https://arxiv.org/abs/2411.17607)