# BattleAgentBench：评估多智能体系统中语言模型合作与竞争能力的基准

发布时间：2024年08月28日

`Agent` `人工智能` `软件开发`

> BattleAgentBench: A Benchmark for Evaluating Cooperation and Competition Capabilities of Language Models in Multi-Agent Systems

# 摘要

> 随着大型语言模型 (LLM) 的能力日益增强，它们不仅能处理复杂任务，如构建单一代理和多代理系统，而且多代理系统对语言模型的协作能力提出了更高要求。尽管已有多种基准测试评估其协作能力，但缺乏细粒度评估，且忽视了多代理的协作与竞争场景。为此，我们推出了 BattleAgentBench 基准，通过定义三个难度级别的七个子阶段，细致评估语言模型在单一代理导航、配对代理任务执行及多代理协作竞争方面的能力。我们对多个领先模型进行了全面测试，发现基于 API 的模型在简单任务中表现优异，而开源小型模型则面临挑战。在需要高度协作与竞争的复杂任务中，基于 API 的模型虽显示出一定潜力，但提升空间巨大。

> Large Language Models (LLMs) are becoming increasingly powerful and capable of handling complex tasks, e.g., building single agents and multi-agent systems. Compared to single agents, multi-agent systems have higher requirements for the collaboration capabilities of language models. Many benchmarks are proposed to evaluate their collaborative abilities. However, these benchmarks lack fine-grained evaluations of LLM collaborative capabilities. Additionally, multi-agent collaborative and competitive scenarios are ignored in existing works. To address these two problems, we propose a benchmark, called BattleAgentBench, which defines seven sub-stages of three varying difficulty levels and conducts a fine-grained evaluation of language models in terms of single-agent scenario navigation capabilities, paired-agent task execution abilities, and multi-agent collaboration and competition capabilities. We conducted extensive evaluations on leading four closed-source and seven open-source models. Experimental results indicate that API-based models perform excellently on simple tasks but open-source small models struggle with simple tasks. Regarding difficult tasks that require collaborative and competitive abilities, although API-based models have demonstrated some collaborative capabilities, there is still enormous room for improvement.

[Arxiv](https://arxiv.org/abs/2408.15971)