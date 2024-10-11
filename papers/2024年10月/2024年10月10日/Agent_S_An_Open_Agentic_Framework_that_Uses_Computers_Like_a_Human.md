# Agent S：一个让计算机像人类一样思考的开放代理框架

发布时间：2024年10月10日

`Agent` `人机交互` `自动化`

> Agent S: An Open Agentic Framework that Uses Computers Like a Human

# 摘要

> 我们推出了 Agent S，这是一个开放的代理框架，通过图形用户界面 (GUI) 实现与计算机的自主交互，旨在通过自动化复杂的多步骤任务来革新人机交互。Agent S 专注于解决自动化计算机任务中的三大难题：领域知识的获取、长时间任务的规划以及动态、非均匀界面的处理。为此，Agent S 引入了经验增强的分层规划，通过多层次的外部知识搜索和内部经验检索，实现高效的任务规划和子任务执行。此外，它还采用了代理-计算机接口 (ACI)，以更好地发挥基于多模态大型语言模型 (MLLM) 的 GUI 代理的推理和控制能力。在 OSWorld 基准测试中，Agent S 的成功率比基线高出 9.37%（相对提升 83.6%），并刷新了最先进记录。全面的分析不仅展示了各组件的效能，也为未来的优化提供了方向。此外，Agent S 在新发布的 WindowsAgentArena 基准测试中展现了广泛的适用性，支持多种操作系统。代码已开放，访问地址为 https://github.com/simular-ai/Agent-S。

> We present Agent S, an open agentic framework that enables autonomous interaction with computers through a Graphical User Interface (GUI), aimed at transforming human-computer interaction by automating complex, multi-step tasks. Agent S aims to address three key challenges in automating computer tasks: acquiring domain-specific knowledge, planning over long task horizons, and handling dynamic, non-uniform interfaces. To this end, Agent S introduces experience-augmented hierarchical planning, which learns from external knowledge search and internal experience retrieval at multiple levels, facilitating efficient task planning and subtask execution. In addition, it employs an Agent-Computer Interface (ACI) to better elicit the reasoning and control capabilities of GUI agents based on Multimodal Large Language Models (MLLMs). Evaluation on the OSWorld benchmark shows that Agent S outperforms the baseline by 9.37% on success rate (an 83.6% relative improvement) and achieves a new state-of-the-art. Comprehensive analysis highlights the effectiveness of individual components and provides insights for future improvements. Furthermore, Agent S demonstrates broad generalizability to different operating systems on a newly-released WindowsAgentArena benchmark. Code available at https://github.com/simular-ai/Agent-S.

[Arxiv](https://arxiv.org/abs/2410.08164)