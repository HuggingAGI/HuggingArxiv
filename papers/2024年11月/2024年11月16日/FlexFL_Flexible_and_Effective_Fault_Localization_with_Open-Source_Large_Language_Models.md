# FlexFL：借助开源大型语言模型实现灵活有效的故障定位

发布时间：2024年11月16日

`LLM应用` `软件测试` `故障定位`

> FlexFL: Flexible and Effective Fault Localization with Open-Source Large Language Models

# 摘要

> 由于大型语言模型（LLMs）出色的代码理解能力，一些研究提出借助 LLMs 来定位错误，即基于 LLM 的故障定位（FL），且展现出了良好的性能。然而，其一，这些方法灵活性不足。它们依靠触发错误的测试用例来执行 FL，无法利用其他可用的错误相关信息，比如错误报告。其二，它们基于专有 LLMs，这些 LLMs 虽强大，却存在数据隐私风险。为解决这些局限，我们提出了一个名为 FlexFL 的新型基于 LLM 的 FL 框架，它能够灵活运用不同类型的错误相关信息，并能与开源 LLMs 有效协作。FlexFL 包含两个阶段。在第一阶段，FlexFL 运用不同家族的前沿 FL 技术缩小错误代码的搜索范围，并提供错误相关方法的候选列表。在第二阶段，FlexFL 借助 LLMs 深入探究，再次核查第一阶段所建议方法的代码片段，优化故障定位结果。在每个阶段，FlexFL 基于开源 LLMs 构建代理，它们共享相同的流程，该流程不预设任何类型的错误相关信息，且能与函数调用交互，无需现成的能力。Defects4J 上的大量实验结果表明，FlexFL 优于基线，并且能与不同的开源 LLMs 配合工作。具体来说，采用轻量级开源 LLM Llama3-8B 的 FlexFL 比均使用 GPT-3.5 的两个前沿的基于 LLM 的 FL 方法 AutoFL 和 AgentFL 能多定位 42 和 63 个错误。

> Due to the impressive code comprehension ability of Large Language Models (LLMs), a few studies have proposed to leverage LLMs to locate bugs, i.e., LLM-based FL, and demonstrated promising performance. However, first, these methods are limited in flexibility. They rely on bug-triggering test cases to perform FL and cannot make use of other available bug-related information, e.g., bug reports. Second, they are built upon proprietary LLMs, which are, although powerful, confronted with risks in data privacy. To address these limitations, we propose a novel LLM-based FL framework named FlexFL, which can flexibly leverage different types of bug-related information and effectively work with open-source LLMs. FlexFL is composed of two stages. In the first stage, FlexFL reduces the search space of buggy code using state-of-the-art FL techniques of different families and provides a candidate list of bug-related methods. In the second stage, FlexFL leverages LLMs to delve deeper to double-check the code snippets of methods suggested by the first stage and refine fault localization results. In each stage, FlexFL constructs agents based on open-source LLMs, which share the same pipeline that does not postulate any type of bug-related information and can interact with function calls without the out-of-the-box capability. Extensive experimental results on Defects4J demonstrate that FlexFL outperforms the baselines and can work with different open-source LLMs. Specifically, FlexFL with a lightweight open-source LLM Llama3-8B can locate 42 and 63 more bugs than two state-of-the-art LLM-based FL approaches AutoFL and AgentFL that both use GPT-3.5.

[Arxiv](https://arxiv.org/abs/2411.10714)