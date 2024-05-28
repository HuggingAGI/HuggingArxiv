# 多奖励模型驱动的大型语言模型微调机制设计

发布时间：2024年05月25日

`Agent

这篇论文主要探讨了大型语言模型（LLMs）在多参数机制设计中的应用，特别是在代理误报偏好的情况下，如何通过训练和支付规则来实现特定目标并鼓励真实偏好披露。论文关注的是如何设计机制以最大化社会福利，并确保激励兼容性和个人理性。这些问题和解决方案更多地涉及代理（Agent）的行为和机制设计，而不是直接关于LLM的理论或应用，因此将其归类为Agent。` `人工智能`

> Mechanism Design for LLM Fine-tuning with Multiple Reward Models

# 摘要

> 近期，通过聚合多种偏好微调大型语言模型（LLMs）的研究备受瞩目。但现有研究多聚焦于聚合算法的实证效果，却鲜少探究代理误报偏好的深层原因。本文将此问题归结为多参数机制设计，探讨LLM提供者如何通过训练与支付规则，达成特定目标并鼓励真实偏好披露。首先，我们论证了支付机制的不可或缺性，指出在众多训练规则下，无支付时诚实报告实为劣势策略。随后，我们提出了一种适用于广泛实践中的社会福利最大化训练规则的仿射最大化支付方案，确保了占优策略激励兼容性与个人理性。进一步地，我们证明在适度的条件下，任何其他实现DSIC的支付规则均可通过添加与代理报告无关的因子，转化为仿射最大化支付。此外，当机制输入为报告偏好的有偏版本时，该机制展现出近似DSIC的特性，彰显了其在现实世界应用中的稳健性。

> Recent research on fine-tuning large language models (LLMs) through the aggregation of multiple preferences has attracted considerable attention. However, the existing literature predominantly focuses on the empirical performance of aggregation algorithms, while neglecting the underlying motivation for agents to misreport their preferences. In this paper, we formalize this as a multi-parameter mechanism design problem, where an LLM provider designs both training and payment rules to achieve specific objectives and promote the truthful reporting of preferences. Firstly, we claim the necessity of a payment scheme by demonstrating that without payments, truth-telling is a strictly dominated strategy under a wide range of training rules. Then, we introduce the affine maximizer payment scheme for the social welfare maximizing training rules that are widely used in practice, which ensures both dominant-strategy incentive compatibility (DSIC) and individual rationality (IR). Furthermore, we prove that under mild conditions, any other payment rule that also implements these training rules in DSIC can be converted to the affine maximizer payment by adding a factor irrelevant to the agents' own reports. We also show that this mechanism satisfies approximate DSIC when the input of the mechanism is a biased version of the reported preferences, showcasing its robustness in real-world applications.

[Arxiv](https://arxiv.org/abs/2405.16276)