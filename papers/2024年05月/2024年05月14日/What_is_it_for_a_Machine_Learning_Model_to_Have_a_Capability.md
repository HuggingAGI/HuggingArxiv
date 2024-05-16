# 机器学习模型的能力究竟指何物？这关乎其内在潜能与应用效能的展现。

发布时间：2024年05月14日

`LLM理论

这篇论文探讨了大型语言模型（LLMs）的能力评估问题，并提出了模型能力的条件分析（CAMA）。它不仅关注模型的实际表现，还深入探讨了模型能力的理论基础和评估标准。这与LLM的理论研究相关，因为它试图定义和理解模型能力的概念，而不是专注于特定的应用或攻击方法。因此，它属于LLM理论分类。` `机器学习` `模型评估`

> What is it for a Machine Learning Model to Have a Capability?

# 摘要

> 当代ML模型能做什么？这个问题对于社会中广泛应用ML模型的各种利益相关者至关重要。评估模型能力已成为现代ML的关键领域，得益于监管和政府资助。然而，我们对于ML模型能力的理解尚浅：当我们说模型能做某事时，我们究竟在表达什么？哪些证据与此相关？本文以LLMs为例，探讨这些问题。我们借鉴哲学文献，提出ML模型能力的解释，并提出模型能力的条件分析（CAMA）：简言之，模型具备做X的能力，当且仅当它在尝试时能可靠地成功完成X。本文的主要贡献是在ML背景下精确化CAMA，并将其应用于LLMs。我们进一步展示CAMA如何帮助理解模型评估实践，并提出公平比较模型的方法。

> What can contemporary machine learning (ML) models do? Given the proliferation of ML models in society, answering this question matters to a variety of stakeholders, both public and private. The evaluation of models' capabilities is rapidly emerging as a key subfield of modern ML, buoyed by regulatory attention and government grants. Despite this, the notion of an ML model possessing a capability has not been interrogated: what are we saying when we say that a model is able to do something? And what sorts of evidence bear upon this question? In this paper, we aim to answer these questions, using the capabilities of large language models (LLMs) as a running example. Drawing on the large philosophical literature on abilities, we develop an account of ML models' capabilities which can be usefully applied to the nascent science of model evaluation. Our core proposal is a conditional analysis of model abilities (CAMA): crudely, a machine learning model has a capability to X just when it would reliably succeed at doing X if it 'tried'. The main contribution of the paper is making this proposal precise in the context of ML, resulting in an operationalisation of CAMA applicable to LLMs. We then put CAMA to work, showing that it can help make sense of various features of ML model evaluation practice, as well as suggest procedures for performing fair inter-model comparisons.

[Arxiv](https://arxiv.org/abs/2405.08989)