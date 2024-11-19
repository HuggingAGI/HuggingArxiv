# JRadiEvo：一个由模型合并的进化优化所增强的日本放射学报告生成模型

发布时间：2024年11月14日

`LLM应用` `放射学`

> JRadiEvo: A Japanese Radiology Report Generation Model Enhanced by Evolutionary Optimization of Model Merging

# 摘要

> 随着大型语言模型（LLMs）的迅猛发展，基础模型（FMs）取得了重大进展。在众多应用领域中，医疗保健对于这些基础模型至关重要，毕竟医生分析海量患者数据需要耗费大量时间与精力。近来，人们致力于通过诸如指令调整之类的技术，让多模态基础模型适配医疗领域，由此催生了医疗基础模型（MFMs）。然而，这类方法往往需要海量训练数据，才能让模型有效适配医疗领域。再者，现有的多数模型都是基于英语数据集训练的，这就限制了它们在非英语地区的实用性，因为那里的医疗保健专业人员和患者并非都能熟练使用英语。对翻译的需求不仅带来额外成本，还导致效率低下。为应对这些挑战，我们提出了一个通过模型合并的进化优化得以增强的日本放射学报告生成模型（JRadiEvo）。这是首次尝试借助模型合并的进化优化，将非医疗的视觉语言基础模型拓展至医疗领域。我们成功创建了一个模型，仅用来自公开数据的 50 个翻译样本，就能从 X 射线图像生成准确的日语报告。该模型在有限数据的高效利用下研发而成，表现优于近期研究中基于更大数据集训练的领先模型。此外，这个相对紧凑的基础模型仅含 80 亿个参数，能够在医院内部本地部署，对于因严格的隐私和安全要求而无法使用 API 及其他外部服务的环境而言，不失为一种实用的解决方案。

> With the rapid advancement of large language models (LLMs), foundational models (FMs) have seen significant advancements. Healthcare is one of the most crucial application areas for these FMs, given the significant time and effort required for physicians to analyze large volumes of patient data. Recent efforts have focused on adapting multimodal FMs to the medical domain through techniques like instruction-tuning, leading to the development of medical foundation models (MFMs). However, these approaches typically require large amounts of training data to effectively adapt models to the medical field. Moreover, most existing models are trained on English datasets, limiting their practicality in non-English-speaking regions where healthcare professionals and patients are not always fluent in English. The need for translation introduces additional costs and inefficiencies. To address these challenges, we propose a \textbf{J}apanese \textbf{Radi}ology report generation model enhanced by \textbf{Evo}lutionary optimization of model merging (JRadiEvo). This is the first attempt to extend a non-medical vision-language foundation model to the medical domain through evolutionary optimization of model merging. We successfully created a model that generates accurate Japanese reports from X-ray images using only 50 translated samples from publicly available data. This model, developed with highly efficient use of limited data, outperformed leading models from recent research trained on much larger datasets. Additionally, with only 8 billion parameters, this relatively compact foundation model can be deployed locally within hospitals, making it a practical solution for environments where APIs and other external services cannot be used due to strict privacy and security requirements.

[Arxiv](https://arxiv.org/abs/2411.09933)