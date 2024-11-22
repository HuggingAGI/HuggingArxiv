# NewsInterview：一个用于通过信息性访谈评估LLM基础差距的数据集和试验场

发布时间：2024年11月20日

`LLM应用`

> NewsInterview: a Dataset and a Playground to Evaluate LLMs' Ground Gap via Informational Interviews

# 摘要

> 大型语言模型（LLMs）在生成连贯文本方面能力出众，但在语言落地和策略性对话方面却常遇难题。为弥补这一差距，我们着眼于新闻采访领域，此领域交流落地性强且数据丰富。我们从NPR和CNN精心整理了一个包含40,000个两人信息采访的数据集，发现LLMs与人类采访者相比，明显较少使用确认手段和提出更高级别的问题。由于察觉到在多轮规划和策略性思考方面存在根本缺陷，我们打造了一个逼真的模拟环境，融入源角色和说服性元素，以助力开发具有更长远回报的代理。我们的实验表明，源LLMs在信息共享方面虽能模仿人类行为，但采访者LLMs在识别问题何时得到回答以及进行有说服力的互动方面表现欠佳，致使不同模型规模和能力下的信息提取效果不理想。这些发现凸显了增强LLMs策略性对话能力的迫切需求。

> Large Language Models (LLMs) have demonstrated impressive capabilities in generating coherent text but often struggle with grounding language and strategic dialogue. To address this gap, we focus on journalistic interviews, a domain rich in grounding communication and abundant in data. We curate a dataset of 40,000 two-person informational interviews from NPR and CNN, and reveal that LLMs are significantly less likely than human interviewers to use acknowledgements and to pivot to higher-level questions. Realizing that a fundamental deficit exists in multi-turn planning and strategic thinking, we develop a realistic simulated environment, incorporating source personas and persuasive elements, in order to facilitate the development of agents with longer-horizon rewards. Our experiments show that while source LLMs mimic human behavior in information sharing, interviewer LLMs struggle with recognizing when questions are answered and engaging persuasively, leading to suboptimal information extraction across model size and capability. These findings underscore the need for enhancing LLMs' strategic dialogue capabilities.

[Arxiv](https://arxiv.org/abs/2411.13779)