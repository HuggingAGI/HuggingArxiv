# 少数伪君子：通过少样本学习和子类型定义，检测在线气候变化辩论中的伪善指控

发布时间：2024年09月25日

`LLM应用` `气候研究`

> A Few Hypocrites: Few-Shot Learning and Subtype Definitions for Detecting Hypocrisy Accusations in Online Climate Change Debates

# 摘要

> 气候危机的讨论中，虚伪指控是一个关键的修辞元素。然而，在大规模文本分析中，虚伪指控检测的研究却相对不足。本文将其定义为NLP的独立任务，并识别了多种虚伪指控类型。我们构建了包含420条Reddit评论的气候虚伪指控语料库（CHAC），并评估了GPT-4o和Llama-3等模型在少样本学习中的表现。结果显示，这些模型在检测虚伪指控方面表现出色，但在复杂的政治虚伪指控识别上仍有挑战。本研究不仅深化了对虚伪检测的理解，也为未来在线气候辩论的大规模分析奠定了基础。

> The climate crisis is a salient issue in online discussions, and hypocrisy accusations are a central rhetorical element in these debates. However, for large-scale text analysis, hypocrisy accusation detection is an understudied tool, most often defined as a smaller subtask of fallacious argument detection. In this paper, we define hypocrisy accusation detection as an independent task in NLP, and identify different relevant subtypes of hypocrisy accusations. Our Climate Hypocrisy Accusation Corpus (CHAC) consists of 420 Reddit climate debate comments, expert-annotated into two different types of hypocrisy accusations: personal versus political hypocrisy. We evaluate few-shot in-context learning with 6 shots and 3 instruction-tuned Large Language Models (LLMs) for detecting hypocrisy accusations in this dataset. Results indicate that the GPT-4o and Llama-3 models in particular show promise in detecting hypocrisy accusations (F1 reaching 0.68, while previous work shows F1 of 0.44). However, context matters for a complex semantic concept such as hypocrisy accusations, and we find models struggle especially at identifying political hypocrisy accusations compared to personal moral hypocrisy. Our study contributes new insights in hypocrisy detection and climate change discourse, and is a stepping stone for large-scale analysis of hypocrisy accusation in online climate debates.

[Arxiv](https://arxiv.org/abs/2409.16807)