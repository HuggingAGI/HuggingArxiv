# YOLO-RD：利用检索器-字典技术，为 YOLO 注入相关且精炼的显式知识。

发布时间：2024年10月20日

`RAG` `计算机视觉` `自动驾驶`

> YOLO-RD: Introducing Relevant and Compact Explicit Knowledge to YOLO by Retriever-Dictionary

# 摘要

> 识别和定位图像中的物体是一个基本挑战，尽管通过实验不同架构和改进训练策略，模型准确性已有所提升，但现有模型普遍存在过度关注当前输入而忽略整体数据集信息的问题。为此，我们创新性地引入了 {\em \textbf{R}etriever}-{\em\textbf{D}ictionary} (RD) 模块。该模块使基于 YOLO 的模型能够高效地从包含数据集洞察的 Dictionary 中检索特征，该 Dictionary 由视觉模型 (VM)、大型语言模型 (LLM) 或视觉语言模型 (VLM) 的知识构建。灵活的 RD 模块不仅增强了模型从像素到图像级别的分割、检测和分类能力，还显著提升了模型性能，在对象检测中实现了超过 3\% 的 mAP 提升，而模型参数仅增加不到 1\%。此外，RD 模块还提升了两阶段模型和基于 DETR 的架构（如 Faster R-CNN 和 Deformable DETR）的有效性。

> Identifying and localizing objects within images is a fundamental challenge, and numerous efforts have been made to enhance model accuracy by experimenting with diverse architectures and refining training strategies. Nevertheless, a prevalent limitation in existing models is overemphasizing the current input while ignoring the information from the entire dataset. We introduce an innovative {\em \textbf{R}etriever}-{\em\textbf{D}ictionary} (RD) module to address this issue. This architecture enables YOLO-based models to efficiently retrieve features from a Dictionary that contains the insight of the dataset, which is built by the knowledge from Visual Models (VM), Large Language Models (LLM), or Visual Language Models (VLM). The flexible RD enables the model to incorporate such explicit knowledge that enhances the ability to benefit multiple tasks, specifically, segmentation, detection, and classification, from pixel to image level. The experiments show that using the RD significantly improves model performance, achieving more than a 3\% increase in mean Average Precision for object detection with less than a 1\% increase in model parameters. Beyond 1-stage object detection models, the RD module improves the effectiveness of 2-stage models and DETR-based architectures, such as Faster R-CNN and Deformable DETR

[Arxiv](https://arxiv.org/abs/2410.15346)