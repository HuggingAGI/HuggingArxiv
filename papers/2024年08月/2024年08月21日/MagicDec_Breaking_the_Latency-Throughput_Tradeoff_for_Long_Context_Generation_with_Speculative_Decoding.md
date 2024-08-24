# MagicDec 技术通过推测性解码，成功打破了长上下文生成中的延迟与吞吐量之间的权衡。

发布时间：2024年08月21日

`LLM应用` `信息技术` `人工智能`

> MagicDec: Breaking the Latency-Throughput Tradeoff for Long Context Generation with Speculative Decoding

# 摘要

> 大型语言模型（LLM）在长上下文应用中日益普及，如聊天机器人和文档分析，但处理长上下文请求时保持低延迟和高吞吐量颇具挑战。推测解码（SD）虽能减少延迟，传统上其效果受限于小批量。MagicDec 却揭示了 SD 在中至长序列的高吞吐量推理中仍能加速，且智能草稿策略随批量增大加速更佳。MagicDec 识别并应对了批量和序列增长带来的瓶颈，优化了 SD 的应用。此外，通过稀疏 KV 缓存，解决了 KV 瓶颈问题。这表明 SD 在长上下文服务中能提升性能，减少延迟，且不影响准确性。实验显示，在 8 个 NVIDIA A100 GPU 上，LLaMA-2-7B-32K 和 LLaMA-3.1-8B 分别实现了高达 2 倍和 1.84 倍的加速。代码已公开，供研究者参考。

> Large Language Models (LLMs) have become more prevalent in long-context applications such as interactive chatbots, document analysis, and agent workflows, but it is challenging to serve long-context requests with low latency and high throughput. Speculative decoding (SD) is a widely used technique to reduce latency without sacrificing performance but the conventional wisdom suggests that its efficacy is limited to small batch sizes. In MagicDec, we show that surprisingly SD can achieve speedup even for a high throughput inference regime for moderate to long sequences. More interestingly, an intelligent drafting strategy can achieve better speedup with increasing batch size based on our rigorous analysis. MagicDec first identifies the bottleneck shifts with increasing batch size and sequence length, and uses these insights to deploy speculative decoding more effectively for high throughput inference. Then, it leverages draft models with sparse KV cache to address the KV bottleneck that scales with both sequence length and batch size. This finding underscores the broad applicability of speculative decoding in long-context serving, as it can enhance throughput and reduce latency without compromising accuracy. For moderate to long sequences, we demonstrate up to 2x speedup for LLaMA-2-7B-32K and 1.84x speedup for LLaMA-3.1-8B when serving batch sizes ranging from 32 to 256 on 8 NVIDIA A100 GPUs. The code is available at https://github.com/Infini-AI-Lab/MagicDec/.

[Arxiv](https://arxiv.org/abs/2408.11049)