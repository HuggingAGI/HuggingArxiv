# 大型语言模型的随机性如何影响解释的敏感性？以新闻文本分类为例，探讨这一问题。

发布时间：2024年10月07日

`LLM理论`

> Explanation sensitivity to the randomness of large language models: the case of journalistic text classification

# 摘要

> 大型语言模型（LLM）在多项自然语言处理任务中表现优异，但也带来了可解释性难题。本文探讨了LLM训练中的随机因素如何影响其预测的可解释性，特别是在法语观点性新闻文本分类任务中。通过微调的CamemBERT模型和相关性传播解释方法，我们发现不同随机种子训练的模型虽准确性相近，但解释性各异。因此，我们提出需要分析解释的统计分布，以提升LLM的可解释性。随后，我们研究了一个基于文本特征的简化模型，该模型解释稳定但准确性较低，体现了准确性与可解释性之间的另一种权衡。我们还展示了通过引入CamemBERT解释中的特征，可以提升该简化模型的性能。最后，我们根据研究结果提出了新的研究方向，特别是关于训练随机性中敏感性来源的探讨。

> Large language models (LLMs) perform very well in several natural language processing tasks but raise explainability challenges. In this paper, we examine the effect of random elements in the training of LLMs on the explainability of their predictions. We do so on a task of opinionated journalistic text classification in French. Using a fine-tuned CamemBERT model and an explanation method based on relevance propagation, we find that training with different random seeds produces models with similar accuracy but variable explanations. We therefore claim that characterizing the explanations' statistical distribution is needed for the explainability of LLMs. We then explore a simpler model based on textual features which offers stable explanations but is less accurate. Hence, this simpler model corresponds to a different tradeoff between accuracy and explainability. We show that it can be improved by inserting features derived from CamemBERT's explanations. We finally discuss new research directions suggested by our results, in particular regarding the origin of the sensitivity observed in the training randomness.

[Arxiv](https://arxiv.org/abs/2410.05085)