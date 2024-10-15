# Ada-K 路由：为基于 MoE 的 LLM 注入高效动力

发布时间：2024年10月14日

`LLM理论` `人工智能` `机器学习`

> Ada-K Routing: Boosting the Efficiency of MoE-based LLMs

# 摘要

> 在 LLM 时代，MoE 架构通过动态调整专家数量，既节省计算成本又提升模型性能。我们提出的 Ada-K 路由策略，通过可学习的分配器模块，根据每个 token 的上下文需求灵活分配专家资源，显著优于传统的 Top-K 路由。实验表明，Ada-K 在减少计算量的同时，仍能提升模型表现，训练效率也极高。未来，Ada-K 将为自适应 MoE 系统设计提供新思路。

> In the era of Large Language Models (LLMs), Mixture-of-Experts (MoE) architectures offer a promising approach to managing computational costs while scaling up model parameters. Conventional MoE-based LLMs typically employ static Top-K routing, which activates a fixed and equal number of experts for each token regardless of their significance within the context. In this paper, we propose a novel Ada-K routing strategy that dynamically adjusts the number of activated experts for each token, thereby improving the balance between computational efficiency and model performance. Specifically, our strategy incorporates learnable and lightweight allocator modules that decide customized expert resource allocation tailored to the contextual needs for each token. These allocators are designed to be fully pluggable, making it broadly applicable across all mainstream MoE-based LLMs. We leverage the Proximal Policy Optimization (PPO) algorithm to facilitate an end-to-end learning process for this non-differentiable decision-making framework. Extensive evaluations on four popular baseline models demonstrate that our Ada-K routing method significantly outperforms conventional Top-K routing. Compared to Top-K, our method achieves over 25% reduction in FLOPs and more than 20% inference speedup while still improving performance across various benchmarks. Moreover, the training of Ada-K is highly efficient. Even for Mixtral-8x22B, a MoE-based LLM with more than 140B parameters, the training time is limited to 8 hours. Detailed analysis shows that harder tasks, middle layers, and content words tend to activate more experts, providing valuable insights for future adaptive MoE system designs. Both the training code and model checkpoints will be publicly available.

[Arxiv](https://arxiv.org/abs/2410.10456)