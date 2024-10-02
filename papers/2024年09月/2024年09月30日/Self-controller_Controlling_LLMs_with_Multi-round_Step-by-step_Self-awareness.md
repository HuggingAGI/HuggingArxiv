# 自我控制器：借助多轮逐步自我意识，驾驭大型语言模型

发布时间：2024年09月30日

`LLM应用` `人工智能`

> Self-controller: Controlling LLMs with Multi-round Step-by-step Self-awareness

# 摘要

> 大型语言模型 (LLM) 的应用已遍布各领域，但其基本能力如可控性仍有限。为此，我们提出“自我控制器”，一种将自我意识融入 LLM 推理逻辑的新框架。核心在于基于 LLM 响应维持状态，使其自我感知当前状态，并在多轮思维链中逐步推理。实验表明，自我控制器在文本长度上的可控性和有效性。我们还实现了二分搜索算法，基于文本长度的线性和单调性加速生成过程。结合深度求索的上下文缓存技术，当对话共享相同前缀时，显著节省计算资源。理论上，额外时间复杂度为 $O(c \log n)$。粗略估计显示，我们的方法令牌消耗不超过单轮生成的两倍。消融研究进一步证明，自我控制器在所有基础模型中保持一致可控性。

> The applications of large language models (LLMs) have been widely spread across all domains. However, the basic abilities such as the controllability of LLMs are still limited. To address this, we propose "Self-controller", a novel agentic framework bringing self-awareness into LLMs' reasoning logic. The core idea of this work is to maintain states based on the LLM's response, letting the LLM become self-aware of current status and think step by step in a multi-round chain-of-thought paradigm. Our experiment on the state of textual length has shown the controllability and effectiveness of the Self-controller. We further implement a binary search algorithm to accelerate the generation process based on the linearity and monotonicity of the textual length state. Another advantage of the Self-controller comes with DeepSeek's Context Caching technology, which significantly saves computational token consumption when a cluster of conversations shares the same prefix of context. Theoretically, we prove that in this scenario the extra time complexity is $O(c \log n)$. Results of the back-of-the-envelope estimation suggest that the token consumption of our method is no more than twice as much as that of the trivial single-round generation. Furthermore, our ablation study on word constraints demonstrates the Self-controller's consistent controllability across all foundation models.

[Arxiv](https://arxiv.org/abs/2410.00359)