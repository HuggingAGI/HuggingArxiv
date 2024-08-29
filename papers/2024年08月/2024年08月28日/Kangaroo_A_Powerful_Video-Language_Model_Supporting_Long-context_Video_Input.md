# Kangaroo 模型：专为长视频输入设计，融合视频与语言的强大工具

发布时间：2024年08月28日

`LLM应用` `视频处理` `人工智能`

> Kangaroo: A Powerful Video-Language Model Supporting Long-context Video Input

# 摘要

> 大型语言模型向多模态模型的扩展取得了显著进展，但将视频数据纳入其中仍充满挑战，尤其是长视频。为此，我们推出了 Kangaroo，一款专为解决这些难题而设计的视频多模态模型。面对高质量视频数据的稀缺，我们精心构建了一个大规模、高标注质量的数据集，用于视觉与语言的预训练及指令微调。同时，我们创新性地设计了渐进式训练流程，逐步提升视频分辨率与帧数，以更好地适应长视频的处理需求。评估结果令人振奋：Kangaroo 以 80 亿参数之姿，在多项视频理解测试中独占鳌头，甚至在专为长视频设定的基准上，超越了那些拥有百亿参数的庞然大物和专属模型。

> Rapid advancements have been made in extending Large Language Models (LLMs) to Large Multi-modal Models (LMMs). However, extending input modality of LLMs to video data remains a challenging endeavor, especially for long videos. Due to insufficient access to large-scale high-quality video data and the excessive compression of visual features, current methods exhibit limitations in effectively processing long videos. In this paper, we introduce Kangaroo, a powerful Video LMM aimed at addressing these challenges. Confronted with issue of inadequate training data, we develop a data curation system to build a large-scale dataset with high-quality annotations for vision-language pre-training and instruction tuning. In addition, we design a curriculum training pipeline with gradually increasing resolution and number of input frames to accommodate long videos. Evaluation results demonstrate that, with 8B parameters, Kangaroo achieves state-of-the-art performance across a variety of video understanding benchmarks while exhibiting competitive results on others. Particularly, on benchmarks specialized for long videos, Kangaroo excels some larger models with over 10B parameters and proprietary models.

[Arxiv](https://arxiv.org/abs/2408.15542)