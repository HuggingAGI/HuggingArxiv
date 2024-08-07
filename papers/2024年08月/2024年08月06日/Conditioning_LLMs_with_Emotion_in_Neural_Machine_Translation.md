# 情感调节在神经机器翻译中对大型语言模型的应用

发布时间：2024年08月06日

`LLM应用` `语音识别` `机器翻译`

> Conditioning LLMs with Emotion in Neural Machine Translation

# 摘要

> 本研究提出了一种创新的机器翻译流程，通过整合语音情感识别模型提取的情感信息到大型语言模型中，以提升翻译质量。我们首先在 Libri-trans 数据集上微调了五个 LLM，并选出最佳模型。接着，我们为 LLM 提示添加了不同维度的情感信息，并在多种配置下训练该模型。实验结果显示，特别是加入唤醒度情感信息后，LLM 的翻译质量得到了显著提升。

> Large Language Models (LLMs) have shown remarkable performance in Natural Language Processing tasks, including Machine Translation (MT). In this work, we propose a novel MT pipeline that integrates emotion information extracted from a Speech Emotion Recognition (SER) model into LLMs to enhance translation quality. We first fine-tune five existing LLMs on the Libri-trans dataset and select the most performant model. Subsequently, we augment LLM prompts with different dimensional emotions and train the selected LLM under these different configurations. Our experiments reveal that integrating emotion information, especially arousal, into LLM prompts leads to notable improvements in translation quality.

[Arxiv](https://arxiv.org/abs/2408.03150)