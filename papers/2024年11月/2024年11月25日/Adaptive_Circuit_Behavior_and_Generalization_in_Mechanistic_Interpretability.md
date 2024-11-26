# 关于自适应电路行为以及机械可解释性中的泛化

发布时间：2024年11月25日

`LLM理论` `神经网络`

> Adaptive Circuit Behavior and Generalization in Mechanistic Interpretability

# 摘要

> 机械可解释性旨在通过找出电路（即模型中实现执行特定任务算法的最小子图）来洞悉大型神经网络的内部运作机制。这些电路通常借助狭义定义的提示格式来发现和分析。然而，鉴于大型语言模型（LLMs）能在相同任务的各类提示格式中泛化，这些电路的泛化程度尚不明确。比如，不清楚模型泛化是源于重复使用相同电路组件、组件表现各异，还是使用了完全不同的组件。在本文中，我们探究了在 GPT-2 小模型中广受研究且被认为实现了简单可解释算法的间接对象识别（IOI）电路的通用性。我们评估了其在挑战该算法假设的提示变体上的表现。我们的发现显示，该电路的泛化能力超乎寻常地好，在仅添加额外输入边的情况下重复使用了所有组件和机制。尤为值得注意的是，该电路甚至在原本算法应失效的提示变体上也能泛化；我们发现了一种能解释此现象的机制，称之为 S2 黑客攻击。我们的发现表明，LLMs 内的电路可能比以往所认知的更具灵活性和通用性，突显了研究电路泛化以更好地理解这些模型更广泛能力的重要性。

> Mechanistic interpretability aims to understand the inner workings of large neural networks by identifying circuits, or minimal subgraphs within the model that implement algorithms responsible for performing specific tasks. These circuits are typically discovered and analyzed using a narrowly defined prompt format. However, given the abilities of large language models (LLMs) to generalize across various prompt formats for the same task, it remains unclear how well these circuits generalize. For instance, it is unclear whether the models generalization results from reusing the same circuit components, the components behaving differently, or the use of entirely different components. In this paper, we investigate the generality of the indirect object identification (IOI) circuit in GPT-2 small, which is well-studied and believed to implement a simple, interpretable algorithm. We evaluate its performance on prompt variants that challenge the assumptions of this algorithm. Our findings reveal that the circuit generalizes surprisingly well, reusing all of its components and mechanisms while only adding additional input edges. Notably, the circuit generalizes even to prompt variants where the original algorithm should fail; we discover a mechanism that explains this which we term S2 Hacking. Our findings indicate that circuits within LLMs may be more flexible and general than previously recognized, underscoring the importance of studying circuit generalization to better understand the broader capabilities of these models.

[Arxiv](https://arxiv.org/abs/2411.16105)