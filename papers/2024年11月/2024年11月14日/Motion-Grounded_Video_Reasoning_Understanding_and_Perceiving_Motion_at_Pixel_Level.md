# 运动为基的视频推理：于像素层面理解与感知运动

发布时间：2024年11月14日

`LLM应用` `视频推理`

> Motion-Grounded Video Reasoning: Understanding and Perceiving Motion at Pixel Level

# 摘要

> 在本文中，我们引入了“运动基础视频推理”这一新的运动理解任务，它要求依据输入问题生成视觉答案（即视频分割掩码），所以需要进行隐式时空推理和基础处理。该任务把现有的聚焦于显式动作/运动基础的时空基础工作拓展到了更通用的形式，借助问题实现隐式推理。为推动新任务的开展，我们收集了一个大规模的数据集，名为 GROUNDMORE，其中涵盖 1715 个视频片段、24.9 万个特意设计了 4 种问题类型（因果、顺序、反事实和描述）的对象掩码，用于对深度且全面的运动推理能力进行基准测试。GROUNDMORE 独特地要求模型生成视觉答案，提供比纯文本更具体且视觉可解释的回应。它从时空基础和推理两方面对模型进行评估，有助于解决运动相关视频推理、时间感知和像素级理解中的复杂难题。此外，我们推出了一个名为“运动基础视频推理助手”（MORA）的新型基线模型。MORA 融合了来自多模态 LLM 的多模态推理能力、来自基础模型（SAM）的像素级感知能力以及来自轻量级定位头的时间感知能力。MORA 在 GROUNDMORE 上表现出色，相对现有的最佳视觉基础基线模型，平均高出 21.5％。我们期望这个新颖且富有挑战性的任务能够为通过视频推理分割在强大且通用的运动理解领域的未来发展铺平道路。

> In this paper, we introduce Motion-Grounded Video Reasoning, a new motion understanding task that requires generating visual answers (video segmentation masks) according to the input question, and hence needs implicit spatiotemporal reasoning and grounding. This task extends existing spatiotemporal grounding work focusing on explicit action/motion grounding, to a more general format by enabling implicit reasoning via questions. To facilitate the development of the new task, we collect a large-scale dataset called GROUNDMORE, which comprises 1,715 video clips, 249K object masks that are deliberately designed with 4 question types (Causal, Sequential, Counterfactual, and Descriptive) for benchmarking deep and comprehensive motion reasoning abilities. GROUNDMORE uniquely requires models to generate visual answers, providing a more concrete and visually interpretable response than plain texts. It evaluates models on both spatiotemporal grounding and reasoning, fostering to address complex challenges in motion-related video reasoning, temporal perception, and pixel-level understanding. Furthermore, we introduce a novel baseline model named Motion-Grounded Video Reasoning Assistant (MORA). MORA incorporates the multimodal reasoning ability from the Multimodal LLM, the pixel-level perception capability from the grounding model (SAM), and the temporal perception ability from a lightweight localization head. MORA achieves respectable performance on GROUNDMORE outperforming the best existing visual grounding baseline model by an average of 21.5% relatively. We hope this novel and challenging task will pave the way for future advancements in robust and general motion understanding via video reasoning segmentation

[Arxiv](https://arxiv.org/abs/2411.09921)