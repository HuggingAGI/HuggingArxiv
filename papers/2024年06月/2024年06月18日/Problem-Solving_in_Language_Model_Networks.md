# 语言模型网络中的问题解决艺术

发布时间：2024年06月18日

`Agent

这篇论文主要探讨了多代理系统在大型语言模型（LLMs）中的应用，特别是在推理和问答能力方面的提升。研究者们通过扩展多代理辩论至不同的网络拓扑结构，并评估了这些结构对问答准确性、影响力、共识及偏见的影响。论文中提到的代理间的交互、共识与分歧、自我反思与互联性的平衡，以及偏见中心节点的作用，都是围绕代理系统的特性和优化进行的讨论。因此，这篇论文更适合归类于Agent分类，因为它主要关注的是代理系统的设计和优化，以及它们在增强LLMs性能中的作用。` `人工智能` `问答系统`

> Problem-Solving in Language Model Networks

# 摘要

> 为了增强大型语言模型（LLMs）的推理和问答能力，研究者们采用了多代理方法。虽然这些方法提升了性能，但集体智能在复杂网络结构和代理交互中的应用仍有待深入探索。本研究将多代理辩论扩展至更广泛的网络拓扑，并评估了问答准确性、影响力、共识及偏见的影响。研究发现，尽管令牌使用量较少，随机网络的表现与完全连接网络相当。代理间的强烈共识往往预示着正确答案，而分歧则通常指向错误答案。分析还揭示了自我反思与互联性之间的微妙平衡：自我反思在局部交互出错时发挥作用，而局部交互则在代理本身出错时提供帮助。此外，正确的偏见中心节点能显著提升系统性能。这些发现提示，通过在随机或幂律分布网络的中心位置部署知识丰富的代理，可以有效提升多代理系统的性能。

> To improve the reasoning and question-answering capabilities of Large Language Models (LLMs), several multi-agent approaches have been introduced. While these methods enhance performance, the application of collective intelligence-based approaches to complex network structures and the dynamics of agent interactions remain underexplored. This work extends the concept of multi-agent debate to more general network topologies, measuring the question-answering accuracy, influence, consensus, and the effects of bias on the collective. The results show that random networks perform similarly to fully connected networks despite using significantly fewer tokens. Furthermore, a strong consensus among agents in correlates with correct answers, whereas divided responses typically indicate incorrect answers. Analysing the influence of the agents reveals a balance between self-reflection and interconnectedness; self-reflection aids when local interactions are incorrect, and local interactions aid when the agent itself is incorrect. Additionally, bias plays a strong role in system performance with correctly biased hub nodes boosting performance. These insights suggest that using random networks or scale-free networks with knowledgeable agents placed in central positions can enhance the overall performance of multi-agent systems.

![语言模型网络中的问题解决艺术](../../../paper_images/2406.12374/architecture.png)

![语言模型网络中的问题解决艺术](../../../paper_images/2406.12374/question.png)

![语言模型网络中的问题解决艺术](../../../paper_images/2406.12374/follow_up.png)

![语言模型网络中的问题解决艺术](../../../paper_images/2406.12374/bias.png)

![语言模型网络中的问题解决艺术](../../../paper_images/2406.12374/sf_networks.png)

![语言模型网络中的问题解决艺术](../../../paper_images/2406.12374/random_networks.png)

![语言模型网络中的问题解决艺术](../../../paper_images/2406.12374/accuracy_vs_round_structure.png)

![语言模型网络中的问题解决艺术](../../../paper_images/2406.12374/accuracy_vs_round_bias.png)

![语言模型网络中的问题解决艺术](../../../paper_images/2406.12374/neighbours_accuracy.png)

![语言模型网络中的问题解决艺术](../../../paper_images/2406.12374/opinion_changes_fully_connected.png)

![语言模型网络中的问题解决艺术](../../../paper_images/2406.12374/opinion_changes_fully_disconnected.png)

![语言模型网络中的问题解决艺术](../../../paper_images/2406.12374/opinion_changes_scale_free_unbiased.png)

![语言模型网络中的问题解决艺术](../../../paper_images/2406.12374/opinion_changes_random.png)

![语言模型网络中的问题解决艺术](../../../paper_images/2406.12374/opinion_changes_scale_free_correct_hub.png)

![语言模型网络中的问题解决艺术](../../../paper_images/2406.12374/opinion_changes_scale_free_incorrect_hub.png)

![语言模型网络中的问题解决艺术](../../../paper_images/2406.12374/opinion_changes_scale_free_correct_edge.png)

![语言模型网络中的问题解决艺术](../../../paper_images/2406.12374/opinion_changes_scale_free_incorrect_edge.png)

![语言模型网络中的问题解决艺术](../../../paper_images/2406.12374/correct_prop_vs_network_type.png)

![语言模型网络中的问题解决艺术](../../../paper_images/2406.12374/simpson_fully_connected.png)

![语言模型网络中的问题解决艺术](../../../paper_images/2406.12374/simpson_fully_disconnected.png)

![语言模型网络中的问题解决艺术](../../../paper_images/2406.12374/simpson_scale_free_unbiased.png)

![语言模型网络中的问题解决艺术](../../../paper_images/2406.12374/simpson_random.png)

[Arxiv](https://arxiv.org/abs/2406.12374)