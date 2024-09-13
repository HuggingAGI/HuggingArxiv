# 通过多令牌预测，Speech-LLaMA 的推理速度得以提升。

发布时间：2024年09月12日

`LLM应用` `语音识别` `人工智能`

> Faster Speech-LLaMA Inference with Multi-token Prediction

# 摘要

> 大型语言模型 (LLM) 在处理多模态任务方面表现出色。通过结合语音编码器和配对数据训练，LLaMA 等模型获得了语音识别 (ASR) 能力，成为 Speech-LLaMA。然而，自回归推理的顺序性和解码器的大小导致推理时间较长。为此，我们提出在单步解码中预测多个标记以加速推理。我们测试了多种模型架构，并采用基于阈值和验证的策略评估其性能。此外，我们设计了基于前缀的束搜索方法，以高效进行最低词错误率 (MWER) 训练。实验结果显示，我们的模型在保持或提升 WER 性能的同时，将解码器调用次数减少了约 3.2 倍。

> Large language models (LLMs) have become proficient at solving a wide variety of tasks, including those involving multi-modal inputs. In particular, instantiating an LLM (such as LLaMA) with a speech encoder and training it on paired data imparts speech recognition (ASR) abilities to the decoder-only model, hence called Speech-LLaMA. Nevertheless, due to the sequential nature of auto-regressive inference and the relatively large decoder, Speech-LLaMA models require relatively high inference time. In this work, we propose to speed up Speech-LLaMA inference by predicting multiple tokens in the same decoding step. We explore several model architectures that enable this, and investigate their performance using threshold-based and verification-based inference strategies. We also propose a prefix-based beam search decoding method that allows efficient minimum word error rate (MWER) training for such models. We evaluate our models on a variety of public benchmarks, where they reduce the number of decoder calls by ~3.2x while maintaining or improving WER performance.

[Arxiv](https://arxiv.org/abs/2409.08148)