# 大型语言模型（LLMs）的内在自我校正能力探究：不确定性与潜在概念之谜

发布时间：2024年06月04日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）的自我修正能力的有效性及其背后的原因，并提出了数学模型来解释这一现象。这些内容涉及LLMs的理论分析和模型内部机制的探讨，因此属于LLM理论分类。虽然文中提到了自我修正在实际应用中的效果，但主要焦点在于理论分析和模型解释，而非具体的应用案例或Agent行为。` `社交偏见缓解`

> On the Intrinsic Self-Correction Capability of LLMs: Uncertainty and Latent Concept

# 摘要

> 大型语言模型（LLMs）具备自我修正能力，即在接收到改进指令时能优化其响应。当指令不具体时，模型依赖其内在的自我修正能力。这种能力在文本去毒化和社交偏见缓解等应用中已见成效。然而，自我修正并非总能奏效，有时甚至会误改正确答案。本文探讨了自我修正的有效性及其原因，发现恰当的指令能使LLMs达到性能不再提升的收敛状态。我们实证了模型不确定性与激活的潜在概念共同影响自我修正的效果，并提出了数学模型来解释这一现象。此分析同样适用于视觉-语言模型（VLMs）的自我修正行为。此外，我们的原则在选择微调样本时对任务无关的去偏见有益，展示了指令调整和安全对齐的潜在进步。

> Large Language Models (LLMs) can improve their responses when instructed to do so, a capability known as self-correction. When these instructions lack specific details about the issues in the response, this is referred to as leveraging the intrinsic self-correction capability. The empirical success of self-correction can be found in various applications, e.g., text detoxification and social bias mitigation. However, leveraging this self-correction capability may not always be effective, as it has the potential to revise an initially correct response into an incorrect one. In this paper, we endeavor to understand how and why leveraging the self-correction capability is effective. We identify that appropriate instructions can guide LLMs to a convergence state, wherein additional self-correction steps do not yield further performance improvements. We empirically demonstrate that model uncertainty and activated latent concepts jointly characterize the effectiveness of self-correction. Furthermore, we provide a mathematical formulation indicating that the activated latent concept drives the convergence of the model uncertainty and self-correction performance. Our analysis can also be generalized to the self-correction behaviors observed in Vision-Language Models (VLMs). Moreover, we highlight that task-agnostic debiasing can benefit from our principle in terms of selecting effective fine-tuning samples. Such initial success demonstrates the potential extensibility for better instruction tuning and safety alignment.

![大型语言模型（LLMs）的内在自我校正能力探究：不确定性与潜在概念之谜](../../../paper_images/2406.02378/x1.png)

![大型语言模型（LLMs）的内在自我校正能力探究：不确定性与潜在概念之谜](../../../paper_images/2406.02378/x2.png)

![大型语言模型（LLMs）的内在自我校正能力探究：不确定性与潜在概念之谜](../../../paper_images/2406.02378/x3.png)

![大型语言模型（LLMs）的内在自我校正能力探究：不确定性与潜在概念之谜](../../../paper_images/2406.02378/x4.png)

![大型语言模型（LLMs）的内在自我校正能力探究：不确定性与潜在概念之谜](../../../paper_images/2406.02378/x5.png)

![大型语言模型（LLMs）的内在自我校正能力探究：不确定性与潜在概念之谜](../../../paper_images/2406.02378/x6.png)

![大型语言模型（LLMs）的内在自我校正能力探究：不确定性与潜在概念之谜](../../../paper_images/2406.02378/x7.png)

![大型语言模型（LLMs）的内在自我校正能力探究：不确定性与潜在概念之谜](../../../paper_images/2406.02378/x8.png)

[Arxiv](https://arxiv.org/abs/2406.02378)