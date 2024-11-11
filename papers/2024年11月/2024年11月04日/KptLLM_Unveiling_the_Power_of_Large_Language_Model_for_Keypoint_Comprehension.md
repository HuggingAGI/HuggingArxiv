# KptLLM：揭示大型语言模型在关键点理解方面的力量

发布时间：2024年11月04日

`LLM应用` `图像理解` `多模态模型`

> KptLLM: Unveiling the Power of Large Language Model for Keypoint Comprehension

# 摘要

> 多模态大型语言模型（MLLM）的最新进展极大地提高了它们在图像理解方面的能力。然而，这些模型经常难以掌握像素级的语义细节，例如物体的关键点。为了弥补这一差距，我们引入了语义关键点理解的新挑战，旨在理解不同任务场景中的关键点，包括关键点语义理解、基于视觉提示的关键点检测和基于文本提示的关键点检测。此外，我们引入了 KptLLM，这是一个统一的多模态模型，它利用先识别后检测的策略来有效应对这些挑战。KptLLM 强调了关键点中语义的初始识别，然后通过思维链过程精确确定其位置。凭借几个精心设计的模块，KptLLM 熟练处理各种模态输入，有助于解释语义内容和关键点位置。我们的大量实验表明，KptLLM 在各种关键点检测基准中具有优越性，并且在解释关键点方面具有独特的语义能力。

> Recent advancements in Multimodal Large Language Models (MLLMs) have greatly improved their abilities in image understanding. However, these models often struggle with grasping pixel-level semantic details, e.g., the keypoints of an object. To bridge this gap, we introduce the novel challenge of Semantic Keypoint Comprehension, which aims to comprehend keypoints across different task scenarios, including keypoint semantic understanding, visual prompt-based keypoint detection, and textual prompt-based keypoint detection. Moreover, we introduce KptLLM, a unified multimodal model that utilizes an identify-then-detect strategy to effectively address these challenges. KptLLM underscores the initial discernment of semantics in keypoints, followed by the precise determination of their positions through a chain-of-thought process. With several carefully designed modules, KptLLM adeptly handles various modality inputs, facilitating the interpretation of both semantic contents and keypoint locations. Our extensive experiments demonstrate KptLLM's superiority in various keypoint detection benchmarks and its unique semantic capabilities in interpreting keypoints.

[Arxiv](https://arxiv.org/abs/2411.01846)