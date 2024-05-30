# 探究大型语言模型如何融合外部与参数知识

发布时间：2024年05月29日

`RAG

理由：这篇论文主要探讨了如何将外部知识与大型语言模型（LLMs）的内部参数知识进行融合，以克服LLMs的静态参数记忆限制。这种研究方向与RAG（Retrieval-Augmented Generation）模型紧密相关，因为RAG模型正是通过结合检索到的外部知识和模型自身的生成能力来提升性能。论文中提到的系统性知识融合方法和控制实验，以及对LLMs在不同情境下表现的考察，都与RAG模型的研究和应用密切相关。因此，将这篇论文归类为RAG是合适的。` `人工智能`

> Evaluating the External and Parametric Knowledge Fusion of Large Language Models

# 摘要

> 将外部知识融入大型语言模型（LLMs），为克服其陈旧静态的参数记忆限制提供了新思路。然而，过往研究常过度依赖外部知识，忽视了LLMs自身参数知识的价值。特别是在外部知识不完整时，LLMs如何融合外部与内部知识，这一问题鲜有深入探讨。我们首次系统地将知识融合细分为四种情境，并全面考察了LLMs在这些情境下的表现。通过构建数据和知识注入的系统流程，我们模拟了这些融合场景，并开展了一系列控制实验。研究发现，强化LLMs的参数知识能显著提升其知识整合能力。但同时，我们也识别出在记忆、提取参数知识及界定其边界方面的持续挑战。这些发现将为未来LLMs中外部与参数知识的和谐融合研究指明方向。

> Integrating external knowledge into large language models (LLMs) presents a promising solution to overcome the limitations imposed by their antiquated and static parametric memory. Prior studies, however, have tended to over-reliance on external knowledge, underestimating the valuable contributions of an LLMs' intrinsic parametric knowledge. The efficacy of LLMs in blending external and parametric knowledge remains largely unexplored, especially in cases where external knowledge is incomplete and necessitates supplementation by their parametric knowledge. We propose to deconstruct knowledge fusion into four distinct scenarios, offering the first thorough investigation of LLM behavior across each. We develop a systematic pipeline for data construction and knowledge infusion to simulate these fusion scenarios, facilitating a series of controlled experiments. Our investigation reveals that enhancing parametric knowledge within LLMs can significantly bolster their capability for knowledge integration. Nonetheless, we identify persistent challenges in memorizing and eliciting parametric knowledge, and determining parametric knowledge boundaries. Our findings aim to steer future explorations on harmonizing external and parametric knowledge within LLMs.

![探究大型语言模型如何融合外部与参数知识](../../../paper_images/2405.19010/x1.png)

![探究大型语言模型如何融合外部与参数知识](../../../paper_images/2405.19010/x2.png)

[Arxiv](https://arxiv.org/abs/2405.19010)