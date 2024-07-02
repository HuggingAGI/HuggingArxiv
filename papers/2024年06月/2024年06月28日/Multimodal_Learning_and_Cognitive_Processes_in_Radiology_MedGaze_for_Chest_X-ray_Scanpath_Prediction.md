# 多模态学习与放射学认知：MedGaze在胸部X光扫描路径预测中的应用

发布时间：2024年06月28日

`LLM应用` `计算机视觉`

> Multimodal Learning and Cognitive Processes in Radiology: MedGaze for Chest X-ray Scanpath Prediction

# 摘要

> 在计算机视觉领域，预测人类的注视行为对于构建能够预判用户注意力的交互系统至关重要，同时也为认知科学的基本问题提供了解决方案，并对HCI和AR/VR系统等领域产生深远影响。尽管已有方法用于模拟人类的眼睛注视行为，但在医学影像领域应用这些模型进行扫描路径预测的研究尚属空白。我们提出的系统致力于从放射学报告和CXR图像中预测眼睛注视序列，有望简化数据收集流程，并利用更大数据集提升AI系统的性能。然而，预测医学图像上的扫描路径因异常区域的多样性而充满挑战。我们的模型在预测关键的固定坐标和持续时间方面表现卓越，超越了计算机视觉领域的现有模型。通过采用两阶段训练流程和利用大型公开数据集，我们的方法能够生成与放射学报告相匹配的静态热图和眼睛注视视频，从而促进深入分析。我们通过对比最先进方法的性能并评估其在不同放射科医生间的泛化能力来验证我们的方法，并创新性地模拟了放射科医生在CXR图像诊断时的搜索模式。根据放射科医生的评价，MedGaze能够生成高度聚焦于CXR图像上相关区域的人类样注视序列，甚至在扫描路径的冗余和随机性方面有时超越人类表现。

> Predicting human gaze behavior within computer vision is integral for developing interactive systems that can anticipate user attention, address fundamental questions in cognitive science, and hold implications for fields like human-computer interaction (HCI) and augmented/virtual reality (AR/VR) systems. Despite methodologies introduced for modeling human eye gaze behavior, applying these models to medical imaging for scanpath prediction remains unexplored. Our proposed system aims to predict eye gaze sequences from radiology reports and CXR images, potentially streamlining data collection and enhancing AI systems using larger datasets. However, predicting human scanpaths on medical images presents unique challenges due to the diverse nature of abnormal regions. Our model predicts fixation coordinates and durations critical for medical scanpath prediction, outperforming existing models in the computer vision community. Utilizing a two-stage training process and large publicly available datasets, our approach generates static heatmaps and eye gaze videos aligned with radiology reports, facilitating comprehensive analysis. We validate our approach by comparing its performance with state-of-the-art methods and assessing its generalizability among different radiologists, introducing novel strategies to model radiologists' search patterns during CXR image diagnosis. Based on the radiologist's evaluation, MedGaze can generate human-like gaze sequences with a high focus on relevant regions over the CXR images. It sometimes also outperforms humans in terms of redundancy and randomness in the scanpaths.

[Arxiv](https://arxiv.org/abs/2407.00129)