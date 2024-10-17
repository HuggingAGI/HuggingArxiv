# 探究合并大型语言模型的模型亲缘关系

发布时间：2024年10月16日

`LLM理论` `人工智能` `机器学习`

> Exploring Model Kinship for Merging Large Language Models

# 摘要

> 模型合并是提升 LLM 性能与效率的关键技术，但我们对合并模型的预期效果和原则知之甚少。本文提出“模型亲缘关系”概念，类比生物进化中的相似性，通过实证分析揭示其与合并后性能提升的关联，助力候选模型选择。基于此，我们创新提出“Top-k 贪心合并”策略，显著提升基准数据集表现。研究发现，模型亲缘关系不仅助益持续合并，还能规避进化中的性能退化。相关代码已公开，详见 https://github.com/zjunlp/ModelKinship。

> Model merging has become one of the key technologies for enhancing the capabilities and efficiency of Large Language Models (LLMs). However, our understanding of the expected performance gains and principles when merging any two models remains limited. In this work, we introduce model kinship, the degree of similarity or relatedness between LLMs, analogous to biological evolution. With comprehensive empirical analysis, we find that there is a certain relationship between model kinship and the performance gains after model merging, which can help guide our selection of candidate models. Inspired by this, we propose a new model merging strategy: Top-k Greedy Merging with Model Kinship, which can yield better performance on benchmark datasets. Specifically, we discover that using model kinship as a criterion can assist us in continuously performing model merging, alleviating the degradation (local optima) in model evolution, whereas model kinship can serve as a guide to escape these traps. Code is available at https://github.com/zjunlp/ModelKinship.

[Arxiv](https://arxiv.org/abs/2410.12613)