# THInC：理论驱动的计算幽默检测框架

发布时间：2024年09月02日

`LLM应用`

> THInC: A Theory-Driven Framework for Computational Humor Detection

# 摘要

> 幽默在人类社交互动中至关重要，但关于其理论的共识仍未形成。尽管大型语言模型有所进步，计算识别幽默依旧困难重重。本文通过THInC框架，结合多理论，为幽默分类提供了解释性，并设计了透明流程以量化理论特征。该框架F1分数达0.85，可分析理论与笑话特征的契合度，为幽默检测开辟新径，并首次尝试定量比较幽默理论。

> Humor is a fundamental aspect of human communication and cognition, as it plays a crucial role in social engagement. Although theories about humor have evolved over centuries, there is still no agreement on a single, comprehensive humor theory. Likewise, computationally recognizing humor remains a significant challenge despite recent advances in large language models. Moreover, most computational approaches to detecting humor are not based on existing humor theories. This paper contributes to bridging this long-standing gap between humor theory research and computational humor detection by creating an interpretable framework for humor classification, grounded in multiple humor theories, called THInC (Theory-driven Humor Interpretation and Classification). THInC ensembles interpretable GA2M classifiers, each representing a different humor theory. We engineered a transparent flow to actively create proxy features that quantitatively reflect different aspects of theories. An implementation of this framework achieves an F1 score of 0.85. The associative interpretability of the framework enables analysis of proxy efficacy, alignment of joke features with theories, and identification of globally contributing features. This paper marks a pioneering effort in creating a humor detection framework that is informed by diverse humor theories and offers a foundation for future advancements in theory-driven humor classification. It also serves as a first step in automatically comparing humor theories in a quantitative manner.

[Arxiv](https://arxiv.org/abs/2409.01232)