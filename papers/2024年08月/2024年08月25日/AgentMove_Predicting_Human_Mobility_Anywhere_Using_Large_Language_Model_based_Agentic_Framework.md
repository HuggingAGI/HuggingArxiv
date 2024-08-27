# AgentMove：借助大型语言模型的代理框架，精准预测全球人类流动性。

发布时间：2024年08月25日

`Agent` `城市规划`

> AgentMove: Predicting Human Mobility Anywhere Using Large Language Model based Agentic Framework

# 摘要

> 人类流动性预测在众多实际应用中至关重要。尽管深度学习模型在过去十年中表现出色，但其对大量私人数据和零-shot预测能力的依赖限制了进一步发展。近期，尝试将大型语言模型（LLMs）应用于移动预测，但由于缺乏系统的工作流程设计，性能受限。为此，我们提出了AgentMove框架，通过分解任务、设计模块（包括时空记忆、全球知识生成器和集体知识提取器）并结合推理步骤，实现全球城市的通用移动预测。实验表明，AgentMove在多个指标上优于现有最佳方法8%以上，且在不同LLMs基础上表现稳健，城市间地理偏见较小。详细代码和数据请访问：https://github.com/tsinghua-fib-lab/AgentMove。

> Human mobility prediction plays a crucial role in various real-world applications. Although deep learning based models have shown promising results over the past decade, their reliance on extensive private mobility data for training and their inability to perform zero-shot predictions, have hindered further advancements. Recently, attempts have been made to apply large language models (LLMs) to mobility prediction task. However, their performance has been constrained by the absence of a systematic design of workflow. They directly generate the final output using LLMs, which limits the potential of LLMs to uncover complex mobility patterns and underestimates their extensive reserve of global geospatial knowledge. In this paper, we introduce AgentMove, a systematic agentic prediction framework to achieve generalized mobility prediction for any cities worldwide. In AgentMove, we first decompose the mobility prediction task into three sub-tasks and then design corresponding modules to complete these subtasks, including spatial-temporal memory for individual mobility pattern mining, world knowledge generator for modeling the effects of urban structure and collective knowledge extractor for capturing the shared patterns among population. Finally, we combine the results of three modules and conduct a reasoning step to generate the final predictions. Extensive experiments on mobility data from two sources in 12 cities demonstrate that AgentMove outperforms the best baseline more than 8% in various metrics and it shows robust predictions with various LLMs as base and also less geographical bias across cities. Codes and data can be found in https://github.com/tsinghua-fib-lab/AgentMove.

[Arxiv](https://arxiv.org/abs/2408.13986)