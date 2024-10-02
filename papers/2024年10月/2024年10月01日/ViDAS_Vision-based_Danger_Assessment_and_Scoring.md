# ViDAS：视觉驱动的危险评估与评分系统

发布时间：2024年10月01日

`LLM应用` `视频分析` `人工智能`

> ViDAS: Vision-based Danger Assessment and Scoring

# 摘要

> 我们推出了一款创新数据集，旨在通过量化视频中的危险和评估 LLM 的人类相似性，推动危险分析。该数据集包含 100 个 YouTube 视频，每个视频均由人类标注，危险等级从 0 到 10，并附有危险时刻的精确时间戳。此外，LLM 利用视频摘要独立评估危险。我们引入了 MSE 分数，用于衡量人类与 LLM 评估的一致性。这不仅为视频危险评估提供了新工具，还展示了 LLM 在模拟人类评估方面的潜力。

> We present a novel dataset aimed at advancing danger analysis and assessment by addressing the challenge of quantifying danger in video content and identifying how human-like a Large Language Model (LLM) evaluator is for the same. This is achieved by compiling a collection of 100 YouTube videos featuring various events. Each video is annotated by human participants who provided danger ratings on a scale from 0 (no danger to humans) to 10 (life-threatening), with precise timestamps indicating moments of heightened danger. Additionally, we leverage LLMs to independently assess the danger levels in these videos using video summaries. We introduce Mean Squared Error (MSE) scores for multimodal meta-evaluation of the alignment between human and LLM danger assessments. Our dataset not only contributes a new resource for danger assessment in video content but also demonstrates the potential of LLMs in achieving human-like evaluations.

[Arxiv](https://arxiv.org/abs/2410.00477)