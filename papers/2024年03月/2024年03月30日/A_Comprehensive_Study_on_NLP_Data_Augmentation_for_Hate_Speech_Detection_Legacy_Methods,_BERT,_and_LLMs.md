# 本研究深入探讨了自然语言处理领域中仇恨言论检测的数据增强技术，涵盖了传统方法、BERT 以及大型语言模型（LLMs）的应用。

发布时间：2024年03月30日

`LLM应用` `社交媒体`

> A Comprehensive Study on NLP Data Augmentation for Hate Speech Detection: Legacy Methods, BERT, and LLMs

# 摘要

> 自然语言处理领域对数据增强的兴趣激增，旨在应对仇恨言论的挑战、社交媒体词汇的多变性，以及大规模神经网络对大量训练数据的需求。但数据增强中常用的词汇替换可能意外改变原意，影响监督学习模型的效果。本研究尝试了从传统方法到现代实践，如大型语言模型（LLM），包括GPT在仇恨言论检测中的应用。我们还提出了一种改进的基于BERT的编码器模型，结合上下文余弦相似度过滤，以解决传统同义词替换的不足。通过对比五种流行技术：WordNet和Fast-Text的同义词替换、回译、BERT掩码增强和LLM，我们发现传统回译技术标签改变率低（0.3-1.5%），而BERT的上下文同义词替换虽丰富句子多样性，却增加了标签改变率（超6%）。我们的方法将标签改变率降至0.05%，F1性能提升0.7%。使用GPT-3增强数据，不仅避免了数据量增加七倍导致的过拟合，还提高了15%的嵌入空间覆盖率和1.4%的分类F1分数，相较于传统方法，甚至比我们的方法高出0.8%。

> The surge of interest in data augmentation within the realm of NLP has been driven by the need to address challenges posed by hate speech domains, the dynamic nature of social media vocabulary, and the demands for large-scale neural networks requiring extensive training data. However, the prevalent use of lexical substitution in data augmentation has raised concerns, as it may inadvertently alter the intended meaning, thereby impacting the efficacy of supervised machine learning models. In pursuit of suitable data augmentation methods, this study explores both established legacy approaches and contemporary practices such as Large Language Models (LLM), including GPT in Hate Speech detection. Additionally, we propose an optimized utilization of BERT-based encoder models with contextual cosine similarity filtration, exposing significant limitations in prior synonym substitution methods. Our comparative analysis encompasses five popular augmentation techniques: WordNet and Fast-Text synonym replacement, Back-translation, BERT-mask contextual augmentation, and LLM. Our analysis across five benchmarked datasets revealed that while traditional methods like back-translation show low label alteration rates (0.3-1.5%), and BERT-based contextual synonym replacement offers sentence diversity but at the cost of higher label alteration rates (over 6%). Our proposed BERT-based contextual cosine similarity filtration markedly reduced label alteration to just 0.05%, demonstrating its efficacy in 0.7% higher F1 performance. However, augmenting data with GPT-3 not only avoided overfitting with up to sevenfold data increase but also improved embedding space coverage by 15% and classification F1 score by 1.4% over traditional methods, and by 0.8% over our method.

[Arxiv](https://arxiv.org/abs/2404.00303)