# 本研究致力于将视觉-语言模型应用于医疗图像领域，使其能够进行具有泛化能力的异常检测，即针对各种医疗图像场景都能有效识别异常情况。

发布时间：2024年03月19日

`LLM应用` `异常检测`

> Adapting Visual-Language Models for Generalizable Anomaly Detection in Medical Images

# 摘要

> 近期大型视觉-语言预训练模型技术突破，使得在自然图像领域的零样本及少量样本异常检测上成绩斐然。但自然图像与医学图像间巨大的领域鸿沟制约了此类方法在医学异常检测上的应用效果。为此，本文创新性地提出了一种轻量级多层级适应与对比框架，旨在重新调教 CLIP 模型服务于医学异常检测任务。我们巧妙地在预训练视觉编码器中嵌入多个残差适配器，以此逐层强化视觉特征表达。这一多层级适应过程依托于多层级、像素级的视觉-语言特征对齐损失函数引导，有效帮助模型从关注自然图像中的物体语义转向聚焦医学图像中的异常识别。经此调整后的特征在多种医学数据类型上展现出更强的泛化性能，即便在训练期间面对前所未见的医学模态和解剖区域，依然能在零样本情况下保持出色的表现。实验证明，在医学异常检测基准测试中，我们的方法大幅超越现有最优模型，在零样本条件下，异常分类的平均 AUC 提升达到 6.24% 至 7.33%，异常分割提升 2.03% 至 2.37%；在少量样本条件下同样实现显著提升。相关源代码已公开，访问地址为：https://github.com/MediaBrain-SJTU/MVFA-AD。

> Recent advancements in large-scale visual-language pre-trained models have led to significant progress in zero-/few-shot anomaly detection within natural image domains. However, the substantial domain divergence between natural and medical images limits the effectiveness of these methodologies in medical anomaly detection. This paper introduces a novel lightweight multi-level adaptation and comparison framework to repurpose the CLIP model for medical anomaly detection. Our approach integrates multiple residual adapters into the pre-trained visual encoder, enabling a stepwise enhancement of visual features across different levels. This multi-level adaptation is guided by multi-level, pixel-wise visual-language feature alignment loss functions, which recalibrate the model's focus from object semantics in natural imagery to anomaly identification in medical images. The adapted features exhibit improved generalization across various medical data types, even in zero-shot scenarios where the model encounters unseen medical modalities and anatomical regions during training. Our experiments on medical anomaly detection benchmarks demonstrate that our method significantly surpasses current state-of-the-art models, with an average AUC improvement of 6.24% and 7.33% for anomaly classification, 2.03% and 2.37% for anomaly segmentation, under the zero-shot and few-shot settings, respectively. Source code is available at: https://github.com/MediaBrain-SJTU/MVFA-AD

![本研究致力于将视觉-语言模型应用于医疗图像领域，使其能够进行具有泛化能力的异常检测，即针对各种医疗图像场景都能有效识别异常情况。](../../../paper_images/2403.12570/x1.png)

![本研究致力于将视觉-语言模型应用于医疗图像领域，使其能够进行具有泛化能力的异常检测，即针对各种医疗图像场景都能有效识别异常情况。](../../../paper_images/2403.12570/x2.png)

![本研究致力于将视觉-语言模型应用于医疗图像领域，使其能够进行具有泛化能力的异常检测，即针对各种医疗图像场景都能有效识别异常情况。](../../../paper_images/2403.12570/x3.png)

![本研究致力于将视觉-语言模型应用于医疗图像领域，使其能够进行具有泛化能力的异常检测，即针对各种医疗图像场景都能有效识别异常情况。](../../../paper_images/2403.12570/x4.png)

![本研究致力于将视觉-语言模型应用于医疗图像领域，使其能够进行具有泛化能力的异常检测，即针对各种医疗图像场景都能有效识别异常情况。](../../../paper_images/2403.12570/x5.png)

![本研究致力于将视觉-语言模型应用于医疗图像领域，使其能够进行具有泛化能力的异常检测，即针对各种医疗图像场景都能有效识别异常情况。](../../../paper_images/2403.12570/x6.png)

![本研究致力于将视觉-语言模型应用于医疗图像领域，使其能够进行具有泛化能力的异常检测，即针对各种医疗图像场景都能有效识别异常情况。](../../../paper_images/2403.12570/x7.png)

![本研究致力于将视觉-语言模型应用于医疗图像领域，使其能够进行具有泛化能力的异常检测，即针对各种医疗图像场景都能有效识别异常情况。](../../../paper_images/2403.12570/x8.png)

![本研究致力于将视觉-语言模型应用于医疗图像领域，使其能够进行具有泛化能力的异常检测，即针对各种医疗图像场景都能有效识别异常情况。](../../../paper_images/2403.12570/x9.png)

![本研究致力于将视觉-语言模型应用于医疗图像领域，使其能够进行具有泛化能力的异常检测，即针对各种医疗图像场景都能有效识别异常情况。](../../../paper_images/2403.12570/x10.png)

![本研究致力于将视觉-语言模型应用于医疗图像领域，使其能够进行具有泛化能力的异常检测，即针对各种医疗图像场景都能有效识别异常情况。](../../../paper_images/2403.12570/x11.png)

![本研究致力于将视觉-语言模型应用于医疗图像领域，使其能够进行具有泛化能力的异常检测，即针对各种医疗图像场景都能有效识别异常情况。](../../../paper_images/2403.12570/x12.png)

![本研究致力于将视觉-语言模型应用于医疗图像领域，使其能够进行具有泛化能力的异常检测，即针对各种医疗图像场景都能有效识别异常情况。](../../../paper_images/2403.12570/x13.png)

![本研究致力于将视觉-语言模型应用于医疗图像领域，使其能够进行具有泛化能力的异常检测，即针对各种医疗图像场景都能有效识别异常情况。](../../../paper_images/2403.12570/x14.png)

![本研究致力于将视觉-语言模型应用于医疗图像领域，使其能够进行具有泛化能力的异常检测，即针对各种医疗图像场景都能有效识别异常情况。](../../../paper_images/2403.12570/x15.png)

[Arxiv](https://arxiv.org/abs/2403.12570)