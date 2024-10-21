# 探索跨文化机器翻译，借助多语言知识图谱的检索增强生成技术

发布时间：2024年10月17日

`LLM应用` `跨文化交流`

> Towards Cross-Cultural Machine Translation with Retrieval-Augmented Generation from Multilingual Knowledge Graphs

# 摘要

> 翻译包含实体名称的文本极具挑战，因为文化参考在不同语言间差异巨大。这些差异还可能源于转译，即不仅仅是音译和逐字翻译的适应过程。本文从两方面解决跨文化翻译问题：首先，我们推出了 XC-Translate，这是首个专注于文化微妙实体名称的大规模手动创建的机器翻译基准；其次，我们提出了 KG-MT，一种通过密集检索机制将多语言知识图谱信息整合到神经机器翻译模型中的创新方法。实验显示，现有机器翻译系统和大型语言模型在处理此类文本时仍显吃力，而 KG-MT 则大幅领先，分别比 NLLB-200 和 GPT-4 提升了 129% 和 62%。

> Translating text that contains entity names is a challenging task, as cultural-related references can vary significantly across languages. These variations may also be caused by transcreation, an adaptation process that entails more than transliteration and word-for-word translation. In this paper, we address the problem of cross-cultural translation on two fronts: (i) we introduce XC-Translate, the first large-scale, manually-created benchmark for machine translation that focuses on text that contains potentially culturally-nuanced entity names, and (ii) we propose KG-MT, a novel end-to-end method to integrate information from a multilingual knowledge graph into a neural machine translation model by leveraging a dense retrieval mechanism. Our experiments and analyses show that current machine translation systems and large language models still struggle to translate texts containing entity names, whereas KG-MT outperforms state-of-the-art approaches by a large margin, obtaining a 129% and 62% relative improvement compared to NLLB-200 and GPT-4, respectively.

[Arxiv](https://arxiv.org/abs/2410.14057)