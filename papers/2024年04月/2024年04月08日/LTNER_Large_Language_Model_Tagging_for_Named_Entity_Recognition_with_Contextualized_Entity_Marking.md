# LTNER：一种大型语言模型，通过情境化标记技术，专门用于命名实体的识别。

发布时间：2024年04月08日

`LLM应用` `实体识别`

> LTNER: Large Language Model Tagging for Named Entity Recognition with Contextualized Entity Marking

# 摘要

> 近两年，大型语言模型在自然语言处理领域的应用日益受到青睐，归功于其出色的上下文理解与学习能力，引发了学术界与产业界的广泛关注。尽管如此，在命名实体识别等特定 NLP 任务上，LLM 相较于监督学习仍有提升空间。我们研究团队打造了 LTNER 框架，引入创新的上下文化实体标记技术，结合经济高效的 GPT-3.5 与无需额外训练的上下文学习，大幅提升了 LLM 在 NER 任务的准确度。CoNLL03 数据集的 F1 得分从 85.9% 跃升至 91.9%，几近监督学习微调的水平。这一突破性成果深化了我们对 LLM 潜能的认识。

> The use of LLMs for natural language processing has become a popular trend in the past two years, driven by their formidable capacity for context comprehension and learning, which has inspired a wave of research from academics and industry professionals. However, for certain NLP tasks, such as NER, the performance of LLMs still falls short when compared to supervised learning methods. In our research, we developed a NER processing framework called LTNER that incorporates a revolutionary Contextualized Entity Marking Gen Method. By leveraging the cost-effective GPT-3.5 coupled with context learning that does not require additional training, we significantly improved the accuracy of LLMs in handling NER tasks. The F1 score on the CoNLL03 dataset increased from the initial 85.9% to 91.9%, approaching the performance of supervised fine-tuning. This outcome has led to a deeper understanding of the potential of LLMs.

[Arxiv](https://arxiv.org/abs/2404.05624)