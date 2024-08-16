# 通过置信度加权整合人机判断，提升决策质量

发布时间：2024年08月15日

`LLM应用` `神经科学` `人工智能`

> Confidence-weighted integration of human and machine judgments for superior decision-making

# 摘要

> 大型语言模型（LLMs）已成为多领域的强大工具。最新研究发现，LLMs 在某些任务上甚至能超越人类，如预测神经科学研究结果。在决策过程中，人类的角色何在？一种可能是，尽管人类表现不及 LLMs，但与机器合作时仍能贡献价值。当人机团队成员的信心得到适当校准，且在任务难度认知上存在差异时，团队整体表现能超越单个成员。我们采用简化的贝叶斯方法，通过逻辑回归框架整合了多成员的信心加权判断。实验证明，在神经科学预测任务中，即使人类表现逊色，与 LLMs 结合后团队表现仍显著提升。我们期待这一简单高效的策略能促进人机间的有效合作。

> Large language models (LLMs) have emerged as powerful tools in various domains. Recent studies have shown that LLMs can surpass humans in certain tasks, such as predicting the outcomes of neuroscience studies. What role does this leave for humans in the overall decision process? One possibility is that humans, despite performing worse than LLMs, can still add value when teamed with them. A human and machine team can surpass each individual teammate when team members' confidence is well-calibrated and team members diverge in which tasks they find difficult (i.e., calibration and diversity are needed). We simplified and extended a Bayesian approach to combining judgments using a logistic regression framework that integrates confidence-weighted judgments for any number of team members. Using this straightforward method, we demonstrated in a neuroscience forecasting task that, even when humans were inferior to LLMs, their combination with one or more LLMs consistently improved team performance. Our hope is that this simple and effective strategy for integrating the judgments of humans and machines will lead to productive collaborations.

[Arxiv](https://arxiv.org/abs/2408.08083)