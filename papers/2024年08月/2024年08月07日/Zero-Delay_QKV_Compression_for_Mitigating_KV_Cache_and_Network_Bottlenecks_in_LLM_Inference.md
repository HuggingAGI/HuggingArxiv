# 通过零延迟 QKV 压缩技术，我们旨在缓解 LLM 推理过程中 KV 缓存和网络的瓶颈问题。

发布时间：2024年08月07日

`LLM应用` `计算机科学` `人工智能`

> Zero-Delay QKV Compression for Mitigating KV Cache and Network Bottlenecks in LLM Inference

# 摘要

> 在大型语言模型中，键值缓存（KVC）的内存限制在处理长提示时成为推理的难题。我们发现，压缩KV值在提升准确性和缩短作业完成时间（JCT）方面比压缩模型更为有效。但量化KV值和舍弃次要令牌会带来显著的运行时计算延迟。这些方法也无法解决长提示在序列并行（SP）框架中的高计算和通信开销问题。为此，我们基于深入的实验分析，提出了ZeroC系统，该系统不仅消除了延迟，还减少了模型操作的计算和通信时间。ZeroC巧妙地将压缩与解压缩融入模型操作，并智能调整压缩比。此外，它还优化了SP推理框架的通信效率。实验数据显示，ZeroC在降低JCT、减少困惑度、提升吞吐量方面表现卓越，且在保持相同延迟的情况下，性能远超现有技术。ZeroC还能在困惑度增加极小的情况下，大幅降低LLM服务系统的JCT。我们已将相关代码开源。

> In large-language models, memory constraints in the key-value cache (KVC) pose a challenge during inference, especially with long prompts. In this work, we observed that compressing KV values is more effective than compressing the model regarding accuracy and job completion time (JCT). However, quantizing KV values and dropping less-important tokens incur significant runtime computational time overhead, delaying JCT. These methods also cannot reduce computation time or high network communication time overhead in sequence-parallelism (SP) frameworks for long prompts. To tackle these issues, based on our insightful observations from experimental analysis, we propose ZeroC, a Zero-delay QKV Compression system that eliminates time overhead and even reduces computation and communication time of the model operations. ZeroC innovatively embeds compression and decompression operations within model operations and adaptively determines compression ratios at a hybrid layer-token level. Further, it enables a communication-efficient SP inference framework. Trace-driven experiments demonstrate that ZeroC achieves up to 80% lower average JCT, 35% lower average perplexity, and 2.8x higher throughput with the same latency compared to state-of-the-art compression methods. ZeroC also reduces the average JCT of current LLM serving systems by up to 91% with the constraint of 0.1 perplexity increase. We open-sourced the code.

[Arxiv](https://arxiv.org/abs/2408.04107)