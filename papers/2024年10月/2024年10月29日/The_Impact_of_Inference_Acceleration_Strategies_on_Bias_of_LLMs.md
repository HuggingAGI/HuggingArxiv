# 推理加速策略对 LLMs 偏差所产生的影响

发布时间：2024年10月29日

`LLM应用` `语言模型` `推理加速`

> The Impact of Inference Acceleration Strategies on Bias of LLMs

# 摘要

> 过去几年，大型语言模型（LLMs）的能力取得了前所未有的进步，有望为众多应用领域带来巨大利好。但因其规模庞大，用 LLMs 进行推理成本高且速度慢。于是，近期众多研究提出了诸如量化、修剪和缓存等提升推理效率的策略。这些加速策略能大幅降低推理成本和延迟，同时在常见基准衡量的大部分预测性能上保持稳定。在本研究中，我们探讨了 LLM 性能的另一个关键方面：推理加速优化引发的模型生成中的人口统计学偏差。通过多种指标，我们从多个角度探究模型输出中的偏差。对推理加速前后的输出进行分析，发现偏差有显著变化。令人担忧的是，这些偏差效应复杂且难以预测。一种加速策略和偏差类型的组合在一个模型中可能偏差变化不大，但在另一个模型中可能影响巨大。我们的研究结果表明，在为加速推理而修改模型后，有必要对模型偏差进行深入且具体问题具体分析的评估。

> Last few years have seen unprecedented advances in capabilities of Large Language Models (LLMs). These advancements promise to deeply benefit a vast array of application domains. However, due to their immense size, performing inference with LLMs is both costly and slow. Consequently, a plethora of recent work has proposed strategies to enhance inference efficiency, e.g., quantization, pruning, and caching. These acceleration strategies reduce the inference cost and latency, often by several factors, while maintaining much of the predictive performance measured via common benchmarks. In this work, we explore another critical aspect of LLM performance: demographic bias in model generations due to inference acceleration optimizations. Using a wide range of metrics, we probe bias in model outputs from a number of angles. Analysis of outputs before and after inference acceleration shows significant change in bias. Worryingly, these bias effects are complex and unpredictable. A combination of an acceleration strategy and bias type may show little bias change in one model but may lead to a large effect in another. Our results highlight a need for in-depth and case-by-case evaluation of model bias after it has been modified to accelerate inference.

[Arxiv](https://arxiv.org/abs/2410.22118)