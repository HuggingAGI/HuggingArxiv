# 论视频大型语言模型在时间理解方面的一致性

发布时间：2024年11月19日

`LLM应用` `语言模型`

> On the Consistency of Video Large Language Models in Temporal Comprehension

# 摘要

> 视频大型语言模型（Video-LLMs）能够在时间维度上定位语言查询并检索视频片段。然而，这种时间理解能力尚未得到充分研究和理解。于是，我们针对预测一致性展开研究——这是衡量时间定位的鲁棒性与可信度的关键指标。当模型识别出视频内容中的初始时刻后，我们运用一系列探测来检验模型的响应是否与该初始定位相符，以此作为可靠理解的衡量标准。我们的研究结果显示，当前的 Video-LLMs 对视频内容、语言查询以及任务设置的变化颇为敏感，暴露出在保持一致性方面存在严重不足。我们进一步探索了常见的提示和指令调整方法作为可能的解决方案，却发现它们的改进常常不稳定。为此，我们提出了明确考虑一致性的事件时间验证调整，并在定位和一致性方面取得了显著的改进。我们的数据和代码可在 https://github.com/minjoong507/Consistency-of-Video-LLM 获取。

> Video large language models (Video-LLMs) can temporally ground language queries and retrieve video moments. Yet, such temporal comprehension capabilities are neither well-studied nor understood. So we conduct a study on prediction consistency -- a key indicator for robustness and trustworthiness of temporal grounding. After the model identifies an initial moment within the video content, we apply a series of probes to check if the model's responses align with this initial grounding as an indicator of reliable comprehension. Our results reveal that current Video-LLMs are sensitive to variations in video contents, language queries, and task settings, unveiling severe deficiencies in maintaining consistency. We further explore common prompting and instruction-tuning methods as potential solutions, but find that their improvements are often unstable. To that end, we propose event temporal verification tuning that explicitly accounts for consistency, and demonstrate significant improvements for both grounding and consistency. Our data and code will be available at https://github.com/minjoong507/Consistency-of-Video-LLM.

[Arxiv](https://arxiv.org/abs/2411.12951)