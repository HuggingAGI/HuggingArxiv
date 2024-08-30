# 利用大规模预训练模型实现无需训练的视频时间定位

发布时间：2024年08月28日

`LLM应用` `视频分析`

> Training-free Video Temporal Grounding using Large-scale Pre-trained Models

# 摘要

> 视频时间定位任务旨在从长视频中精准识别与自然语言查询最相关的片段。传统模型依赖特定数据集训练，数据成本高且泛化能力有限。为此，我们提出无需训练的TFVTG方法，利用预训练大型模型优势。首先，通过枚举视频提案并借助预训练VLMs选择最佳匹配，但现有VLMs在处理多事件关系和动态过渡时存在局限。我们引入LLMs分析查询中的子事件及其时间关系，将子事件细分为动态过渡与静态状态，并设计动态与静态评分函数以精准评估相关性。最终，结合LLMs提供的子事件顺序与关系，筛选并整合提案。实验证明，该方法在Charades-STA和ActivityNet Captions数据集上实现零样本最佳性能，且在跨数据集与OOD场景中泛化能力更强。

> Video temporal grounding aims to identify video segments within untrimmed videos that are most relevant to a given natural language query. Existing video temporal localization models rely on specific datasets for training and have high data collection costs, but they exhibit poor generalization capability under the across-dataset and out-of-distribution (OOD) settings. In this paper, we propose a Training-Free Video Temporal Grounding (TFVTG) approach that leverages the ability of pre-trained large models. A naive baseline is to enumerate proposals in the video and use the pre-trained visual language models (VLMs) to select the best proposal according to the vision-language alignment. However, most existing VLMs are trained on image-text pairs or trimmed video clip-text pairs, making it struggle to (1) grasp the relationship and distinguish the temporal boundaries of multiple events within the same video; (2) comprehend and be sensitive to the dynamic transition of events (the transition from one event to another) in the video. To address these issues, we propose leveraging large language models (LLMs) to analyze multiple sub-events contained in the query text and analyze the temporal order and relationships between these events. Secondly, we split a sub-event into dynamic transition and static status parts and propose the dynamic and static scoring functions using VLMs to better evaluate the relevance between the event and the description. Finally, for each sub-event description, we use VLMs to locate the top-k proposals and leverage the order and relationships between sub-events provided by LLMs to filter and integrate these proposals. Our method achieves the best performance on zero-shot video temporal grounding on Charades-STA and ActivityNet Captions datasets without any training and demonstrates better generalization capabilities in cross-dataset and OOD settings.

[Arxiv](https://arxiv.org/abs/2408.16219)