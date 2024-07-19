# 本模型为设备端流式自动语音识别设计，轻巧高效，专攻标点与单词大小写预测。

发布时间：2024年07月18日

`LLM应用` `语音识别` `智能设备`

> A light-weight and efficient punctuation and word casing prediction model for on-device streaming ASR

# 摘要

> 在自动语音识别（ASR）中，标点符号和单词大小写的预测至关重要。随着设备端流式ASR系统的兴起，设备端进行这些预测的需求日益增长，但相关讨论却不多见。尽管基于Transformer的模型在此领域有所探索，但其庞大的体积并不适合设备端应用。为此，我们设计了一种轻巧高效的模型，结合卷积神经网络（CNN）和双向长短期记忆（BiLSTM），能够实时处理标点符号和单词大小写的预测。实验表明，我们的模型在IWSLT2011测试集上，相较于非Transformer模型的最佳表现，总体F1分数提升了9%。与基于Transformer的代表性模型相比，我们的模型不仅体积小巧（仅为后者的四十分之一），推理速度也快了2.5倍，非常适合集成到设备端的流式ASR系统中。我们的代码已公开，供大家参考使用。

> Punctuation and word casing prediction are necessary for automatic speech recognition (ASR). With the popularity of on-device end-to-end streaming ASR systems, the on-device punctuation and word casing prediction become a necessity while we found little discussion on this. With the emergence of Transformer, Transformer based models have been explored for this scenario. However, Transformer based models are too large for on-device ASR systems. In this paper, we propose a light-weight and efficient model that jointly predicts punctuation and word casing in real time. The model is based on Convolutional Neural Network (CNN) and Bidirectional Long Short-Term Memory (BiLSTM). Experimental results on the IWSLT2011 test set show that the proposed model obtains 9% relative improvement compared to the best of non-Transformer models on overall F1-score. Compared to the representative of Transformer based models, the proposed model achieves comparable results to the representative model while being only one-fortieth its size and 2.5 times faster in terms of inference time. It is suitable for on-device streaming ASR systems. Our code is publicly available.

[Arxiv](https://arxiv.org/abs/2407.13142)