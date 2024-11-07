# VLM-Grounder：用于零样本 3D 视觉定位的 VLM 代理

发布时间：2024年10月17日

`LLM应用` `机器人` `3D 视觉`

> VLM-Grounder: A VLM Agent for Zero-Shot 3D Visual Grounding

# 摘要

> 摘要：3D 视觉基础对于机器人至关重要，需要自然语言和 3D 场景理解的集成。传统方法依赖于 3D 点云的监督学习，受到稀缺数据集的限制。最近，利用大型语言模型（LLMs）的零样本方法已被提出以解决数据问题。虽然有效，但这些方法仅使用以对象为中心的信息，限制了它们处理复杂查询的能力。在这项工作中，我们提出了 VLM-Grounder，这是一个仅基于 2D 图像使用视觉语言模型（VLMs）进行零样本 3D 视觉基础的新框架。VLM-Grounder 动态拼接图像序列，采用基础和反馈方案来找到目标对象，并使用多视图集成投影来准确估计 3D 边界框。在 ScanRefer 和 Nr3D 数据集上的实验表明，VLM-Grounder 优于以前的零样本方法，在 ScanRefer 上达到 51.6％的 Acc@0.25，在 Nr3D 上达到 48.0％的 Acc，且不依赖于 3D 几何或对象先验。代码可在这个 https URL 获得。

> 
Abstract:3D visual grounding is crucial for robots, requiring integration of natural language and 3D scene understanding. Traditional methods depending on supervised learning with 3D point clouds are limited by scarce datasets. Recently zero-shot methods leveraging LLMs have been proposed to address the data issue. While effective, these methods only use object-centric information, limiting their ability to handle complex queries. In this work, we present VLM-Grounder, a novel framework using vision-language models (VLMs) for zero-shot 3D visual grounding based solely on 2D images. VLM-Grounder dynamically stitches image sequences, employs a grounding and feedback scheme to find the target object, and uses a multi-view ensemble projection to accurately estimate 3D bounding boxes. Experiments on ScanRefer and Nr3D datasets show VLM-Grounder outperforms previous zero-shot methods, achieving 51.6% Acc@0.25 on ScanRefer and 48.0% Acc on Nr3D, without relying on 3D geometry or object priors. Codes are available at this https URL .
    

[Arxiv](https://arxiv.org/pdf/2410.13860)