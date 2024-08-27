# GeoPlant 数据集：专为空间植物物种预测设计

发布时间：2024年08月25日

`LLM应用

解释：尽管这篇论文主要关注的是生物多样性的监测和物种分布模型（SDMs）的开发，但它利用了高分辨率的卫星图像和气候数据，这些数据可能涉及大型语言模型（LLM）在数据处理和分析中的应用。因此，将其归类为LLM应用是合理的，因为论文中的方法和资源可能依赖于或受益于LLM技术在数据处理和模型构建中的应用。` `生态学` `生物多样性`

> GeoPlant: Spatial Plant Species Prediction Dataset

# 摘要

> 监测细尺度和大面积的生物多样性难度大，限制了生态学研究和保护行动。为此，我们开发了高分辨率（10-50米）的欧洲物种分布模型（SDMs）数据集，涵盖了大部分欧洲植物。该数据集整合了500万条异质的存在记录和9万条详尽的调查记录，并附带多种环境数据。此外，还提供了高分辨率的卫星图像和气候数据。我们还创建了一个公开的SDM基准，方便研究者快速上手。所有资源均可在Kaggle上获取。

> The difficulty of monitoring biodiversity at fine scales and over large areas limits ecological knowledge and conservation efforts. To fill this gap, Species Distribution Models (SDMs) predict species across space from spatially explicit features. Yet, they face the challenge of integrating the rich but heterogeneous data made available over the past decade, notably millions of opportunistic species observations and standardized surveys, as well as multi-modal remote sensing data. In light of that, we have designed and developed a new European-scale dataset for SDMs at high spatial resolution (10-50 m), including more than 10k species (i.e., most of the European flora). The dataset comprises 5M heterogeneous Presence-Only records and 90k exhaustive Presence-Absence survey records, all accompanied by diverse environmental rasters (e.g., elevation, human footprint, and soil) that are traditionally used in SDMs. In addition, it provides Sentinel-2 RGB and NIR satellite images with 10 m resolution, a 20-year time-series of climatic variables, and satellite time-series from the Landsat program. In addition to the data, we provide an openly accessible SDM benchmark (hosted on Kaggle), which has already attracted an active community and a set of strong baselines for single predictor/modality and multimodal approaches. All resources, e.g., the dataset, pre-trained models, and baseline methods (in the form of notebooks), are available on Kaggle, allowing one to start with our dataset literally with two mouse clicks.

[Arxiv](https://arxiv.org/abs/2408.13928)