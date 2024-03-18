# [CAT研究致力于提升大型多模态语言模型，在充满变化的音视频场景下解答问题的能力。]

发布时间：2024年03月07日

`Agent`

> CAT: Enhancing Multimodal Large Language Model to Answer Questions in Dynamic Audio-Visual Scenarios

> 面对富含复杂动态音视频元素的场景下解答问题的难题，本文重点介绍CAT技术，通过三种创新手段提升多模态大型语言模型（MLLM）的表现力。首先，CAT不仅简单融合音频和视频信息，更设计了线索聚合器，智能汇集相关线索，充实大型语言模型所需的具体情境知识。其次，CAT基于混合多模态数据集进行训练，能够直接适用于音频-视觉场景，并特别构建了名为AVinstruct的音频-视觉联合指令数据集，进一步强化模型跨越语义关联的能力。最后，我们提出了AI辅助的消除模糊性倾向优化策略，针对模型进行微调，使其倾向于给出明确无误的回答，并提升精确锁定特定视听对象的能力。大量实验证明，CAT在多模态任务上表现卓越，尤其是在音频-视觉问答（AVQA）任务中。相关代码和收集的指令集已公开在https://github.com/rikeilong/Bay-CAT。

> This paper focuses on the challenge of answering questions in scenarios that are composed of rich and complex dynamic audio-visual components. Although existing Multimodal Large Language Models (MLLMs) can respond to audio-visual content, these responses are sometimes ambiguous and fail to describe specific audio-visual events. To overcome this limitation, we introduce the CAT, which enhances MLLM in three ways: 1) besides straightforwardly bridging audio and video, we design a clue aggregator that aggregates question-related clues in dynamic audio-visual scenarios to enrich the detailed knowledge required for large language models. 2) CAT is trained on a mixed multimodal dataset, allowing direct application in audio-visual scenarios. Notably, we collect an audio-visual joint instruction dataset named AVinstruct, to further enhance the capacity of CAT to model cross-semantic correlations. 3) we propose AI-assisted ambiguity-aware direct preference optimization, a strategy specialized in retraining the model to favor the non-ambiguity response and improve the ability to localize specific audio-visual objects. Extensive experimental results demonstrate that CAT outperforms existing methods on multimodal tasks, especially in Audio-Visual Question Answering (AVQA) tasks. The codes and the collected instructions are released at https://github.com/rikeilong/Bay-CAT.

[Arxiv](https://arxiv.org/abs/2403.04640)