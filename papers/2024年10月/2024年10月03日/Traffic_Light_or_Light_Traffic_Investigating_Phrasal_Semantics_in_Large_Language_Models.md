# 是“交通灯”还是“轻交通”？探讨大语言模型中的短语语义

发布时间：2024年10月03日

`LLM应用` `人工智能`

> Traffic Light or Light Traffic? Investigating Phrasal Semantics in Large Language Models

# 摘要

> 短语是人类表达语义的基本单位。本研究深入探讨了基于API的大型语言模型（LLM）对短语语义的理解能力，借助三个精心标注的数据集。我们不仅评估了LLM在自然语言指令引导下的短语语义推理任务中的表现，还探究了少样本演示和思维链推理等提示技术的影响。结果表明，LLM在各数据集上均大幅超越传统嵌入方法，但在微调方法面前并未展现出显著优势。高级提示策略的效果则呈现出多样性。通过详尽的错误分析，我们揭示了LLM在理解短语语义方面的局限。相关代码和数据已公开，详见https://github.com/memray/llm_phrase_semantics。

> Phrases are fundamental linguistic units through which humans convey semantics. This study critically examines the capacity of API-based large language models (LLMs) to comprehend phrase semantics, utilizing three human-annotated datasets. We assess the performance of LLMs in executing phrase semantic reasoning tasks guided by natural language instructions and explore the impact of common prompting techniques, including few-shot demonstrations and Chain-of-Thought reasoning. Our findings reveal that LLMs greatly outperform traditional embedding methods across the datasets; however, they do not show a significant advantage over fine-tuned methods. The effectiveness of advanced prompting strategies shows variability. We conduct detailed error analyses to interpret the limitations faced by LLMs in comprehending phrase semantics. Code and data can be found at https://github.com/memray/llm_phrase_semantics.

[Arxiv](https://arxiv.org/abs/2410.02308)