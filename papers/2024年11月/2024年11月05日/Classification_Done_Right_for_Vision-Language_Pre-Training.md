# 分类正确用于视觉语言预训练

发布时间：2024年11月05日

`LLM应用` `计算机视觉` `图像 - 文本数据`

> Classification Done Right for Vision-Language Pre-Training

# 摘要

> 我们引入 SuperClass，这是一种用于图像 - 文本数据的视觉语言预训练的超级简单分类方法。与它的对比对应物 CLIP 不同，CLIP 与文本编码器进行对比，SuperClass 直接利用标记化的原始文本作为监督分类标签，无需额外的文本过滤或选择。由于没有作为对比目标的文本编码，SuperClass 不需要文本编码器，也不需要像 CLIP 那样保持大的批量大小。SuperClass 在各种下游任务上表现出卓越的性能，包括经典的计算机视觉基准和视觉语言下游任务。我们进一步探索了 SuperClass 在模型大小、训练长度或数据大小方面的缩放行为，并报告了令人鼓舞的结果以及与 CLIP 的比较。https://github.com/x-cls/superclass

> We introduce SuperClass, a super simple classification method for vision-language pre-training on image-text data. Unlike its contrastive counterpart CLIP who contrast with a text encoder, SuperClass directly utilizes tokenized raw text as supervised classification labels, without the need for additional text filtering or selection. Due to the absence of the text encoding as contrastive target, SuperClass does not require a text encoder and does not need to maintain a large batch size as CLIP does. SuperClass demonstrated superior performance on various downstream tasks, including classic computer vision benchmarks and vision language downstream tasks. We further explored the scaling behavior of SuperClass on model size, training length, or data size, and reported encouraging results and comparisons to CLIP. https://github.com/x-cls/superclass

[Arxiv](https://arxiv.org/abs/2411.03313)