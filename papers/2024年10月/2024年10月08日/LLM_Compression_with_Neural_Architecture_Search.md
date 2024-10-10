# 通过神经架构搜索实现 LLM 压缩

发布时间：2024年10月08日

`LLM理论` `人工智能` `计算机视觉`

> LLM Compression with Neural Architecture Search

# 摘要

> LLM 的强大推理能力使其在多种下游任务中表现出色，但随着模型规模的扩大，推理成本急剧上升。我们能否通过压缩 LLM 来满足不同尺寸和延迟的需求？我们采用 NAS 技术，通过精简模型结构（如注意力头、神经元和层），在性能与效率间找到最佳平衡。尽管 NAS 在小模型上已有成功案例，本文进一步扩展其应用至 LLM，显著提升了 MMLU 任务的性能，并实现了更快的设备响应速度。

> Large language models (LLMs) exhibit remarkable reasoning abilities, allowing them to generalize across a wide range of downstream tasks, such as commonsense reasoning or instruction following. However, as LLMs scale, inference costs become increasingly prohibitive, accumulating significantly over their life cycle. This poses the question: Can we compress pre-trained LLMs to meet diverse size and latency requirements? We leverage Neural Architecture Search (NAS) to compress LLMs by pruning structural components, such as attention heads, neurons, and layers, aiming to achieve a Pareto-optimal balance between performance and efficiency. While NAS already achieved promising results on small language models in previous work, in this paper we propose various extensions that allow us to scale to LLMs. Compared to structural pruning baselines, we show that NAS improves performance up to 3.4% on MMLU with an on-device latency speedup.

[Arxiv](https://arxiv.org/abs/2410.06479)