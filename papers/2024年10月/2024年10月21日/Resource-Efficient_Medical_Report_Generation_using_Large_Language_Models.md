# 利用大型语言模型实现资源高效的医疗报告生成

发布时间：2024年10月21日

`LLM应用` `人工智能`

> Resource-Efficient Medical Report Generation using Large Language Models

# 摘要

> 医学报告生成旨在自动编写胸部X光报告，减轻放射科医生的负担，推动医疗领域的临床自动化。我们提出了一种利用视觉支持的大型语言模型（LLM）的新框架，并引入轻量级解决方案，在性能上超越或媲美以往方法。通过探索不同模型大小和增强技术，如前缀调优，我们提升了LLM的文本生成能力。在MIMIC-CXR数据集上的评估显示，我们的框架能高效生成具有高精度和强医学上下文理解的患者特定报告。

> Medical report generation is the task of automatically writing radiology reports for chest X-ray images. Manually composing these reports is a time-consuming process that is also prone to human errors. Generating medical reports can therefore help reduce the burden on radiologists. In other words, we can promote greater clinical automation in the medical domain. In this work, we propose a new framework leveraging vision-enabled Large Language Models (LLM) for the task of medical report generation. We introduce a lightweight solution that achieves better or comparative performance as compared to previous solutions on the task of medical report generation. We conduct extensive experiments exploring different model sizes and enhancement approaches, such as prefix tuning to improve the text generation abilities of the LLMs. We evaluate our approach on a prominent large-scale radiology report dataset - MIMIC-CXR. Our results demonstrate the capability of our resource-efficient framework to generate patient-specific reports with strong medical contextual understanding and high precision.

[Arxiv](https://arxiv.org/abs/2410.15642)