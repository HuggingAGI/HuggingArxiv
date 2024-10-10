# LLM 的适应之旅：为何额外预训练有时未能带来提升？

发布时间：2024年10月07日

`LLM理论` `人工智能`

> Adaptation Odyssey in LLMs: Why Does Additional Pretraining Sometimes Fail to Improve?

# 摘要

> 过去十年，深度学习模型的泛化和适应能力常在固定数据集上评估。然而，大型语言模型 (LLM) 则不同，它们 (i) 参数更多，(ii) 在互联网无标签文本上训练，人类干预少，(iii) 在线训练。这些差异使传统深度学习的经验难以应用于 LLM。为此，我们通过实证观察，揭示了预训练模型进一步训练的影响。我们发现，在某一领域训练模型可能降低其在该领域测试集上的表现。进一步分析表明，性能下降与新旧训练数据集的相似性正相关。词元级困惑度分析显示，下降源于少数与领域无关的词元。这些发现有助于我们决定何时调整模型，何时依赖其基础能力。

> In the last decade, the generalization and adaptation abilities of deep learning models were typically evaluated on fixed training and test distributions. Contrary to traditional deep learning, large language models (LLMs) are (i) even more overparameterized, (ii) trained on unlabeled text corpora curated from the Internet with minimal human intervention, and (iii) trained in an online fashion. These stark contrasts prevent researchers from transferring lessons learned on model generalization and adaptation in deep learning contexts to LLMs. To this end, our short paper introduces empirical observations that aim to shed light on further training of already pretrained language models. Specifically, we demonstrate that training a model on a text domain could degrade its perplexity on the test portion of the same domain. We observe with our subsequent analysis that the performance degradation is positively correlated with the similarity between the additional and the original pretraining dataset of the LLM. Our further token-level perplexity observations reveals that the perplexity degradation is due to a handful of tokens that are not informative about the domain. We hope these findings will guide us in determining when to adapt a model vs when to rely on its foundational capabilities.

[Arxiv](https://arxiv.org/abs/2410.05581)