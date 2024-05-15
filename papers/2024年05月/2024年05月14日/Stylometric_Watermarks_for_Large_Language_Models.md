# 大型语言模型风格水印：为LLM嵌入独特标识，确保内容来源的可追溯性与安全性。

发布时间：2024年05月14日

`LLM应用

这篇论文探讨了在大型语言模型（LLM）生成的文本中嵌入水印的方法，以区分人机文本。这种方法通过调整生成过程中的令牌概率来融入语言特征，并采用了特定的技术（如acrostica和感觉运动规范）来增强水印的鲁棒性。论文的评估结果表明，该方法在误报和误检率方面表现出色，这对于确保LLM的责任归属和防范社会风险具有重要意义。因此，这篇论文属于LLM应用类别，因为它关注的是LLM技术在实际应用中的一个具体问题和解决方案。` `内容安全`

> Stylometric Watermarks for Large Language Models

# 摘要

> 随着LLMs技术的飞速发展，区分人机文本的难度日益增加。为此，我们提出了一种创新的水印生成方法，通过调整生成过程中的令牌概率，巧妙地融入语言特征，如文体学。我们引入了acrostica和感觉运动规范，并采用每句更新的密钥进行参数化，利用语义零射分类增强其鲁棒性。评估显示，三句以上时，该方法的误报和误检率低至0.02，即使在面对循环翻译攻击时，七句以上也能保持类似效果。这项研究对于专有LLMs具有重要意义，有助于确保责任归属并防范潜在的社会风险。

> The rapid advancement of large language models (LLMs) has made it increasingly difficult to distinguish between text written by humans and machines. Addressing this, we propose a novel method for generating watermarks that strategically alters token probabilities during generation. Unlike previous works, this method uniquely employs linguistic features such as stylometry. Concretely, we introduce acrostica and sensorimotor norms to LLMs. Further, these features are parameterized by a key, which is updated every sentence. To compute this key, we use semantic zero shot classification, which enhances resilience. In our evaluation, we find that for three or more sentences, our method achieves a false positive and false negative rate of 0.02. For the case of a cyclic translation attack, we observe similar results for seven or more sentences. This research is of particular of interest for proprietary LLMs to facilitate accountability and prevent societal harm.

[Arxiv](https://arxiv.org/abs/2405.08400)