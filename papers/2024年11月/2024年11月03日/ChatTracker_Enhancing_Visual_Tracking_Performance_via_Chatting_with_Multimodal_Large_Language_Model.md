# ChatTracker：通过与多模态大型语言模型聊天来提高视觉跟踪性能

发布时间：2024年11月03日

`LLM应用` `视觉跟踪`

> ChatTracker: Enhancing Visual Tracking Performance via Chatting with Multimodal Large Language Model

# 摘要

> 视觉对象跟踪旨在根据初始边界框在视频序列中定位目标对象。最近，视觉语言（VL）跟踪器已被提出利用额外的自然语言描述来增强在各种应用中的通用性。然而，就跟踪性能而言，VL 跟踪器仍不如最先进（SoTA）的视觉跟踪器。我们发现这种劣势主要源于它们严重依赖手动文本注释，其中包括频繁提供模糊的语言描述。在本文中，我们提出 ChatTracker 以利用多模态大语言模型（MLLM）中的丰富世界知识来生成高质量的语言描述并提高跟踪性能。为此，我们提出了一种新颖的基于反射的提示优化模块，以利用跟踪反馈迭代地改进目标的模糊和不准确描述。为了进一步利用 MLLM 产生的语义信息，提出了一个简单而有效的 VL 跟踪框架，并且可以轻松地作为即插即用模块集成，以提高 VL 和视觉跟踪器的性能。实验结果表明，我们提出的 ChatTracker 实现了与现有方法相当的性能。

> Visual object tracking aims to locate a targeted object in a video sequence based on an initial bounding box. Recently, Vision-Language~(VL) trackers have proposed to utilize additional natural language descriptions to enhance versatility in various applications. However, VL trackers are still inferior to State-of-The-Art (SoTA) visual trackers in terms of tracking performance. We found that this inferiority primarily results from their heavy reliance on manual textual annotations, which include the frequent provision of ambiguous language descriptions. In this paper, we propose ChatTracker to leverage the wealth of world knowledge in the Multimodal Large Language Model (MLLM) to generate high-quality language descriptions and enhance tracking performance. To this end, we propose a novel reflection-based prompt optimization module to iteratively refine the ambiguous and inaccurate descriptions of the target with tracking feedback. To further utilize semantic information produced by MLLM, a simple yet effective VL tracking framework is proposed and can be easily integrated as a plug-and-play module to boost the performance of both VL and visual trackers. Experimental results show that our proposed ChatTracker achieves a performance comparable to existing methods.

[Arxiv](https://arxiv.org/abs/2411.01756)