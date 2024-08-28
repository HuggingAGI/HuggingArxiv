# 揭秘思维链提示法的统计根基

发布时间：2024年08月25日

`LLM理论` `人工智能` `机器学习`

> Unveiling the Statistical Foundations of Chain-of-Thought Prompting Methods

# 摘要

> CoT 提示及其变体因其解决多步骤推理问题的有效性而广受欢迎。我们通过统计估计视角深入分析 CoT 提示，全面揭示其样本复杂性。为此，我们构建了一个包含推理过程的多步骤潜在变量模型，其中潜在变量承载任务信息。在此框架内，我们发现当预训练数据集庞大时，CoT 提示形成的估计器与贝叶斯估计器等效，通过整合提示示例中的后验分布，高效解决多步骤推理问题。我们还揭示了 CoT 估计器的统计误差由两部分组成：一是由 CoT 提示推断真实任务产生的提示误差，二是预训练 LLM 的统计误差。在合理假设下，我们证明提示误差随演示数量增加而指数级减少。此外，我们详细阐述了预训练 LLM 的近似与泛化误差。特别地，我们设计的转换器模型能以转换器块数量指数级减少的误差逼近多步骤推理问题的目标分布。我们的分析涵盖了 CoT 的其他变体，如 Self-Consistent CoT、Tree-of-Thought 和 Selection-Inference，全面评估这些方法的有效性。最后，我们通过数值实验验证了理论分析的正确性。

> Chain-of-Thought (CoT) prompting and its variants have gained popularity as effective methods for solving multi-step reasoning problems using pretrained large language models (LLMs). In this work, we analyze CoT prompting from a statistical estimation perspective, providing a comprehensive characterization of its sample complexity. To this end, we introduce a multi-step latent variable model that encapsulates the reasoning process, where the latent variable encodes the task information. Under this framework, we demonstrate that when the pretraining dataset is sufficiently large, the estimator formed by CoT prompting is equivalent to a Bayesian estimator. This estimator effectively solves the multi-step reasoning problem by aggregating a posterior distribution inferred from the demonstration examples in the prompt. Moreover, we prove that the statistical error of the CoT estimator can be decomposed into two main components: (i) a prompting error, which arises from inferring the true task using CoT prompts, and (ii) the statistical error of the pretrained LLM. We establish that, under appropriate assumptions, the prompting error decays exponentially to zero as the number of demonstrations increases. Additionally, we explicitly characterize the approximation and generalization errors of the pretrained LLM. Notably, we construct a transformer model that approximates the target distribution of the multi-step reasoning problem with an error that decreases exponentially in the number of transformer blocks. Our analysis extends to other variants of CoT, including Self-Consistent CoT, Tree-of-Thought, and Selection-Inference, offering a broad perspective on the efficacy of these methods. We also provide numerical experiments to validate the theoretical findings.

[Arxiv](https://arxiv.org/abs/2408.14511)