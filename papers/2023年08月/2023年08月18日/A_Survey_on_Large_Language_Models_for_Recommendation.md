# 大型语言模型推荐应用综述

发布时间：2023年08月18日

`LLM应用

这篇论文摘要主要讨论了大型语言模型（LLMs）在推荐系统（RS）领域的应用，包括如何通过自监督学习处理大量数据，以及如何通过微调、提示调整等技术提升推荐系统的性能。论文还对基于LLM的推荐系统进行了分类，并分析了各自的方法、技术和性能。此外，论文还指出了关键挑战和重要发现，并为研究者和实践者提供了资源和启示。因此，这篇论文属于LLM应用类别。` `推荐系统`

> A Survey on Large Language Models for Recommendation

# 摘要

> 大型语言模型（LLMs）在自然语言处理（NLP）领域崭露头角，并在推荐系统（RS）领域引起了广泛关注。这些模型通过自监督学习处理海量数据，展现了在通用表示学习上的卓越能力，并有望通过微调、提示调整等迁移技术，全面提升推荐系统的性能。利用LLMs提升推荐质量的关键在于其对文本特征的精准捕捉和对外部知识的广泛涵盖，从而精准连接用户与物品。本综述首次系统地将基于LLM的推荐系统分为判别型（DLLM4Rec）和生成型（GLLM4Rec）两大类，并对每类系统的方法、技术和性能进行了深入分析。此外，我们还揭示了关键挑战和重要发现，为研究者和实践者提供了宝贵的启示。为了方便研究，我们还在GitHub上建立了一个仓库，专门索引与LLMs推荐相关的论文，地址为：https://github.com/WLiK/LLM4Rec。

> Large Language Models (LLMs) have emerged as powerful tools in the field of Natural Language Processing (NLP) and have recently gained significant attention in the domain of Recommendation Systems (RS). These models, trained on massive amounts of data using self-supervised learning, have demonstrated remarkable success in learning universal representations and have the potential to enhance various aspects of recommendation systems by some effective transfer techniques such as fine-tuning and prompt tuning, and so on. The crucial aspect of harnessing the power of language models in enhancing recommendation quality is the utilization of their high-quality representations of textual features and their extensive coverage of external knowledge to establish correlations between items and users. To provide a comprehensive understanding of the existing LLM-based recommendation systems, this survey presents a taxonomy that categorizes these models into two major paradigms, respectively Discriminative LLM for Recommendation (DLLM4Rec) and Generative LLM for Recommendation (GLLM4Rec), with the latter being systematically sorted out for the first time. Furthermore, we systematically review and analyze existing LLM-based recommendation systems within each paradigm, providing insights into their methodologies, techniques, and performance. Additionally, we identify key challenges and several valuable findings to provide researchers and practitioners with inspiration. We have also created a GitHub repository to index relevant papers on LLMs for recommendation, https://github.com/WLiK/LLM4Rec.

[Arxiv](https://arxiv.org/abs/2305.19860)