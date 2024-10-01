# 一种多模态大型语言模型，能够从脑部记录中非侵入性地解码口语文本。

发布时间：2024年09月29日

`LLM应用` `人工智能`

> A multimodal LLM for the non-invasive decoding of spoken text from brain recordings

# 摘要

> 近期，人工智能领域中的脑相关研究备受瞩目，尤其是多模态架构在计算机视觉到自然语言处理领域的扩展。我们的研究聚焦于探索这些架构在非侵入性fMRI记录中解码口语文本的潜力与局限。fMRI数据因其多样性、低分辨率和噪声，以及预训练模型的稀缺性，使得解码任务极具挑战。为此，我们提出了一种端到端的多模态LLM架构，结合了特定变压器编码器和冻结的大型语言模型，以实现更精准的文本解码。实验结果显示，我们的方法在人-人及人-机器人交互的同步fMRI和对话信号记录中表现优异，生成的文本语义更为准确。相关代码已公开在https://github.com/Hmamouche/brain_decode。

> Brain-related research topics in artificial intelligence have recently gained popularity, particularly due to the expansion of what multimodal architectures can do from computer vision to natural language processing. Our main goal in this work is to explore the possibilities and limitations of these architectures in spoken text decoding from non-invasive fMRI recordings. Contrary to vision and textual data, fMRI data represent a complex modality due to the variety of brain scanners, which implies (i) the variety of the recorded signal formats, (ii) the low resolution and noise of the raw signals, and (iii) the scarcity of pretrained models that can be leveraged as foundation models for generative learning. These points make the problem of the non-invasive decoding of text from fMRI recordings very challenging. In this paper, we propose and end-to-end multimodal LLM for decoding spoken text from fMRI signals. The proposed architecture is founded on (i) an encoder derived from a specific transformer incorporating an augmented embedding layer for the encoder and a better-adjusted attention mechanism than that present in the state of the art, and (ii) a frozen large language model adapted to align the embedding of the input text and the encoded embedding of brain activity to decode the output text. A benchmark in performed on a corpus consisting of a set of interactions human-human and human-robot interactions where fMRI and conversational signals are recorded synchronously. The obtained results are very promising, as our proposal outperforms the evaluated models, and is able to generate text capturing more accurate semantics present in the ground truth. The implementation code is provided in https://github.com/Hmamouche/brain_decode.

[Arxiv](https://arxiv.org/abs/2409.19710)