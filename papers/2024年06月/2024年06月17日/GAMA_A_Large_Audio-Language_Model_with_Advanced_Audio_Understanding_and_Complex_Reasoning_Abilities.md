# GAMA：一款集高级音频理解与复杂推理能力于一身的大型音频-语言模型

发布时间：2024年06月17日

`LLM应用

理由：这篇论文主要介绍了一种名为GAMA的大型音频语言模型，它通过整合多种音频表示技术和在特定数据集上的微调，显著提升了音频理解和复杂推理能力。论文的重点在于模型的应用和性能提升，特别是在音频理解和复杂推理任务上的表现，这符合LLM应用的分类，因为它关注的是大型语言模型在特定领域的实际应用和优化。` `音频处理` `问答系统`

> GAMA: A Large Audio-Language Model with Advanced Audio Understanding and Complex Reasoning Abilities

# 摘要

> 为了更好地与环境互动，我们需要准确感知和理解非语音声音及非言语语音。本文介绍了一种名为GAMA的先进大型音频语言模型，它具备强大的音频理解和复杂推理能力。GAMA整合了多种音频表示技术，包括定制的音频Q-Former特征和多层聚合器，后者能从音频编码器的多层提取特征。通过在大型音频语言数据集上进行微调，GAMA的音频理解能力得到显著提升。我们还开发了CompA-R，这是一个专为复杂音频推理设计的指令调优数据集，它要求模型对音频输入进行深入推理。利用CompA-R，我们对GAMA进行了指令调优，并引入了基于音频事件标签的高级语义证据的软提示，进一步增强了其复杂推理能力。最后，我们推出了CompA-R-test，一个用于评估LALMs在开放式音频问答任务上复杂推理能力的人工标注数据集。评估结果显示，GAMA在多种音频理解任务上的表现超越了所有其他文献中的LALMs，提升幅度达到1%至84%。经过CompA-R调优的GAMA在复杂推理和指令遵循方面展现出卓越性能。

> Perceiving and understanding non-speech sounds and non-verbal speech is essential to making decisions that help us interact with our surroundings. In this paper, we propose GAMA, a novel General-purpose Large Audio-Language Model (LALM) with Advanced Audio Understanding and Complex Reasoning Abilities. We build GAMA by integrating an LLM with multiple types of audio representations, including features from a custom Audio Q-Former, a multi-layer aggregator that aggregates features from multiple layers of an audio encoder. We fine-tune GAMA on a large-scale audio-language dataset, which augments it with audio understanding capabilities. Next, we propose CompA-R (Instruction-Tuning for Complex Audio Reasoning), a synthetically generated instruction-tuning (IT) dataset with instructions that require the model to perform complex reasoning on the input audio. We instruction-tune GAMA with CompA-R to endow it with complex reasoning abilities, where we further add a soft prompt as input with high-level semantic evidence by leveraging event tags of the input audio. Finally, we also propose CompA-R-test, a human-labeled evaluation dataset for evaluating the capabilities of LALMs on open-ended audio question-answering that requires complex reasoning. Through automated and expert human evaluations, we show that GAMA outperforms all other LALMs in literature on diverse audio understanding tasks by margins of 1%-84%. Further, GAMA IT-ed on CompA-R proves to be superior in its complex reasoning and instruction following capabilities.

[Arxiv](https://arxiv.org/abs/2406.11768)