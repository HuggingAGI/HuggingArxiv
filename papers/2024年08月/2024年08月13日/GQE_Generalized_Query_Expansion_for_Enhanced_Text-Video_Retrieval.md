# GQE：广义查询扩展，旨在提升文本与视频检索的效能。

发布时间：2024年08月13日

`LLM应用` `视频检索` `内容分发`

> GQE: Generalized Query Expansion for Enhanced Text-Video Retrieval

# 摘要

> 随着网络视频内容的迅猛发展，文本与视频之间的检索任务愈发重要，它跨越了文本与视频间的语义鸿沟。本文提出的广义查询扩展（GQE）方法，专注于解决文本与视频信息不平衡的问题，从而提升检索效率。不同于传统方法，GQE在训练与测试阶段均扩展视频相关文本查询，通过视频片段的自适应分割与零-shot字幕生成，丰富训练数据，有效缓解数据不平衡。检索时，GQE借助大型语言模型生成多样化查询，并通过查询选择模块精挑细选，优化检索性能，降低计算负担。我们的研究不仅深入分析了信息不平衡问题，还创新了查询扩展方法，并引入了高效的查询选择策略。GQE在多个权威基准测试中表现卓越，证明了从数据角度出发解决文本-视频检索问题的有效性。

> In the rapidly expanding domain of web video content, the task of text-video retrieval has become increasingly critical, bridging the semantic gap between textual queries and video data. This paper introduces a novel data-centric approach, Generalized Query Expansion (GQE), to address the inherent information imbalance between text and video, enhancing the effectiveness of text-video retrieval systems. Unlike traditional model-centric methods that focus on designing intricate cross-modal interaction mechanisms, GQE aims to expand the text queries associated with videos both during training and testing phases. By adaptively segmenting videos into short clips and employing zero-shot captioning, GQE enriches the training dataset with comprehensive scene descriptions, effectively bridging the data imbalance gap. Furthermore, during retrieval, GQE utilizes Large Language Models (LLM) to generate a diverse set of queries and a query selection module to filter these queries based on relevance and diversity, thus optimizing retrieval performance while reducing computational overhead. Our contributions include a detailed examination of the information imbalance challenge, a novel approach to query expansion in video-text datasets, and the introduction of a query selection strategy that enhances retrieval accuracy without increasing computational costs. GQE achieves state-of-the-art performance on several benchmarks, including MSR-VTT, MSVD, LSMDC, and VATEX, demonstrating the effectiveness of addressing text-video retrieval from a data-centric perspective.

[Arxiv](https://arxiv.org/abs/2408.07249)