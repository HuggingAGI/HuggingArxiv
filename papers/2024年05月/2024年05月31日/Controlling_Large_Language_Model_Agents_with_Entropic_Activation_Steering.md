# 通过熵激活引导驾驭大型语言模型代理

发布时间：2024年05月31日

`Agent

这篇论文主要探讨了大型语言模型（LLMs）作为情境学习代理的应用，特别是在有限的环境互动中形成实现目标的策略，并分析了LLM代理在决策过程中的过度自信问题。论文提出了一种新的方法——熵激活引导（EAST），以改善LLM代理的探索行为。因此，这篇论文更符合Agent分类，因为它专注于LLM在代理角色中的应用和改进。` `人工智能` `决策支持系统`

> Controlling Large Language Model Agents with Entropic Activation Steering

# 摘要

> 预训练的大型语言模型（LLMs）因其广泛适用性而备受关注，人们开始探索将其作为情境学习代理的可能性。这些代理需在有限的环境互动中形成实现目标的策略，但每一步的最佳行动选择仍充满不确定性。本文通过一系列受控的顺序决策实验，揭示了LLM代理如何基于信念行动。我们发现，LLM代理往往过于自信，仅凭有限信息便做出决策，导致探索不足。进一步分析表明，这种过度自信源于LLM动作分布熵的减少。我们指出，现有的token级采样技术无法有效促进探索。为此，我们提出了熵激活引导（EAST），一种针对LLM代理的新型激活引导方法。EAST通过计算熵加权的引导向量，在模型前向传播过程中调整激活，从而增加动作的熵，激发更多的探索行为。最终，EAST改变了LLM代理对决策不确定性的主观表达，为理解和调控LLM代理的不确定性提供了新途径。

> The generality of pretrained large language models (LLMs) has prompted increasing interest in their use as in-context learning agents. To be successful, such agents must form beliefs about how to achieve their goals based on limited interaction with their environment, resulting in uncertainty about the best action to take at each step. In this paper, we study how LLM agents form and act on these beliefs by conducting experiments in controlled sequential decision-making tasks. To begin, we find that LLM agents are overconfident: They draw strong conclusions about what to do based on insufficient evidence, resulting in inadequately explorative behavior. We dig deeper into this phenomenon and show how it emerges from a collapse in the entropy of the action distribution implied by sampling from the LLM. We then demonstrate that existing token-level sampling techniques are by themselves insufficient to make the agent explore more. Motivated by this fact, we introduce Entropic Activation Steering (EAST), an activation steering method for in-context LLM agents. EAST computes a steering vector as an entropy-weighted combination of representations, and uses it to manipulate an LLM agent's uncertainty over actions by intervening on its activations during the forward pass. We show that EAST can reliably increase the entropy in an LLM agent's actions, causing more explorative behavior to emerge. Finally, EAST modifies the subjective uncertainty an LLM agent expresses, paving the way to interpreting and controlling how LLM agents represent uncertainty about their decisions.

![通过熵激活引导驾驭大型语言模型代理](../../../paper_images/2406.00244/x1.png)

![通过熵激活引导驾驭大型语言模型代理](../../../paper_images/2406.00244/x2.png)

![通过熵激活引导驾驭大型语言模型代理](../../../paper_images/2406.00244/x3.png)

![通过熵激活引导驾驭大型语言模型代理](../../../paper_images/2406.00244/x4.png)

![通过熵激活引导驾驭大型语言模型代理](../../../paper_images/2406.00244/x5.png)

![通过熵激活引导驾驭大型语言模型代理](../../../paper_images/2406.00244/x6.png)

![通过熵激活引导驾驭大型语言模型代理](../../../paper_images/2406.00244/x7.png)

![通过熵激活引导驾驭大型语言模型代理](../../../paper_images/2406.00244/x8.png)

![通过熵激活引导驾驭大型语言模型代理](../../../paper_images/2406.00244/x9.png)

![通过熵激活引导驾驭大型语言模型代理](../../../paper_images/2406.00244/x10.png)

![通过熵激活引导驾驭大型语言模型代理](../../../paper_images/2406.00244/x11.png)

![通过熵激活引导驾驭大型语言模型代理](../../../paper_images/2406.00244/x12.png)

![通过熵激活引导驾驭大型语言模型代理](../../../paper_images/2406.00244/x13.png)

[Arxiv](https://arxiv.org/abs/2406.00244)