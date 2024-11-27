# EfficientEQA：用于开放词汇具身问答的高效之法

发布时间：2024年10月26日

`LLM应用` `机器人` `家用设备`

> EfficientEQA: An Efficient Approach for Open Vocabulary Embodied Question Answering

# 摘要

> 具身问答（EQA）对家用机器人助手而言，是重要却颇具挑战的任务。近期研究显示，大型视觉语言模型（VLMs）能有效用于 EQA，然而现有工作要么聚焦于无具身探索的基于视频的问答，要么依赖封闭式选择集。在真实场景中，机器人代理得在开放词汇环境下高效探索并准确回答问题。为应对这些挑战，我们提出名为 EfficientEQA 的新框架用于开放词汇的 EQA，能实现高效探索与精准回答。在 EfficientEQA 中，机器人通过语义价值加权前沿探索积极探索未知环境，此策略依据黑箱 VLMs 提供的校准置信度所确定的语义重要性来优先探索，从而快速收集相关信息。为生成准确答案，我们运用检索增强生成（RAG），借助 BLIP 从积累的观察中检索有用图像，并通过 VLM 推理来产生响应，不依赖预定义的答案选项。另外，我们把与问题高度相关的观察检测为异常值，让机器人能判定何时有足够信息停止探索并给出答案。实验结果表明我们方法的有效性，与前沿方法相比，回答准确率提升超 15%，以运行步骤衡量的效率提高超 20%。

> Embodied Question Answering (EQA) is an essential yet challenging task for robotic home assistants. Recent studies have shown that large vision-language models (VLMs) can be effectively utilized for EQA, but existing works either focus on video-based question answering without embodied exploration or rely on closed-form choice sets. In real-world scenarios, a robotic agent must efficiently explore and accurately answer questions in open-vocabulary settings. To address these challenges, we propose a novel framework called EfficientEQA for open-vocabulary EQA, which enables efficient exploration and accurate answering. In EfficientEQA, the robot actively explores unknown environments using Semantic-Value-Weighted Frontier Exploration, a strategy that prioritizes exploration based on semantic importance provided by calibrated confidence from black-box VLMs to quickly gather relevant information. To generate accurate answers, we employ Retrieval-Augmented Generation (RAG), which utilizes BLIP to retrieve useful images from accumulated observations and VLM reasoning to produce responses without relying on predefined answer choices. Additionally, we detect observations that are highly relevant to the question as outliers, allowing the robot to determine when it has sufficient information to stop exploring and provide an answer. Experimental results demonstrate the effectiveness of our approach, showing an improvement in answering accuracy by over 15% and efficiency, measured in running steps, by over 20% compared to state-of-the-art methods.

[Arxiv](https://arxiv.org/abs/2410.20263)