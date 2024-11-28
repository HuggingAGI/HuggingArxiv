# 用于零样本定制图像生成的扩散自蒸馏

发布时间：2024年11月27日

`LLM应用` `图像生成`

> Diffusion Self-Distillation for Zero-Shot Customized Image Generation

# 摘要

> 文本到图像的扩散模型成果斐然，但对于期望精细掌控的艺术家而言，却是令人懊恼的工具。比如，常见的应用场景是在新奇的情境中生成特定实例的图像，也就是“保持身份的生成”。此设定以及众多其他任务（如重新打光），与图像+文本条件生成模型十分契合。然而，直接训练这样的模型缺乏足够的高质量配对数据。我们提出了扩散自蒸馏法，这是一种利用预训练的文本到图像模型为文本条件的图像到图像任务生成自身数据集的方法。我们先是借助文本到图像扩散模型的上下文生成能力创建图像网格，并在视觉语言模型的协助下整理出一个大型配对数据集。接着，使用整理好的配对数据集将文本到图像模型微调为文本+图像到图像模型。我们表明，在一系列保持身份的生成任务中，扩散自蒸馏优于现有的零样本方法，且与每个实例的调优技术相比也不逊色，并且无需测试时优化。

> Text-to-image diffusion models produce impressive results but are frustrating tools for artists who desire fine-grained control. For example, a common use case is to create images of a specific instance in novel contexts, i.e., "identity-preserving generation". This setting, along with many other tasks (e.g., relighting), is a natural fit for image+text-conditional generative models. However, there is insufficient high-quality paired data to train such a model directly. We propose Diffusion Self-Distillation, a method for using a pre-trained text-to-image model to generate its own dataset for text-conditioned image-to-image tasks. We first leverage a text-to-image diffusion model's in-context generation ability to create grids of images and curate a large paired dataset with the help of a Visual-Language Model. We then fine-tune the text-to-image model into a text+image-to-image model using the curated paired dataset. We demonstrate that Diffusion Self-Distillation outperforms existing zero-shot methods and is competitive with per-instance tuning techniques on a wide range of identity-preservation generation tasks, without requiring test-time optimization.

[Arxiv](https://arxiv.org/abs/2411.18616)