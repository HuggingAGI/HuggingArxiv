# 具有模拟器反馈的后验推理的流匹配

发布时间：2024年10月29日

`其他` `物理科学` `天文学`

> Flow Matching for Posterior Inference with Simulator Feedback

# 摘要

> 摘要：基于流的生成建模是解决物理科学中逆问题的强大工具，与传统方法相比，它可用于采样和似然评估，推理时间要低得多。我们提议基于模拟器用额外的控制信号来改进流。如果模拟器是可微的，控制信号可以包括梯度和特定问题的成本函数，或者它们可以完全从模拟器输出中学习。在我们提出的方法中，我们预训练流网络，并仅在微调时包含来自模拟器的反馈，因此只需要少量的额外参数和计算。我们在基于模拟推理的几个基准问题上说明了我们的设计选择，并针对建模强引力透镜系统（天文学中具有挑战性的逆问题）评估了具有模拟器反馈的流匹配与经典 MCMC 方法。我们证明，包含来自模拟器的反馈可将准确性提高 53％，使其与传统技术具有竞争力，同时推理速度快 67 倍。

> 
Abstract:Flow-based generative modeling is a powerful tool for solving inverse problems in physical sciences that can be used for sampling and likelihood evaluation with much lower inference times than traditional methods. We propose to refine flows with additional control signals based on a simulator. Control signals can include gradients and a problem-specific cost function if the simulator is differentiable, or they can be fully learned from the simulator output. In our proposed method, we pretrain the flow network and include feedback from the simulator exclusively for finetuning, therefore requiring only a small amount of additional parameters and compute. We motivate our design choices on several benchmark problems for simulation-based inference and evaluate flow matching with simulator feedback against classical MCMC methods for modeling strong gravitational lens systems, a challenging inverse problem in astronomy. We demonstrate that including feedback from the simulator improves the accuracy by $53\%$, making it competitive with traditional techniques while being up to $67$x faster for inference.
    

[Arxiv](https://arxiv.org/pdf/2410.22573)