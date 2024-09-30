# “为什么”在模型编辑中副作用最少

发布时间：2024年09月27日

`LLM理论` `人工智能` `机器学习`

> "Why" Has the Least Side Effect on Model Editing

# 摘要

> 训练 LLM 成本高昂，且需不断更新。模型编辑虽有潜力，但易生副作用。本文通过分类问题类型，揭示了不同问题导致的性能下降差异，为知识编辑实验设计提供新思路。同时，我们发现小型模型的经验未必适用于大型模型，且增加批次大小可缓解性能下降。

> Training large language models (LLMs) from scratch is an expensive endeavor, particularly as world knowledge continually evolves. To maintain relevance and accuracy of LLMs, model editing has emerged as a pivotal research area. While these methods hold promise, they can also produce unintended side effects. Their underlying factors and causes remain largely unexplored. This paper delves into a critical factor-question type-by categorizing model editing questions. Our findings reveal that the extent of performance degradation varies significantly across different question types, providing new insights for experimental design in knowledge editing. Furthermore, we investigate whether insights from smaller models can be extrapolated to larger models. Our results indicate discrepancies in findings between models of different sizes, suggesting that insights from smaller models may not necessarily apply to larger models. Additionally, we examine the impact of batch size on side effects, discovering that increasing the batch size can mitigate performance drops.

[Arxiv](https://arxiv.org/abs/2409.18679)