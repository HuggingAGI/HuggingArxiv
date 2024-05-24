# 大型语言模型展现出卓越的自发性多语言学习能力，这引发了一个问题：我们是否真的需要多语言标注数据？

发布时间：2024年05月22日

`LLM应用

这篇论文主要探讨了大型语言模型（LLMs）在多语言环境下的应用，特别是通过多语言对齐策略来提升模型在不同语言上的表现。研究内容涉及实验评估和机制解释，这些都是针对LLMs在实际应用中的性能提升，而非理论研究或Agent、RAG相关的研究。因此，最合适的分类是LLM应用。` `多语言技术`

> Large Language Models are Good Spontaneous Multilingual Learners: Is the Multilingual Annotated Data Necessary?

# 摘要

> 近期，大型语言模型（LLMs）在语言能力上展现了显著的进步，但多数模型仍以英语为主，导致在不同语言上的表现参差不齐。多语言对齐策略是提升LLMs跨语言能力的关键。本研究深入探讨了基于翻译数据的多语言对齐方法，并全面评估了LLMs在多语言环境下的自发性进步。实验表明，即使在没有答案标注的情况下，仅通过问题翻译数据训练的LLMs也能在多种未接触过的语言中实现显著的性能提升。此外，我们还通过多样化的实验设置和机制解释方法，深入剖析了LLMs在多语言应用中的表现。

> Recently, Large Language Models (LLMs) have shown impressive language capabilities. However, most of the existing LLMs are all English-centric, which have very unstable and unbalanced performance across different languages. Multilingual alignment is an effective method to enhance the LLMs' multilingual capabilities. In this work, we explore the multilingual alignment paradigm which utilizes translation data and comprehensively investigate the spontaneous multilingual improvement of LLMs. We find that LLMs only instruction-tuned on question translation data without annotated answers are able to get significant multilingual performance enhancement even across a wide range of languages unseen during instruction-tuning. Additionally, we utilize different settings and mechanistic interpretability methods to comprehensively analyze the LLM's performance in the multilingual scenario.

[Arxiv](https://arxiv.org/abs/2405.13816)