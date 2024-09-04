# 提升遥感视觉-语言模型，实现零-shot场景分类

发布时间：2024年09月01日

`LLM应用` `计算机视觉`

> Enhancing Remote Sensing Vision-Language Models for Zero-Shot Scene Classification

# 摘要

> 视觉-语言模型在遥感领域的应用前景广阔，但传统的零-shot场景分类方法仍需将大图像分割成小块进行独立预测，忽略了重要的上下文信息。我们提出一种新方法，通过文本提示和图像编码器中的小块关系，利用传导推理提升零-shot能力，无需额外监督且计算成本低。实验结果显示，在10个遥感数据集上，我们的方法显著提高了分类准确性。源代码已公开在Github：https://github.com/elkhouryk/RS-TransCLIP。

> Vision-Language Models for remote sensing have shown promising uses thanks to their extensive pretraining. However, their conventional usage in zero-shot scene classification methods still involves dividing large images into patches and making independent predictions, i.e., inductive inference, thereby limiting their effectiveness by ignoring valuable contextual information. Our approach tackles this issue by utilizing initial predictions based on text prompting and patch affinity relationships from the image encoder to enhance zero-shot capabilities through transductive inference, all without the need for supervision and at a minor computational cost. Experiments on 10 remote sensing datasets with state-of-the-art Vision-Language Models demonstrate significant accuracy improvements over inductive zero-shot classification. Our source code is publicly available on Github: https://github.com/elkhouryk/RS-TransCLIP

[Arxiv](https://arxiv.org/abs/2409.00698)