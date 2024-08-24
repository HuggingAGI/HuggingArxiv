# 帧序关键：少样本动作识别中的时间序列感知模型

发布时间：2024年08月22日

`LLM应用` `人工智能` `计算机视觉`

> Frame Order Matters: A Temporal Sequence-Aware Model for Few-Shot Action Recognition

# 摘要

> 本文提出了一种创新的时序序列感知模型 (TSAM)，用于少样本动作识别 (FSAR)，通过在预训练框架中加入序列感知适配器，整合空间信息与时序动态至特征嵌入。不同于传统微调方法，我们的感知器适配器沿时间线捕捉序列动态，感知顺序变化。为提升类别判别性，我们扩展了每个类别的文本语料库，并丰富视觉原型，融入上下文语义信息。同时，采用不平衡最优传输策略进行特征匹配，减少无关特征干扰，优化决策过程。实验结果显示，我们的方法在五个 FSAR 数据集上创下新纪录，显著领先于其他竞争者。

> In this paper, we propose a novel Temporal Sequence-Aware Model (TSAM) for few-shot action recognition (FSAR), which incorporates a sequential perceiver adapter into the pre-training framework, to integrate both the spatial information and the sequential temporal dynamics into the feature embeddings. Different from the existing fine-tuning approaches that capture temporal information by exploring the relationships among all the frames, our perceiver-based adapter recurrently captures the sequential dynamics alongside the timeline, which could perceive the order change. To obtain the discriminative representations for each class, we extend a textual corpus for each class derived from the large language models (LLMs) and enrich the visual prototypes by integrating the contextual semantic information. Besides, We introduce an unbalanced optimal transport strategy for feature matching that mitigates the impact of class-unrelated features, thereby facilitating more effective decision-making. Experimental results on five FSAR datasets demonstrate that our method set a new benchmark, beating the second-best competitors with large margins.

[Arxiv](https://arxiv.org/abs/2408.12475)