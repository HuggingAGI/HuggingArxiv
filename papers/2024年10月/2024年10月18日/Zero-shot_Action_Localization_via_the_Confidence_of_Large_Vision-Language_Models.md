# 零-shot 动作定位依赖于大型视觉-语言模型的置信度。

发布时间：2024年10月18日

`LLM应用`

> Zero-shot Action Localization via the Confidence of Large Vision-Language Models

# 摘要

> 在未修剪视频中精确的动作定位，对于专业体育和微创手术等领域至关重要。然而，大规模视频-标签数据集的缺乏，限制了视频理解模型的微调。最近，大型视觉-语言模型（LVLM）凭借其零-shot能力，为这一问题提供了新思路。但我们发现，基于图像的LVLMs在长视频动作定位方面的应用仍待探索。为此，我们提出了ZEAL方法，利用大型语言模型的内置知识，将动作细节化，并以此查询LVLM，生成帧级置信度分数，进而实现动作定位。该方法简单灵活，适用于未来更强大的LVLMs，并在零-shot动作定位任务中取得了显著成果，无需任何训练。

> Precise action localization in untrimmed video is vital for fields such as professional sports and minimally invasive surgery, where the delineation of particular motions in recordings can dramatically enhance analysis. But in many cases, large scale datasets with video-label pairs for localization are unavailable, limiting the opportunity to fine-tune video-understanding models. Recent developments in large vision-language models (LVLM) address this need with impressive zero-shot capabilities in a variety of video understanding tasks. However, the adaptation of image-based LVLMs, with their powerful visual question answering capabilities, to action localization in long-form video is still relatively unexplored. To this end, we introduce a true ZEro-shot Action Localization method (ZEAL). Specifically, we leverage the built-in action knowledge of a large language model (LLM) to inflate actions into highly-detailed descriptions of the archetypal start and end of the action. These descriptions serve as queries to LVLM for generating frame-level confidence scores which can be aggregated to produce localization outputs. The simplicity and flexibility of our method lends it amenable to more capable LVLMs as they are developed, and we demonstrate remarkable results in zero-shot action localization on a challenging benchmark, without any training.

[Arxiv](https://arxiv.org/abs/2410.14340)