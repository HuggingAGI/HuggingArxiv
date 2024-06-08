# PLaD：利用伪偏好对进行基于偏好的大型语言模型蒸馏

发布时间：2024年06月04日

`LLM应用

这篇论文摘要讨论了大型语言模型（LLMs）在资源有限环境中的应用限制，并提出了一种名为PLaD的知识蒸馏框架来解决这些问题。PLaD框架通过利用教师与学生模型的容量差异，生成偏好对，并通过排序损失重新校准学生模型，使其关注输出质量而非单纯模仿。这种方法无需访问教师模型的内部状态，有效解决了表达限制和校准问题。因此，这篇论文属于LLM应用分类，因为它专注于改进和应用LLMs的技术，以适应资源有限的环境。`

> PLaD: Preference-based Large Language Model Distillation with Pseudo-Preference Pairs

# 摘要

> 大型语言模型（LLMs）虽在多任务中表现出色，但其庞大的参数规模限制了其在资源有限环境中的应用。知识蒸馏（KD）技术提供了一种解决方案，通过将大型模型的知识转移至小型模型。然而，传统KD技术在处理LLMs时遇到挑战，如访问受限、容量差距大及校准误差。我们提出的PLaD框架，利用教师与学生模型的容量差异，生成偏好对，通过排序损失重新校准学生模型，使其关注输出质量而非单纯模仿。PLaD无需访问教师模型的内部状态，有效解决了表达限制和校准问题。实验证明，PLaD在序列生成任务中表现出色，适用于多种LLMs。

> Large Language Models (LLMs) have exhibited impressive capabilities in various tasks, yet their vast parameter sizes restrict their applicability in resource-constrained settings. Knowledge distillation (KD) offers a viable solution by transferring expertise from large teacher models to compact student models. However, traditional KD techniques face specific challenges when applied to LLMs, including restricted access to LLM outputs, significant teacher-student capacity gaps, and the inherited mis-calibration issue. In this work, we present PLaD, a novel preference-based LLM distillation framework. PLaD exploits the teacher-student capacity discrepancy to generate pseudo-preference pairs where teacher outputs are preferred over student outputs. Then, PLaD leverages a ranking loss to re-calibrate student's estimation of sequence likelihood, which steers the student's focus towards understanding the relative quality of outputs instead of simply imitating the teacher. PLaD bypasses the need for access to teacher LLM's internal states, tackles the student's expressivity limitations, and mitigates the student mis-calibration issue. Through extensive experiments on two sequence generation tasks and with various LLMs, we demonstrate the effectiveness of our proposed PLaD framework.

![PLaD：利用伪偏好对进行基于偏好的大型语言模型蒸馏](../../../paper_images/2406.02886/x1.png)

![PLaD：利用伪偏好对进行基于偏好的大型语言模型蒸馏](../../../paper_images/2406.02886/x2.png)

![PLaD：利用伪偏好对进行基于偏好的大型语言模型蒸馏](../../../paper_images/2406.02886/x3.png)

![PLaD：利用伪偏好对进行基于偏好的大型语言模型蒸馏](../../../paper_images/2406.02886/x4.png)

![PLaD：利用伪偏好对进行基于偏好的大型语言模型蒸馏](../../../paper_images/2406.02886/x5.png)

[Arxiv](https://arxiv.org/abs/2406.02886)