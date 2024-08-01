# Maverick：突破近期趋势，实现高效准确的共指消解

发布时间：2024年07月31日

`LLM应用` `学术研究`

> Maverick: Efficient and Accurate Coreference Resolution Defying Recent Trends

# 摘要

> 自回归生成模型已成为NLP领域的翘楚，但追求卓越有时导致任务特定方法的过早替代。在指代消解任务中，最新方案均采用大型自回归模型，超越了传统编码器系统。我们推出的Maverick，虽设计简洁，却能在学术预算内运行顶尖的指代消解系统，以5亿参数之姿，超越了130亿参数的巨型模型。Maverick在CoNLL-2012测试中表现卓越，训练内存需求仅为前代的0.006倍，推理速度飙升170倍。通过多样实验，我们验证了Maverick在数据稀缺、长文档及域外环境中的稳健性，并已在GitHub上公开代码与模型，供研究之用。

> Large autoregressive generative models have emerged as the cornerstone for achieving the highest performance across several Natural Language Processing tasks. However, the urge to attain superior results has, at times, led to the premature replacement of carefully designed task-specific approaches without exhaustive experimentation. The Coreference Resolution task is no exception; all recent state-of-the-art solutions adopt large generative autoregressive models that outperform encoder-based discriminative systems. In this work,we challenge this recent trend by introducing Maverick, a carefully designed - yet simple - pipeline, which enables running a state-of-the-art Coreference Resolution system within the constraints of an academic budget, outperforming models with up to 13 billion parameters with as few as 500 million parameters. Maverick achieves state-of-the-art performance on the CoNLL-2012 benchmark, training with up to 0.006x the memory resources and obtaining a 170x faster inference compared to previous state-of-the-art systems. We extensively validate the robustness of the Maverick framework with an array of diverse experiments, reporting improvements over prior systems in data-scarce, long-document, and out-of-domain settings. We release our code and models for research purposes at https://github.com/SapienzaNLP/maverick-coref.

[Arxiv](https://arxiv.org/abs/2407.21489)