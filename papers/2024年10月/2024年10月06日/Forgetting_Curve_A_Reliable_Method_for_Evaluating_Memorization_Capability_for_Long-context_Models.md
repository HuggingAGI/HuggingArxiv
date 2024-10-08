# 遗忘曲线：评估长上下文模型记忆力的有效工具

发布时间：2024年10月06日

`LLM理论` `人工智能`

> Forgetting Curve: A Reliable Method for Evaluating Memorization Capability for Long-context Models

# 摘要

> 近期，许多研究致力于提升语言模型的上下文长度，并开发了多种方法和基准来评估模型的记忆能力。然而，我们发现现有评估方法存在局限。为此，我们深入探讨了这些局限，并提出了一种名为“遗忘曲线”的新方法，用于衡量长上下文模型的记忆能力。遗忘曲线具有鲁棒性，不受测试语料和实验设置影响，且无需依赖提示，适用于各种模型。我们将其应用于多种模型，包括变压器和RNN/SSM架构。结果显示，变压器扩展技术效果显著，而RNN/SSM模型的有效长度则引发疑问。此外，我们还对比了新方法与现有基准及流行指标的差异。相关代码和结果已公开在https://github.com/1azybug/ForgettingCurve。

> Numerous recent works target to extend effective context length for language models and various methods, tasks and benchmarks exist to measure model's effective memorization length. However, through thorough investigations, we find limitations for currently existing evaluations on model's memorization capability. We provide an extensive survey for limitations in this work and propose a new method called forgetting curve to measure the memorization capability of long-context models. We show that forgetting curve has the advantage of being robust to the tested corpus and the experimental settings, of not relying on prompts and can be applied to any model size.
  We apply our forgetting curve to a large variety of models involving both transformer and RNN/SSM based architectures. Our measurement provides empirical evidence for the effectiveness of transformer extension techniques while raises questions for the effective length of RNN/SSM based models. We also examine the difference between our measurement and existing benchmarks as well as popular metrics for various models. Our code and results can be found at https://github.com/1azybug/ForgettingCurve.

[Arxiv](https://arxiv.org/abs/2410.04727)