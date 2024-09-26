# 探索通用文本引导的图像合成技术，以实现定制化多模态脑部MRI的生成

发布时间：2024年09月25日

`LLM应用` `神经科学`

> Towards General Text-guided Image Synthesis for Customized Multimodal Brain MRI Generation

# 摘要

> 多模态脑磁共振成像在神经科学和神经病学中至关重要，但由于 MRI 扫描仪的普及度和采集时间较长，多模态 MR 图像并不常见。现有的 MR 图像合成方法通常针对特定任务在独立数据集上训练，导致在新数据集和任务中表现不佳。为此，我们推出了 TUMSyn，一个文本引导的通用 MR 图像合成模型，能够根据文本提示从常规扫描中生成所需的脑 MR 图像。为确保 TUMSyn 的合成精度、多功能性和通用性，我们构建了一个包含 31,407 个 3D 图像的脑 MR 数据库，涵盖 7 种 MRI 模态，来自 13 个中心。我们还预训练了一个 MRI 特定的文本编码器，通过对比学习有效控制图像合成。实验和医生评估表明，TUMSyn 在监督和零-shot 场景中均能生成具有指定元数据的临床有意义的 MR 图像。因此，TUMSyn 可与采集的 MR 扫描结合，助力大规模脑疾病筛查和诊断。

> Multimodal brain magnetic resonance (MR) imaging is indispensable in neuroscience and neurology. However, due to the accessibility of MRI scanners and their lengthy acquisition time, multimodal MR images are not commonly available. Current MR image synthesis approaches are typically trained on independent datasets for specific tasks, leading to suboptimal performance when applied to novel datasets and tasks. Here, we present TUMSyn, a Text-guided Universal MR image Synthesis generalist model, which can flexibly generate brain MR images with demanded imaging metadata from routinely acquired scans guided by text prompts. To ensure TUMSyn's image synthesis precision, versatility, and generalizability, we first construct a brain MR database comprising 31,407 3D images with 7 MRI modalities from 13 centers. We then pre-train an MRI-specific text encoder using contrastive learning to effectively control MR image synthesis based on text prompts. Extensive experiments on diverse datasets and physician assessments indicate that TUMSyn can generate clinically meaningful MR images with specified imaging metadata in supervised and zero-shot scenarios. Therefore, TUMSyn can be utilized along with acquired MR scan(s) to facilitate large-scale MRI-based screening and diagnosis of brain diseases.

[Arxiv](https://arxiv.org/abs/2409.16818)