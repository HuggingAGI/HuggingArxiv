# 探讨大型语言模型（LLMs）的内在自我校正机制：聚焦不确定性与潜在概念

发布时间：2024年06月04日

`LLM理论

这篇论文主要探讨了大型语言模型（LLMs）的自我修正能力的有效性及其背后的理论机制。它通过实证研究和数学模型来解释自我修正效果的影响因素，并指出这些分析也适用于视觉-语言模型（VLMs）。因此，这篇论文更偏向于理论研究，特别是关于LLMs的自我修正机制和性能收敛状态的探讨，属于LLM理论分类。` `人工智能安全`

> On the Intrinsic Self-Correction Capability of LLMs: Uncertainty and Latent Concept

# 摘要

> 大型语言模型（LLMs）具备自我修正能力，即在接收到改进指令时能提升响应质量。尽管这种能力在文本去毒化和社交偏见缓解等应用中取得了成功，但其效果并非总是可靠，有时甚至会将正确响应修改错误。本文探讨了自我修正能力的有效性及其原因，指出恰当的指令能使LLMs达到性能不再提升的收敛状态。我们通过实证揭示，模型的不确定性与激活的潜在概念共同影响自我修正的效果，并提供了一个数学模型来解释这一现象。此外，我们的分析也适用于视觉-语言模型（VLMs）的自我修正行为，并指出任务无关的去偏见在选择微调样本时可借鉴我们的原则。这些初步成果预示着指令调整和安全对齐的广阔前景。

> Large Language Models (LLMs) can improve their responses when instructed to do so, a capability known as self-correction. When these instructions lack specific details about the issues in the response, this is referred to as leveraging the intrinsic self-correction capability. The empirical success of self-correction can be found in various applications, e.g., text detoxification and social bias mitigation. However, leveraging this self-correction capability may not always be effective, as it has the potential to revise an initially correct response into an incorrect one. In this paper, we endeavor to understand how and why leveraging the self-correction capability is effective. We identify that appropriate instructions can guide LLMs to a convergence state, wherein additional self-correction steps do not yield further performance improvements. We empirically demonstrate that model uncertainty and activated latent concepts jointly characterize the effectiveness of self-correction. Furthermore, we provide a mathematical formulation indicating that the activated latent concept drives the convergence of the model uncertainty and self-correction performance. Our analysis can also be generalized to the self-correction behaviors observed in Vision-Language Models (VLMs). Moreover, we highlight that task-agnostic debiasing can benefit from our principle in terms of selecting effective fine-tuning samples. Such initial success demonstrates the potential extensibility for better instruction tuning and safety alignment.

![探讨大型语言模型（LLMs）的内在自我校正机制：聚焦不确定性与潜在概念](../../../paper_images/2406.02378/x1.png)

![探讨大型语言模型（LLMs）的内在自我校正机制：聚焦不确定性与潜在概念](../../../paper_images/2406.02378/x2.png)

![探讨大型语言模型（LLMs）的内在自我校正机制：聚焦不确定性与潜在概念](../../../paper_images/2406.02378/x3.png)

![探讨大型语言模型（LLMs）的内在自我校正机制：聚焦不确定性与潜在概念](../../../paper_images/2406.02378/x4.png)

![探讨大型语言模型（LLMs）的内在自我校正机制：聚焦不确定性与潜在概念](../../../paper_images/2406.02378/x5.png)

![探讨大型语言模型（LLMs）的内在自我校正机制：聚焦不确定性与潜在概念](../../../paper_images/2406.02378/x6.png)

![探讨大型语言模型（LLMs）的内在自我校正机制：聚焦不确定性与潜在概念](../../../paper_images/2406.02378/x7.png)

![探讨大型语言模型（LLMs）的内在自我校正机制：聚焦不确定性与潜在概念](../../../paper_images/2406.02378/x8.png)

[Arxiv](https://arxiv.org/abs/2406.02378)