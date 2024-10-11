# 奖励进步：扩展 LLM 推理的自动化验证器

发布时间：2024年10月10日

`LLM理论` `人工智能` `机器学习`

> Rewarding Progress: Scaling Automated Process Verifiers for LLM Reasoning

# 摘要

> 提升大型语言模型推理能力，过程奖励模型 (PRMs) 是个好办法。PRMs 在推理每一步都给反馈，比只在最后一步反馈的结果奖励模型 (ORMs) 更有效。但密集的人类标签收集不易，自动标记数据训练 PRMs 效果有限。我们探讨如何设计过程奖励，关键在于衡量每步进展，即采取步骤前后正确响应的可能性变化。这需在不同于基础策略的证明者策略下评估。理论分析显示，优化这些证明者的过程奖励能提升测试搜索和在线 RL 的探索效率。实验表明，弱证明者策略能大幅提升强基础策略。通过训练过程优势验证器 (PAVs) 预测进展，我们发现测试搜索准确率提升 $>8\%$，计算效率提升 $1.5-5\times$。在线 RL 使用 PAVs 密集奖励，样本效率提升 $5-6\times$，准确率提升 $>6\%$。

> A promising approach for improving reasoning in large language models is to use process reward models (PRMs). PRMs provide feedback at each step of a multi-step reasoning trace, potentially improving credit assignment over outcome reward models (ORMs) that only provide feedback at the final step. However, collecting dense, per-step human labels is not scalable, and training PRMs from automatically-labeled data has thus far led to limited gains. To improve a base policy by running search against a PRM or using it as dense rewards for reinforcement learning (RL), we ask: "How should we design process rewards?". Our key insight is that, to be effective, the process reward for a step should measure progress: a change in the likelihood of producing a correct response in the future, before and after taking the step, corresponding to the notion of step-level advantages in RL. Crucially, this progress should be measured under a prover policy distinct from the base policy. We theoretically characterize the set of good provers and our results show that optimizing process rewards from such provers improves exploration during test-time search and online RL. In fact, our characterization shows that weak prover policies can substantially improve a stronger base policy, which we also observe empirically. We validate our claims by training process advantage verifiers (PAVs) to predict progress under such provers, and show that compared to ORMs, test-time search against PAVs is $>8\%$ more accurate, and $1.5-5\times$ more compute-efficient. Online RL with dense rewards from PAVs enables one of the first results with $5-6\times$ gain in sample efficiency, and $>6\%$ gain in accuracy, over ORMs.

[Arxiv](https://arxiv.org/abs/2410.08146)