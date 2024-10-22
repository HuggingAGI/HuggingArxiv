# 单图零-shot场景重建，借助深度先验的巧妙组合

发布时间：2024年10月21日

`LLM应用` `计算机视觉` `人工智能`

> Zero-Shot Scene Reconstruction from Single Images with Deep Prior Assembly

# 摘要

> 大型语言和视觉模型正在革新视觉计算领域。通过大幅扩展数据和模型参数，这些模型学习到强大的深度先验知识，从而在多种任务中表现出色。我们提出了深度先验组合框架，该框架以零-shot 方式从大型模型中提取并组合多种深度先验，用于单张图像的场景重建。我们证明，无需额外知识，只需在一个子任务中泛化一个深度先验，即可完成这一挑战性任务。为此，我们引入了与姿态、尺度和遮挡解析相关的新方法，确保深度先验能够稳健地协同工作。深度先验组合无需 3D 或 2D 数据驱动的训练，在将先验知识泛化到开放世界场景中表现优异。我们在多个数据集上进行了评估，并通过与最新方法的全面比较，展示了我们的优势。项目页面：https://junshengzhou.github.io/DeepPriorAssembly。

> Large language and vision models have been leading a revolution in visual computing. By greatly scaling up sizes of data and model parameters, the large models learn deep priors which lead to remarkable performance in various tasks. In this work, we present deep prior assembly, a novel framework that assembles diverse deep priors from large models for scene reconstruction from single images in a zero-shot manner. We show that this challenging task can be done without extra knowledge but just simply generalizing one deep prior in one sub-task. To this end, we introduce novel methods related to poses, scales, and occlusion parsing which are keys to enable deep priors to work together in a robust way. Deep prior assembly does not require any 3D or 2D data-driven training in the task and demonstrates superior performance in generalizing priors to open-world scenes. We conduct evaluations on various datasets, and report analysis, numerical and visual comparisons with the latest methods to show our superiority. Project page: https://junshengzhou.github.io/DeepPriorAssembly.

[Arxiv](https://arxiv.org/abs/2410.15971)