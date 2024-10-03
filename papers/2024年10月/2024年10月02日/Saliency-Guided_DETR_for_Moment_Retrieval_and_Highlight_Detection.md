# 显著性引导的 DETR 技术，专为时刻检索和高光检测而生。

发布时间：2024年10月02日

`LLM应用` `视频分析`

> Saliency-Guided DETR for Moment Retrieval and Highlight Detection

# 摘要

> 现有的视频时刻检索和高光检测方法在文本与视频特征对齐上表现不佳，限制了实际应用。为此，我们设计了一种新型架构，结合了显著性引导的交叉注意力机制和混合 DETR 架构，大幅提升了这两项任务的性能。此外，我们还创建了 InterVid-MR 数据集，助力我们的架构在 QVHighlights、Charades-STA 和 TACoS 等基准测试中达到顶尖水平。这一创新方法为视频-语言任务中的零-shot 和微调场景提供了高效且可扩展的解决方案。

> Existing approaches for video moment retrieval and highlight detection are not able to align text and video features efficiently, resulting in unsatisfying performance and limited production usage. To address this, we propose a novel architecture that utilizes recent foundational video models designed for such alignment. Combined with the introduced Saliency-Guided Cross Attention mechanism and a hybrid DETR architecture, our approach significantly enhances performance in both moment retrieval and highlight detection tasks. For even better improvement, we developed InterVid-MR, a large-scale and high-quality dataset for pretraining. Using it, our architecture achieves state-of-the-art results on the QVHighlights, Charades-STA and TACoS benchmarks. The proposed approach provides an efficient and scalable solution for both zero-shot and fine-tuning scenarios in video-language tasks.

[Arxiv](https://arxiv.org/abs/2410.01615)