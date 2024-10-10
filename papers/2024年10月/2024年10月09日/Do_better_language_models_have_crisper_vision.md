# 语言模型越先进，视觉理解是否越精准？

发布时间：2024年10月09日

`LLM应用` `计算机视觉`

> Do better language models have crisper vision?

# 摘要

> 文本-only 大型语言模型 (LLM) 对视觉世界的理解程度如何？随着 LLM 在计算机视觉中的应用越来越广泛，解决这个问题变得既基础又相关。然而，现有研究主要集中在有限场景，例如它们生成视觉内容或聚类多模态数据的能力。为此，我们提出了视觉文本表示基准 (ViTeRB)，以隔离使语言模型与视觉世界良好对齐的关键属性。通过这个，我们确定大规模基于解码器的 LLM 是表示以视觉为中心的上下文中文本的理想候选者，这与当前使用文本编码器的做法相反。基于这些发现，我们提出了 ShareLock，一个超轻量级的类似 CLIP 的模型。通过利用来自强视觉和语言模型的预计算冻结特征，ShareLock 在 ImageNet 上实现了令人印象深刻的 51% 准确率，尽管仅使用了 563k 图像-标题对。此外，训练仅需 1 GPU 小时（或包括特征预计算在内的 10 小时）——比先前方法少几个数量级。代码将发布。

> How well do text-only Large Language Models (LLMs) grasp the visual world? As LLMs are increasingly used in computer vision, addressing this question becomes both fundamental and pertinent. However, existing studies have primarily focused on limited scenarios, such as their ability to generate visual content or cluster multimodal data. To this end, we propose the Visual Text Representation Benchmark (ViTeRB) to isolate key properties that make language models well-aligned with the visual world. With this, we identify large-scale decoder-based LLMs as ideal candidates for representing text in vision-centric contexts, counter to the current practice of utilizing text encoders. Building on these findings, we propose ShareLock, an ultra-lightweight CLIP-like model. By leveraging precomputable frozen features from strong vision and language models, ShareLock achieves an impressive 51% accuracy on ImageNet despite utilizing just 563k image-caption pairs. Moreover, training requires only 1 GPU hour (or 10 hours including the precomputation of features) - orders of magnitude less than prior methods. Code will be released.

[Arxiv](https://arxiv.org/abs/2410.07173)