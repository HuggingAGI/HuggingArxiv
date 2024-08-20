# 利用文本-音频对的自监督后训练，提升音频-语言模型的性能

发布时间：2024年08月17日

`LLM应用` `音频处理`

> Enhancing Audio-Language Models through Self-Supervised Post-Training with Text-Audio Pairs

# 摘要

> 多模态对比学习策略在音频与文本领域的研究正迅速升温。通过对比训练的音频-语言模型（如CLAP），在音频和语言模态间构建统一表示，显著提升了后续任务的效能，如零-shot音频分类和检索等。然而，模型对自然语言及时序关系的理解仍待深入。本文提出通过时间注入方法TeminAL，增强多模态ALMs的时间理解能力，同时保持其在音频-语言任务中的固有能力。我们采用两阶段训练方案TeminAL A $\&$ B，先在TeminAL A中训练模型区分多种声音，再于TeminAL B中注入时间感，从而提升时间理解。此法在ESC-50数据集上使时间理解平均提升$5.28\%$，且在AudioCap/Clotho数据集的零-shot任务中保持竞争力。此外，我们指出对比ALMs评估技术的不足，并提出零-shot设置下的评估策略。通用零-shot模型评估策略ZSTE被用于评估多种模型，展示了一种评估零-shot对比模型的通用方法。通过TeminAL训练的模型在多数下游任务上表现卓越。

> Research on multi-modal contrastive learning strategies for audio and text has rapidly gained interest. Contrastively trained Audio-Language Models (ALMs), such as CLAP, which establish a unified representation across audio and language modalities, have enhanced the efficacy in various subsequent tasks by providing good text aligned audio encoders and vice versa. These improvements are evident in areas like zero-shot audio classification and audio retrieval, among others. However, the ability of these models to understand natural language and temporal relations is still a largely unexplored and open field for research. In this paper, we propose to equip the multi-modal ALMs with temporal understanding without loosing their inherent prior capabilities of audio-language tasks with a temporal instillation method TeminAL. We implement a two-stage training scheme TeminAL A $\&$ B, where the model first learns to differentiate between multiple sounds in TeminAL A, followed by a phase that instills a sense of time, thereby enhancing its temporal understanding in TeminAL B. This approach results in an average performance gain of $5.28\%$ in temporal understanding on the ESC-50 dataset, while the model remains competitive in zero-shot retrieval and classification tasks on the AudioCap/Clotho datasets. We also note the lack of proper evaluation techniques for contrastive ALMs and propose a strategy for evaluating ALMs in zero-shot settings. The general-purpose zero-shot model evaluation strategy ZSTE, is used to evaluate various prior models. ZSTE demonstrates a general strategy to evaluate all ZS contrastive models. The model trained with TeminAL successfully outperforms current models on most downstream tasks.

[Arxiv](https://arxiv.org/abs/2408.09269)