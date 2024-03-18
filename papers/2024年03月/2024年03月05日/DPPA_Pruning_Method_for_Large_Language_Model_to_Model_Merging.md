# [DPPA：一种针对大型语言模型整合的高效剪枝技术，旨在优化模型合并过程。](https://arxiv.org/abs/2403.02799)

发布时间：2024年03月05日

`Agent`

> DPPA: Pruning Method for Large Language Model to Model Merging

> 模型融合致力于整合多领域微调模型，以提升模型跨域能力，关键挑战在于解决参数冲突问题。已有诸多研究在融合阶段对此进行优化，最新的研究更聚焦于通过剪枝阶段解决这一难题。DARE 方法在处理简单微调模型时展现出良好效果，但在处理与基准模型存在较大参数偏移的复杂微调模型时，效果有所下降。为此，本文提出了一种创新的双阶段方法——动态剪枝分区放大法（DPPA）。首阶段采用改良的动态剪枝技术（DP），在高剪枝率下增强模型性能；第二阶段引入动态分区放大策略（DPA），智能地按参数的重要性调整分区权重。实验中，我们的方法仅保留了20%的领域特有参数，却能匹敌那些保留高达90%参数的方法。更令人欣喜的是，经过剪枝后的模型性能跃升，使得模型融合性能提高了接近20%。目前，我们的代码已在 Github 开源。

> Model merging is to combine fine-tuned models derived from multiple domains, with the intent of enhancing the model's proficiency across various domains. The principal concern is the resolution of parameter conflicts. A substantial amount of existing research remedy this issue during the merging stage, with the latest study focusing on resolving this issue throughout the pruning stage. The DARE approach has exhibited promising outcomes when applied to a simplistic fine-tuned model. However, the efficacy of this method tends to wane when employed on complex fine-tuned models that show a significant parameter bias relative to the baseline model. In this paper, we introduce a dual-stage method termed Dynamic Pruning Partition Amplification (DPPA), devised to tackle the challenge of merging complex fine-tuned models. Initially, we introduce Dynamically Pruning (DP), an improved approach based on magnitude pruning, which aim is to enhance performance at higher pruning rates. Subsequently, we propose Dynamically Partition Amplification (DPA), a rescaling strategy, is designed to dynamically amplify parameter partitions in relation to their significance levels. The experimental results show that our method maintains a mere 20% of domain-specific parameters and yet delivers a performance comparable to other methodologies that preserve up to 90% of parameters. Furthermore, our method displays outstanding performance post-pruning, leading to a significant improvement of nearly 20% performance in model merging. We make our code on Github.

[Arxiv](https://arxiv.org/abs/2403.02799)