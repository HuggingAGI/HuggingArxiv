# 重温前缀微调：提示重新参数化的统计益处

发布时间：2024年10月03日

`LLM理论` `人工智能`

> Revisiting Prefix-tuning: Statistical Benefits of Reparameterization among Prompts

# 摘要

> 提示调优和前缀调优等技术因其高效性而备受瞩目，但它们的理论基础尚不明确。例如，前缀调优的成功关键在于重参数化策略，但其背后的理论尚未深入探讨。我们发现，重参数化不仅是技术手段，更基于深厚理论。它隐含地编码了前缀键和值向量间的共享结构，显著提升了参数估计的样本效率。实验证实，这种共享结构增强了前缀调优在多任务中的效果。此外，提示调优也受益于类似结构，为其成功提供了新视角。我们的研究深化了对这些方法及其机制的理解，提供了理论与实证的双重贡献。

> Prompt-based techniques, such as prompt-tuning and prefix-tuning, have gained prominence for their efficiency in fine-tuning large pre-trained models. Despite their widespread adoption, the theoretical foundations of these methods remain limited. For instance, in prefix-tuning, we observe that a key factor in achieving performance parity with full fine-tuning lies in the reparameterization strategy. However, the theoretical principles underpinning the effectiveness of this approach have yet to be thoroughly examined. Our study demonstrates that reparameterization is not merely an engineering trick but is grounded in deep theoretical foundations. Specifically, we show that the reparameterization strategy implicitly encodes a shared structure between prefix key and value vectors. Building on recent insights into the connection between prefix-tuning and mixture of experts models, we further illustrate that this shared structure significantly improves sample efficiency in parameter estimation compared to non-shared alternatives. The effectiveness of prefix-tuning across diverse tasks is empirically confirmed to be enhanced by the shared structure, through extensive experiments in both visual and language domains. Additionally, we uncover similar structural benefits in prompt-tuning, offering new perspectives on its success. Our findings provide theoretical and empirical contributions, advancing the understanding of prompt-based methods and their underlying mechanisms.

[Arxiv](https://arxiv.org/abs/2410.02200)