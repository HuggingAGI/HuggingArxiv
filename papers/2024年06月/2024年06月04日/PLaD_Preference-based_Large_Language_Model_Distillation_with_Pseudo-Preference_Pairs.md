# PLaD：利用伪偏好对进行基于偏好的大型语言模型蒸馏

发布时间：2024年06月04日

`LLM应用

这篇论文讨论了大型语言模型（LLMs）在资源有限环境中的应用限制，并提出了一种新的知识蒸馏（KD）框架——PLaD，以解决传统KD技术在LLMs上应用时遇到的问题。该框架通过生成偏好对来优化学生模型对输出质量的评估，而不是简单地模仿教师模型。这种方法不需要访问教师模型的内部状态，有效地解决了学生模型的表达限制和校准问题。因此，这篇论文属于LLM应用分类，因为它专注于改进和应用LLMs的技术，以适应资源受限的环境。`

> PLaD: Preference-based Large Language Model Distillation with Pseudo-Preference Pairs

# 摘要

> 大型语言模型（LLMs）虽在多任务中表现出色，但其庞大的参数规模限制了其在资源有限环境中的应用。知识蒸馏（KD）通过将大型模型的知识转移至小型模型，提供了解决方案。但传统KD技术在LLMs上应用时，面临输出访问受限、模型容量差距大及校准误差等挑战。为此，我们开发了PLaD，一种基于偏好的LLM蒸馏新框架。PLaD利用模型间容量差异，生成偏好对，优化学生模型对输出质量的评估，而非单纯模仿教师。此方法无需访问教师模型的内部状态，有效解决了学生模型的表达限制和校准问题。通过在多个序列生成任务上的实验，我们验证了PLaD框架的显著效果。

> Large Language Models (LLMs) have exhibited impressive capabilities in various tasks, yet their vast parameter sizes restrict their applicability in resource-constrained settings. Knowledge distillation (KD) offers a viable solution by transferring expertise from large teacher models to compact student models. However, traditional KD techniques face specific challenges when applied to LLMs, including restricted access to LLM outputs, significant teacher-student capacity gaps, and the inherited mis-calibration issue. In this work, we present PLaD, a novel preference-based LLM distillation framework. PLaD exploits the teacher-student capacity discrepancy to generate pseudo-preference pairs where teacher outputs are preferred over student outputs. Then, PLaD leverages a ranking loss to re-calibrate student's estimation of sequence likelihood, which steers the student's focus towards understanding the relative quality of outputs instead of simply imitating the teacher. PLaD bypasses the need for access to teacher LLM's internal states, tackles the student's expressivity limitations, and mitigates the student mis-calibration issue. Through extensive experiments on two sequence generation tasks and with various LLMs, we demonstrate the effectiveness of our proposed PLaD framework.

![PLaD：利用伪偏好对进行基于偏好的大型语言模型蒸馏](../../../paper_images/2406.02886/x1.png)

![PLaD：利用伪偏好对进行基于偏好的大型语言模型蒸馏](../../../paper_images/2406.02886/x2.png)

![PLaD：利用伪偏好对进行基于偏好的大型语言模型蒸馏](../../../paper_images/2406.02886/x3.png)

![PLaD：利用伪偏好对进行基于偏好的大型语言模型蒸馏](../../../paper_images/2406.02886/x4.png)

![PLaD：利用伪偏好对进行基于偏好的大型语言模型蒸馏](../../../paper_images/2406.02886/x5.png)

[Arxiv](https://arxiv.org/abs/2406.02886)