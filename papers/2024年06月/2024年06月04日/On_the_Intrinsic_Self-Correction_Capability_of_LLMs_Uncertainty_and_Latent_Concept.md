# 探究大型语言模型（LLMs）的内在自我校正机制：聚焦不确定性与潜在概念

发布时间：2024年06月04日

`LLM理论

这篇论文探讨了大型语言模型（LLMs）的自我修正能力的有效性及其原理，通过实证研究和数学模型来解释这一现象。研究内容涉及模型的内在机制和性能优化，这属于对LLM理论的深入探讨。因此，将其归类为LLM理论是合适的。` `人工智能安全`

> On the Intrinsic Self-Correction Capability of LLMs: Uncertainty and Latent Concept

# 摘要

> 大型语言模型（LLMs）具备自我修正的能力，即在接收到改进指令时能优化其响应。当指令不够具体时，模型依赖其内在的自我修正能力。这种能力在文本净化和偏见缓解等应用中已取得实证成功。然而，自我修正并非总能奏效，有时甚至会误改正确答案。本文探讨了自我修正能力的有效性及其原理，发现恰当的指令能使LLMs达到性能不再提升的收敛状态。我们通过实证揭示，模型的不确定性与激活的潜在概念共同影响自我修正的效果，并提供了一个数学模型来解释这一现象。我们的分析同样适用于视觉-语言模型（VLMs）的自我修正行为，并指出任务无关的去偏见策略可从我们的原则中获益，特别是在选择微调样本时。这一初步成果预示了未来在指令调整和安全对齐方面的广阔前景。

> Large Language Models (LLMs) can improve their responses when instructed to do so, a capability known as self-correction. When these instructions lack specific details about the issues in the response, this is referred to as leveraging the intrinsic self-correction capability. The empirical success of self-correction can be found in various applications, e.g., text detoxification and social bias mitigation. However, leveraging this self-correction capability may not always be effective, as it has the potential to revise an initially correct response into an incorrect one. In this paper, we endeavor to understand how and why leveraging the self-correction capability is effective. We identify that appropriate instructions can guide LLMs to a convergence state, wherein additional self-correction steps do not yield further performance improvements. We empirically demonstrate that model uncertainty and activated latent concepts jointly characterize the effectiveness of self-correction. Furthermore, we provide a mathematical formulation indicating that the activated latent concept drives the convergence of the model uncertainty and self-correction performance. Our analysis can also be generalized to the self-correction behaviors observed in Vision-Language Models (VLMs). Moreover, we highlight that task-agnostic debiasing can benefit from our principle in terms of selecting effective fine-tuning samples. Such initial success demonstrates the potential extensibility for better instruction tuning and safety alignment.

![探究大型语言模型（LLMs）的内在自我校正机制：聚焦不确定性与潜在概念](../../../paper_images/2406.02378/x1.png)

![探究大型语言模型（LLMs）的内在自我校正机制：聚焦不确定性与潜在概念](../../../paper_images/2406.02378/x2.png)

![探究大型语言模型（LLMs）的内在自我校正机制：聚焦不确定性与潜在概念](../../../paper_images/2406.02378/x3.png)

![探究大型语言模型（LLMs）的内在自我校正机制：聚焦不确定性与潜在概念](../../../paper_images/2406.02378/x4.png)

![探究大型语言模型（LLMs）的内在自我校正机制：聚焦不确定性与潜在概念](../../../paper_images/2406.02378/x5.png)

![探究大型语言模型（LLMs）的内在自我校正机制：聚焦不确定性与潜在概念](../../../paper_images/2406.02378/x6.png)

![探究大型语言模型（LLMs）的内在自我校正机制：聚焦不确定性与潜在概念](../../../paper_images/2406.02378/x7.png)

![探究大型语言模型（LLMs）的内在自我校正机制：聚焦不确定性与潜在概念](../../../paper_images/2406.02378/x8.png)

[Arxiv](https://arxiv.org/abs/2406.02378)