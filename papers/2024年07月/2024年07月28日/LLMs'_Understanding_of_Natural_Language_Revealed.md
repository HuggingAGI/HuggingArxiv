# 大型语言模型对自然语言的理解得以展现

发布时间：2024年07月28日

`LLM理论` `人工智能`

> LLMs' Understanding of Natural Language Revealed

# 摘要

> 大型语言模型（LLM）是基于海量数据的自底向上逆向工程的成果。尽管在众多NLP下游任务中表现出色，但研究显示，LLM在涉及符号变量量化与操作的推理任务（如规划和问题解决）中表现不佳。本文将聚焦于测试LLM的语言理解能力，这一领域常被夸大。虽然LLM能生成类人连贯文本，但其语言理解力未获充分验证。我们提出，应通过反向操作——输入文本片段并查询其“理解”内容——来测试其理解力。实践表明，LLM的理解仅停留在表面，实质上依赖于对大量文本的记忆。

> Large language models (LLMs) are the result of a massive experiment in bottom-up, data-driven reverse engineering of language at scale. Despite their utility in a number of downstream NLP tasks, ample research has shown that LLMs are incapable of performing reasoning in tasks that require quantification over and the manipulation of symbolic variables (e.g., planning and problem solving); see for example [25][26]. In this document, however, we will focus on testing LLMs for their language understanding capabilities, their supposed forte. As we will show here, the language understanding capabilities of LLMs have been widely exaggerated. While LLMs have proven to generate human-like coherent language (since that's how they were designed), their language understanding capabilities have not been properly tested. In particular, we believe that the language understanding capabilities of LLMs should be tested by performing an operation that is the opposite of 'text generation' and specifically by giving the LLM snippets of text as input and then querying what the LLM "understood". As we show here, when doing so it will become apparent that LLMs do not truly understand language, beyond very superficial inferences that are essentially the byproduct of the memorization of massive amounts of ingested text.

[Arxiv](https://arxiv.org/abs/2407.19630)