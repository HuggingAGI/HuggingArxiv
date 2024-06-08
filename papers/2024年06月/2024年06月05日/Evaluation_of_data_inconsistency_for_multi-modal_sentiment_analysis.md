# 评估多模态情感分析中的数据一致性问题

发布时间：2024年06月05日

`Agent

这篇论文主要关注的是多模态情感分析（MSA）中的情感语义不一致问题，以及这种不一致如何影响人工代理（Agent）的预测能力。论文通过引入模态冲突测试集，评估了传统模型和多模态大型语言模型（MLLMs）在处理这种数据时的表现，并指出了这些模型在面对语义冲突时的局限性。因此，这篇论文更符合Agent分类，因为它探讨了人工代理在多模态情感分析中的应用和挑战。` `情感分析` `多模态分析`

> Evaluation of data inconsistency for multi-modal sentiment analysis

# 摘要

> 情感语义不一致在多模态情感分析（MSA）中无处不在，MSA 分析跨多种模态（如文本、音频和视频）的情感表达。由于人类表达的细腻差异，各模态传达的情感方面可能不同，导致不一致，影响人工代理的预测。本研究引入了一个模态冲突测试集，评估了传统模型和多模态大型语言模型（MLLMs）在处理此类数据时的表现。结果显示，传统模型在语义冲突数据面前性能显著下降，而 MLLMs 在多模态情感分析中也显露出不足。我们的研究不仅揭示了这一新挑战，也为情感分析系统的未来发展提供了重要启示。

> Emotion semantic inconsistency is an ubiquitous challenge in multi-modal sentiment analysis (MSA). MSA involves analyzing sentiment expressed across various modalities like text, audio, and videos. Each modality may convey distinct aspects of sentiment, due to subtle and nuanced expression of human beings, leading to inconsistency, which may hinder the prediction of artificial agents. In this work, we introduce a modality conflicting test set and assess the performance of both traditional multi-modal sentiment analysis models and multi-modal large language models (MLLMs). Our findings reveal significant performance degradation across traditional models when confronted with semantically conflicting data and point out the drawbacks of MLLMs when handling multi-modal emotion analysis. Our research presents a new challenge and offer valuable insights for the future development of sentiment analysis systems.

![评估多模态情感分析中的数据一致性问题](../../../paper_images/2406.03004/conflict.png)

![评估多模态情感分析中的数据一致性问题](../../../paper_images/2406.03004/distri.png)

![评估多模态情感分析中的数据一致性问题](../../../paper_images/2406.03004/mllm.png)

[Arxiv](https://arxiv.org/abs/2406.03004)