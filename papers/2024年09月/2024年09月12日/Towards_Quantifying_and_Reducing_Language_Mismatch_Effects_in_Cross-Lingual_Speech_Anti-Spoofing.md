# 量化并减少跨语言语音反欺骗中的语言不匹配效应

发布时间：2024年09月12日

`LLM应用` `语音识别`

> Towards Quantifying and Reducing Language Mismatch Effects in Cross-Lingual Speech Anti-Spoofing

# 摘要

> 语言不匹配对语音反欺骗系统的影响尚未得到充分研究。现有数据集多为英语，获取多语言数据的高成本限制了语言无关模型的训练。我们评估了在英语数据上训练但在其他语言上测试的顶级系统，发现性能显著下降。为此，我们提出了一种创新方法——ACCENT，通过TTS技术引入多样语言知识，提升单语模型的跨语言能力。我们在包含300多万样本的大规模数据集上进行实验，结果显示，ACCENT显著减少了15%以上的语言不匹配效应。这一简单易行的方法在多语言和低资源语言场景中展现出巨大潜力。

> The effects of language mismatch impact speech anti-spoofing systems, while investigations and quantification of these effects remain limited. Existing anti-spoofing datasets are mainly in English, and the high cost of acquiring multilingual datasets hinders training language-independent models. We initiate this work by evaluating top-performing speech anti-spoofing systems that are trained on English data but tested on other languages, observing notable performance declines. We propose an innovative approach - Accent-based data expansion via TTS (ACCENT), which introduces diverse linguistic knowledge to monolingual-trained models, improving their cross-lingual capabilities. We conduct experiments on a large-scale dataset consisting of over 3 million samples, including 1.8 million training samples and nearly 1.2 million testing samples across 12 languages. The language mismatch effects are preliminarily quantified and remarkably reduced over 15% by applying the proposed ACCENT. This easily implementable method shows promise for multilingual and low-resource language scenarios.

[Arxiv](https://arxiv.org/abs/2409.08346)