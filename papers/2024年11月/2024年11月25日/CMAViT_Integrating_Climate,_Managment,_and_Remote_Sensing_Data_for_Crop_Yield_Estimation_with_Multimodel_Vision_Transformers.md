# CMAViT：融合气候、管理和遥感数据，借助多模型视觉转换器来估算作物产量

发布时间：2024年11月25日

`其他` `作物产量预测`

> CMAViT: Integrating Climate, Managment, and Remote Sensing Data for Crop Yield Estimation with Multimodel Vision Transformers

# 摘要

> 作物产量预测对农业规划意义重大，然而，鉴于天气、气候和管理实践间复杂的相互作用，其难度颇高。为应对此难题，我们推出了一款基于深度学习的多模型——气候-管理感知视觉转换器（CMAViT），专为像素级的葡萄园产量预测而打造。CMAViT借助遥感影像和短期气象数据，整合了时空数据，捕捉到了生长季变化的影响。此外，它还融入了以文本形式呈现的管理实践，通过交叉注意力编码器来模拟其与时间序列数据的交互。这一创新的多模态转换器在2016 - 2019年涵盖2200公顷、包含八个葡萄品种（超500万株葡萄藤）的大型数据集上接受了测试，表现优于UNet - ConvLSTM等传统模型，在空间变异性捕捉和产量预测方面表现出众，尤其在葡萄园的极端值预测上。CMAViT在未见过的测试数据集上达成了0.84的R2和8.22％的MAPE。屏蔽特定模态会致使性能下降：排除管理实践、气候数据以及两者同时排除，R2分别降至0.73、0.70和0.72，MAPE分别升至11.92％、12.66％和12.39％，凸显了每个模态对于精准产量预测的重要性。代码可在https://github.com/plant-ai-biophysics-lab/CMAViT获取。

> Crop yield prediction is essential for agricultural planning but remains challenging due to the complex interactions between weather, climate, and management practices. To address these challenges, we introduce a deep learning-based multi-model called Climate-Management Aware Vision Transformer (CMAViT), designed for pixel-level vineyard yield predictions. CMAViT integrates both spatial and temporal data by leveraging remote sensing imagery and short-term meteorological data, capturing the effects of growing season variations. Additionally, it incorporates management practices, which are represented in text form, using a cross-attention encoder to model their interaction with time-series data. This innovative multi-modal transformer tested on a large dataset from 2016-2019 covering 2,200 hectares and eight grape cultivars including more than 5 million vines, outperforms traditional models like UNet-ConvLSTM, excelling in spatial variability capture and yield prediction, particularly for extreme values in vineyards. CMAViT achieved an R2 of 0.84 and a MAPE of 8.22% on an unseen test dataset. Masking specific modalities lowered performance: excluding management practices, climate data, and both reduced R2 to 0.73, 0.70, and 0.72, respectively, and raised MAPE to 11.92%, 12.66%, and 12.39%, highlighting each modality's importance for accurate yield prediction. Code is available at https://github.com/plant-ai-biophysics-lab/CMAViT.

[Arxiv](https://arxiv.org/abs/2411.16989)