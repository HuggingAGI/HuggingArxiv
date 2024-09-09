# 密集视频事件问答

发布时间：2024年09月06日

`LLM应用` `视频分析` `问答系统`

> Question-Answering Dense Video Events

# 摘要

> 多模态大型语言模型（MLLM）在单事件视频问答中表现卓越。本文提出了一项新任务——密集视频事件问答，要求模型在长视频中精准回答并定位密集事件，从而考验其对长时间内多事件的理解和推理能力。为此，我们构建了包含 78K 个问题、涉及 26K 个事件的 10.6K 个长视频的 DeVE-QA 数据集。实验显示，擅长单事件问答的现有 MLLM 在 DeVE-QA 中表现欠佳。为提升性能，我们提出了无需训练的 DeVi 方法，通过层次标题、时间事件记忆和自一致性检查模块，分别实现事件检测、上下文记忆和精准定位。实验结果表明，DeVi 在密集事件问答和视频时刻定位方面显著优于现有 MLLM，DeVE-QA 和 NExT-GQA 上的 GQA 准确率分别提升了 4.1% 和 3.7%。

> Multimodal Large Language Models (MLLMs) have shown excellent performance in question-answering of single-event videos. In this paper, we present question-answering dense video events, a novel task that requires answering and grounding the dense-event questions in long videos, thus challenging MLLMs to faithfully comprehend and reason about multiple events occurring over extended time periods. To facilitate the study, we construct DeVE-QA - a dataset featuring 78K questions about 26K events on 10.6K long videos. We then benchmark and show that existing MLLMs excelling at single-event QA struggle to perform well in DeVE-QA. For improvement, we propose DeVi, a novel training-free MLLM approach that highlights a hierarchical captioning module, a temporal event memory module, and a self-consistency checking module to respectively detect, contextualize and memorize, and ground dense-events in long videos for question answering. Extensive experiments show that DeVi is superior at answering dense-event questions and grounding relevant video moments. Compared with existing MLLMs, it achieves a remarkable increase of 4.1 percent and 3.7 percent for G(round)QA accuracy on DeVE-QA and NExT-GQA respectively.

[Arxiv](https://arxiv.org/abs/2409.04388)