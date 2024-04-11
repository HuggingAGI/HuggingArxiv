# 通过连续性的语言模型融合技术，实现文本生成的动态调整与精准控制。

发布时间：2024年04月10日

`LLM应用` `多域适应` `用户偏好学习`

> Continuous Language Model Interpolation for Dynamic and Controllable Text Generation

# 摘要

> 随着大型语言模型在众多应用场景中备受青睐，让它们具备更强的适应性和可控性变得尤为关键，尤其是对于那些直接面向用户的应用。与现有研究主要关注于寻找单一预设目标优化的模型不同，我们着眼于一个更具挑战性的场景——模型需实时适应用户多变的偏好。我们采用了基于线性权重插值的适应技术，将其打造为能够实时创建具有特定生成特质模型的连续性多域插值器。我们通过低秩更新技术对基础模型进行微调，使其适应不同的领域，打造出一系列具有独特生成特性的锚定模型。接着，利用这些锚定模型的权重更新，定义了它们凸包内所有（无限）模型的完整类别。实证结果显示，调整插值权重能够带来与所有控制属性相一致的、可预测的模型输出变化。研究发现，大多数属性间的相互影响较小，我们识别并讨论了其中例外的属性组合。我们的成果揭示，通过在线性权重插值之间进行微调，可以实现对模型输出的可预测、精细控制，同时满足多重风格特征的需求。

> As large language models (LLMs) have gained popularity for a variety of use cases, making them adaptable and controllable has become increasingly important, especially for user-facing applications. While the existing literature on LLM adaptation primarily focuses on finding a model (or models) that optimizes a single predefined objective, here we focus on the challenging case where the model must dynamically adapt to diverse -- and often changing -- user preferences. For this, we leverage adaptation methods based on linear weight interpolation, casting them as continuous multi-domain interpolators that produce models with specific prescribed generation characteristics on-the-fly. Specifically, we use low-rank updates to fine-tune a base model to various different domains, yielding a set of anchor models with distinct generation profiles. Then, we use the weight updates of these anchor models to parametrize the entire (infinite) class of models contained within their convex hull. We empirically show that varying the interpolation weights yields predictable and consistent change in the model outputs with respect to all of the controlled attributes. We find that there is little entanglement between most attributes and identify and discuss the pairs of attributes for which this is not the case. Our results suggest that linearly interpolating between the weights of fine-tuned models facilitates predictable, fine-grained control of model outputs with respect to multiple stylistic characteristics simultaneously.

![通过连续性的语言模型融合技术，实现文本生成的动态调整与精准控制。](../../../paper_images/2404.07117/x1.png)

![通过连续性的语言模型融合技术，实现文本生成的动态调整与精准控制。](../../../paper_images/2404.07117/x2.png)

![通过连续性的语言模型融合技术，实现文本生成的动态调整与精准控制。](../../../paper_images/2404.07117/x3.png)

![通过连续性的语言模型融合技术，实现文本生成的动态调整与精准控制。](../../../paper_images/2404.07117/x4.png)

![通过连续性的语言模型融合技术，实现文本生成的动态调整与精准控制。](../../../paper_images/2404.07117/x5.png)

![通过连续性的语言模型融合技术，实现文本生成的动态调整与精准控制。](../../../paper_images/2404.07117/x6.png)

![通过连续性的语言模型融合技术，实现文本生成的动态调整与精准控制。](../../../paper_images/2404.07117/x7.png)

![通过连续性的语言模型融合技术，实现文本生成的动态调整与精准控制。](../../../paper_images/2404.07117/x8.png)

![通过连续性的语言模型融合技术，实现文本生成的动态调整与精准控制。](../../../paper_images/2404.07117/x9.png)

![通过连续性的语言模型融合技术，实现文本生成的动态调整与精准控制。](../../../paper_images/2404.07117/x10.png)

![通过连续性的语言模型融合技术，实现文本生成的动态调整与精准控制。](../../../paper_images/2404.07117/x11.png)

![通过连续性的语言模型融合技术，实现文本生成的动态调整与精准控制。](../../../paper_images/2404.07117/x12.png)

![通过连续性的语言模型融合技术，实现文本生成的动态调整与精准控制。](../../../paper_images/2404.07117/x13.png)

![通过连续性的语言模型融合技术，实现文本生成的动态调整与精准控制。](../../../paper_images/2404.07117/x14.png)

![通过连续性的语言模型融合技术，实现文本生成的动态调整与精准控制。](../../../paper_images/2404.07117/x15.png)

![通过连续性的语言模型融合技术，实现文本生成的动态调整与精准控制。](../../../paper_images/2404.07117/x17.png)

![通过连续性的语言模型融合技术，实现文本生成的动态调整与精准控制。](../../../paper_images/2404.07117/x18.png)

![通过连续性的语言模型融合技术，实现文本生成的动态调整与精准控制。](../../../paper_images/2404.07117/x19.png)

![通过连续性的语言模型融合技术，实现文本生成的动态调整与精准控制。](../../../paper_images/2404.07117/x20.png)

![通过连续性的语言模型融合技术，实现文本生成的动态调整与精准控制。](../../../paper_images/2404.07117/x21.png)

![通过连续性的语言模型融合技术，实现文本生成的动态调整与精准控制。](../../../paper_images/2404.07117/x22.png)

![通过连续性的语言模型融合技术，实现文本生成的动态调整与精准控制。](../../../paper_images/2404.07117/x23.png)

![通过连续性的语言模型融合技术，实现文本生成的动态调整与精准控制。](../../../paper_images/2404.07117/x24.png)

![通过连续性的语言模型融合技术，实现文本生成的动态调整与精准控制。](../../../paper_images/2404.07117/x25.png)

![通过连续性的语言模型融合技术，实现文本生成的动态调整与精准控制。](../../../paper_images/2404.07117/x26.png)

![通过连续性的语言模型融合技术，实现文本生成的动态调整与精准控制。](../../../paper_images/2404.07117/x27.png)

![通过连续性的语言模型融合技术，实现文本生成的动态调整与精准控制。](../../../paper_images/2404.07117/x28.png)

![通过连续性的语言模型融合技术，实现文本生成的动态调整与精准控制。](../../../paper_images/2404.07117/x29.png)

![通过连续性的语言模型融合技术，实现文本生成的动态调整与精准控制。](../../../paper_images/2404.07117/x30.png)

![通过连续性的语言模型融合技术，实现文本生成的动态调整与精准控制。](../../../paper_images/2404.07117/x31.png)

![通过连续性的语言模型融合技术，实现文本生成的动态调整与精准控制。](../../../paper_images/2404.07117/x32.png)

![通过连续性的语言模型融合技术，实现文本生成的动态调整与精准控制。](../../../paper_images/2404.07117/x33.png)

![通过连续性的语言模型融合技术，实现文本生成的动态调整与精准控制。](../../../paper_images/2404.07117/x34.png)

![通过连续性的语言模型融合技术，实现文本生成的动态调整与精准控制。](../../../paper_images/2404.07117/x35.png)

![通过连续性的语言模型融合技术，实现文本生成的动态调整与精准控制。](../../../paper_images/2404.07117/x36.png)

![通过连续性的语言模型融合技术，实现文本生成的动态调整与精准控制。](../../../paper_images/2404.07117/x37.png)

![通过连续性的语言模型融合技术，实现文本生成的动态调整与精准控制。](../../../paper_images/2404.07117/x38.png)

![通过连续性的语言模型融合技术，实现文本生成的动态调整与精准控制。](../../../paper_images/2404.07117/x39.png)

![通过连续性的语言模型融合技术，实现文本生成的动态调整与精准控制。](../../../paper_images/2404.07117/x40.png)

![通过连续性的语言模型融合技术，实现文本生成的动态调整与精准控制。](../../../paper_images/2404.07117/x41.png)

![通过连续性的语言模型融合技术，实现文本生成的动态调整与精准控制。](../../../paper_images/2404.07117/x42.png)

![通过连续性的语言模型融合技术，实现文本生成的动态调整与精准控制。](../../../paper_images/2404.07117/x43.png)

![通过连续性的语言模型融合技术，实现文本生成的动态调整与精准控制。](../../../paper_images/2404.07117/x44.png)

![通过连续性的语言模型融合技术，实现文本生成的动态调整与精准控制。](../../../paper_images/2404.07117/x45.png)

![通过连续性的语言模型融合技术，实现文本生成的动态调整与精准控制。](../../../paper_images/2404.07117/x46.png)

![通过连续性的语言模型融合技术，实现文本生成的动态调整与精准控制。](../../../paper_images/2404.07117/x47.png)

[Arxiv](https://arxiv.org/abs/2404.07117)