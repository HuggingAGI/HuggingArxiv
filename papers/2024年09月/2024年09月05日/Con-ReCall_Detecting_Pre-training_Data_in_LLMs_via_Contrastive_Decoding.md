# Con-ReCall：利用对比解码技术，精准检测 LLM 中的预训练数据。

发布时间：2024年09月05日

`LLM理论` `网络安全` `数据隐私`

> Con-ReCall: Detecting Pre-training Data in LLMs via Contrastive Decoding

# 摘要

> 大型语言模型的训练数据虽是其成功的关键，但也潜藏隐私与安全风险，因其可能包含敏感信息。检测预训练数据对缓解这些风险至关重要。现有方法多孤立分析目标文本或仅依赖非成员上下文，忽略了同时考虑成员与非成员上下文的价值。尽管先前研究认为成员上下文因微小分布偏移而信息量有限，我们的分析却揭示，对比非成员上下文时，这些微妙偏移可被有效利用。本文提出 Con-ReCall，通过对比解码利用成员与非成员上下文的非对称分布偏移，放大微小差异以提升成员推断。实证评估显示，Con-ReCall 在 WikiMIA 基准上表现卓越，且能抵御多种文本操纵技术。

> The training data in large language models is key to their success, but it also presents privacy and security risks, as it may contain sensitive information. Detecting pre-training data is crucial for mitigating these concerns. Existing methods typically analyze target text in isolation or solely with non-member contexts, overlooking potential insights from simultaneously considering both member and non-member contexts. While previous work suggested that member contexts provide little information due to the minor distributional shift they induce, our analysis reveals that these subtle shifts can be effectively leveraged when contrasted with non-member contexts. In this paper, we propose Con-ReCall, a novel approach that leverages the asymmetric distributional shifts induced by member and non-member contexts through contrastive decoding, amplifying subtle differences to enhance membership inference. Extensive empirical evaluations demonstrate that Con-ReCall achieves state-of-the-art performance on the WikiMIA benchmark and is robust against various text manipulation techniques.

[Arxiv](https://arxiv.org/abs/2409.03363)