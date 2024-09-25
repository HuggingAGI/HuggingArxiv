# AI 也可能有认知偏差：一项探索性研究揭示了基于 LLM 的批量相关性评估中阈值启动的影响。

发布时间：2024年09月24日

`LLM理论` `信息检索` `人工智能`

> AI Can Be Cognitively Biased: An Exploratory Study on Threshold Priming in LLM-Based Batch Relevance Assessment

# 摘要

> 认知偏差是思维中的系统性偏差，导致非理性判断和有问题的决策，广泛研究于各个领域。最近，大型语言模型 (LLM) 展示了先进的理解能力，但可能从其训练数据中继承了人类偏见。虽然 LLM 中的社会偏见已被广泛研究，但认知偏见受到的关注较少，现有研究主要集中在特定场景。认知偏见对 LLM 在各种决策情境中的广泛影响仍未得到充分探索。我们研究了 LLM 是否受到阈值启动效应在相关性判断中的影响，这是信息检索 (IR) 社区的核心任务和广泛讨论的研究课题。启动效应发生在接触某些刺激无意识地影响后续行为和决策时。我们的实验使用了 TREC 2019 深度学习段落轨道集合中的 10 个主题，并在不同文档相关性评分、批次长度和 LLM 模型（包括 GPT-3.5、GPT-4、LLaMa2-13B 和 LLaMa2-70B）下测试了 AI 判断。结果显示，无论使用何种组合和模型，LLM 倾向于对较早的高相关性文档给予较低评分，反之亦然。我们的发现表明，LLM 的判断与人类判断类似，也受到阈值启动偏见的影响，并建议研究人员和系统工程师在设计、评估和审计 LLM 时，应考虑潜在的人类认知偏见，尤其是在 IR 任务及其他领域。

> Cognitive biases are systematic deviations in thinking that lead to irrational judgments and problematic decision-making, extensively studied across various fields. Recently, large language models (LLMs) have shown advanced understanding capabilities but may inherit human biases from their training data. While social biases in LLMs have been well-studied, cognitive biases have received less attention, with existing research focusing on specific scenarios. The broader impact of cognitive biases on LLMs in various decision-making contexts remains underexplored. We investigated whether LLMs are influenced by the threshold priming effect in relevance judgments, a core task and widely-discussed research topic in the Information Retrieval (IR) coummunity. The priming effect occurs when exposure to certain stimuli unconsciously affects subsequent behavior and decisions. Our experiment employed 10 topics from the TREC 2019 Deep Learning passage track collection, and tested AI judgments under different document relevance scores, batch lengths, and LLM models, including GPT-3.5, GPT-4, LLaMa2-13B and LLaMa2-70B. Results showed that LLMs tend to give lower scores to later documents if earlier ones have high relevance, and vice versa, regardless of the combination and model used. Our finding demonstrates that LLM%u2019s judgments, similar to human judgments, are also influenced by threshold priming biases, and suggests that researchers and system engineers should take into account potential human-like cognitive biases in designing, evaluating, and auditing LLMs in IR tasks and beyond.

[Arxiv](https://arxiv.org/abs/2409.16022)