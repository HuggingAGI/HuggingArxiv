# 大型语言模型需掌握拼音，以提升中文语音识别的纠错能力。

发布时间：2024年09月20日

`LLM应用` `语音识别`

> Large Language Model Should Understand Pinyin for Chinese ASR Error Correction

# 摘要

> 大型语言模型通过生成错误纠正技术，能够显著提升自动语音识别系统的性能。本文提出的拼音增强GEC方法，巧妙利用拼音作为补充信息，有效改进了中文ASR的错误纠正。训练时仅依赖合成错误，推理时则采用最佳假设策略。此外，通过拼音与文本间的多任务训练，成功对齐了二者的特征空间。实验结果显示，该方法在Aishell-1和Common Voice数据集上均超越了传统文本输入的GEC。更值得一提的是，我们从增加拼音特征关注权重和对齐拼音与文本隐藏状态特征空间两个角度，深入剖析了PY-GEC及多任务训练的成功之道。

> Large language models can enhance automatic speech recognition systems through generative error correction. In this paper, we propose Pinyin-enhanced GEC, which leverages Pinyi, the phonetic representation of Mandarin Chinese, as supplementary information to improve Chinese ASR error correction. Our approach only utilizes synthetic errors for training and employs the one-best hypothesis during inference. Additionally, we introduce a multitask training approach involving conversion tasks between Pinyin and text to align their feature spaces. Experiments on the Aishell-1 and the Common Voice datasets demonstrate that our approach consistently outperforms GEC with text-only input. More importantly, we provide intuitive explanations for the effectiveness of PY-GEC and multitask training from two aspects: 1) increased attention weight on Pinyin features; and 2) aligned feature space between Pinyin and text hidden states.

[Arxiv](https://arxiv.org/abs/2409.13262)