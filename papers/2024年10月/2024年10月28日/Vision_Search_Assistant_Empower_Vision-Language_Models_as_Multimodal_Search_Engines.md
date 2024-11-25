# 视觉搜索助手：让视觉语言模型成为多模态搜索引擎

发布时间：2024年10月28日

`LLM应用` `搜索引擎` `视觉语言模型`

> Vision Search Assistant: Empower Vision-Language Models as Multimodal Search Engines

# 摘要

> 搜索引擎能凭借文本检索未知信息。但在理解陌生视觉内容时，传统方法力有不逮，比如识别模型从未见过的物体。对于大型视觉语言模型（VLMs）而言，此挑战更为显著：若模型未曾接触过图像所描绘的对象，就难以针对用户关于该图像的问题给出可靠答案。而且，随着新对象和新事件不断涌现，由于计算量巨大，频繁更新 VLMs 并不可行。为突破这一局限，我们提出了视觉搜索助手这一全新框架，以促进 VLMs 与网络代理的协作。该方法借助 VLMs 的视觉理解能力和网络代理的实时信息获取，通过网络进行开放世界的检索增强生成。通过这种协作整合视觉和文本表征，即便图像对系统而言是全新的，模型也能给出有见地的回应。在开放集和封闭集的问答基准上开展的大量实验表明，视觉搜索助手显著优于其他模型，且能广泛应用于现有的 VLMs。

> Search engines enable the retrieval of unknown information with texts. However, traditional methods fall short when it comes to understanding unfamiliar visual content, such as identifying an object that the model has never seen before. This challenge is particularly pronounced for large vision-language models (VLMs): if the model has not been exposed to the object depicted in an image, it struggles to generate reliable answers to the user's question regarding that image. Moreover, as new objects and events continuously emerge, frequently updating VLMs is impractical due to heavy computational burdens. To address this limitation, we propose Vision Search Assistant, a novel framework that facilitates collaboration between VLMs and web agents. This approach leverages VLMs' visual understanding capabilities and web agents' real-time information access to perform open-world Retrieval-Augmented Generation via the web. By integrating visual and textual representations through this collaboration, the model can provide informed responses even when the image is novel to the system. Extensive experiments conducted on both open-set and closed-set QA benchmarks demonstrate that the Vision Search Assistant significantly outperforms the other models and can be widely applied to existing VLMs.

[Arxiv](https://arxiv.org/abs/2410.21220)