# 大型语言模型在空间任务上的评估：一项涵盖多任务的基准研究

发布时间：2024年08月26日

`LLM应用` `空间任务` `人工智能`

> Evaluating Large Language Models on Spatial Tasks: A Multi-Task Benchmarking Study

# 摘要

> 随着ChatGPT、Gemini等大型语言模型的兴起，评估其在自然语言理解到代码生成等多方面能力的重要性日益凸显。然而，这些模型在空间任务上的表现尚未得到全面检验。本研究通过引入一个创新的多任务空间评估数据集，旨在系统地探索和比较多个先进模型在空间任务上的性能。该数据集涵盖十二种不同任务类型，包括空间理解和路径规划，每项任务均配有经过验证的准确答案。我们采用两阶段测试方法，评估了包括OpenAI的gpt-3.5-turbo、gpt-4o以及ZhipuAI的glm-4在内的多个模型。首先进行零-shot测试，随后根据难度对数据集进行分类并进行提示调优测试。结果表明，gpt-4o在第一阶段以71.3%的平均准确率领先。尽管moonshot-v1-8k总体表现稍逊，但在地名识别任务中表现更佳。此外，研究还揭示了提示策略对特定任务模型性能的显著影响。例如，思维链策略大幅提升了gpt-4o在路径规划任务中的准确率，而一次提示策略则显著提高了moonshot-v1-8k在地图任务中的表现。

> The advent of large language models such as ChatGPT, Gemini, and others has underscored the importance of evaluating their diverse capabilities, ranging from natural language understanding to code generation. However, their performance on spatial tasks has not been comprehensively assessed. This study addresses this gap by introducing a novel multi-task spatial evaluation dataset, designed to systematically explore and compare the performance of several advanced models on spatial tasks. The dataset encompasses twelve distinct task types, including spatial understanding and path planning, each with verified, accurate answers. We evaluated multiple models, including OpenAI's gpt-3.5-turbo, gpt-4o, and ZhipuAI's glm-4, through a two-phase testing approach. Initially, we conducted zero-shot testing, followed by categorizing the dataset by difficulty and performing prompt tuning tests. Results indicate that gpt-4o achieved the highest overall accuracy in the first phase, with an average of 71.3%. Although moonshot-v1-8k slightly underperformed overall, it surpassed gpt-4o in place name recognition tasks. The study also highlights the impact of prompt strategies on model performance in specific tasks. For example, the Chain-of-Thought (COT) strategy increased gpt-4o's accuracy in path planning from 12.4% to 87.5%, while a one-shot strategy enhanced moonshot-v1-8k's accuracy in mapping tasks from 10.1% to 76.3%.

[Arxiv](https://arxiv.org/abs/2408.14438)