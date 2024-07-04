# MedVH：探索在医学领域中，如何系统评估大型视觉语言模型的幻觉问题。

发布时间：2024年07月02日

`LLM应用` `人工智能`

> MedVH: Towards Systematic Evaluation of Hallucination for Large Vision Language Models in the Medical Context

# 摘要

> 近期，大型视觉语言模型（LVLMs）在处理自然图像和文本数据的多项任务中表现卓越，引发了大量关于其微调和训练的研究。然而，针对较小数据集微调时，这些模型对幻觉的鲁棒性研究却相对匮乏。为此，我们推出了医学视觉幻觉测试（MedVH）这一新基准数据集，旨在评估特定领域LVLMs的幻觉现象。MedVH通过五个任务，全面考察医学背景下LVLMs对文本和视觉输入的理解及长文本响应生成能力。实验结果显示，尽管医学LVLMs在标准医学任务中表现优异，但其幻觉倾向尤为严重，甚至超过通用模型，这对其可靠性提出了严峻挑战。要使医学LVLMs在实际应用中发挥真正价值，不仅需精准融合医学知识，更需强化推理能力，以防幻觉产生。我们的研究为未来相关评估奠定了基础。

> Large Vision Language Models (LVLMs) have recently achieved superior performance in various tasks on natural image and text data, which inspires a large amount of studies for LVLMs fine-tuning and training. Despite their advancements, there has been scant research on the robustness of these models against hallucination when fine-tuned on smaller datasets. In this study, we introduce a new benchmark dataset, the Medical Visual Hallucination Test (MedVH), to evaluate the hallucination of domain-specific LVLMs. MedVH comprises five tasks to evaluate hallucinations in LVLMs within the medical context, which includes tasks for comprehensive understanding of textual and visual input, as well as long textual response generation. Our extensive experiments with both general and medical LVLMs reveal that, although medical LVLMs demonstrate promising performance on standard medical tasks, they are particularly susceptible to hallucinations, often more so than the general models, raising significant concerns about the reliability of these domain-specific models. For medical LVLMs to be truly valuable in real-world applications, they must not only accurately integrate medical knowledge but also maintain robust reasoning abilities to prevent hallucination. Our work paves the way for future evaluations of these studies.

![MedVH：探索在医学领域中，如何系统评估大型视觉语言模型的幻觉问题。](../../../paper_images/2407.02730/figure0_1.png)

![MedVH：探索在医学领域中，如何系统评估大型视觉语言模型的幻觉问题。](../../../paper_images/2407.02730/figure1_1.png)

![MedVH：探索在医学领域中，如何系统评估大型视觉语言模型的幻觉问题。](../../../paper_images/2407.02730/MC-all.png)

![MedVH：探索在医学领域中，如何系统评估大型视觉语言模型的幻觉问题。](../../../paper_images/2407.02730/temperature.png)

![MedVH：探索在医学领域中，如何系统评估大型视觉语言模型的幻觉问题。](../../../paper_images/2407.02730/prompt_var.png)

![MedVH：探索在医学领域中，如何系统评估大型视觉语言模型的幻觉问题。](../../../paper_images/2407.02730/prompt_FCJ.png)

![MedVH：探索在医学领域中，如何系统评估大型视觉语言模型的幻觉问题。](../../../paper_images/2407.02730/c_score.png)

![MedVH：探索在医学领域中，如何系统评估大型视觉语言模型的幻觉问题。](../../../paper_images/2407.02730/pie_wi.png)

![MedVH：探索在医学领域中，如何系统评估大型视觉语言模型的幻觉问题。](../../../paper_images/2407.02730/pie_nota.png)

![MedVH：探索在医学领域中，如何系统评估大型视觉语言模型的幻觉问题。](../../../paper_images/2407.02730/pie_cli.png)

![MedVH：探索在医学领域中，如何系统评估大型视觉语言模型的幻觉问题。](../../../paper_images/2407.02730/pie_fcj.png)

![MedVH：探索在医学领域中，如何系统评估大型视觉语言模型的幻觉问题。](../../../paper_images/2407.02730/Prompt.png)

[Arxiv](https://arxiv.org/abs/2407.02730)