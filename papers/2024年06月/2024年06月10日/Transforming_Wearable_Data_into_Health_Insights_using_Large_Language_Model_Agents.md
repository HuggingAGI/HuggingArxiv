# 借助大型语言模型代理，将可穿戴数据转化为深具价值的健康洞察

发布时间：2024年06月10日

`Agent

理由：这篇论文介绍了一个名为个人健康见解代理（PHIA）的系统，该系统利用大型语言模型（LLM）代理的能力，通过代码生成和信息检索工具对可穿戴设备的行为健康数据进行分析和解读。这个系统展示了LLM代理在个人健康分析领域的应用潜力，并且通过构建基准问答数据集和进行人类与专家评估，证明了其在提供个性化健康见解方面的有效性。因此，这篇论文更符合Agent分类，因为它主要关注的是一个具体的LLM代理应用实例，即在个人健康分析领域的应用。` `健康追踪` `个性化健康分析`

> Transforming Wearable Data into Health Insights using Large Language Model Agents

# 摘要

> 尽管可穿戴健康追踪器日益普及，且睡眠与运动对健康至关重要，但从这些设备数据中提炼出实用的个性化见解依旧困难重重，因为这需要对数据进行深入且开放的分析。近期，大型语言模型（LLM）代理的崛起为我们带来了希望，这些代理能运用工具进行逻辑推理并与现实世界互动，为大规模个性化分析开辟了新途径。然而，LLM代理在个人健康分析领域的应用潜力尚未充分挖掘。本文中，我们推出了个人健康见解代理（PHIA），这一系统借助尖端的代码生成与信息检索工具，对来自可穿戴设备的行为健康数据进行分析与解读。我们构建了两个包含4000多个健康见解问题的基准问答数据集。经过650小时的人类与专家评估，PHIA在事实性数字问题上的准确解答率超过84%，在众包开放式问题上的准确率也超过了83%。此项研究有望推动全民行为健康的发展，使个人能够解读自己的可穿戴数据，引领一个基于数据驱动见解的、可及且个性化的健康养生新时代。

> Despite the proliferation of wearable health trackers and the importance of sleep and exercise to health, deriving actionable personalized insights from wearable data remains a challenge because doing so requires non-trivial open-ended analysis of these data. The recent rise of large language model (LLM) agents, which can use tools to reason about and interact with the world, presents a promising opportunity to enable such personalized analysis at scale. Yet, the application of LLM agents in analyzing personal health is still largely untapped. In this paper, we introduce the Personal Health Insights Agent (PHIA), an agent system that leverages state-of-the-art code generation and information retrieval tools to analyze and interpret behavioral health data from wearables. We curate two benchmark question-answering datasets of over 4000 health insights questions. Based on 650 hours of human and expert evaluation we find that PHIA can accurately address over 84% of factual numerical questions and more than 83% of crowd-sourced open-ended questions. This work has implications for advancing behavioral health across the population, potentially enabling individuals to interpret their own wearable data, and paving the way for a new era of accessible, personalized wellness regimens that are informed by data-driven insights.

[Arxiv](https://arxiv.org/abs/2406.06464)