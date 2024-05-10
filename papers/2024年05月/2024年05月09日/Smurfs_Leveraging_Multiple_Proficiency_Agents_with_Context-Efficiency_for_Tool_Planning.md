# 蓝精灵策略：借助高效利用上下文的多技能代理，实现工具规划的优化在翻译过程中，我首先确保原文的核心概念和术语被准确地转换成中文，如“Smurfs”、“Multiple Proficiency Agents”和“Context-Efficiency”。接着，我调整了语言风格，使其更加符合中文的表达习惯，同时保持了原文的生动性和简洁性。通过这种方式，翻译既忠实于原文，又易于中文读者理解。

发布时间：2024年05月09日

`Agent

这篇论文介绍了一种名为“蓝精灵”的多代理框架，它通过将大型语言模型（LLMs）转化为协同工作的多代理团队来提升任务分解与执行的效率。这种框架通过巧妙的提示策略为模型内的每个代理分配独特角色，促进专业分工与合作，并且整合了外部工具以应对复杂挑战。因此，它属于Agent分类，因为它专注于开发和应用多代理系统来增强LLMs的能力。` `人工智能` `自动化任务处理`

> Smurfs: Leveraging Multiple Proficiency Agents with Context-Efficiency for Tool Planning

# 摘要

> 大型语言模型（LLMs）的崛起为自动化复杂任务带来了前所未有的机遇，其表现可与人类媲美。然而，面对高精度与复杂性要求，LLMs仍显捉襟见肘，因其难以独力应对多面性问题。本文推出的“蓝精灵”（Smurfs），是一款革命性的多代理框架，旨在重塑LLMs的应用前景。通过将传统LLM转化为协同工作的多代理团队，蓝精灵在不增加额外训练的情况下，提升了任务分解与执行的效率。这一创新得益于巧妙的提示策略，它为模型内的每个代理分配独特角色，促进专业分工与合作。框架还整合了外部工具，以高效应对复杂挑战。我们的实证研究以mistral-7b-instruct模型为例，展示了蓝精灵在复杂工具运用场景中的卓越表现。在ToolBench I2和I3基准测试中，蓝精灵以84.4%的胜率超越了ChatGPT-ReACT，刷新了GPT-4模型的最佳记录。通过深入的消融研究，我们揭示了多代理框架核心组件对整体效能的贡献，这不仅证实了框架的效力，也为未来多代理LLM系统的探索指明了方向。

> The emergence of large language models (LLMs) has opened up unprecedented possibilities for automating complex tasks that are often comparable to human performance. Despite their capabilities, LLMs still encounter difficulties in completing tasks that require high levels of accuracy and complexity due to their inherent limitations in handling multifaceted problems single-handedly. This paper introduces "Smurfs", a cutting-edge multi-agent framework designed to revolutionize the application of LLMs. By transforming a conventional LLM into a synergistic multi-agent ensemble, Smurfs enhances task decomposition and execution without necessitating extra training. This is achieved through innovative prompting strategies that allocate distinct roles within the model, thereby facilitating collaboration among specialized agents. The framework gives access to external tools to efficiently solve complex tasks. Our empirical investigation, featuring the mistral-7b-instruct model as a case study, showcases Smurfs' superior capability in intricate tool utilization scenarios. Notably, Smurfs outmatches the ChatGPT-ReACT in the ToolBench I2 and I3 benchmark with a remarkable 84.4% win rate, surpassing the highest recorded performance of a GPT-4 model at 73.5%. Furthermore, through comprehensive ablation studies, we dissect the contribution of the core components of the multi-agent framework to its overall efficacy. This not only verifies the effectiveness of the framework, but also sets a route for future exploration of multi-agent LLM systems.

[Arxiv](https://arxiv.org/abs/2405.05955)