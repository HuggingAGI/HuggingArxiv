# 探索大型语言模型中思维理论的稳健性

发布时间：2024年10月08日

`LLM理论` `人工智能` `心理学`

> Probing the Robustness of Theory of Mind in Large Language Models

# 摘要

> 随着 ChatGPT 等大型语言模型的成功，科学界开始探讨这些模型是否具备类似人类的心智理论 (ToM) 能力。一方面，ToM 能力已在类似心理学的任务中得到验证 (Kosinski, 2023)；另一方面，任务稍作调整后，这些能力便不复存在 (Ullman, 2023)。为此，我们创建了一个包含 68 个任务的新数据集，涵盖 10 个复杂度类别，旨在深入探究 LLM 在 ToM 任务中的表现。我们评估了四个开源 LLM 在两个数据集上的 ToM 性能，发现总体准确率较低，表明 ToM 能力有限。简单任务中，各模型表现相近；但在涉及环境自动变化的任务中，即使明确告知，模型表现仍不佳。此外，替换介词改变对象关系的任务中，所有模型性能均下降，混合专家模型受影响最大。通过这一数据集，我们为提升 LLM 的 ToM 能力指明了研究方向。

> With the success of ChatGPT and other similarly sized SotA LLMs, claims of emergent human like social reasoning capabilities, especially Theory of Mind (ToM), in these models have appeared in the scientific literature. On the one hand those ToM-capabilities have been successfully tested using tasks styled similar to those used in psychology (Kosinski, 2023). On the other hand, follow up studies showed that those capabilities vanished when the tasks were slightly altered (Ullman, 2023). In this work we introduce a novel dataset of 68 tasks for probing ToM in LLMs, including potentially challenging variations which are assigned to 10 complexity classes. This way it is providing novel insights into the challenges LLMs face with those task variations. We evaluate the ToM performance of four SotA open source LLMs on our dataset and the dataset introduced by (Kosinski, 2023). The overall low goal accuracy across all evaluated models indicates only a limited degree of ToM capabilities. The LLMs' performance on simple complexity class tasks from both datasets are similar. Whereas we find a consistent tendency in all tested LLMs to perform poorly on tasks that require the realization that an agent has knowledge of automatic state changes in its environment, even when those are spelled out to the model. For task complications that change the relationship between objects by replacing prepositions, we notice a performance drop in all models, with the strongest impact on the mixture-of-experts model. With our dataset of tasks grouped by complexity we offer directions for further research on how to stabilize and advance ToM capabilities in LLM.

[Arxiv](https://arxiv.org/abs/2410.06271)