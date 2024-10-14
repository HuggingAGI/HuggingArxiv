# 空中视觉-语言导航：基于语义-拓扑-度量表示引导的 LLM 推理

发布时间：2024年10月10日

`LLM应用` `无人驾驶`

> Aerial Vision-and-Language Navigation via Semantic-Topo-Metric Representation Guided LLM Reasoning

# 摘要

> 空中视觉-语言导航 (VLN) 让无人机通过自然语言指令和视觉线索在户外环境中自如导航，但复杂的空中场景使其颇具挑战。本文提出了一种端到端的零-shot 框架，利用大型语言模型 (LLM) 进行动作预测。我们创新的语义-拓扑-度量表示 (STMR) 增强了 LLM 的空间推理能力，通过将指令相关的地标信息投影到包含位置信息的地图上，并转换为矩阵形式作为 LLM 的输入。实验证明，该方法在真实和模拟环境中均表现出色，使 AerialVLN-S 数据集上的 Oracle 成功率提升了 15.9% 和 12.5%。

> Aerial Vision-and-Language Navigation (VLN) is a novel task enabling Unmanned Aerial Vehicles (UAVs) to navigate in outdoor environments through natural language instructions and visual cues. It remains challenging due to the complex spatial relationships in outdoor aerial scenes. In this paper, we propose an end-to-end zero-shot framework for aerial VLN tasks, where the large language model (LLM) is introduced as our agent for action prediction. Specifically, we develop a novel Semantic-Topo-Metric Representation (STMR) to enhance the spatial reasoning ability of LLMs. This is achieved by extracting and projecting instruction-related semantic masks of landmarks into a top-down map that contains the location information of surrounding landmarks. Further, this map is transformed into a matrix representation with distance metrics as the text prompt to the LLM, for action prediction according to the instruction. Experiments conducted in real and simulation environments have successfully proved the effectiveness and robustness of our method, achieving 15.9% and 12.5% improvements (absolute) in Oracle Success Rate (OSR) on AerialVLN-S dataset.

[Arxiv](https://arxiv.org/abs/2410.08500)