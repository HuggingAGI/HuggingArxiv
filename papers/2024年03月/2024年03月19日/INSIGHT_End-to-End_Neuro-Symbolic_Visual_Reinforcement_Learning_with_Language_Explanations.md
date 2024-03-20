# 洞见：通过引入语言解释，实现从感知至决策的端到端神经符号视觉强化学习

发布时间：2024年03月19日

`Agent`

> INSIGHT: End-to-End Neuro-Symbolic Visual Reinforcement Learning with Language Explanations

> NS-RL作为一种有望实现可解释决策的新模式备受瞩目，其特点在于符号策略易于理解。然而，在处理涉及视觉观察的任务时，虽然NS-RL需构建结构化的状态表示，但之前的算法因效率低下而难以通过奖励信号优化这些结构化状态，同时，解读当前符号策略往往需要深厚的专业知识背景。本文介绍了一种创新框架，该框架可以高效地同步学习结构化状态与符号策略，其秘诀在于将视觉基础模型提炼至一个可扩展的感知模块以突破效率瓶颈。此外，我们设计了一套使用大型语言模型生成策略及决策简洁明了的语言解释的流水线。在对九个Atari任务进行的实验中，我们的方法相较于现有的NSRL方法展现出了显著的性能提升，并且我们还演示了对策略和决策的解释说明。

> Neuro-symbolic reinforcement learning (NS-RL) has emerged as a promising paradigm for explainable decision-making, characterized by the interpretability of symbolic policies. For tasks with visual observations, NS-RL entails structured representations for states, but previous algorithms are unable to refine the structured states with reward signals due to a lack of efficiency. Accessibility is also an issue, as extensive domain knowledge is required to interpret current symbolic policies. In this paper, we present a framework that is capable of learning structured states and symbolic policies simultaneously, whose key idea is to overcome the efficiency bottleneck by distilling vision foundation models into a scalable perception module. Moreover, we design a pipeline that uses large language models to generate concise and readable language explanations for policies and decisions. In experiments on nine Atari tasks, our approach demonstrates substantial performance gains over existing NSRL methods. We also showcase explanations for policies and decisions.

![洞见：通过引入语言解释，实现从感知至决策的端到端神经符号视觉强化学习](../../../paper_images/2403.12451/x1.png)

![洞见：通过引入语言解释，实现从感知至决策的端到端神经符号视觉强化学习](../../../paper_images/2403.12451/x2.png)

![洞见：通过引入语言解释，实现从感知至决策的端到端神经符号视觉强化学习](../../../paper_images/2403.12451/x3.png)

![洞见：通过引入语言解释，实现从感知至决策的端到端神经符号视觉强化学习](../../../paper_images/2403.12451/x4.png)

![洞见：通过引入语言解释，实现从感知至决策的端到端神经符号视觉强化学习](../../../paper_images/2403.12451/x5.png)

![洞见：通过引入语言解释，实现从感知至决策的端到端神经符号视觉强化学习](../../../paper_images/2403.12451/x6.png)

![洞见：通过引入语言解释，实现从感知至决策的端到端神经符号视觉强化学习](../../../paper_images/2403.12451/x7.png)

![洞见：通过引入语言解释，实现从感知至决策的端到端神经符号视觉强化学习](../../../paper_images/2403.12451/x8.png)

![洞见：通过引入语言解释，实现从感知至决策的端到端神经符号视觉强化学习](../../../paper_images/2403.12451/x9.png)

![洞见：通过引入语言解释，实现从感知至决策的端到端神经符号视觉强化学习](../../../paper_images/2403.12451/x10.png)

![洞见：通过引入语言解释，实现从感知至决策的端到端神经符号视觉强化学习](../../../paper_images/2403.12451/x11.png)

![洞见：通过引入语言解释，实现从感知至决策的端到端神经符号视觉强化学习](../../../paper_images/2403.12451/x12.png)

![洞见：通过引入语言解释，实现从感知至决策的端到端神经符号视觉强化学习](../../../paper_images/2403.12451/x13.png)

![洞见：通过引入语言解释，实现从感知至决策的端到端神经符号视觉强化学习](../../../paper_images/2403.12451/x14.png)

![洞见：通过引入语言解释，实现从感知至决策的端到端神经符号视觉强化学习](../../../paper_images/2403.12451/x15.png)

![洞见：通过引入语言解释，实现从感知至决策的端到端神经符号视觉强化学习](../../../paper_images/2403.12451/x16.png)

![洞见：通过引入语言解释，实现从感知至决策的端到端神经符号视觉强化学习](../../../paper_images/2403.12451/x17.png)

![洞见：通过引入语言解释，实现从感知至决策的端到端神经符号视觉强化学习](../../../paper_images/2403.12451/x18.png)

![洞见：通过引入语言解释，实现从感知至决策的端到端神经符号视觉强化学习](../../../paper_images/2403.12451/x19.png)

![洞见：通过引入语言解释，实现从感知至决策的端到端神经符号视觉强化学习](../../../paper_images/2403.12451/x20.png)

![洞见：通过引入语言解释，实现从感知至决策的端到端神经符号视觉强化学习](../../../paper_images/2403.12451/x21.png)

![洞见：通过引入语言解释，实现从感知至决策的端到端神经符号视觉强化学习](../../../paper_images/2403.12451/x22.png)

![洞见：通过引入语言解释，实现从感知至决策的端到端神经符号视觉强化学习](../../../paper_images/2403.12451/x23.png)

![洞见：通过引入语言解释，实现从感知至决策的端到端神经符号视觉强化学习](../../../paper_images/2403.12451/x24.png)

![洞见：通过引入语言解释，实现从感知至决策的端到端神经符号视觉强化学习](../../../paper_images/2403.12451/x25.png)

![洞见：通过引入语言解释，实现从感知至决策的端到端神经符号视觉强化学习](../../../paper_images/2403.12451/x26.png)

[Arxiv](https://arxiv.org/abs/2403.12451)