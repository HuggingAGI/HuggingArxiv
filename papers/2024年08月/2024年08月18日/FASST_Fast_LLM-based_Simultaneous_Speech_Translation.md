# FASST：基于大型语言模型的快速同步语音翻译

发布时间：2024年08月18日

`LLM应用` `语音翻译` `实时通信`

> FASST: Fast LLM-based Simultaneous Speech Translation

# 摘要

> 同时语音翻译（SST）技术能够实时处理流式语音输入并生成翻译文本。然而，现有技术要么延迟高，要么翻译质量不及离线版本。为此，我们推出了FASST，一种基于大型语言模型的快速流式语音翻译方法。通过引入块状因果语音编码和一致性掩码，我们实现了无需重新计算的增量编码。我们还设计了两阶段训练策略，以优化FASST的实时推理性能。在MuST-C数据集上的测试表明，FASST在质量与延迟之间取得了最佳平衡，平均超过同类最佳模型1.5 BLEU，尤其在英语到西班牙语翻译中表现突出。

> Simultaneous speech translation (SST) takes streaming speech input and generates text translation on the fly. Existing methods either have high latency due to recomputation of input representations, or fall behind of offline ST in translation quality. In this paper, we propose FASST, a fast large language model based method for streaming speech translation. We propose blockwise-causal speech encoding and consistency mask, so that streaming speech input can be encoded incrementally without recomputation. Furthermore, we develop a two-stage training strategy to optimize FASST for simultaneous inference. We evaluate FASST and multiple strong prior models on MuST-C dataset. Experiment results show that FASST achieves the best quality-latency trade-off. It outperforms the previous best model by an average of 1.5 BLEU under the same latency for English to Spanish translation.

[Arxiv](https://arxiv.org/abs/2408.09430)