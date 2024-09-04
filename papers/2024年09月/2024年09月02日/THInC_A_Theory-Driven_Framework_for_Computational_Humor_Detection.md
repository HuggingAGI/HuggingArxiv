# THInC：理论驱动的计算幽默检测框架

发布时间：2024年09月02日

`LLM应用` `社交互动` `人工智能`

> THInC: A Theory-Driven Framework for Computational Humor Detection

# 摘要

> 幽默在人类社交互动中至关重要，但关于其理论的共识仍未形成。尽管大型语言模型有所进步，计算识别幽默依旧困难重重。本文通过THInC框架，结合多理论，为幽默分类提供了新思路。THInC采用GA2M分类器，每种代表一理论，设计透明流程生成定量代理特征。实测F1分数达0.85，框架的解释性助力分析特征效能与理论契合度。本文不仅开创了多理论驱动的幽默检测先河，也为未来理论驱动的分类研究奠定了基础，并首次尝试以定量方式自动比较幽默理论。

> Humor is a fundamental aspect of human communication and cognition, as it plays a crucial role in social engagement. Although theories about humor have evolved over centuries, there is still no agreement on a single, comprehensive humor theory. Likewise, computationally recognizing humor remains a significant challenge despite recent advances in large language models. Moreover, most computational approaches to detecting humor are not based on existing humor theories. This paper contributes to bridging this long-standing gap between humor theory research and computational humor detection by creating an interpretable framework for humor classification, grounded in multiple humor theories, called THInC (Theory-driven Humor Interpretation and Classification). THInC ensembles interpretable GA2M classifiers, each representing a different humor theory. We engineered a transparent flow to actively create proxy features that quantitatively reflect different aspects of theories. An implementation of this framework achieves an F1 score of 0.85. The associative interpretability of the framework enables analysis of proxy efficacy, alignment of joke features with theories, and identification of globally contributing features. This paper marks a pioneering effort in creating a humor detection framework that is informed by diverse humor theories and offers a foundation for future advancements in theory-driven humor classification. It also serves as a first step in automatically comparing humor theories in a quantitative manner.

[Arxiv](https://arxiv.org/abs/2409.01232)