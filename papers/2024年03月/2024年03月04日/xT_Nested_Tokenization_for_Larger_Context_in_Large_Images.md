# [xT 技术提出了一种针对大型图像的嵌套分词方法，旨在捕获并处理更大范围的上下文信息。]

发布时间：2024年03月04日

`Agent`

> xT: Nested Tokenization for Larger Context in Large Images

> 当前计算机视觉流程在处理大型图像时，普遍采取下采样或裁剪这两种牺牲信息量和图像上下文的方法。然而，在诸如卫星图像等实际应用场景中，全局语境与高频率细节同等关键，这让研究者面临难以抉择的信息剔除问题。为此，我们创新性地提出了xT——一个简洁易用的视觉Transformer框架，它能有效聚合全局上下文与局部细节，并借助现代GPU实现对大型图像的端到端建模。我们精选了一系列覆盖经典视觉任务的基准数据集，它们能精确衡量模型对大型且包含丰富细节图像的理解能力。通过将原本用于自然语言处理的长序列模型与大型图像的嵌套分词方案相结合，我们在棘手的图像分类任务上提升了最高达8.6%的准确率，在大型图像基于上下文的分割任务上提高了11.6的F1分数。

> Modern computer vision pipelines handle large images in one of two sub-optimal ways: down-sampling or cropping. These two methods incur significant losses in the amount of information and context present in an image. There are many downstream applications in which global context matters as much as high frequency details, such as in real-world satellite imagery; in such cases researchers have to make the uncomfortable choice of which information to discard. We introduce xT, a simple framework for vision transformers which effectively aggregates global context with local details and can model large images end-to-end on contemporary GPUs. We select a set of benchmark datasets across classic vision tasks which accurately reflect a vision model's ability to understand truly large images and incorporate fine details over large scales and assess our method's improvement on them. By introducing a nested tokenization scheme for large images in conjunction with long-sequence length models normally used for natural language processing, we are able to increase accuracy by up to 8.6% on challenging classification tasks and $F_1$ score by 11.6 on context-dependent segmentation in large images.

[Arxiv](https://arxiv.org/abs/2403.01915)