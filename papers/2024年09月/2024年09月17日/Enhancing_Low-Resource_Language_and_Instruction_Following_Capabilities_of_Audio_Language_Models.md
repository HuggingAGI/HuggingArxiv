# 提升音频语言模型在低资源语言和指令跟随方面的能力

发布时间：2024年09月17日

`LLM应用` `语音识别` `多语言处理`

> Enhancing Low-Resource Language and Instruction Following Capabilities of Audio Language Models

# 摘要

> 音频语言模型能理解音频输入，并根据文本指令执行语音识别等任务。这些模型多基于预训练的音频编码器和大型语言模型（LLM），尽管支持多语言，但主要在英语数据上训练，可能仅适用于英语指令或输入。本文首先以泰语为例，探讨现有模型在非主流语言中的表现，发现其缺乏对低资源语言的跨语言能力。接着，研究了数据混合以优化目标语言和英语的模型。此外，整合了音频理解和语音指令跟随能力。实验表明，数据混合能有效提升低资源语言和英语的指令跟随能力。我们的Typhoon-Audio模型在开源音频语言模型中表现优异，与最先进的Gemini-1.5-Pro在英语和泰语中相当。

> Audio language models can understand audio inputs and perform a range of audio-related tasks based on instructions, such as speech recognition and audio captioning, where the instructions are usually textual prompts. Audio language models are mostly initialized from pre-trained audio encoders and large language models (LLMs). Although these pre-trained components were developed to support multiple languages, audio-language models are trained predominantly on English data, which may limit their usability to only English instructions or English speech inputs. First, this paper examines the performance of existing audio language models in an underserved language using Thai as an example. This paper demonstrates that, despite being built on multilingual backbones, audio language models do not exhibit cross-lingual emergent abilities to low-resource languages. Second, this paper studies data mixture for developing audio language models that are optimized for a target language as well as English. In addition. this paper integrates audio comprehension and speech instruction-following capabilities into a single unified model. Our experiments provide insights into data mixture for enhancing instruction-following capabilities in both a low-resource language and English. Our model, Typhoon-Audio, outperforms existing open-source audio language models by a considerable margin, and it is comparable to state-of-the-art Gemini-1.5-Pro in both English and Thai languages.

[Arxiv](https://arxiv.org/abs/2409.10999)