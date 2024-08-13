# Hyperion：借助 LLM 与数据流引导的符号执行，揭露 DApp 的不一致之处

发布时间：2024年08月12日

`LLM应用` `区块链` `软件工程`

> Hyperion: Unveiling DApp Inconsistencies using LLM and Dataflow-Guided Symbolic Execution

# 摘要

> 随着区块链技术的迅猛发展，去中心化应用（DApps）迎来了蓬勃发展。这些应用如同传统应用一样，通过前端描述展示其特色以吸引用户，并通过后端智能合约执行核心业务逻辑。然而，前端描述与实际合约实现之间的功能不一致可能会误导用户，影响 DApps 的信誉。本文首先通过实证研究，揭示了七种常见的不一致类型，并提供了真实案例。接着，我们提出了 HYPERION 方法，该方法能够自动检测 DApps 中前端描述与后端实现的不一致。HYPERION 利用微调后的 LLaMA2 模型分析 DApp 描述，并结合数据流引导的符号执行技术分析合约字节码，最终依据预设的检测模式报告不一致情况。实验表明，HYPERION 在检测不一致性方面表现出色，整体召回率达到 84.06%，精确度高达 92.06%。此外，我们还应用 HYPERION 分析了 835 个真实 DApps，成功识别出 459 个存在至少一种不一致性的应用。

> The rapid advancement of blockchain platforms has significantly accelerated the growth of decentralized applications (DApps). Similar to traditional applications, DApps integrate front-end descriptions that showcase their features to attract users, and back-end smart contracts for executing their business logic. However, inconsistencies between the features promoted in front-end descriptions and those actually implemented in the contract can confuse users and undermine DApps's trustworthiness. In this paper, we first conducted an empirical study to identify seven types of inconsistencies, each exemplified by a real-world DApp. Furthermore, we introduce HYPERION, an approach designed to automatically identify inconsistencies between front-end descriptions and back-end code implementation in DApps. This method leverages a fine-tuned large language model LLaMA2 to analyze DApp descriptions and employs dataflow-guided symbolic execution for contract bytecode analysis. Finally, HYPERION reports the inconsistency based on predefined detection patterns. The experiment on our ground truth dataset consisting of 54 DApps shows that HYPERION reaches 84.06% overall recall and 92.06% overall precision in reporting DApp inconsistencies. We also implement HYPERION to analyze 835 real-world DApps. The experimental results show that HYPERION discovers 459 real-world DApps containing at least one inconsistency.

[Arxiv](https://arxiv.org/abs/2408.06037)