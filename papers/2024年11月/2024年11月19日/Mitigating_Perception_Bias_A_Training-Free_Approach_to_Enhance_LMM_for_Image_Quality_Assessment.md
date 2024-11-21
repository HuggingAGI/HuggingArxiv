# 减轻感知偏差：一种无需训练即可增强 LMM 以用于图像质量评估的方法

发布时间：2024年11月19日

`LLM应用` `图像质量评估` `多模态模型`

> Mitigating Perception Bias: A Training-Free Approach to Enhance LMM for Image Quality Assessment

# 摘要

> 尽管大型多模态模型（LMMs）在高级视觉任务中表现抢眼，但其在图像质量评估（IQA）方面的能力却较为有限。主要原因在于，LMMs 主要针对高级任务（如图像描述）进行训练，注重在不同质量下统一提取图像语义。这种注重语义但对质量不敏感的感知偏差，必然导致这些 LMMs 在进行质量评级时严重依赖图像语义。在本文中，我们没有耗费成本地重新训练或调整 LMM，而是提出了一个无需训练的去偏框架，通过减轻图像语义导致的偏差来校正图像质量预测。具体来说，我们首先探索了几种能在保持可识别语义的同时大幅降低图像质量的语义保留失真。将这些特定失真应用于查询或测试图像，能确保降级图像被认定为低质量，同时其语义不变。在质量推断时，将查询图像及其相应的降级版本与提示一同输入 LMM，提示表明应在降级版本被视为低质量的条件下推断查询图像的质量。这一先验条件有效地校准了 LMM 的质量感知，因为所有降级图像无论语义差异如何，都被一致评为低质量。最后，利用条件概率模型聚合在不同先验条件（降级版本）下推断出的查询图像的质量分数。在各类 IQA 数据集上的大量实验表明，我们的去偏框架能够持续提升 LMM 的性能，且代码将公开可用。

> Despite the impressive performance of large multimodal models (LMMs) in high-level visual tasks, their capacity for image quality assessment (IQA) remains limited. One main reason is that LMMs are primarily trained for high-level tasks (e.g., image captioning), emphasizing unified image semantics extraction under varied quality. Such semantic-aware yet quality-insensitive perception bias inevitably leads to a heavy reliance on image semantics when those LMMs are forced for quality rating. In this paper, instead of retraining or tuning an LMM costly, we propose a training-free debiasing framework, in which the image quality prediction is rectified by mitigating the bias caused by image semantics. Specifically, we first explore several semantic-preserving distortions that can significantly degrade image quality while maintaining identifiable semantics. By applying these specific distortions to the query or test images, we ensure that the degraded images are recognized as poor quality while their semantics remain. During quality inference, both a query image and its corresponding degraded version are fed to the LMM along with a prompt indicating that the query image quality should be inferred under the condition that the degraded one is deemed poor quality.This prior condition effectively aligns the LMM's quality perception, as all degraded images are consistently rated as poor quality, regardless of their semantic difference.Finally, the quality scores of the query image inferred under different prior conditions (degraded versions) are aggregated using a conditional probability model. Extensive experiments on various IQA datasets show that our debiasing framework could consistently enhance the LMM performance and the code will be publicly available.

[Arxiv](https://arxiv.org/abs/2411.12791)