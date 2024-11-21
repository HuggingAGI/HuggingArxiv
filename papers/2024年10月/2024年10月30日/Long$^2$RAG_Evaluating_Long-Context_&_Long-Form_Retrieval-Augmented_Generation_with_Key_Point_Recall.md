# Long$^2$RAG：通过关键点召回对长上下文和长格式的检索增强生成进行评估

发布时间：2024年10月30日

`RAG` `语言模型` `评估基准`

> Long$^2$RAG: Evaluating Long-Context & Long-Form Retrieval-Augmented Generation with Key Point Recall

# 摘要

> 检索增强生成（RAG）是解决大型语言模型（LLMs）固定知识局限性的颇具前景的办法。然而，当下评估 RAG 系统的基准存在两大关键缺陷：其一，因缺乏能体现检索文档特征的数据集，无法充分衡量 LLMs 处理长上下文检索的能力；其二，缺少评估 LLMs 生成有效利用检索信息的长形式响应能力的综合评估方法。为弥补这些不足，我们推出了 Long$^2$RAG 基准和关键要点召回（KPR）指标。Long$^2$RAG 涵盖 280 个问题，涉及 10 个领域和 8 个问题类别，每个问题都与 5 个平均长度为 2444 个单词的检索文档相关。KPR 评估 LLMs 将从检索文档中提取的关键要点融入其生成响应的程度，为其利用检索信息的能力提供更精细的评估。

> Retrieval-augmented generation (RAG) is a promising approach to address the limitations of fixed knowledge in large language models (LLMs). However, current benchmarks for evaluating RAG systems suffer from two key deficiencies: (1) they fail to adequately measure LLMs' capability in handling long-context retrieval due to a lack of datasets that reflect the characteristics of retrieved documents, and (2) they lack a comprehensive evaluation method for assessing LLMs' ability to generate long-form responses that effectively exploits retrieved information. To address these shortcomings, we introduce the Long$^2$RAG benchmark and the Key Point Recall (KPR) metric. Long$^2$RAG comprises 280 questions spanning 10 domains and across 8 question categories, each associated with 5 retrieved documents with an average length of 2,444 words. KPR evaluates the extent to which LLMs incorporate key points extracted from the retrieved documents into their generated responses, providing a more nuanced assessment of their ability to exploit retrieved information.

[Arxiv](https://arxiv.org/abs/2410.23000)