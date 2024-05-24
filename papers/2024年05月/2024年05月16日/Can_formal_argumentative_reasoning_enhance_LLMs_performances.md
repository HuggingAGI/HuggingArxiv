# 论证推理能否助力大型语言模型（LLMs）性能飞跃？

发布时间：2024年05月16日

`Agent

这篇论文主要介绍了一种名为MQArgEng的流程，旨在评估计算论证语义对大型语言模型（LLMs）性能的影响。这种方法通过捕捉代理间的交互及信息冲突来提升LLMs的推理与对话能力。因此，这篇论文更符合Agent分类，因为它关注的是如何通过代理间的交互来增强语言模型的能力。` `人工智能` `对话系统`

> Can formal argumentative reasoning enhance LLMs performances?

# 摘要

> 近年来，深度学习推动的自然语言模型在性能上取得了显著进步，特别是大型语言模型（LLMs）的开发与发布。尽管这些进步，AI输出的质量得以提升，但仍依赖于资源密集型的模型训练与升级。虽然已有多种技术在不重新训练的情况下增强LLMs，但计算论证这一选项尚未被考虑。这是一个被忽视的机会，因为计算论证能直观地捕捉代理间的交互及信息冲突，非常适合提升LLMs的推理与对话能力。本文介绍了一种名为MQArgEng的流程及初步研究，旨在评估计算论证语义对LLMs性能的影响。实验旨在验证概念并分析可行性，以推动未来研究向完整的论证引擎插件发展。初步结果显示，MQArgEng在多数主题类别中带来了适度的性能提升，预示着其潜力，值得深入研究。

> Recent years witnessed significant performance advancements in deep-learning-driven natural language models, with a strong focus on the development and release of Large Language Models (LLMs). These improvements resulted in better quality AI-generated output but rely on resource-expensive training and upgrading of models. Although different studies have proposed a range of techniques to enhance LLMs without retraining, none have considered computational argumentation as an option. This is a missed opportunity since computational argumentation is an intuitive mechanism that formally captures agents' interactions and the information conflict that may arise during such interplays, and so it seems well-suited for boosting the reasoning and conversational abilities of LLMs in a seamless manner. In this paper, we present a pipeline (MQArgEng) and preliminary study to evaluate the effect of introducing computational argumentation semantics on the performance of LLMs. Our experiment's goal was to provide a proof-of-concept and a feasibility analysis in order to foster (or deter) future research towards a fully-fledged argumentation engine plugin for LLMs. Exploratory results using the MT-Bench indicate that MQArgEng provides a moderate performance gain in most of the examined topical categories and, as such, show promise and warrant further research.

[Arxiv](https://arxiv.org/abs/2405.13036)