# 利用分层事件记忆提升长视频理解

发布时间：2024年09月10日

`LLM应用` `视频处理` `人工智能`

> Enhancing Long Video Understanding via Hierarchical Event-Based Memory

# 摘要

> 近期，将视觉基础模型融入 LLM 以构建视频理解系统备受瞩目。现有模型多将视频中的多样化语义信息压缩后输入 LLM，虽在短视频理解上表现优异，但长视频中因粗压缩导致的多个事件信息混合，易引发信息冗余，进而掩盖关键事件语义，影响模型理解。为此，我们提出 HEM-LLM，通过自适应序列分割方案划分长视频中的多个事件，为每个事件单独建模，减少冗余，同时压缩并注入前一事件信息，增强长期事件间依赖。实验结果显示，HEM-LLM 在多项视频理解任务中表现卓越，达到业界领先水平。

> Recently, integrating visual foundation models into large language models (LLMs) to form video understanding systems has attracted widespread attention. Most of the existing models compress diverse semantic information within the whole video and feed it into LLMs for content comprehension. While this method excels in short video understanding, it may result in a blend of multiple event information in long videos due to coarse compression, which causes information redundancy. Consequently, the semantics of key events might be obscured within the vast information that hinders the model's understanding capabilities. To address this issue, we propose a Hierarchical Event-based Memory-enhanced LLM (HEM-LLM) for better understanding of long videos. Firstly, we design a novel adaptive sequence segmentation scheme to divide multiple events within long videos. In this way, we can perform individual memory modeling for each event to establish intra-event contextual connections, thereby reducing information redundancy. Secondly, while modeling current event, we compress and inject the information of the previous event to enhance the long-term inter-event dependencies in videos. Finally, we perform extensive experiments on various video understanding tasks and the results show that our model achieves state-of-the-art performances.

[Arxiv](https://arxiv.org/abs/2409.06299)