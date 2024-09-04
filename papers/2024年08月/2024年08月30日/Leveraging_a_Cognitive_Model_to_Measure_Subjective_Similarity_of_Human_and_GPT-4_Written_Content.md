# 借助认知模型，我们探究人类与 GPT-4 创作内容的主观相似度。

发布时间：2024年08月30日

`LLM应用` `推荐系统`

> Leveraging a Cognitive Model to Measure Subjective Similarity of Human and GPT-4 Written Content

# 摘要

> 通过大型语言模型（如GPT-4）生成的词嵌入，可以计算文档间的余弦相似度，并应用于多种分类场景。但这种相似度受限于训练LLM的语料库，未必能准确反映个体的主观感受或其偏见与限制对相似度测量的影响。在教育和推荐系统中，由于个体判断有限且偏见显著，缺乏认知感知的个性化相似度尤为棘手。为此，我们结合基于实例的学习（IBL）认知模型与LLM嵌入，开发了基于实例的个性化相似度（IBIS）指标，该指标能基于认知决策机制，考虑个体偏见与约束。我们还创建了一个包含人类对电子邮件危险性分类的数据集，以验证IBIS在教育环境中衡量主观相似度的有效性。

> Cosine similarity between two documents can be computed using token embeddings formed by Large Language Models (LLMs) such as GPT-4, and used to categorize those documents across a range of uses. However, these similarities are ultimately dependent on the corpora used to train these LLMs, and may not reflect subjective similarity of individuals or how their biases and constraints impact similarity metrics. This lack of cognitively-aware personalization of similarity metrics can be particularly problematic in educational and recommendation settings where there is a limited number of individual judgements of category or preference, and biases can be particularly relevant. To address this, we rely on an integration of an Instance-Based Learning (IBL) cognitive model with LLM embeddings to develop the Instance-Based Individualized Similarity (IBIS) metric. This similarity metric is beneficial in that it takes into account individual biases and constraints in a manner that is grounded in the cognitive mechanisms of decision making. To evaluate the IBIS metric, we also introduce a dataset of human categorizations of emails as being either dangerous (phishing) or safe (ham). This dataset is used to demonstrate the benefits of leveraging a cognitive model to measure the subjective similarity of human participants in an educational setting.

[Arxiv](https://arxiv.org/abs/2409.00269)