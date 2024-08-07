# 大型模型的多任务与多模态神经调谐

发布时间：2024年08月06日

`LLM应用` `人工智能` `计算机视觉`

> Multitask and Multimodal Neural Tuning for Large Models

# 摘要

> 近年来，大规模多模态模型在多个领域展现了卓越能力，但如何让这些模型同时高效执行多项多模态任务仍是一大挑战。为此，我们提出了一种创新的调谐方法——神经调谐，它能同时应对推理分割、指涉分割、图像描述和文本到图像生成等多种任务。神经调谐模仿人脑的稀疏分布式表示，仅激活特定神经元子集以适应不同任务。我们还推出了新基准MMUD，每样本附带多任务标签。应用神经调谐于MMUD上的预训练模型，我们实现了任务处理的简便与高效。相关模型、代码及数据集将在发表后公开，助力该领域研究与发展。

> In recent years, large-scale multimodal models have demonstrated impressive capabilities across various domains. However, enabling these models to effectively perform multiple multimodal tasks simultaneously remains a significant challenge. To address this, we introduce a novel tuning method called neural tuning, designed to handle diverse multimodal tasks concurrently, including reasoning segmentation, referring segmentation, image captioning, and text-to-image generation. Neural tuning emulates sparse distributed representation in human brain, where only specific subsets of neurons are activated for each task. Additionally, we present a new benchmark, MMUD, where each sample is annotated with multiple task labels. By applying neural tuning to pretrained large models on the MMUD benchmark, we achieve simultaneous task handling in a streamlined and efficient manner. All models, code, and datasets will be publicly available after publication, facilitating further research and development in this field.

![大型模型的多任务与多模态神经调谐](../../../paper_images/2408.03001/x1.png)

![大型模型的多任务与多模态神经调谐](../../../paper_images/2408.03001/x2.png)

![大型模型的多任务与多模态神经调谐](../../../paper_images/2408.03001/x3.png)

![大型模型的多任务与多模态神经调谐](../../../paper_images/2408.03001/x4.png)

![大型模型的多任务与多模态神经调谐](../../../paper_images/2408.03001/x5.png)

[Arxiv](https://arxiv.org/abs/2408.03001)