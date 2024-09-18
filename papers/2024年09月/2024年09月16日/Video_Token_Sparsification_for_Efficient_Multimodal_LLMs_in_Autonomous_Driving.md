# 通过视频令牌稀疏化，提升自动驾驶中多模态大型语言模型的效率

发布时间：2024年09月16日

`LLM应用` `自动驾驶` `视频处理`

> Video Token Sparsification for Efficient Multimodal LLMs in Autonomous Driving

# 摘要

> 多模态大型语言模型 (MLLM) 凭借强大的逻辑推理能力，为自动驾驶系统的场景理解带来了显著提升。然而，由于其庞大的参数和计算需求，这些模型的实际部署面临巨大挑战。特别是，捕捉细粒度和长上下文视觉信息所需的大量视觉标记，导致延迟和内存消耗增加。为此，我们提出了视频标记稀疏化 (VTS)，通过利用视频帧间的冗余，大幅减少视觉标记数量，同时保留关键信息。VTS 使用轻量级 CNN 模型，自适应地筛选关键帧并剔除冗余标记，从而在不牺牲性能的前提下，提升推理速度并降低内存占用。实验结果表明，VTS 在 DRAMA 和 LingoQA 基准测试中，推理吞吐量提升 33%，内存使用减少 28%，效果显著。

> Multimodal large language models (MLLMs) have demonstrated remarkable potential for enhancing scene understanding in autonomous driving systems through powerful logical reasoning capabilities. However, the deployment of these models faces significant challenges due to their substantial parameter sizes and computational demands, which often exceed the constraints of onboard computation. One major limitation arises from the large number of visual tokens required to capture fine-grained and long-context visual information, leading to increased latency and memory consumption. To address this issue, we propose Video Token Sparsification (VTS), a novel approach that leverages the inherent redundancy in consecutive video frames to significantly reduce the total number of visual tokens while preserving the most salient information. VTS employs a lightweight CNN-based proposal model to adaptively identify key frames and prune less informative tokens, effectively mitigating hallucinations and increasing inference throughput without compromising performance. We conduct comprehensive experiments on the DRAMA and LingoQA benchmarks, demonstrating the effectiveness of VTS in achieving up to a 33\% improvement in inference throughput and a 28\% reduction in memory usage compared to the baseline without compromising performance.

[Arxiv](https://arxiv.org/abs/2409.11182)