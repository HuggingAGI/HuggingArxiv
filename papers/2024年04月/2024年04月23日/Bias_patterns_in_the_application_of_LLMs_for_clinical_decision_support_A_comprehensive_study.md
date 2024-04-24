# 探究大型语言模型在临床决策支持应用中的偏见模式：一项深入的综合研究。

发布时间：2024年04月23日

`分类：LLM应用

这篇论文主要关注大型语言模型（LLMs）在临床决策支持中的应用，以及它们可能表现出的社会偏见问题。研究者们对多个主流的LLMs进行了评估，分析了不同人口统计特征对LLMs输出的影响，并探讨了模型架构、提示策略等因素如何影响这些偏见。此外，论文还研究了如何通过特定的表述方式和反思型方法减少偏见结果。这些研究内容都与LLMs在实际应用中的表现和潜在问题密切相关，因此将其归类为LLM应用。` `人工智能`

> Bias patterns in the application of LLMs for clinical decision support: A comprehensive study

# 摘要

> 大型语言模型（LLMs）正成为辅助临床决策的强大工具。然而，随着它们在数字医疗领域的日益重要，也带来了两个主要的担忧：一是LLMs可能基于患者的敏感属性（例如种族）表现出多大程度的社会偏见；二是设计决策（如模型架构和提示策略）如何影响这些偏见。为了深入探讨这些问题，我们对八个主流的LLMs进行了评估，这些评估覆盖了三个问答（QA）数据集，并使用了标准化的临床案例（患者描述）进行偏见评估。我们采用对抗性策略，分析了不同人口统计特征对LLMs输出的影响，并对比了通用模型与专门针对临床训练的模型。我们的广泛实验发现了受保护群体之间的多种差异，其中一些差异非常明显。我们还发现了一些反直觉的现象，比如模型规模更大并不一定意味着偏见更小，以及针对医学数据进行微调的模型并不总比通用模型表现更佳。此外，我们的研究还揭示了提示设计对偏见模式的影响，并指出特定的表述方式可以改变偏见模式，而反思型方法（如思维链）能有效减少偏见结果。与以往的研究一致，我们呼吁对应用于临床决策支持的LLMs进行更多的评估、审查和改进。

> Large Language Models (LLMs) have emerged as powerful candidates to inform clinical decision-making processes. While these models play an increasingly prominent role in shaping the digital landscape, two growing concerns emerge in healthcare applications: 1) to what extent do LLMs exhibit social bias based on patients' protected attributes (like race), and 2) how do design choices (like architecture design and prompting strategies) influence the observed biases? To answer these questions rigorously, we evaluated eight popular LLMs across three question-answering (QA) datasets using clinical vignettes (patient descriptions) standardized for bias evaluations. We employ red-teaming strategies to analyze how demographics affect LLM outputs, comparing both general-purpose and clinically-trained models. Our extensive experiments reveal various disparities (some significant) across protected groups. We also observe several counter-intuitive patterns such as larger models not being necessarily less biased and fined-tuned models on medical data not being necessarily better than the general-purpose models. Furthermore, our study demonstrates the impact of prompt design on bias patterns and shows that specific phrasing can influence bias patterns and reflection-type approaches (like Chain of Thought) can reduce biased outcomes effectively. Consistent with prior studies, we call on additional evaluations, scrutiny, and enhancement of LLMs used in clinical decision support applications.

[Arxiv](https://arxiv.org/abs/2404.15149)