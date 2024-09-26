# ControlCity：一种多模态扩散模型，专为精准地理数据生成和城市形态分析而设计

发布时间：2024年09月25日

`LLM应用` `城市规划` `地理信息系统`

> ControlCity: A Multimodal Diffusion Model Based Approach for Accurate Geospatial Data Generation and Urban Morphology Analysis

# 摘要

> 志愿者地理信息 (VGI) 凭借其多样性、大数据量、快速更新和多源特性，已成为地理空间数据的关键来源。然而，OSM 等平台的 VGI 数据在城市建筑数据方面存在显著的质量异质性。为此，我们提出了一种多源地理数据转换方案，利用可访问且完整的 VGI 数据生成城市建筑轮廓数据，并通过多模态数据生成框架提升准确性。首先，我们构建了一个“图像-文本-元数据-建筑轮廓”数据集，主要基于道路网络数据，辅以其他多模态数据。接着，我们推出了 ControlCity，一种基于多模态扩散模型的地理数据转换方法。该方法首先通过预训练的文本到图像模型对齐文本、元数据和建筑轮廓数据，再通过改进的 ControlNet 整合道路网络和土地利用图像，生成精细的建筑轮廓数据。在 22 个全球城市的实验中，ControlCity 成功模拟了真实的城市建筑模式，达到最先进水平。具体来说，我们的方法在 FID 和 MIoU 分数上均表现优异，尤其在城市形态转移、零样本城市生成和空间数据完整性评估等任务中表现突出。在零样本城市任务中，我们的方法准确预测并生成了类似的城市结构，展现了强大的泛化能力。本研究证实了我们的方法在生成城市建筑轮廓数据和捕捉复杂城市特征方面的有效性。

> Volunteer Geographic Information (VGI), with its rich variety, large volume, rapid updates, and diverse sources, has become a critical source of geospatial data. However, VGI data from platforms like OSM exhibit significant quality heterogeneity across different data types, particularly with urban building data. To address this, we propose a multi-source geographic data transformation solution, utilizing accessible and complete VGI data to assist in generating urban building footprint data. We also employ a multimodal data generation framework to improve accuracy. First, we introduce a pipeline for constructing an 'image-text-metadata-building footprint' dataset, primarily based on road network data and supplemented by other multimodal data. We then present ControlCity, a geographic data transformation method based on a multimodal diffusion model. This method first uses a pre-trained text-to-image model to align text, metadata, and building footprint data. An improved ControlNet further integrates road network and land-use imagery, producing refined building footprint data. Experiments across 22 global cities demonstrate that ControlCity successfully simulates real urban building patterns, achieving state-of-the-art performance. Specifically, our method achieves an average FID score of 50.94, reducing error by 71.01% compared to leading methods, and a MIoU score of 0.36, an improvement of 38.46%. Additionally, our model excels in tasks like urban morphology transfer, zero-shot city generation, and spatial data completeness assessment. In the zero-shot city task, our method accurately predicts and generates similar urban structures, demonstrating strong generalization. This study confirms the effectiveness of our approach in generating urban building footprint data and capturing complex city characteristics.

[Arxiv](https://arxiv.org/abs/2409.17049)