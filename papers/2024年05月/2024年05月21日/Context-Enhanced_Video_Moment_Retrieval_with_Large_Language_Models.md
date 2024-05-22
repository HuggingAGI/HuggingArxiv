# 大型语言模型助力上下文增强的视频时刻检索

发布时间：2024年05月21日

`LLM应用

这篇论文介绍了一种名为“大型语言模型引导的时刻检索（LMR）”的新方法，该方法利用大型语言模型的知识来增强视频的上下文表示和跨模态对齐，以精准定位视频中的目标时刻。这种方法通过融合语言模型生成的关键语义与视觉特征，形成高度区分性的视频表示，并设计了一个语言条件下的变压器来实时解码语言查询，用于时刻检索。由于这种方法直接应用了大型语言模型来解决视频时刻检索的问题，因此属于LLM应用分类。` `视频检索` `多媒体内容分析`

> Context-Enhanced Video Moment Retrieval with Large Language Models

# 摘要

> 当前的视频时刻检索方法在处理包含特定环境细节、角色描述和动作叙述的复杂场景时显得力不从心。为此，我们提出了一种新颖的解决方案——大型语言模型引导的时刻检索（LMR），它巧妙地利用了大型语言模型的丰富知识，不仅增强了视频的上下文表示，还优化了跨模态对齐，从而精准定位目标时刻。LMR通过引入一种基于大型语言模型的上下文增强技术，生成了与目标紧密相关的关键语义，并将这些语义与视觉特征融合，形成了具有高度区分性的视频表示。此外，我们还设计了一个语言条件下的变压器，它能实时解码自由形式的语言查询，并利用这些对齐的视频表示进行时刻检索。实验结果令人鼓舞，LMR在QVHighlights和Charades-STA这两个极具挑战性的基准测试中，分别以3.28%和4.06%的优势超越了其他竞争者，尤其是在处理复杂查询时，其性能提升更为显著。

> Current methods for Video Moment Retrieval (VMR) struggle to align complex situations involving specific environmental details, character descriptions, and action narratives. To tackle this issue, we propose a Large Language Model-guided Moment Retrieval (LMR) approach that employs the extensive knowledge of Large Language Models (LLMs) to improve video context representation as well as cross-modal alignment, facilitating accurate localization of target moments. Specifically, LMR introduces a context enhancement technique with LLMs to generate crucial target-related context semantics. These semantics are integrated with visual features for producing discriminative video representations. Finally, a language-conditioned transformer is designed to decode free-form language queries, on the fly, using aligned video representations for moment retrieval. Extensive experiments demonstrate that LMR achieves state-of-the-art results, outperforming the nearest competitor by up to 3.28\% and 4.06\% on the challenging QVHighlights and Charades-STA benchmarks, respectively. More importantly, the performance gains are significantly higher for localization of complex queries.

[Arxiv](https://arxiv.org/abs/2405.12540)