# MAGDA：多智能体指南驱动的诊断助手

发布时间：2024年09月10日

`Agent` `人工智能`

> MAGDA: Multi-agent guideline-driven diagnostic assistance

# 摘要

> 在急诊科、农村医院或欠发达地区的诊所，临床医生常常因缺乏快速影像分析而面临挑战，这可能影响患者的医疗质量。大型语言模型 (LLM) 通过提供决策支持，有望缓解这一问题。尽管 LLM 在医学考试中表现优异，但它们往往不遵循医学指南。为此，我们提出了一种新的零-shot 指南驱动决策支持方法。我们构建了一个由多个 LLM 代理组成的系统，这些代理通过对比视觉语言模型协作进行患者诊断。在提供简单诊断指南后，代理们综合提示并筛选图像，最终提供清晰的思维链推理，并自我完善以考虑疾病间的相互依赖。由于我们的方法是零-shot，因此特别适用于罕见疾病，即使训练数据有限，也能利用专家制作的疾病描述。我们在两个胸部 X 光数据集上进行了评估，结果显示性能优于现有零-shot 方法，并具备对罕见疾病的泛化能力。

> In emergency departments, rural hospitals, or clinics in less developed regions, clinicians often lack fast image analysis by trained radiologists, which can have a detrimental effect on patients' healthcare. Large Language Models (LLMs) have the potential to alleviate some pressure from these clinicians by providing insights that can help them in their decision-making. While these LLMs achieve high test results on medical exams showcasing their great theoretical medical knowledge, they tend not to follow medical guidelines. In this work, we introduce a new approach for zero-shot guideline-driven decision support. We model a system of multiple LLM agents augmented with a contrastive vision-language model that collaborate to reach a patient diagnosis. After providing the agents with simple diagnostic guidelines, they will synthesize prompts and screen the image for findings following these guidelines. Finally, they provide understandable chain-of-thought reasoning for their diagnosis, which is then self-refined to consider inter-dependencies between diseases. As our method is zero-shot, it is adaptable to settings with rare diseases, where training data is limited, but expert-crafted disease descriptions are available. We evaluate our method on two chest X-ray datasets, CheXpert and ChestX-ray 14 Longtail, showcasing performance improvement over existing zero-shot methods and generalizability to rare diseases.

[Arxiv](https://arxiv.org/abs/2409.06351)