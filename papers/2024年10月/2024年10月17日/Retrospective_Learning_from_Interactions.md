# 从过往互动中汲取经验

发布时间：2024年10月17日

`LLM应用` `人工智能`

> Retrospective Learning from Interactions

# 摘要

> 在 LLM 与用户的互动中，隐含的反馈信号自然存在。当 LLM 对指令反应异常时，用户可能会通过调整请求、表达不满或切换任务来传达信息。这些信号独立于具体任务，且语言形式相对固定，使 LLM 即使在任务失败时也能识别。这为无额外标注的持续学习开辟了道路。我们提出了 ReSpect 方法，通过回顾过往互动中的信号进行学习。在多模态交互场景中，人类指导 LLM 解决复杂推理任务，ReSpect 通过数千次互动，将任务完成率从 31% 提升至 82%，全程无需外部标注。

> Multi-turn interactions between large language models (LLMs) and users naturally include implicit feedback signals. If an LLM responds in an unexpected way to an instruction, the user is likely to signal it by rephrasing the request, expressing frustration, or pivoting to an alternative task. Such signals are task-independent and occupy a relatively constrained subspace of language, allowing the LLM to identify them even if it fails on the actual task. This creates an avenue for continually learning from interactions without additional annotations. We introduce ReSpect, a method to learn from such signals in past interactions via retrospection. We deploy ReSpect in a new multimodal interaction scenario, where humans instruct an LLM to solve an abstract reasoning task with a combinatorial solution space. Through thousands of interactions with humans, we show how ReSpect gradually improves task completion rate from 31% to 82%, all without any external annotation.

[Arxiv](https://arxiv.org/abs/2410.13852)