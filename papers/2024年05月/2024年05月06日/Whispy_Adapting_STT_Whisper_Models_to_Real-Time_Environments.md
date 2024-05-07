# Whispy：为实时环境量身定制的 STT Whisper 模型

发布时间：2024年05月06日

`LLM应用` `语音识别` `实时处理`

> Whispy: Adapting STT Whisper Models to Real-Time Environments

# 摘要

> 近期，大型通用变换器模型在语音分析领域崭露头角，尤其是 Whisper 在语音识别、翻译、语言识别和声音活动检测等任务上取得了行业领先的成绩。但 Whisper 模型并不适用于实时环境，这限制了其在众多实际应用场景中的使用。本文提出了 Whispy 系统，旨在为预训练的 Whisper 模型赋予实时处理能力。通过一系列结构优化，Whispy 不仅能够实时处理音频流，还能生成高级、连贯的语音转文字，同时保持较低的计算开销。我们在广泛的公开语音数据集上对系统性能进行了评估，探讨了 Whispy 新引入的转录机制对 Whisper 输出的影响。实验结果显示，Whispy 在稳定性、响应速度和准确度上均表现优异。

> Large general-purpose transformer models have recently become the mainstay in the realm of speech analysis. In particular, Whisper achieves state-of-the-art results in relevant tasks such as speech recognition, translation, language identification, and voice activity detection. However, Whisper models are not designed to be used in real-time conditions, and this limitation makes them unsuitable for a vast plethora of practical applications. In this paper, we introduce Whispy, a system intended to bring live capabilities to the Whisper pretrained models. As a result of a number of architectural optimisations, Whispy is able to consume live audio streams and generate high level, coherent voice transcriptions, while still maintaining a low computational cost. We evaluate the performance of our system on a large repository of publicly available speech datasets, investigating how the transcription mechanism introduced by Whispy impacts on the Whisper output. Experimental results show how Whispy excels in robustness, promptness, and accuracy.

[Arxiv](https://arxiv.org/abs/2405.03484)