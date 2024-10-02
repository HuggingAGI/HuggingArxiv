# VideoCLIP-XL：提升视频 CLIP 模型对长描述的理解能力

发布时间：2024年10月01日

`LLM应用` `人工智能`

> VideoCLIP-XL: Advancing Long Description Understanding for Video CLIP Models

# 摘要

> CLIP 在众多应用中表现出色，但其对简短摘要的依赖限制了其对长描述的理解，尤其在视频领域。为此，我们推出了 VideoCLIP-XL 模型，旨在提升对长描述的解析能力。我们首先构建了自动数据收集系统，并创建了包含视频与长描述的大规模 VILD 数据集。接着，我们引入了文本相似性引导的主成分匹配 (TPCM)，以优化特征空间分布并增强长描述处理能力。此外，我们还设计了细节感知和幻觉感知描述排序任务 (DDR 和 HDR)，以深化理解。最后，我们设立了长视频描述排序基准 (LVDR)，以全面评估长描述能力。实验结果表明，我们的方法在处理长描述时表现优异。

> Contrastive Language-Image Pre-training (CLIP) has been widely studied and applied in numerous applications. However, the emphasis on brief summary texts during pre-training prevents CLIP from understanding long descriptions. This issue is particularly acute regarding videos given that videos often contain abundant detailed contents. In this paper, we propose the VideoCLIP-XL (eXtra Length) model, which aims to unleash the long-description understanding capability of video CLIP models. Firstly, we establish an automatic data collection system and gather a large-scale VILD pre-training dataset with VIdeo and Long-Description pairs. Then, we propose Text-similarity-guided Primary Component Matching (TPCM) to better learn the distribution of feature space while expanding the long description capability. We also introduce two new tasks namely Detail-aware Description Ranking (DDR) and Hallucination-aware Description Ranking (HDR) for further understanding improvement. Finally, we construct a Long Video Description Ranking (LVDR) benchmark for evaluating the long-description capability more comprehensively. Extensive experimental results on widely-used text-video retrieval benchmarks with both short and long descriptions and our LVDR benchmark can fully demonstrate the effectiveness of our method.

[Arxiv](https://arxiv.org/abs/2410.00741)