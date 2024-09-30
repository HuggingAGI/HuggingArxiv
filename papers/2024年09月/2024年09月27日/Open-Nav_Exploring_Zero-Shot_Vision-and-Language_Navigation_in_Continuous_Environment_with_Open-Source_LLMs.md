# Open-Nav：在连续环境中，利用开源 LLM 探索零-shot 视觉与语言导航的新领域

发布时间：2024年09月27日

`Agent` `人工智能` `机器人`

> Open-Nav: Exploring Zero-Shot Vision-and-Language Navigation in Continuous Environment with Open-Source LLMs

# 摘要

> 视觉与语言导航 (VLN) 任务要求代理根据文本指令在 3D 环境中导航。传统方法依赖特定领域的数据集进行监督学习，而近期方法尝试利用 GPT-4 等闭源 LLM 以零-shot 方式解决 VLN 任务，但面临高昂的 token 成本和潜在的数据泄露风险。为此，我们提出了 Open-Nav，一项探索开源 LLM 在连续环境中进行零-shot VLN 的新研究。Open-Nav 通过时空链式思维 (CoT) 推理方法，将任务分解为指令理解、进度估计和决策制定，并结合细粒度的对象和空间知识增强场景感知，从而提升 LLM 的导航推理能力。实验结果显示，Open-Nav 在使用闭源 LLM 的情况下表现出色。

> Vision-and-Language Navigation (VLN) tasks require an agent to follow textual instructions to navigate through 3D environments. Traditional approaches use supervised learning methods, relying heavily on domain-specific datasets to train VLN models. Recent methods try to utilize closed-source large language models (LLMs) like GPT-4 to solve VLN tasks in zero-shot manners, but face challenges related to expensive token costs and potential data breaches in real-world applications. In this work, we introduce Open-Nav, a novel study that explores open-source LLMs for zero-shot VLN in the continuous environment. Open-Nav employs a spatial-temporal chain-of-thought (CoT) reasoning approach to break down tasks into instruction comprehension, progress estimation, and decision-making. It enhances scene perceptions with fine-grained object and spatial knowledge to improve LLM's reasoning in navigation. Our extensive experiments in both simulated and real-world environments demonstrate that Open-Nav achieves competitive performance compared to using closed-source LLMs.

[Arxiv](https://arxiv.org/abs/2409.18794)