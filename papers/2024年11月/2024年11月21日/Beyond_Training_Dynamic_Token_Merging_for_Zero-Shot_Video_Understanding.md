# 超越训练：零样本视频理解中的动态令牌合并

发布时间：2024年11月21日

`LLM应用` `计算机视觉`

> Beyond Training: Dynamic Token Merging for Zero-Shot Video Understanding

# 摘要

> 近期，多模态大型语言模型（MLLMs）的新进展为视频理解开拓了新道路。然而，在零样本视频任务中达成高保真度仍困难重重。传统的视频处理方式高度依赖微调来抓取细微的时空细节，这会带来大量的数据和计算成本。相较而言，免训练的方法虽高效，但在保留复杂视频内容中丰富的上下文特征时，往往不够稳健。为此，我们提出了 DYTO，这是一个用于零样本视频理解的全新动态令牌合并框架，能在保留关键场景细节的同时，自适应优化令牌效率。DYTO 融合了分层帧选择和二分令牌合并策略，可动态聚类关键帧并选择性压缩令牌序列，在计算效率和语义丰富度之间实现平衡。在多个基准上开展的大量实验表明了 DYTO 的有效性，其性能优于微调方法和免训练方法，为零样本视频理解树立了新的前沿标杆。

> Recent advancements in multimodal large language models (MLLMs) have opened new avenues for video understanding. However, achieving high fidelity in zero-shot video tasks remains challenging. Traditional video processing methods rely heavily on fine-tuning to capture nuanced spatial-temporal details, which incurs significant data and computation costs. In contrast, training-free approaches, though efficient, often lack robustness in preserving context-rich features across complex video content. To this end, we propose DYTO, a novel dynamic token merging framework for zero-shot video understanding that adaptively optimizes token efficiency while preserving crucial scene details. DYTO integrates a hierarchical frame selection and a bipartite token merging strategy to dynamically cluster key frames and selectively compress token sequences, striking a balance between computational efficiency with semantic richness. Extensive experiments across multiple benchmarks demonstrate the effectiveness of DYTO, achieving superior performance compared to both fine-tuned and training-free methods and setting a new state-of-the-art for zero-shot video understanding.

[Arxiv](https://arxiv.org/abs/2411.14401)