# MemBench：迈向真实世界中内存增强对话系统的评估

发布时间：2024年09月23日

`Agent` `人工智能` `对话系统`

> MemBench: Towards Real-world Evaluation of Memory-Augmented Dialogue Systems

# 摘要

> 长期记忆对聊天机器人和对话系统至关重要，但现有评估方法与人类对话实际情况脱节。它们仅关注事实信息准确性或生成响应的困惑度，忽视了人类记忆召回的多样性，如情感和环境。为此，我们基于认知科学和心理学理论，构建了涵盖多种记忆召回范式的Memory Benchmark（MemBench），包含记忆检索、识别和注入两阶段任务。该基准首次综合考虑了被动和主动记忆召回，并提出新评分标准全面评估生成响应。实验显示，现有对话系统仍有很大提升空间，且记忆注入与情感支持技能和亲密度密切相关。我们将发布代码和数据集。

> Long-term memory is so important for chatbots and dialogue systems (DS) that researchers have developed numerous memory-augmented DS. However, their evaluation methods are different from the real situation in human conversation. They only measured the accuracy of factual information or the perplexity of generated responses given a query, which hardly reflected their performance. Moreover, they only consider passive memory retrieval based on similarity, neglecting diverse memory-recalling paradigms in humans, e.g. emotions and surroundings. To bridge the gap, we construct a novel benchmark covering various memory recalling paradigms based on cognitive science and psychology theory. The Memory Benchmark (MemBench) contains two tasks according to the two-phrase theory in cognitive science: memory retrieval, memory recognition and injection. The benchmark considers both passive and proactive memory recalling based on meta information for the first time. In addition, novel scoring aspects are proposed to comprehensively measure the generated responses. Results from the strongest embedding models and LLMs on MemBench show that there is plenty of room for improvement in existing dialogue systems. Extensive experiments also reveal the correlation between memory injection and emotion supporting (ES) skillfulness, and intimacy. Our code and dataset will be released.

[Arxiv](https://arxiv.org/abs/2409.15240)