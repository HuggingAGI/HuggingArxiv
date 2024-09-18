# 多语言模型在非洲低资源语言中的跨语言迁移

发布时间：2024年09月17日

`LLM应用` `低资源语言`

> Cross-lingual transfer of multilingual models on low resource African Languages

# 摘要

> 大型多语言模型在NLP领域取得了显著进展，但其高资源需求和数据偏见引发了对其在低资源语言中有效性的担忧。相比之下，单语模型可能更好地捕捉目标语言的细微差别，提供更准确的结果。本研究对比了单语和多语言模型从高资源语言到低资源语言的跨语言迁移能力，重点关注基尼亚瓦达和基隆迪两种班图语。我们评估了mBERT、AfriBERT等Transformer模型与BiGRU等神经网络模型的性能。AfriBERT在微调后达到88.3%的跨语言准确率，而BiGRU以83.3%的准确率成为最佳神经模型。研究还分析了微调后的遗忘程度。尽管单语模型表现不俗，但多语言模型在资源有限的环境中展现了强大的跨语言迁移能力。

> Large multilingual models have significantly advanced natural language processing (NLP) research. However, their high resource demands and potential biases from diverse data sources have raised concerns about their effectiveness across low-resource languages. In contrast, monolingual models, trained on a single language, may better capture the nuances of the target language, potentially providing more accurate results. This study benchmarks the cross-lingual transfer capabilities from a high-resource language to a low-resource language for both, monolingual and multilingual models, focusing on Kinyarwanda and Kirundi, two Bantu languages. We evaluate the performance of transformer based architectures like Multilingual BERT (mBERT), AfriBERT, and BantuBERTa against neural-based architectures such as BiGRU, CNN, and char-CNN. The models were trained on Kinyarwanda and tested on Kirundi, with fine-tuning applied to assess the extent of performance improvement and catastrophic forgetting. AfriBERT achieved the highest cross-lingual accuracy of 88.3% after fine-tuning, while BiGRU emerged as the best-performing neural model with 83.3% accuracy. We also analyze the degree of forgetting in the original language post-fine-tuning. While monolingual models remain competitive, this study highlights that multilingual models offer strong cross-lingual transfer capabilities in resource limited settings.

[Arxiv](https://arxiv.org/abs/2409.10965)