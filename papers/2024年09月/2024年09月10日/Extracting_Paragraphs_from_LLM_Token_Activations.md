# 解析 LLM 令牌激活，提取段落信息

发布时间：2024年09月10日

`LLM理论` `人工智能`

> Extracting Paragraphs from LLM Token Activations

# 摘要

> 生成式 LLM 在 NLP 任务中表现卓越，但其内部机制仍待深入探索。本研究揭示了这些模型在段落开始时如何决定内容，通过分析 "\textbackslash n\textbackslash n" 双换行符 token 的激活信息，我们发现修补这些激活能有效传递后续段落的上下文信息，从而深入了解模型提前规划的能力。

> Generative large language models (LLMs) excel in natural language processing tasks, yet their inner workings remain underexplored beyond token-level predictions. This study investigates the degree to which these models decide the content of a paragraph at its onset, shedding light on their contextual understanding. By examining the information encoded in single-token activations, specifically the "\textbackslash n\textbackslash n" double newline token, we demonstrate that patching these activations can transfer significant information about the context of the following paragraph, providing further insights into the model's capacity to plan ahead.

[Arxiv](https://arxiv.org/abs/2409.06328)