# 在遥感平台上，对工具辅助代理的评估

发布时间：2024年04月23日

`Agent` `地理空间分析`

> Evaluating Tool-Augmented Agents in Remote Sensing Platforms

# 摘要

> 增强版的大型语言模型（LLMs）在遥感（RS）领域展现出了卓越的性能。但现有的评估标准通常基于预设的图文数据对，采用问答式的输入模板，忽略了真实用户任务的复杂性。想象一位地理空间分析师的操作：他们放大地图的特定区域，选定一个区域来搜集卫星图像，然后简洁地提出“检测这里的所有物体”。如果“这里”并非模板中硬编码指定，而是需要系统根据实时地图定位等状态信息来理解，那么该如何界定“这里”的范围？为了解决这一问题，我们设计了GeoLLM-QA，这是一个新型基准测试，旨在模拟真实用户界面上的语言、视觉和点击操作的长序列。通过对当前顶尖的LLMs在1000项多样化任务上进行深入评估，我们为提升RS应用中的智能代理提供了宝贵的洞见。

> Tool-augmented Large Language Models (LLMs) have shown impressive capabilities in remote sensing (RS) applications. However, existing benchmarks assume question-answering input templates over predefined image-text data pairs. These standalone instructions neglect the intricacies of realistic user-grounded tasks. Consider a geospatial analyst: they zoom in a map area, they draw a region over which to collect satellite imagery, and they succinctly ask "Detect all objects here". Where is `here`, if it is not explicitly hardcoded in the image-text template, but instead is implied by the system state, e.g., the live map positioning? To bridge this gap, we present GeoLLM-QA, a benchmark designed to capture long sequences of verbal, visual, and click-based actions on a real UI platform. Through in-depth evaluation of state-of-the-art LLMs over a diverse set of 1,000 tasks, we offer insights towards stronger agents for RS applications.

[Arxiv](https://arxiv.org/abs/2405.00709)