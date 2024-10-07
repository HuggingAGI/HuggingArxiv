# 从 Hopfieldian 视角解读思维链中的推理过程

发布时间：2024年10月04日

`LLM理论` `认知科学` `人工智能`

> Understanding Reasoning in Chain-of-Thought from the Hopfieldian View

# 摘要

> 大型语言模型在多任务中表现出色，尤其是 Chain-of-Thought (CoT) 提示技术，显著提升了推理能力。然而，现有研究多聚焦于性能提升，却忽视了 CoT 成功背后的根本原因。为此，我们基于认知神经科学的 Hopfieldian 认知观，提出新视角，揭示 CoT 推理与刺激、动作、神经群体及表示空间等关键认知元素的关联。我们视推理为这些空间间的移动，并据此开发了定位 CoT 推理错误的方法。此外，我们提出的 Representation-of-Thought (RoT) 框架，利用低维表示空间的鲁棒性，强化了 CoT 推理的稳健性。实验证明，RoT 不仅提升了 CoT 推理的鲁棒性和可解释性，还实现了对推理过程的精细调控。

> Large Language Models have demonstrated remarkable abilities across various tasks, with Chain-of-Thought (CoT) prompting emerging as a key technique to enhance reasoning capabilities. However, existing research primarily focuses on improving performance, lacking a comprehensive framework to explain and understand the fundamental factors behind CoT's success. To bridge this gap, we introduce a novel perspective grounded in the Hopfieldian view of cognition in cognitive neuroscience. We establish a connection between CoT reasoning and key cognitive elements such as stimuli, actions, neural populations, and representation spaces. From our view, we can understand the reasoning process as the movement between these representation spaces. Building on this insight, we develop a method for localizing reasoning errors in the response of CoTs. Moreover, we propose the Representation-of-Thought (RoT) framework, which leverages the robustness of low-dimensional representation spaces to enhance the robustness of the reasoning process in CoTs. Experimental results demonstrate that RoT improves the robustness and interpretability of CoT reasoning while offering fine-grained control over the reasoning process.

[Arxiv](https://arxiv.org/abs/2410.03595)