# 异步 RLHF：用于语言模型的更快且更高效的离线策略强化学习

发布时间：2024年10月23日

`LLM应用` `人工智能`

> Asynchronous RLHF: Faster and More Efficient Off-Policy RL for Language Models

# 摘要

> 摘要：RLHF 的主导范式是在线和同策略 RL：从大型语言模型（LLM）策略同步生成，用奖励模型进行标注，并根据 LLM 自身的输出使用反馈进行学习。虽然有效，但这种范式在计算上效率低下。受经典深度 RL 文献的启发，我们提议在 RLHF 中分离生成和学习。这使得能够异步生成新样本，同时对旧样本进行训练，从而实现更快的训练和更优化的计算扩展。然而，异步训练依赖于一个未充分探索的机制，即在线但异策略 RLHF：在我们模型的先前迭代的样本上学习。为了理解这种机制中的挑战，我们研究了一个基本问题：为了加快学习速度但保持性能，我们可以容忍多少异策略性用于异步训练？在我们测试的几种 RLHF 算法中，我们发现在线 DPO 对异策略数据最稳健，并且稳健性随着策略模型的规模而增加。我们进一步研究了异步 RLHF 的计算优化，但发现它们会带来性能成本，从而产生权衡。最后，我们通过在指令跟随任务上训练 LLaMA 3.1 8B 比同步运行快 40％，同时匹配最终性能，验证了异步 RLHF 的可扩展性。

> 
Abstract:The dominant paradigm for RLHF is online and on-policy RL: synchronously generating from the large language model (LLM) policy, labelling with a reward model, and learning using feedback on the LLM's own outputs. While performant, this paradigm is computationally inefficient. Inspired by classical deep RL literature, we propose separating generation and learning in RLHF. This enables asynchronous generation of new samples while simultaneously training on old samples, leading to faster training and more compute-optimal scaling. However, asynchronous training relies on an underexplored regime, online but off-policy RLHF: learning on samples from previous iterations of our model. To understand the challenges in this regime, we investigate a fundamental question: how much off-policyness can we tolerate for asynchronous training to speed up learning but maintain performance? Among several RLHF algorithms we tested, we find that online DPO is most robust to off-policy data, and robustness increases with the scale of the policy model. We study further compute optimizations for asynchronous RLHF but find that they come at a performance cost, giving rise to a trade-off. Finally, we verify the scalability of asynchronous RLHF by training LLaMA 3.1 8B on an instruction-following task 40% faster than a synchronous run while matching final performance.
    

[Arxiv](https://arxiv.org/pdf/2410.18252)