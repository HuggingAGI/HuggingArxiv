# SonifyAR：在增强现实中，声音生成技术能够感知并适应环境，为用户带来沉浸式的听觉体验。

发布时间：2024年05月11日

`LLM应用

解释：这篇论文介绍了一个名为SonifyAR的系统，该系统利用大型语言模型（LLM）技术来增强增强现实（AR）体验中的声音效果。它通过捕捉AR事件的上下文信息，并使用LLM处理这些信息以生成与场景匹配的声音，从而提升了AR体验的沉浸感。这个系统展示了LLM技术在实际应用中的潜力，特别是在增强现实领域中的声音设计。因此，这篇论文属于LLM应用分类。` `增强现实` `声音设计`

> SonifyAR: Context-Aware Sound Generation in Augmented Reality

# 摘要

> 声音在AR中是提升体验和沉浸感的关键。但目前，由于交互限制、上下文信息获取难题和声音资产匹配不易，AR声音创作的支持不足。我们开发的SonifyAR系统，利用LLM技术，为AR体验量身定制智能声音效果。它不仅拓宽了AR声音设计的可能性，还通过PbD技术自动捕捉AR事件的上下文，包括虚拟内容和现实环境的信息。这些信息经过LLM处理，生成与场景完美匹配的声音。我们通过一项包含八名参与者的研究，以及五个应用实例，包括科学实验、安全增强和视觉辅助等，来验证SonifyAR的实用性和效果。

> Sound plays a crucial role in enhancing user experience and immersiveness in Augmented Reality (AR). However, current platforms lack support for AR sound authoring due to limited interaction types, challenges in collecting and specifying context information, and difficulty in acquiring matching sound assets. We present SonifyAR, an LLM-based AR sound authoring system that generates context-aware sound effects for AR experiences. SonifyAR expands the current design space of AR sound and implements a Programming by Demonstration (PbD) pipeline to automatically collect contextual information of AR events, including virtual content semantics and real world context. This context information is then processed by a large language model to acquire sound effects with Recommendation, Retrieval, Generation, and Transfer methods. To evaluate the usability and performance of our system, we conducted a user study with eight participants and created five example applications, including an AR-based science experiment, an improving case for AR headset safety, and an assisting example for low vision AR users.

[Arxiv](https://arxiv.org/abs/2405.07089)