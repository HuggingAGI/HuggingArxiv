# 探索文本生成之谜：挑战与机遇并存

发布时间：2024年05月14日

`LLM理论

这篇论文关注的是大型语言模型（LLM）的解释性问题，特别是在文本生成任务中的应用。它提出了与解释性AI方法设计与评估相关的挑战，并探讨了这些挑战之间的相互联系。虽然解释性AI方法可以应用于各种模型，包括Agent和RAG，但本文的重点是LLM的理论层面，即如何理解和解释LLM的行为，而不是特定应用或模型的构建。因此，它属于LLM理论分类。` `人工智能解释性`

> Challenges and Opportunities in Text Generation Explainability

# 摘要

> 随着大型语言模型在NLP领域的日益重要，对其解释性的需求也随之增长。文本生成作为自回归模型的核心任务，引起了NLP社区的广泛关注。为此，社区开始探索适用于各种模型的可解释AI方法。然而，这些方法的设计与评估颇具挑战，因为它们受到文本生成过程中多种因素的影响，如模型的随机性。本文列举了17个挑战，分为三类，这些挑战涉及分词、解释相似性定义、标记重要性评估等多个方面。文章强调了这些挑战之间的相互联系，并提出了新的研究方向，如开发概率词级解释方法，以及在解释性流程中引入人类参与，从数据设计到最终评估，以确保对xAI方法的深入理解。

> The necessity for interpretability in natural language processing (NLP) has risen alongside the growing prominence of large language models. Among the myriad tasks within NLP, text generation stands out as a primary objective of autoregressive models. The NLP community has begun to take a keen interest in gaining a deeper understanding of text generation, leading to the development of model-agnostic explainable artificial intelligence (xAI) methods tailored to this task. The design and evaluation of explainability methods are non-trivial since they depend on many factors involved in the text generation process, e.g., the autoregressive model and its stochastic nature. This paper outlines 17 challenges categorized into three groups that arise during the development and assessment of attribution-based explainability methods. These challenges encompass issues concerning tokenization, defining explanation similarity, determining token importance and prediction change metrics, the level of human intervention required, and the creation of suitable test datasets. The paper illustrates how these challenges can be intertwined, showcasing new opportunities for the community. These include developing probabilistic word-level explainability methods and engaging humans in the explainability pipeline, from the data design to the final evaluation, to draw robust conclusions on xAI methods.

[Arxiv](https://arxiv.org/abs/2405.08468)