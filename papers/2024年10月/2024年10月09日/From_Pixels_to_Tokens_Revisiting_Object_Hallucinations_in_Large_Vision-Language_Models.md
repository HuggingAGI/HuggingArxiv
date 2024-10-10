# 从像素到标记：探索大型视觉-语言模型中的对象幻觉现象

发布时间：2024年10月09日

`LLM应用` `计算机视觉` `人工智能`

> From Pixels to Tokens: Revisiting Object Hallucinations in Large Vision-Language Models

# 摘要

> 大型视觉-语言模型中的幻觉问题，即生成视觉输入中不存在的对象，严重影响了其可靠性。尽管近期研究多将其归咎于视觉理解不足，却忽视了更根本的问题——模型无法有效提取或解耦视觉特征。本文从架构角度重新审视幻觉问题，探究其根源在于视觉编码器还是模态对齐模块。基于此，我们提出新型调优策略 PATCH，通过自适应虚拟令牌从边界框中提取对象特征，有效缓解幻觉问题。PATCH 在多模态幻觉数据集上表现卓越，有望为研究人员揭示幻觉的根本原因，推动该领域的进一步创新。

> Hallucinations in large vision-language models (LVLMs) are a significant challenge, i.e., generating objects that are not presented in the visual input, which impairs their reliability. Recent studies often attribute hallucinations to a lack of understanding of visual input, yet ignore a more fundamental issue: the model's inability to effectively extract or decouple visual features. In this paper, we revisit the hallucinations in LVLMs from an architectural perspective, investigating whether the primary cause lies in the visual encoder (feature extraction) or the modal alignment module (feature decoupling). Motivated by our findings on the preliminary investigation, we propose a novel tuning strategy, PATCH, to mitigate hallucinations in LVLMs. This plug-and-play method can be integrated into various LVLMs, utilizing adaptive virtual tokens to extract object features from bounding boxes, thereby addressing hallucinations caused by insufficient decoupling of visual features. PATCH achieves state-of-the-art performance on multiple multi-modal hallucination datasets. We hope this approach provides researchers with deeper insights into the underlying causes of hallucinations in LVLMs, fostering further advancements and innovation in this field.

[Arxiv](https://arxiv.org/abs/2410.06795)