# 零-shot POS 标注：在实际应用中是否有效？

发布时间：2024年10月14日

`LLM应用` `语言学`

> Recipe for Zero-shot POS Tagging: Is It Useful in Realistic Scenarios?

# 摘要

> POS 标注在众多应用中至关重要。尽管在资源充足时，POS 标注器表现优异，但在数据有限或缺失时则表现不佳。本文探讨了数据有限语言的 POS 标注问题。我们致力于找出无需目标语言标注数据即可训练 POS 模型的数据集特征，即零-shot 方法。我们比较了在相关语言上微调的多语言模型 (mBERT) 与直接在目标语言上训练的模型的准确性，涉及三种低资源语言。研究显示，准确的数据集选择对零-shot POS 标注至关重要，尤其是语言关系紧密和高品质数据集能带来最佳效果。对于极度低资源的语言，零-shot 模型提供了一个可行的解决方案。

> POS tagging plays a fundamental role in numerous applications. While POS taggers are highly accurate in well-resourced settings, they lag behind in cases of limited or missing training data. This paper focuses on POS tagging for languages with limited data. We seek to identify the characteristics of datasets that make them favourable for training POS tagging models without using any labelled training data from the target language. This is a zero-shot approach. We compare the accuracies of a multilingual large language model (mBERT) fine-tuned on one or more languages related to the target language. Additionally, we compare these results with models trained directly on the target language itself. We do this for three target low-resource languages. Our research highlights the importance of accurate dataset selection for effective zero-shot POS tagging. Particularly, a strong linguistic relationship and high-quality datasets ensure optimal results. For extremely low-resource languages, zero-shot models prove to be a viable option.

[Arxiv](https://arxiv.org/abs/2410.10576)