# 证明流：形式推理中生成流网络语言模型调优的初步探索

发布时间：2024年10月17日

`LLM应用` `人工智能`

> Proof Flow: Preliminary Study on Generative Flow Network Language Model Tuning for Formal Reasoning

# 摘要

> 推理是解决复杂问题的基石。尽管在系统2推理框架的发展上取得了显著进展，但开放模型仍难以应对高度复杂的问题。为此，我们探索了生成流网络（GFlowNets）作为LLM微调手段，以提升其推理能力。本文在形式推理领域，特别是神经定理证明（NTP）中，展示了GFlowNets的应用潜力。与传统强化学习不同，GFlowNets通过采样组合对象、增强泛化能力及维持多样假设，展现出独特优势。初步结果显示，GFlowNets微调在搜索任务中显著提升模型性能，尤其在当前推理时间计算扩展和“慢思考”趋势下，具有重要意义。

> Reasoning is a fundamental substrate for solving novel and complex problems. Deliberate efforts in learning and developing frameworks around System 2 reasoning have made great strides, yet problems of sufficient complexity remain largely out of reach for open models. To address this gap, we examine the potential of Generative Flow Networks as a fine-tuning method for LLMs to unlock advanced reasoning capabilities. In this paper, we present a proof of concept in the domain of formal reasoning, specifically in the Neural Theorem Proving (NTP) setting, where proofs specified in a formal language such as Lean can be deterministically and objectively verified. Unlike classical reward-maximization reinforcement learning, which frequently over-exploits high-reward actions and fails to effectively explore the state space, GFlowNets have emerged as a promising approach for sampling compositional objects, improving generalization, and enabling models to maintain diverse hypotheses. Our early results demonstrate GFlowNet fine-tuning's potential for enhancing model performance in a search setting, which is especially relevant given the paradigm shift towards inference time compute scaling and "thinking slowly."

[Arxiv](https://arxiv.org/abs/2410.13224)