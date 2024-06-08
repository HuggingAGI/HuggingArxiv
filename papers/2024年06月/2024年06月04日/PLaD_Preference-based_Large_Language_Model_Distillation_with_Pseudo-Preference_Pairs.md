# 偏好导向的大型语言模型蒸馏：利用伪偏好对进行优化

发布时间：2024年06月04日

`LLM应用

这篇论文主要讨论了大型语言模型（LLMs）在资源有限环境中的应用限制，并提出了一种名为PLaD的知识蒸馏框架来解决这些问题。论文通过开发一种基于偏好的蒸馏方法，解决了传统KD技术在处理LLMs时遇到的挑战，如难以获取LLM输出、教师与学生模型间的巨大容量差异以及校准误差问题。因此，这篇论文更符合LLM应用分类，因为它关注的是如何应用技术来优化和改进LLMs的实际应用。` `人工智能` `模型优化`

> PLaD: Preference-based Large Language Model Distillation with Pseudo-Preference Pairs

# 摘要

> 大型语言模型（LLMs）虽在多任务中表现出色，但其庞大的参数规模限制了其在资源有限环境中的应用。知识蒸馏（KD）技术提供了一种解决方案，通过将大型教师模型的知识传递给更紧凑的学生模型。然而，传统KD技术在处理LLMs时面临挑战，如难以获取LLM输出、教师与学生模型间的巨大容量差异以及校准误差问题。为此，我们开发了PLaD框架，一种基于偏好的LLM蒸馏方法。PLaD通过利用教师与学生间的容量差异，生成教师输出优于学生的伪偏好对，并使用排序损失调整学生对序列可能性的评估，使其关注输出质量而非单纯模仿教师。PLaD无需访问教师模型的内部状态，有效解决了学生模型的表达限制和校准问题。通过在多个序列生成任务和不同LLMs上的实验，我们验证了PLaD框架的有效性。

> Large Language Models (LLMs) have exhibited impressive capabilities in various tasks, yet their vast parameter sizes restrict their applicability in resource-constrained settings. Knowledge distillation (KD) offers a viable solution by transferring expertise from large teacher models to compact student models. However, traditional KD techniques face specific challenges when applied to LLMs, including restricted access to LLM outputs, significant teacher-student capacity gaps, and the inherited mis-calibration issue. In this work, we present PLaD, a novel preference-based LLM distillation framework. PLaD exploits the teacher-student capacity discrepancy to generate pseudo-preference pairs where teacher outputs are preferred over student outputs. Then, PLaD leverages a ranking loss to re-calibrate student's estimation of sequence likelihood, which steers the student's focus towards understanding the relative quality of outputs instead of simply imitating the teacher. PLaD bypasses the need for access to teacher LLM's internal states, tackles the student's expressivity limitations, and mitigates the student mis-calibration issue. Through extensive experiments on two sequence generation tasks and with various LLMs, we demonstrate the effectiveness of our proposed PLaD framework.

![偏好导向的大型语言模型蒸馏：利用伪偏好对进行优化](../../../paper_images/2406.02886/x1.png)

![偏好导向的大型语言模型蒸馏：利用伪偏好对进行优化](../../../paper_images/2406.02886/x2.png)

![偏好导向的大型语言模型蒸馏：利用伪偏好对进行优化](../../../paper_images/2406.02886/x3.png)

![偏好导向的大型语言模型蒸馏：利用伪偏好对进行优化](../../../paper_images/2406.02886/x4.png)

![偏好导向的大型语言模型蒸馏：利用伪偏好对进行优化](../../../paper_images/2406.02886/x5.png)

[Arxiv](https://arxiv.org/abs/2406.02886)