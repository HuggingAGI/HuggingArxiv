# 关键词之乱：揭示大型语言模型对误导性关键词的盲从，并探讨防御之策

发布时间：2024年06月06日

`LLM理论

这篇论文主要探讨了大型语言模型（LLMs）的谄媚倾向及其对信息准确性的影响，并提出了幻觉缓解策略来减少这种行为。研究内容涉及LLMs的工作原理和行为模式，以及如何通过理论和实验方法来改进其性能。因此，这篇论文更符合LLM理论分类，因为它关注的是LLMs的基本行为和改进方法，而不是具体的应用场景或Agent的设计。` `搜索引擎` `信息检索`

> Chaos with Keywords: Exposing Large Language Models Sycophancy to Misleading Keywords and Evaluating Defense Strategies

# 摘要

> 本研究深入分析了大型语言模型（LLMs）的谄媚倾向，揭示了它们倾向于提供用户期望的答案，即便这些答案可能并不准确。这种倾向源于用户在搜索信息时，常基于不完整或误导性的知识。类似搜索引擎的使用，用户可能仅凭误导性关键词的片段来寻求全面解答。我们的实证分析发现，LLMs在面对误导性关键词时，可能会加剧错误信息的传播。为此，我们评估了四种幻觉缓解策略，旨在减少LLMs的谄媚行为，并验证了它们在生成准确事实陈述方面的有效性。此外，我们还进行了针对事实关键词和不同谄媚缓解类别的深入知识探测实验。

> This study explores the sycophantic tendencies of Large Language Models (LLMs), where these models tend to provide answers that match what users want to hear, even if they are not entirely correct. The motivation behind this exploration stems from the common behavior observed in individuals searching the internet for facts with partial or misleading knowledge. Similar to using web search engines, users may recall fragments of misleading keywords and submit them to an LLM, hoping for a comprehensive response. Our empirical analysis of several LLMs shows the potential danger of these models amplifying misinformation when presented with misleading keywords. Additionally, we thoroughly assess four existing hallucination mitigation strategies to reduce LLMs sycophantic behavior. Our experiments demonstrate the effectiveness of these strategies for generating factually correct statements. Furthermore, our analyses delve into knowledge-probing experiments on factual keywords and different categories of sycophancy mitigation.

![关键词之乱：揭示大型语言模型对误导性关键词的盲从，并探讨防御之策](../../../paper_images/2406.03827/x1.png)

![关键词之乱：揭示大型语言模型对误导性关键词的盲从，并探讨防御之策](../../../paper_images/2406.03827/x2.png)

![关键词之乱：揭示大型语言模型对误导性关键词的盲从，并探讨防御之策](../../../paper_images/2406.03827/x3.png)

![关键词之乱：揭示大型语言模型对误导性关键词的盲从，并探讨防御之策](../../../paper_images/2406.03827/x4.png)

![关键词之乱：揭示大型语言模型对误导性关键词的盲从，并探讨防御之策](../../../paper_images/2406.03827/x5.png)

![关键词之乱：揭示大型语言模型对误导性关键词的盲从，并探讨防御之策](../../../paper_images/2406.03827/x6.png)

![关键词之乱：揭示大型语言模型对误导性关键词的盲从，并探讨防御之策](../../../paper_images/2406.03827/x7.png)

![关键词之乱：揭示大型语言模型对误导性关键词的盲从，并探讨防御之策](../../../paper_images/2406.03827/x8.png)

![关键词之乱：揭示大型语言模型对误导性关键词的盲从，并探讨防御之策](../../../paper_images/2406.03827/x9.png)

![关键词之乱：揭示大型语言模型对误导性关键词的盲从，并探讨防御之策](../../../paper_images/2406.03827/x10.png)

![关键词之乱：揭示大型语言模型对误导性关键词的盲从，并探讨防御之策](../../../paper_images/2406.03827/x11.png)

![关键词之乱：揭示大型语言模型对误导性关键词的盲从，并探讨防御之策](../../../paper_images/2406.03827/x12.png)

[Arxiv](https://arxiv.org/abs/2406.03827)