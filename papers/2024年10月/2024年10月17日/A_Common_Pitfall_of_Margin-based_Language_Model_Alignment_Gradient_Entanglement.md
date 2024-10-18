# 语言模型对齐中的常见误区：边界依赖导致的梯度纠缠

发布时间：2024年10月17日

`LLM理论` `人工智能`

> A Common Pitfall of Margin-based Language Model Alignment: Gradient Entanglement

# 摘要

> 从人类反馈中进行强化学习 (RLHF) 已成为语言模型 (LM) 对齐的主流方法。其核心在于，RLHF 通过基于边际的损失进行偏好优化，仅依赖于偏好和非偏好响应之间的差异来定义理想行为。然而，我们发现基于边际的方法存在一个常见问题：对理想行为的单独指定不足。这导致了两个意外后果：(1) 非偏好（如不安全）响应的概率可能随边际增加而上升，引发安全对齐问题。(2) 即使响应理想，偏好响应的概率也可能下降。我们揭示了这一问题的根源：基于边际的损失将偏好与非偏好概率的变化紧密耦合，导致两者概率同步变化。我们将这种现象称为梯度纠缠。通过理论分析和实证验证，我们发现当偏好和非偏好对数概率梯度的内积较大时，梯度纠缠问题尤为严重。这一发现不仅解释了不同偏好优化算法的训练差异，还为改进基于边际方法、提升语言模型对齐效果提供了新的算法设计思路。

> Reinforcement Learning from Human Feedback (RLHF) has become the predominant approach for language model (LM) alignment. At its core, RLHF uses a margin-based loss for preference optimization, specifying ideal LM behavior only by the difference between preferred and dispreferred responses. In this paper, we identify a common pitfall of margin-based methods -- the under-specification of ideal LM behavior on preferred and dispreferred responses individually, which leads to two unintended consequences as the margin increases: (1) The probability of dispreferred (e.g., unsafe) responses may increase, resulting in potential safety alignment failures. (2) The probability of preferred responses may decrease, even when those responses are ideal. We demystify the reasons behind these problematic behaviors: margin-based losses couple the change in the preferred probability to the gradient of the dispreferred one, and vice versa, often preventing the preferred probability from increasing while the dispreferred one decreases, and thus causing a synchronized increase or decrease in both probabilities. We term this effect, inherent in margin-based objectives, gradient entanglement. Formally, we derive conditions for general margin-based alignment objectives under which gradient entanglement becomes concerning: the inner product of the gradients of preferred and dispreferred log-probabilities is large relative to the individual gradient norms. We theoretically investigate why such inner products can be large when aligning language models and empirically validate our findings. Empirical implications of our framework extend to explaining important differences in the training dynamics of various preference optimization algorithms, and suggesting potential algorithm designs to mitigate the under-specification issue of margin-based methods and thereby improving language model alignment.

[Arxiv](https://arxiv.org/abs/2410.13828)