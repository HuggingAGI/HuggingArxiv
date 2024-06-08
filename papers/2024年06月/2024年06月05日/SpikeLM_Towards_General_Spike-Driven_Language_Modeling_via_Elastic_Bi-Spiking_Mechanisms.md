# SpikeLM：借助弹性双脉冲机制，迈向通用脉冲驱动的语言建模新境界

发布时间：2024年06月05日

`LLM理论

理由：这篇论文探讨了脉冲神经网络（SNNs）在语言模型中的应用，特别是通过引入新的脉冲机制（SpikeLM）来提高语言任务的性能。这种研究不仅限于应用层面，而是深入到语言模型的理论基础，探索如何通过改进神经网络的结构和机制来提升性能。因此，它更符合LLM理论的分类，因为它涉及到对大型语言模型（LLM）工作原理的深入理解和创新。` `人工智能` `语言建模`

> SpikeLM: Towards General Spike-Driven Language Modeling via Elastic Bi-Spiking Mechanisms

# 摘要

> 受生物启发的脉冲神经网络（SNNs）因其生物合理性、事件驱动的稀疏性和二进制激活特性，成为实现人脑般能效的人工智能的有力候选。随着大规模语言模型展现出卓越的泛化能力，探索更通用的脉冲驱动模型变得尤为重要。然而，现有SNNs中的二进制脉冲在编码语义信息方面存在局限，对泛化能力构成挑战。本研究首次提出了适用于通用语言任务的全脉冲机制——SpikeLM，涵盖了判别性和生成性任务。与传统的{0,1}级脉冲不同，SpikeLM引入了双向、弹性幅度和弹性频率的脉冲编码，同时保留了SNNs的加法特性。通过在单个时间步长内增强脉冲的方向和幅度信息，并精心设计脉冲发放率控制策略，SpikeLM在处理通用语言任务时实现了前所未有的高准确性，显著缩小了SNNs与ANNs在语言建模上的性能差距。代码已公开于https://github.com/Xingrun-Xing/SpikeLM。

> Towards energy-efficient artificial intelligence similar to the human brain, the bio-inspired spiking neural networks (SNNs) have advantages of biological plausibility, event-driven sparsity, and binary activation. Recently, large-scale language models exhibit promising generalization capability, making it a valuable issue to explore more general spike-driven models. However, the binary spikes in existing SNNs fail to encode adequate semantic information, placing technological challenges for generalization. This work proposes the first fully spiking mechanism for general language tasks, including both discriminative and generative ones. Different from previous spikes with {0,1} levels, we propose a more general spike formulation with bi-directional, elastic amplitude, and elastic frequency encoding, while still maintaining the addition nature of SNNs. In a single time step, the spike is enhanced by direction and amplitude information; in spike frequency, a strategy to control spike firing rate is well designed. We plug this elastic bi-spiking mechanism in language modeling, named SpikeLM. It is the first time to handle general language tasks with fully spike-driven models, which achieve much higher accuracy than previously possible. SpikeLM also greatly bridges the performance gap between SNNs and ANNs in language modeling. Our code is available at https://github.com/Xingrun-Xing/SpikeLM.

![SpikeLM：借助弹性双脉冲机制，迈向通用脉冲驱动的语言建模新境界](../../../paper_images/2406.03287/x1.png)

![SpikeLM：借助弹性双脉冲机制，迈向通用脉冲驱动的语言建模新境界](../../../paper_images/2406.03287/x2.png)

![SpikeLM：借助弹性双脉冲机制，迈向通用脉冲驱动的语言建模新境界](../../../paper_images/2406.03287/x3.png)

![SpikeLM：借助弹性双脉冲机制，迈向通用脉冲驱动的语言建模新境界](../../../paper_images/2406.03287/f5.png)

![SpikeLM：借助弹性双脉冲机制，迈向通用脉冲驱动的语言建模新境界](../../../paper_images/2406.03287/x4.png)

![SpikeLM：借助弹性双脉冲机制，迈向通用脉冲驱动的语言建模新境界](../../../paper_images/2406.03287/x5.png)

![SpikeLM：借助弹性双脉冲机制，迈向通用脉冲驱动的语言建模新境界](../../../paper_images/2406.03287/x6.png)

![SpikeLM：借助弹性双脉冲机制，迈向通用脉冲驱动的语言建模新境界](../../../paper_images/2406.03287/x7.png)

[Arxiv](https://arxiv.org/abs/2406.03287)