# 系统评估 LLM 在对齐任务中的评判能力，聚焦于可解释指标与多样化提示模板的应用。

发布时间：2024年08月23日

`LLM理论` `人工智能`

> Systematic Evaluation of LLM-as-a-Judge in LLM Alignment Tasks: Explainable Metrics and Diverse Prompt Templates

# 摘要

> RLHF 和 DPO 等对齐方法正被积极探索，旨在使大型语言模型（LLM）与人类偏好相匹配。近期，GPT-4 等商业 LLM 被用于评估和对比不同对齐策略。这些模型因其快速反馈和低成本的优势，能够近似人类偏好，从而扮演着人类评估者的角色，这种方法被称为“LLM 作为法官”。然而，由于 LLM 的偏见和不一致决策，其可靠性受到质疑。过往研究虽尝试构建评估框架以衡量 LLM 法官的可靠性和与人类偏好的对齐程度，但所用指标常缺乏充分解释性，且未能解决 LLM 内部的不一致问题。此外，现有研究未充分探讨不同提示模板对 LLM 法官方法的影响，导致对齐算法比较时可能出现不一致。在本研究中，我们通过设定更具理论解释性的评估指标和区分 LLM 内部不一致性的可靠性指标，系统评估了 LLM 法官在对齐任务（如摘要）上的表现。我们构建了一个框架，用于评估、比较和可视化 LLM 法官的可靠性和对齐性，旨在提供有助于选择对齐任务 LLM 法官的洞察。研究结果显示，提示模板对 LLM 法官性能影响显著，且测试的 LLM 法官与人类评估者之间的对齐水平表现一般。

> Alignment approaches such as RLHF and DPO are actively investigated to align large language models (LLMs) with human preferences. Commercial large language models (LLMs) like GPT-4 have been recently employed to evaluate and compare different LLM alignment approaches. These models act as surrogates for human evaluators due to their promising abilities to approximate human preferences with remarkably faster feedback and lower costs. This methodology is referred to as LLM-as-a-judge. However, concerns regarding its reliability have emerged, attributed to LLM judges' biases and inconsistent decision-making. Previous research has sought to develop robust evaluation frameworks for assessing the reliability of LLM judges and their alignment with human preferences. However, the employed evaluation metrics often lack adequate explainability and fail to address the internal inconsistency of LLMs. Additionally, existing studies inadequately explore the impact of various prompt templates when applying LLM-as-a-judge methods, which leads to potentially inconsistent comparisons between different alignment algorithms. In this work, we systematically evaluate LLM judges on alignment tasks (e.g. summarization) by defining evaluation metrics with improved theoretical interpretability and disentangling reliability metrics with LLM internal inconsistency. We develop a framework to evaluate, compare, and visualize the reliability and alignment of LLM judges to provide informative observations that help choose LLM judges for alignment tasks. Our results indicate a significant impact of prompt templates on LLM judge performance, as well as a mediocre alignment level between the tested LLM judges and human evaluators.

[Arxiv](https://arxiv.org/abs/2408.13006)