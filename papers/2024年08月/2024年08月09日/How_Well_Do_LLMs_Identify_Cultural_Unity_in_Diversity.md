# LLMs 在辨识多元文化中的共性上表现如何？

发布时间：2024年08月09日

`LLM应用` `文化研究` `人工智能`

> How Well Do LLMs Identify Cultural Unity in Diversity?

# 摘要

> 在探讨大型语言模型 (LLM) 的文化意识时，多数研究聚焦于模型对地理文化多样性的敏感度。然而，跨文化之间不仅有差异，更有共通之处。例如，美国的婚纱面纱与中国的红盖头在文化意义上有着相似的角色。本研究中，我们推出了一个名为 CUNIT 的基准数据集，旨在评估仅解码器 LLM 对文化概念统一性的理解。CUNIT 包含了跨越 10 个国家、基于 285 个传统文化特定概念构建的 1,425 个评估样本。通过系统地手动标注每个概念的文化相关特征，我们计算了跨文化概念对之间的文化关联度。基于此，我们设计了一项对比匹配任务，用以测试 LLM 识别高度关联跨文化概念对的能力。我们评估了 3 个强大的 LLM，采用了 3 种流行的提示策略，在提供全部或不提供任何提取概念特征的情况下进行测试。令人惊讶的是，我们发现国家间的文化关联在服装概念与食物概念上存在显著差异。分析表明，LLM 在捕捉跨文化概念关联方面仍不及人类，且地理文化接近度对模型性能的影响甚微。

> Much work on the cultural awareness of large language models (LLMs) focuses on the models' sensitivity to geo-cultural diversity. However, in addition to cross-cultural differences, there also exists common ground across cultures. For instance, a bridal veil in the United States plays a similar cultural-relevant role as a honggaitou in China. In this study, we introduce a benchmark dataset CUNIT for evaluating decoder-only LLMs in understanding the cultural unity of concepts. Specifically, CUNIT consists of 1,425 evaluation examples building upon 285 traditional cultural-specific concepts across 10 countries. Based on a systematic manual annotation of cultural-relevant features per concept, we calculate the cultural association between any pair of cross-cultural concepts. Built upon this dataset, we design a contrastive matching task to evaluate the LLMs' capability to identify highly associated cross-cultural concept pairs. We evaluate 3 strong LLMs, using 3 popular prompting strategies, under the settings of either giving all extracted concept features or no features at all on CUNIT Interestingly, we find that cultural associations across countries regarding clothing concepts largely differ from food. Our analysis shows that LLMs are still limited to capturing cross-cultural associations between concepts compared to humans. Moreover, geo-cultural proximity shows a weak influence on model performance in capturing cross-cultural associations.

[Arxiv](https://arxiv.org/abs/2408.05102)