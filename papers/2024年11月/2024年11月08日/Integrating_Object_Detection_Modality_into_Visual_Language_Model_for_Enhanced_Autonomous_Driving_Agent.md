# 将对象检测模态集成到视觉语言模型中，以增强自动驾驶代理。

发布时间：2024年11月08日

`LLM应用` `自动驾驶` `视觉理解`

> Integrating Object Detection Modality into Visual Language Model for Enhanced Autonomous Driving Agent

# 摘要

> 在本文中，我们提出了一个新的框架，通过将视觉语言模型（VLMs）与专门用于对象检测的附加视觉感知模块相结合，来增强自动驾驶系统中的视觉理解。我们通过将基于 YOLOS 的检测网络与 CLIP 感知网络一起纳入 Llama-Adapter 架构，解决了对象检测和定位的局限性。我们的方法引入了相机 ID 分隔符以改进多视图处理，这对于全面的环境感知至关重要。在 DriveLM 视觉问答挑战上的实验表明，与基线模型相比有显著的改进，ChatGPT 分数、BLEU 分数和 CIDEr 指标的性能得到了增强，表明模型答案与基本事实的接近程度。我们的方法代表了朝着更强大和可解释的自动驾驶系统迈出的有希望的一步。还讨论了检测模式可能带来的安全增强。

> In this paper, we propose a novel framework for enhancing visual comprehension in autonomous driving systems by integrating visual language models (VLMs) with additional visual perception module specialised in object detection. We extend the Llama-Adapter architecture by incorporating a YOLOS-based detection network alongside the CLIP perception network, addressing limitations in object detection and localisation. Our approach introduces camera ID-separators to improve multi-view processing, crucial for comprehensive environmental awareness. Experiments on the DriveLM visual question answering challenge demonstrate significant improvements over baseline models, with enhanced performance in ChatGPT scores, BLEU scores, and CIDEr metrics, indicating closeness of model answer to ground truth. Our method represents a promising step towards more capable and interpretable autonomous driving systems. Possible safety enhancement enabled by detection modality is also discussed.

[Arxiv](https://arxiv.org/abs/2411.05898)