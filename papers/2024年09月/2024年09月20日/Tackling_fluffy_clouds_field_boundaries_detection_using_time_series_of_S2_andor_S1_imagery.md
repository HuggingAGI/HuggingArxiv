# 解决蓬松的云：使用 S2 和/或 S1 图像的时间序列进行场边界检测

发布时间：2024年09月20日

`其他` `卫星遥感`

> Tackling fluffy clouds: field boundaries detection using time series of S2 and/or S1 imagery

# 摘要

> 摘要：准确的农田边界划定在数字农业中是一个关键挑战，影响从作物监测到资源管理的一切。现有的方法经常受到噪声的困扰，并且在不同的景观中难以推广，特别是在处理光学遥感中的云覆盖时。作为回应，本研究提出了一种新的方法，利用 Sentinel-2（S2）和 Sentinel-1（S1）图像的时间序列数据来提高在不同云条件下的性能，无需手动云过滤。我们引入了一种专门为卫星图像时间序列设计的 3D 视觉 Transformer 架构，结合了一种内存高效的注意力机制。提出了两个模型：PTAViT3D，它独立处理 S2 或 S1 数据，以及 PTAViT3D-CA，它融合两个数据集以提高准确性。通过利用时空相关性，在稀疏和密集的云覆盖下对两个模型进行了评估。我们的结果表明，即使在部分（S2 或 S2 和 S1 数据融合）或密集云覆盖（S1）的情况下，这些模型也可以有效地划定农田边界，基于 S1 的模型在空间分辨率方面提供了与 S2 图像相当的性能。这种方法的一个关键优势在于它能够以内存高效的方式利用时空相关性直接处理被云污染的图像。这种方法用于 ePaddocks 产品来绘制澳大利亚的全国农田边界，提供了一种强大、可扩展的解决方案，适用于不同的农业环境，在现有方法失败的地方提供了精度和可靠性。我们的代码可在这个 https URL 获得。

> 
Abstract:Accurate field boundary delineation is a critical challenge in digital agriculture, impacting everything from crop monitoring to resource management. Existing methods often struggle with noise and fail to generalize across varied landscapes, particularly when dealing with cloud cover in optical remote sensing. In response, this study presents a new approach that leverages time series data from Sentinel-2 (S2) and Sentinel-1 (S1) imagery to improve performance under diverse cloud conditions, without the need for manual cloud filtering. We introduce a 3D Vision Transformer architecture specifically designed for satellite image time series, incorporating a memory-efficient attention mechanism. Two models are proposed: PTAViT3D, which handles either S2 or S1 data independently, and PTAViT3D-CA, which fuses both datasets to enhance accuracy. Both models are evaluated under sparse and dense cloud coverage by exploiting spatio-temporal correlations. Our results demonstrate that the models can effectively delineate field boundaries, even with partial (S2 or S2 and S1 data fusion) or dense cloud cover (S1), with the S1-based model providing performance comparable to S2 imagery in terms of spatial resolution. A key strength of this approach lies in its capacity to directly process cloud-contaminated imagery by leveraging spatio-temporal correlations in a memory-efficient manner. This methodology, used in the ePaddocks product to map Australia's national field boundaries, offers a robust, scalable solution adaptable to varying agricultural environments, delivering precision and reliability where existing methods falter. Our code is available at this https URL.
    

[Arxiv](https://arxiv.org/pdf/2409.13568)