# 利用大型语言模型（LLM）从文本中生成特征，助力可解释的机器学习

发布时间：2024年09月11日

`LLM应用` `科学研究` `文本分类`

> LLM-based feature generation from text for interpretable machine learning

# 摘要

> 现有的文本表示方法，如嵌入和词袋模型，由于高维度和特征级可解释性的缺失或疑问，不适合规则学习。本文探讨了大型语言模型 (LLM) 是否能通过提取少量可解释特征来解决这一问题。我们在包含数千篇科学文章的两个数据集（CORD-19 和 M17+）上展示了这一过程，目标是对研究影响进行代理。评估结果显示，LLama 2 生成的特征在语义上有效。我们使用这些特征进行文本分类，预测引用率和专家评分。基于 LLM 生成特征训练的模型在科学文本上的预测性能与最先进的 SciBERT 相当。LLM 仅用 62 个特征，而 SciBERT 用 768 个，且 LLM 的特征直接对应于文章的方法论严谨性、新颖性或语法正确性等概念。最后，我们提取了一组高度可解释的操作规则。在两个主题多样化的数据集上使用相同 LLM 特征集获得的持续竞争性结果表明，这种方法在不同领域中具有普遍性。

> Existing text representations such as embeddings and bag-of-words are not suitable for rule learning due to their high dimensionality and absent or questionable feature-level interpretability. This article explores whether large language models (LLMs) could address this by extracting a small number of interpretable features from text. We demonstrate this process on two datasets (CORD-19 and M17+) containing several thousand scientific articles from multiple disciplines and a target being a proxy for research impact. An evaluation based on testing for the statistically significant correlation with research impact has shown that LLama 2-generated features are semantically meaningful. We consequently used these generated features in text classification to predict the binary target variable representing the citation rate for the CORD-19 dataset and the ordinal 5-class target representing an expert-awarded grade in the M17+ dataset. Machine-learning models trained on the LLM-generated features provided similar predictive performance to the state-of-the-art embedding model SciBERT for scientific text. The LLM used only 62 features compared to 768 features in SciBERT embeddings, and these features were directly interpretable, corresponding to notions such as article methodological rigor, novelty, or grammatical correctness. As the final step, we extract a small number of well-interpretable action rules. Consistently competitive results obtained with the same LLM feature set across both thematically diverse datasets show that this approach generalizes across domains.

[Arxiv](https://arxiv.org/abs/2409.07132)