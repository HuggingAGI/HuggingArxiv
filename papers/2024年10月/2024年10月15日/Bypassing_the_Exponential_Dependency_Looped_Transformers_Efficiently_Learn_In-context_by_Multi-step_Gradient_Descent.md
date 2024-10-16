# 循环Transformer巧妙绕过指数依赖，通过多步梯度下降，高效掌握上下文学习。

发布时间：2024年10月15日

`LLM理论` `人工智能`

> Bypassing the Exponential Dependency: Looped Transformers Efficiently Learn In-context by Multi-step Gradient Descent

# 摘要

> In-context learning 是大型语言模型 (LLM) 成功的关键。它让模型在推理时从上下文示例中实时学习。先前研究表明，Transformer 架构能通过单次前向传递实现单步梯度下降。最近研究更进一步，显示循环 Transformer 能在前向传递中实现多步梯度下降。然而，理论结果需要指数数量的上下文示例才能达到低误差。本文研究了线性循环 Transformer 在向量生成任务上的 in-context learning，发现它能高效实现多步梯度下降。只要输入数据条件数恒定，线性循环 Transformer 就能通过多步梯度下降实现低误差。初步实验验证了理论分析。这些发现揭示了 Transformer 架构比之前理解的更强大的 in-context learning 能力，为 LLM 机制提供了新见解，并可能指导更高效的 LLM 推理算法设计。

> In-context learning has been recognized as a key factor in the success of Large Language Models (LLMs). It refers to the model's ability to learn patterns on the fly from provided in-context examples in the prompt during inference. Previous studies have demonstrated that the Transformer architecture used in LLMs can implement a single-step gradient descent update by processing in-context examples in a single forward pass. Recent work has further shown that, during in-context learning, a looped Transformer can implement multi-step gradient descent updates in forward passes. However, their theoretical results require an exponential number of in-context examples, $n = \exp(Ω(T))$, where $T$ is the number of loops or passes, to achieve a reasonably low error. In this paper, we study linear looped Transformers in-context learning on linear vector generation tasks. We show that linear looped Transformers can implement multi-step gradient descent efficiently for in-context learning. Our results demonstrate that as long as the input data has a constant condition number, e.g., $n = O(d)$, the linear looped Transformers can achieve a small error by multi-step gradient descent during in-context learning. Furthermore, our preliminary experiments validate our theoretical analysis. Our findings reveal that the Transformer architecture possesses a stronger in-context learning capability than previously understood, offering new insights into the mechanisms behind LLMs and potentially guiding the better design of efficient inference algorithms for LLMs.

[Arxiv](https://arxiv.org/abs/2410.11268)