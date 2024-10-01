# 视频数据飞轮：破解视频-语言理解中的“不可能三角”

发布时间：2024年09月28日

`LLM应用` `视频处理` `人工智能`

> Video DataFlywheel: Resolving the Impossible Data Trinity in Video-Language Understanding

# 摘要

> 近期，视频与语言的结合通过大规模预训练取得了显著进展，但数据稀缺仍是主要难题。研究发现，预训练数据集在数量、多样性和质量之间存在“不可能三角”。为应对这一挑战，我们提出了Video DataFlywheel框架，通过迭代改进和创新噪声控制方法AdaTaiLr，有效提升视频注释质量。实验证明，该框架不仅在性能上超越现有基线3%，还显著改善了数据集质量，同时保持了多样性。这一改进不仅提升了视频问答和文本-视频检索等任务的表现，也为视频-语言理解领域带来了新的突破。

> Recently, video-language understanding has achieved great success through large-scale pre-training. However, data scarcity remains a prevailing challenge. This study quantitatively reveals an "impossible trinity" among data quantity, diversity, and quality in pre-training datasets. Recent efforts seek to refine large-scale, diverse ASR datasets compromised by low quality through synthetic annotations. These methods successfully leverage useful information in multimodal video content (frames, tags, ASR transcripts, etc.) to refine the original annotations. Nevertheless, they struggle to mitigate noise within synthetic annotations and lack scalability as the dataset size expands. To address these issues, we introduce the Video DataFlywheel framework, which iteratively refines video annotations with improved noise control methods. For iterative refinement, we first leverage a video-language model to generate synthetic annotations, resulting in a refined dataset. Then, we pre-train on it and fine-tune on human refinement examples for a stronger model. These processes are repeated for continuous improvement. For noise control, we present AdaTaiLr, a novel noise control method that requires weaker assumptions on noise distribution, thereby proving more effective in large datasets with theoretical guarantees. The combination of iterative refinement and AdaTaiLr can achieve better scalability in video-language understanding. Extensive experiments show that our framework outperforms existing data refinement baselines, delivering a 3% performance boost and improving dataset quality with minimal diversity loss. Furthermore, our refined dataset facilitates significant improvements in various video-language understanding tasks, including video question answering and text-video retrieval.

[Arxiv](https://arxiv.org/abs/2409.19532)