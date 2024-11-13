# 认知与感知是否一致？评估和减轻文档理解中的多模态知识冲突

发布时间：2024年11月12日

`LLM应用` `文档理解` `多模态任务`

> Is Cognition consistent with Perception? Assessing and Mitigating Multimodal Knowledge Conflicts in Document Understanding

# 摘要

> 多模态大型语言模型（MLLMs）在文档理解方面展现出了令人印象深刻的能力，这是近年来一个快速发展且具有重大工业需求的研究领域。作为一项多模态任务，文档理解要求模型同时具备感知和认知能力。然而，当前的 MLLMs 经常面临感知和认知之间的冲突。以文档 VQA 任务（认知）为例，一个 MLLM 可能生成与通过其 OCR 识别的相应视觉内容不匹配的答案。这种冲突表明，MLLM 可能难以在其“看到”的信息和“理解”的内容之间建立内在联系。这种冲突挑战了认知与感知一致的直观概念，阻碍了 MLLMs 的性能和可解释性。在本文中，我们将认知和感知之间的冲突定义为认知和感知（C&P）知识冲突，这是一种多模态知识冲突的形式，并以文档理解为重点对其进行了系统评估。我们的分析表明，即使是领先的 MLLM GPT-4o，其 C&P 一致性也仅达到 68.6%。为了减轻 C&P 知识冲突，我们提出了一种名为多模态知识一致性微调的新方法。这种方法首先确保任务特定的一致性，然后连接认知和感知知识。我们的方法显著减少了所有测试的 MLLMs 中的 C&P 知识冲突，并在大多数情况下提高了它们在认知和感知任务中的性能。

> Multimodal large language models (MLLMs) have shown impressive capabilities in document understanding, a rapidly growing research area with significant industrial demand in recent years. As a multimodal task, document understanding requires models to possess both perceptual and cognitive abilities. However, current MLLMs often face conflicts between perception and cognition. Taking a document VQA task (cognition) as an example, an MLLM might generate answers that do not match the corresponding visual content identified by its OCR (perception). This conflict suggests that the MLLM might struggle to establish an intrinsic connection between the information it "sees" and what it "understands." Such conflicts challenge the intuitive notion that cognition is consistent with perception, hindering the performance and explainability of MLLMs. In this paper, we define the conflicts between cognition and perception as Cognition and Perception (C&P) knowledge conflicts, a form of multimodal knowledge conflicts, and systematically assess them with a focus on document understanding. Our analysis reveals that even GPT-4o, a leading MLLM, achieves only 68.6% C&P consistency. To mitigate the C&P knowledge conflicts, we propose a novel method called Multimodal Knowledge Consistency Fine-tuning. This method first ensures task-specific consistency and then connects the cognitive and perceptual knowledge. Our method significantly reduces C&P knowledge conflicts across all tested MLLMs and enhances their performance in both cognitive and perceptual tasks in most scenarios.

[Arxiv](https://arxiv.org/abs/2411.07722)