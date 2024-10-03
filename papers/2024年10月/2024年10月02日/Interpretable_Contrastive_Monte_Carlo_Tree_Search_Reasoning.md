# 可解释对比蒙特卡洛树搜索推理

发布时间：2024年10月02日

`LLM理论` `人工智能`

> Interpretable Contrastive Monte Carlo Tree Search Reasoning

# 摘要

> 我们推出了 SC-MCTS*，这是一种专为大型语言模型（LLM）设计的新型蒙特卡洛树搜索（MCTS）推理算法，不仅大幅提升了推理的准确性，还显著加快了速度。我们的创新灵感源自以下几点：首先，以往的 MCTS 在 LLM 推理中虽表现不俗，但其速度慢于 CoT 的缺点常被忽视；其次，先前的研究多将 MCTS 作为 LLM 推理的辅助工具，却缺乏对其组件的深入定量分析或消融研究；最后，尽管奖励模型在 MCTS 中至关重要，但相关研究却鲜少对其进行深入探讨或改进。为此，我们对 MCTS 的各个组件进行了详尽的消融研究和定量分析，揭示了它们对 LLM 推理性能的具体影响。基于这些发现，我们（i）设计了一款基于对比解码原则的高度可解释奖励模型，（ii）通过推测解码将每个节点的处理速度平均提升了 51.9%。此外，（iii）我们还优化了 UCT 节点选择策略和反向传播机制，进一步提升了整体性能。最终，在使用 Llama-3.1-70B 和 SC-MCTS* 的情况下，我们在 Blocksworld 多步推理数据集上平均超越了 o1-mini 17.4%。

> We propose SC-MCTS*: a novel Monte Carlo Tree Search (MCTS) reasoning algorithm for Large Language Models (LLMs), significantly improves both reasoning accuracy and speed. Our motivation comes from: 1. Previous MCTS LLM reasoning works often overlooked its biggest drawback--slower speed compared to CoT; 2. Previous research mainly used MCTS as a tool for LLM reasoning on various tasks with limited quantitative analysis or ablation studies of its components from reasoning interpretability perspective. 3. The reward model is the most crucial component in MCTS, however previous work has rarely conducted in-depth study or improvement of MCTS's reward models. Thus, we conducted extensive ablation studies and quantitative analysis on components of MCTS, revealing the impact of each component on the MCTS reasoning performance of LLMs. Building on this, (i) we designed a highly interpretable reward model based on the principle of contrastive decoding and (ii) achieved an average speed improvement of 51.9% per node using speculative decoding. Additionally, (iii) we improved UCT node selection strategy and backpropagation used in previous works, resulting in significant performance improvement. We outperformed o1-mini by an average of 17.4% on the Blocksworld multi-step reasoning dataset using Llama-3.1-70B with SC-MCTS*.

[Arxiv](https://arxiv.org/abs/2410.01707)