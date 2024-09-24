# 大型语言模型中的知识规划：领域对齐咨询总结

发布时间：2024年09月23日

`LLM应用` `心理健康` `人工智能`

> Knowledge Planning in Large Language Models for Domain-Aligned Counseling Summarization

# 摘要

> 在心理健康咨询中，将对话精炼为简洁的总结（咨询笔记）至关重要。尽管大型语言模型（LLMs）在生成任务中表现出色，但在适应心理健康领域的复杂性方面仍面临挑战。与普通LLMs不同，心理健康专家在撰写总结时会先运用领域知识。我们通过引入新型规划引擎，增强了LLMs的这一能力，使其能更好地协调知识结构。为实现高阶规划，我们将知识封装分为两个阶段：保持对话结构和融入领域知识。在Llama-2上应用此引擎后，我们开发了名为PIECE的新框架。PIECE系统通过知识过滤与支架结合的方法，有效封装领域知识，并利用束卷积学习提升对对话结构的理解。与14种基线方法相比，PIECE在ROUGE和Bleurt评分上显著提升。专家评估也证实，其生成质量有时甚至超越了黄金标准。此外，PIECE在与Llama-2、Mistral和Zephyr的对比中，分别提升了2.72%、2.04%和1.59%，充分展示了规划引擎的广泛适用性。

> In mental health counseling, condensing dialogues into concise and relevant summaries (aka counseling notes) holds pivotal significance. Large Language Models (LLMs) exhibit remarkable capabilities in various generative tasks; however, their adaptation to domain-specific intricacies remains challenging, especially within mental health contexts. Unlike standard LLMs, mental health experts first plan to apply domain knowledge in writing summaries. Our work enhances LLMs' ability by introducing a novel planning engine to orchestrate structuring knowledge alignment. To achieve high-order planning, we divide knowledge encapsulation into two major phases: (i) holding dialogue structure and (ii) incorporating domain-specific knowledge. We employ a planning engine on Llama-2, resulting in a novel framework, PIECE. Our proposed system employs knowledge filtering-cum-scaffolding to encapsulate domain knowledge. Additionally, PIECE leverages sheaf convolution learning to enhance its understanding of the dialogue's structural nuances. We compare PIECE with 14 baseline methods and observe a significant improvement across ROUGE and Bleurt scores. Further, expert evaluation and analyses validate the generation quality to be effective, sometimes even surpassing the gold standard. We further benchmark PIECE with other LLMs and report improvement, including Llama-2 (+2.72%), Mistral (+2.04%), and Zephyr (+1.59%), to justify the generalizability of the planning engine.

[Arxiv](https://arxiv.org/abs/2409.14907)