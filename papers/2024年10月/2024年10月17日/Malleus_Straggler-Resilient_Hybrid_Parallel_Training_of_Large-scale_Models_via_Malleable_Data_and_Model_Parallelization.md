# Malleus：通过灵活的数据和模型并行化，实现大规模模型的抗滞后混合并行训练

发布时间：2024年10月17日

`其他` `高性能计算` `云计算`

> Malleus: Straggler-Resilient Hybrid Parallel Training of Large-scale Models via Malleable Data and Model Parallelization

# 摘要

> 随着模型和数据规模的扩大，训练大型模型越来越依赖更多GPU，这增加了遇到性能滞后设备的可能性。混合并行训练虽是大型模型训练的常用方法，但对滞后者敏感。本文提出的Malleus框架，能在训练中细致捕捉每GPU的动态滞后问题。一旦发现GPU性能变化，Malleus通过创新算法实时调整并行策略，确保训练稳定。实验显示，Malleus在各种滞后情况下，效率提升2.63-5.28倍，优于现有框架。

> As the scale of models and training data continues to grow, there is an expanding reliance on more GPUs to train large-scale models, which inevitably increases the likelihood of encountering dynamic stragglers that some devices lag behind in performance occasionally. However, hybrid parallel training, one of the de facto paradigms to train large models, is typically sensitive to the stragglers.
  This paper presents Malleus, a straggler-resilient hybrid parallel training framework for large-scale models. Malleus captures the dynamic straggler issues at the nuanced, per-GPU granularity during training. Once a shift in the GPU ability is detected, Malleus adaptively adjusts the parallelization of GPU devices, pipeline stages, model layers, and training data through a novel planning algorithm, accommodating the dynamic stragglers in real time. In addition, Malleus seamlessly and efficiently migrates the model states to fulfill the adjusted parallelization plan on the fly, without sacrificing the stability of the training tasks. Empirical results on large language models with up to 110B parameters show that Malleus consistently outperforms existing parallel training frameworks under various straggler situations, delivering on average 2.63-5.28 times of efficiency improvement.

[Arxiv](https://arxiv.org/abs/2410.13333)