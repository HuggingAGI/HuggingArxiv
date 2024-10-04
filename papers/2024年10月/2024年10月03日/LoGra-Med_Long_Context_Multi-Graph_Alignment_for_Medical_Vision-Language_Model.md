# LoGra-Med：医疗视觉-语言模型的长上下文多图对齐技术

发布时间：2024年10月03日

`LLM应用` `人工智能`

> LoGra-Med: Long Context Multi-Graph Alignment for Medical Vision-Language Model

# 摘要

> 最先进的医疗多模态大型语言模型（如LLaVA-Med和BioMedGPT）在预训练中利用指令跟随数据，但主要通过扩大模型规模和数据量来提升性能，依赖自回归学习目标。然而，我们发现这种学习方案可能导致视觉和语言模态之间的弱对齐，使得模型高度依赖于广泛的预训练数据集，这在医疗领域是一个重大挑战。为此，我们提出了LoGra-Med，一种新的多图对齐算法，强制图像模态、对话描述和扩展字幕之间的三重相关性，帮助模型捕捉上下文意义，处理语言变异性，并在视觉和文本之间建立跨模态关联。我们还设计了一种高效的端到端学习方案，使用黑箱梯度估计，实现了更快的LLaMa 7B训练。实验结果显示，LoGra-Med在医疗VQA任务上与LLAVA-Med表现相当，并且在仅用10%的数据训练时显著优于它。例如，在VQA-RAD上，我们超过了LLAVA-Med 20.13%，并且几乎达到了100%预训练的分数。此外，我们在视觉聊天机器人和零样本图像分类上也超越了SOTA方法，突显了多图对齐的有效性。

> State-of-the-art medical multi-modal large language models (med-MLLM), like LLaVA-Med or BioMedGPT, leverage instruction-following data in pre-training. However, those models primarily focus on scaling the model size and data volume to boost performance while mainly relying on the autoregressive learning objectives. Surprisingly, we reveal that such learning schemes might result in a weak alignment between vision and language modalities, making these models highly reliant on extensive pre-training datasets - a significant challenge in medical domains due to the expensive and time-consuming nature of curating high-quality instruction-following instances. We address this with LoGra-Med, a new multi-graph alignment algorithm that enforces triplet correlations across image modalities, conversation-based descriptions, and extended captions. This helps the model capture contextual meaning, handle linguistic variability, and build cross-modal associations between visuals and text. To scale our approach, we designed an efficient end-to-end learning scheme using black-box gradient estimation, enabling faster LLaMa 7B training. Our results show LoGra-Med matches LLAVA-Med performance on 600K image-text pairs for Medical VQA and significantly outperforms it when trained on 10% of the data. For example, on VQA-RAD, we exceed LLAVA-Med by 20.13% and nearly match the 100% pre-training score (72.52% vs. 72.64%). We also surpass SOTA methods like BiomedGPT on visual chatbots and RadFM on zero-shot image classification with VQA, highlighting the effectiveness of multi-graph alignment.

[Arxiv](https://arxiv.org/abs/2410.02615)