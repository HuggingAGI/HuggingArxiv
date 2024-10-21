# 系统探讨跨层 KV 共享如何提升 LLM 推理效率

发布时间：2024年10月18日

`LLM理论` `人工智能` `高性能计算`

> A Systematic Study of Cross-Layer KV Sharing for Efficient LLM Inference

# 摘要

> 近期研究发现，跨层共享 KV 缓存在 LLM 的高效推理中表现出色。为此，我们构建了一个涵盖多种方法及其变体的统一框架，系统研究了跨层 KV 共享技术。通过全面实验，我们评估了各配置在语言建模和下游任务中的表现。结果显示，当 KV 缓存减半时，多数配置仍能保持与标准变换器相当的性能，且吞吐量更高。然而，进一步缩减缓存时，将各层查询与上层 KV 配对虽能维持性能，但增加了训练成本和预填充延迟。我们期望这项研究能为用户提供选择依据，并推动 LLM 推理加速的研究。

> Recently, sharing key-value (KV) cache across layers has been found effective in efficient inference of large language models (LLMs). To systematically investigate different techniques of cross-layer KV sharing, we propose a unified framework that covers several recent methods and their novel variants. We conduct comprehensive experiments on all the configurations of the framework, evaluating their generation throughput and performance in language modeling and downstream tasks. We find that when reducing the size of the KV cache by 2x, most configurations can achieve competitive performance to and higher throughput than standard transformers, but when further reducing the size of the KV cache, pairing queries of all layers with KVs of upper layers can better maintain performance, although it also introduces additional training cost and prefilling latency. We hope that this work will help users choose the appropriate approach according to their requirements and facilitate research on the acceleration of LLM inference.

[Arxiv](https://arxiv.org/abs/2410.14442)