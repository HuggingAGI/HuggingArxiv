# 多尺度和多模态物种分布建模

发布时间：2024年11月06日

`其他` `物种分布`

> Multi-Scale and Multimodal Species Distribution Modeling

# 摘要

> 物种分布模型（SDMs）旨在通过将物种的出现数据与环境变量相关联来预测物种的分布。深度学习在 SDMs 中的最新应用开辟了新途径，特别是将空间数据（环境栅格、卫星图像）作为模型预测因子纳入，使模型能够考虑每个物种观察点周围的空间背景。然而，图像的适当空间范围并不容易确定，并且可能会影响模型的性能，因为尺度在 SDMs 中被认为是一个重要因素。我们为 SDMs 开发了一个模块化结构，使我们能够在单尺度和多尺度设置中测试尺度的影响。此外，我们的模型使用后期融合方法，能够为不同的模态考虑不同的尺度。在 GeoLifeCLEF 2023 基准上的结果表明，考虑多模态数据和学习多尺度表示会导致更准确的模型。

> Species distribution models (SDMs) aim to predict the distribution of species by relating occurrence data with environmental variables. Recent applications of deep learning to SDMs have enabled new avenues, specifically the inclusion of spatial data (environmental rasters, satellite images) as model predictors, allowing the model to consider the spatial context around each species' observations. However, the appropriate spatial extent of the images is not straightforward to determine and may affect the performance of the model, as scale is recognized as an important factor in SDMs. We develop a modular structure for SDMs that allows us to test the effect of scale in both single- and multi-scale settings. Furthermore, our model enables different scales to be considered for different modalities, using a late fusion approach. Results on the GeoLifeCLEF 2023 benchmark indicate that considering multimodal data and learning multi-scale representations leads to more accurate models.

[Arxiv](https://arxiv.org/abs/2411.04016)