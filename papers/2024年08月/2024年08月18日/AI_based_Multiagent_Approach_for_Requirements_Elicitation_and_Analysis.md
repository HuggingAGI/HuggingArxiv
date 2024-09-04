# 基于人工智能的多代理需求获取与分析方法

发布时间：2024年08月18日

`Agent` `软件开发` `人工智能`

> AI based Multiagent Approach for Requirements Elicitation and Analysis

# 摘要

> 需求工程（RE）在软件开发中至关重要，涉及需求获取、分析、规范和变更管理等任务。尽管其重要性显著，但RE仍面临沟通复杂性、早期不确定性及资源估算准确性等挑战。本研究通过实证方法，探讨了大型语言模型（LLMs）在自动化需求分析中的应用效果。我们构建了一个多代理系统，利用AI模型生成用户故事，评估并提升其质量，并进行优先级排序。我们选用了GPT-3.5、GPT-4 Omni、LLaMA3-70和Mixtral-8B四个模型，对四个真实项目进行了需求分析实验。通过评估模型的语义相似性、API性能及用户反馈，我们发现各模型在任务完成效率上存在差异。Mixtral-8B响应迅速，而GPT-3.5在处理复杂用户故事时表现卓越，能从项目描述中准确提取用户故事。项目成员的反馈进一步验证了LLMs在提升RE流程中的有效性。

> Requirements Engineering (RE) plays a pivotal role in software development, encompassing tasks such as requirements elicitation, analysis, specification, and change management. Despite its critical importance, RE faces challenges including communication complexities, early-stage uncertainties, and accurate resource estimation. This study empirically investigates the effectiveness of utilizing Large Language Models (LLMs) to automate requirements analysis tasks. We implemented a multi-agent system that deploys AI models as agents to generate user stories from initial requirements, assess and improve their quality, and prioritize them using a selected technique. In our implementation, we deployed four models, namely GPT-3.5, GPT-4 Omni, LLaMA3-70, and Mixtral-8B, and conducted experiments to analyze requirements on four real-world projects. We evaluated the results by analyzing the semantic similarity and API performance of different models, as well as their effectiveness and efficiency in requirements analysis, gathering users' feedback on their experiences. Preliminary results indicate notable variations in task completion among the models. Mixtral-8B provided the quickest responses, while GPT-3.5 performed exceptionally well when processing complex user stories with a higher similarity score, demonstrating its capability in deriving accurate user stories from project descriptions. Feedback and suggestions from the four project members further corroborate the effectiveness of LLMs in improving and streamlining RE phases.

[Arxiv](https://arxiv.org/abs/2409.00038)