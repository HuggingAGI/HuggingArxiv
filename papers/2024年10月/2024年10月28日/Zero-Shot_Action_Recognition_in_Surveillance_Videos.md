# 监控视频中的零-Shot 动作识别

发布时间：2024年10月28日

`LLM应用` `公共空间`

> Zero-Shot Action Recognition in Surveillance Videos

# 摘要

> 公共空间对监控的需求日益增长，可人力资源短缺带来了重大挑战。当下基于人工智能的视频监控系统高度依赖核心计算机视觉模型，而这些模型需要大量微调，由于数据集有限以及设置艰难（如视角、低质量等），这在监控场景中尤为棘手。在本项工作中，我们提议借助以强大的零样本和少样本泛化能力著称的大型视觉语言模型（LVLMs）来处理监控中的视频理解任务。具体而言，我们探索了 VideoLLaMA2 这一先进的 LVLM 以及改进的令牌级采样方法——自我反思采样（Self-ReS）。我们在 UCF-Crime 数据集上的实验显示，VideoLLaMA2 在零样本性能上实现了显著飞跃，比基线提升了 20％。Self-ReS 还将零样本动作识别性能提高至 44.6％。这些结果凸显了 LVLMs 与改进采样技术相结合在多种场景中推动监控视频分析的潜力。

> The growing demand for surveillance in public spaces presents significant challenges due to the shortage of human resources. Current AI-based video surveillance systems heavily rely on core computer vision models that require extensive finetuning, which is particularly difficult in surveillance settings due to limited datasets and difficult setting (viewpoint, low quality, etc.). In this work, we propose leveraging Large Vision-Language Models (LVLMs), known for their strong zero and few-shot generalization, to tackle video understanding tasks in surveillance. Specifically, we explore VideoLLaMA2, a state-of-the-art LVLM, and an improved token-level sampling method, Self-Reflective Sampling (Self-ReS). Our experiments on the UCF-Crime dataset show that VideoLLaMA2 represents a significant leap in zero-shot performance, with 20% boost over the baseline. Self-ReS additionally increases zero-shot action recognition performance to 44.6%. These results highlight the potential of LVLMs, paired with improved sampling techniques, for advancing surveillance video analysis in diverse scenarios.

[Arxiv](https://arxiv.org/abs/2410.21113)