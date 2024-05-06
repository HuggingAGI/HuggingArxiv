# 通过不确定性驱动的双层筛选机制，提升对大型语言模型调用的优化效果。

发布时间：2024年05月03日

`LLM应用` `机器学习`

> Optimising Calls to Large Language Models with Uncertainty-Based Two-Tier Selection

# 摘要

> 面临预算限制的研究人员和从业者在成本与性能之间做出艰难抉择。他们常常纠结于是选择性能更优的大型语言模型（LLM），还是成本更低的小型LLM。这一挑战催生了对LLM调用优化的新近研究。研究中提出了两种策略：一种是级联策略，顺序调用小型LLM或两者；另一种是路由策略，只选择一个模型进行调用。这两种策略都需要一个决策标准，通常由额外的神经网络模型来实现。在本研究中，我们提出了一种更简洁的方法：仅以小型LLM生成的不确定性作为决策依据。我们对比了这一方法与现有的级联和路由策略，并在九项不同任务上进行了测试，涵盖了三对预训练的小型和大型LLM。实验结果表明，我们的简化方案在27个实验设置中的25个中，以更优的成本效益比超越了现有方法。

> Researchers and practitioners operating on a limited budget face the cost-performance trade-off dilemma. The challenging decision often centers on whether to use a large LLM with better performance or a smaller one with reduced costs. This has motivated recent research in the optimisation of LLM calls. Either a cascading strategy is used, where a smaller LLM or both are called sequentially, or a routing strategy is used, where only one model is ever called. Both scenarios are dependent on a decision criterion which is typically implemented by an extra neural model. In this work, we propose a simpler solution; we use only the uncertainty of the generations of the small LLM as the decision criterion. We compare our approach with both cascading and routing strategies using three different pairs of pre-trained small and large LLMs, on nine different tasks and against approaches that require an additional neural model. Our experiments reveal this simple solution optimally balances cost and performance, outperforming existing methods on 25 out of 27 experimental setups.

[Arxiv](https://arxiv.org/abs/2405.02134)