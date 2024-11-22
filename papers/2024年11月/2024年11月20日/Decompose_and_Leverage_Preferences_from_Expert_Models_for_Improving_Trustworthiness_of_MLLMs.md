# 分解并借助专家模型的偏好来提升多语言大型语言模型（MLLMs）的可信度

发布时间：2024年11月20日

`LLM应用` `语言模型` `评估模型`

> Decompose and Leverage Preferences from Expert Models for Improving Trustworthiness of MLLMs

# 摘要

> 多模态大型语言模型（MLLMs）能够通过契合人类偏好来提升可信度。鉴于人类偏好标注颇为费力，近期的研究工作采用评估模型来评估 MLLMs 的响应，并利用基于模型的评估来自动构建偏好数据集。然而，此方法在应对 MLLMs 冗长且组合式的响应时面临挑战，这些响应往往需要多样的推理技能，单个评估模型可能无法完全具备。另外，多数现有方法依赖闭源模型作为评估器。为克服这些局限，我们提出了 DecompGen，这是一个可分解的框架，运用了一组开源专家模型。DecompGen 将每个响应拆解为原子验证任务，把每个任务分配给合适的专家模型以生成细粒度评估。DecompGen 的反馈被用于自动构建我们的偏好数据集 DGPref。通过偏好学习与 DGPref 契合的 MLLMs 在可信度上有了提升，彰显了 DecompGen 的有效性。

> Multimodal Large Language Models (MLLMs) can enhance trustworthiness by aligning with human preferences. As human preference labeling is laborious, recent works employ evaluation models for assessing MLLMs' responses, using the model-based assessments to automate preference dataset construction. This approach, however, faces challenges with MLLMs' lengthy and compositional responses, which often require diverse reasoning skills that a single evaluation model may not fully possess. Additionally, most existing methods rely on closed-source models as evaluators. To address limitations, we propose DecompGen, a decomposable framework that uses an ensemble of open-sourced expert models. DecompGen breaks down each response into atomic verification tasks, assigning each task to an appropriate expert model to generate fine-grained assessments. The DecompGen feedback is used to automatically construct our preference dataset, DGPref. MLLMs aligned with DGPref via preference learning show improvements in trustworthiness, demonstrating the effectiveness of DecompGen.

[Arxiv](https://arxiv.org/abs/2411.13697)