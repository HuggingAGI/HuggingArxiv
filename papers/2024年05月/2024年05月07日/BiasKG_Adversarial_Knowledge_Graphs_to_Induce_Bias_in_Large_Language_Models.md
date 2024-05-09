# 偏见图谱BiasKG：塑造大型语言模型的对抗性知识网络，旨在引入并研究模型中的偏见现象。

发布时间：2024年05月07日

`LLM理论

这篇论文关注的是大型语言模型（LLM）中的社会偏见问题，并提出了一种基于知识图谱增强的生成方法来揭示和分析这些偏见。它探讨了LLM的安全性和偏见消除的效果，这是一个理论性的研究，因为它不仅关注模型的应用，还深入到模型内部的工作原理和潜在的偏见机制。因此，它属于LLM理论分类。` `人工智能安全` `社会偏见分析`

> BiasKG: Adversarial Knowledge Graphs to Induce Bias in Large Language Models

# 摘要

> 现代LLMs蕴含丰富的世界知识，使其在常识推理和知识密集任务中大放异彩。然而，它们也可能吸收社会偏见，带来潜在的社会风险。尽管已有多种策略试图提升LLM的安全性，但其在消除偏见方面的效果仍不明朗。本研究创新性地提出了一种基于知识图谱增强的生成方法，用以揭示语言模型中的偏见。我们巧妙地将语言中的刻板印象转化为知识图谱，并运用对抗性策略，成功地从多个开源和闭源模型中引出了偏见性回应。令人警醒的是，即使是有安全措施的模型也未能幸免。这凸显了AI安全研究的紧迫性，以及在对抗性领域深入探索的必要性。

> Modern large language models (LLMs) have a significant amount of world knowledge, which enables strong performance in commonsense reasoning and knowledge-intensive tasks when harnessed properly. The language model can also learn social biases, which has a significant potential for societal harm. There have been many mitigation strategies proposed for LLM safety, but it is unclear how effective they are for eliminating social biases. In this work, we propose a new methodology for attacking language models with knowledge graph augmented generation. We refactor natural language stereotypes into a knowledge graph, and use adversarial attacking strategies to induce biased responses from several open- and closed-source language models. We find our method increases bias in all models, even those trained with safety guardrails. This demonstrates the need for further research in AI safety, and further work in this new adversarial space.

[Arxiv](https://arxiv.org/abs/2405.04756)