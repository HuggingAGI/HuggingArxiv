# 大型语言模型推荐中的提示驱动表示学习方法

发布时间：2024年09月25日

`LLM应用` `推荐系统`

> A Prompting-Based Representation Learning Method for Recommendation with Large Language Models

# 摘要

> 近年来，随着NLP领域中LLM的兴起，推荐系统迎来了革命性的变化。GPT-3.5/4、Llama等模型展现了非凡的文本理解和生成能力。这些LLM的广泛预训练信息，使得从用户和项目的多维上下文中提取深层次语义成为可能。尽管LLM潜力巨大，但如何从上下文信息中精准捕捉用户-项目偏好，并将其有效应用于推荐系统的提升，仍是一个亟待解决的问题。我们坚信，深入理解用户或项目本身是提升推荐效果的关键。为此，我们利用最先进的LLM生成详尽的用户档案。为增强LLM在推荐系统中的表现，我们提出了基于提示的推荐表示学习方法（P4R）。在P4R框架中，我们通过LLM提示策略定制项目档案，并利用预训练的BERT模型将其转化为语义空间。同时，结合图卷积网络（GCN）进行协同过滤。P4R框架通过整合这两大嵌入空间，有效应对推荐任务。在评估中，我们对比了P4R与顶尖推荐模型，验证了基于提示的档案生成的高效性。

> In recent years, Recommender Systems (RS) have witnessed a transformative shift with the advent of Large Language Models (LLMs) in the field of Natural Language Processing (NLP). Models such as GPT-3.5/4, Llama, have demonstrated unprecedented capabilities in understanding and generating human-like text. The extensive information pre-trained by these LLMs allows for the potential to capture a more profound semantic representation from different contextual information of users and items.
  While the great potential lies behind the thriving of LLMs, the challenge of leveraging user-item preferences from contextual information and its alignment with the improvement of Recommender Systems needs to be addressed. Believing that a better understanding of the user or item itself can be the key factor in improving recommendation performance, we conduct research on generating informative profiles using state-of-the-art LLMs.
  To boost the linguistic abilities of LLMs in Recommender Systems, we introduce the Prompting-Based Representation Learning Method for Recommendation (P4R). In our P4R framework, we utilize the LLM prompting strategy to create personalized item profiles. These profiles are then transformed into semantic representation spaces using a pre-trained BERT model for text embedding. Furthermore, we incorporate a Graph Convolution Network (GCN) for collaborative filtering representation. The P4R framework aligns these two embedding spaces in order to address the general recommendation tasks. In our evaluation, we compare P4R with state-of-the-art Recommender models and assess the quality of prompt-based profile generation.

[Arxiv](https://arxiv.org/abs/2409.16674)