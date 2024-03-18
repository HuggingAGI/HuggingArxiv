# [MM1 探究了多模态 LLM 预训练中的方法策略、深度分析及其带来的独到见解。]

发布时间：2024年03月14日

`LLM应用` `多模态`

> MM1: Methods, Analysis & Insights from Multimodal LLM Pre-training

> 本文研究了如何构建高效能的多模态大型语言模型（MLLMs），着重分析了架构组件和数据选择的关键作用。通过详尽的消融实验，我们发现将精心搭配的图像标题、交织图像文本和纯文本数据用于大规模预训练是实现跨多个基准的SOTA少量样本性能的关键。同时揭示出，相比视觉-语言连接器设计，图像编码器及其对应的图像分辨率和图像令牌数量对模型性能影响显著。基于这些发现，我们进一步扩展了这一方法论，打造出MM1系列多模态模型，包括稠密型和混合专家（MoE）变种，参数量最高可达300亿，不仅在预训练指标上傲视群雄，而且在多种权威多模态基准测试上经过监督微调后的性能同样出色。得益于大规模预训练的优势，MM1赋予了诸如提升上下文学习及处理多幅图像推理的能力，使得其能够在少量样本情况下执行链式思维提示任务。

> In this work, we discuss building performant Multimodal Large Language Models (MLLMs). In particular, we study the importance of various architecture components and data choices. Through careful and comprehensive ablations of the image encoder, the vision language connector, and various pre-training data choices, we identified several crucial design lessons. For example, we demonstrate that for large-scale multimodal pre-training using a careful mix of image-caption, interleaved image-text, and text-only data is crucial for achieving state-of-the-art (SOTA) few-shot results across multiple benchmarks, compared to other published pre-training results. Further, we show that the image encoder together with image resolution and the image token count has substantial impact, while the vision-language connector design is of comparatively negligible importance. By scaling up the presented recipe, we build MM1, a family of multimodal models up to 30B parameters, consisting of both dense models and mixture-of-experts (MoE) variants, that are SOTA in pre-training metrics and achieve competitive performance after supervised fine-tuning on a range of established multimodal benchmarks. Thanks to large-scale pre-training, MM1 enjoys appealing properties such as enhanced in-context learning, and multi-image reasoning, enabling few-shot chain-of-thought prompting.

[Arxiv](https://arxiv.org/abs/2403.09611)