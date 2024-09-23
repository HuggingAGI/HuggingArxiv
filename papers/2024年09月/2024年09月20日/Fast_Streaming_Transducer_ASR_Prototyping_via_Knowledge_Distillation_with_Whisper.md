# 借助 Whisper 的知识蒸馏，快速打造流式转录器 ASR 原型

发布时间：2024年09月20日

`LLM应用` `语音识别` `人工智能`

> Fast Streaming Transducer ASR Prototyping via Knowledge Distillation with Whisper

# 摘要

> 在缺乏监督数据的情况下训练自动语音识别（ASR）仍是一个未解之谜。我们发现，流式 Transformer-Transducer（TT）模型可以在普通GPU上，利用基础语音模型（FSM）生成的伪标签语音，从头开始训练。这种方法简化了训练流程，无需庞大的数据和计算资源，避免了传统的预训练和微调两步走。我们深入研究了伪标签流式TT模型的多个关键点，包括n-gram语言模型的浅融合、命名实体的上下文偏置、低延迟流应用的分块解码，以及TT性能与FSM规模的关系。实验证明，即使伪标签质量参差不齐，TT模型也能在没有监督数据的情况下成功训练。我们在CommonVoice的六种语言上验证了这一框架，并设计了多种策略来剔除不可靠的伪标签。

> The training of automatic speech recognition (ASR) with little to no supervised data remains an open question. In this work, we demonstrate that streaming Transformer-Transducer (TT) models can be trained from scratch in consumer and accessible GPUs in their entirety with pseudo-labeled (PL) speech from foundational speech models (FSM). This allows training a robust ASR model just in one stage and does not require large data and computational budget compared to the two-step scenario with pre-training and fine-tuning. We perform a comprehensive ablation on different aspects of PL-based streaming TT models such as the impact of (1) shallow fusion of n-gram LMs, (2) contextual biasing with named entities, (3) chunk-wise decoding for low-latency streaming applications, and (4) TT overall performance as the function of the FSM size. Our results demonstrate that TT can be trained from scratch without supervised data, even with very noisy PLs. We validate the proposed framework on 6 languages from CommonVoice and propose multiple heuristics to filter out hallucinated PLs.

[Arxiv](https://arxiv.org/abs/2409.13499)