# PathInsight：针对组织病理学智能辅助诊断，优化多模态数据集与模型的指令调整

发布时间：2024年08月13日

`LLM应用` `人工智能`

> PathInsight: Instruction Tuning of Multimodal Datasets and Models for Intelligence Assisted Diagnosis in Histopathology

# 摘要

> 病理诊断作为肿瘤识别的金标准，多模态大型模型的出现简化了图像与文本的整合。然而，高昂的训练成本和数据集的稀缺，使得前沿技术与临床实践之间存在鸿沟。我们精心构建了一个包含约45,000病例的数据集，覆盖多种任务，如器官分类、病理报告生成等。通过微调LLaVA、Qwen-VL、InternLM等模型，我们提升了其在特定任务上的表现。评估表明，微调模型在处理病理问题时表现卓越。我们期待这些资源能为医学研究带来助益。

> Pathological diagnosis remains the definitive standard for identifying tumors. The rise of multimodal large models has simplified the process of integrating image analysis with textual descriptions. Despite this advancement, the substantial costs associated with training and deploying these complex multimodal models, together with a scarcity of high-quality training datasets, create a significant divide between cutting-edge technology and its application in the clinical setting. We had meticulously compiled a dataset of approximately 45,000 cases, covering over 6 different tasks, including the classification of organ tissues, generating pathology report descriptions, and addressing pathology-related questions and answers. We have fine-tuned multimodal large models, specifically LLaVA, Qwen-VL, InternLM, with this dataset to enhance instruction-based performance. We conducted a qualitative assessment of the capabilities of the base model and the fine-tuned model in performing image captioning and classification tasks on the specific dataset. The evaluation results demonstrate that the fine-tuned model exhibits proficiency in addressing typical pathological questions. We hope that by making both our models and datasets publicly available, they can be valuable to the medical and research communities.

[Arxiv](https://arxiv.org/abs/2408.07037)