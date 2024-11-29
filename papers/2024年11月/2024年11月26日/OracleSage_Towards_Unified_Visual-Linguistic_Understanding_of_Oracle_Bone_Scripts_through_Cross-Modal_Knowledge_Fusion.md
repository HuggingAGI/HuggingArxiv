# OracleSage：借助跨模态知识融合达成对甲骨文的统一视觉语言理解

发布时间：2024年11月26日

`LLM应用` `古代文本解读`

> OracleSage: Towards Unified Visual-Linguistic Understanding of Oracle Bone Scripts through Cross-Modal Knowledge Fusion

# 摘要

> 甲骨文（OBS）作为中国最早的成熟书写系统，因其复杂的象形结构及与现代汉字的不同，在自动识别上颇具挑战。我们推出了 OracleSage，这一全新的跨模态框架融合了分层视觉理解和基于图的语义推理。具体而言，我们提出了（1）一个分层视觉语义理解模块，借由逐步微调 LLaVA 的视觉骨干来实现多粒度特征提取；（2）一个基于图的语义推理框架，通过动态消息传递捕捉视觉组件与语义概念的关系；（3）OracleSem，一个具备全面象形和语义注释的语义丰富的甲骨文数据集。实验结果显示，OracleSage 明显优于前沿的视觉语言模型。此项研究为古代文本解读开创了新范式，也为考古研究给予了宝贵的技术支撑。

> Oracle bone script (OBS), as China's earliest mature writing system, present significant challenges in automatic recognition due to their complex pictographic structures and divergence from modern Chinese characters. We introduce OracleSage, a novel cross-modal framework that integrates hierarchical visual understanding with graph-based semantic reasoning. Specifically, we propose (1) a Hierarchical Visual-Semantic Understanding module that enables multi-granularity feature extraction through progressive fine-tuning of LLaVA's visual backbone, (2) a Graph-based Semantic Reasoning Framework that captures relationships between visual components and semantic concepts through dynamic message passing, and (3) OracleSem, a semantically enriched OBS dataset with comprehensive pictographic and semantic annotations. Experimental results demonstrate that OracleSage significantly outperforms state-of-the-art vision-language models. This research establishes a new paradigm for ancient text interpretation while providing valuable technical support for archaeological studies.

[Arxiv](https://arxiv.org/abs/2411.17837)