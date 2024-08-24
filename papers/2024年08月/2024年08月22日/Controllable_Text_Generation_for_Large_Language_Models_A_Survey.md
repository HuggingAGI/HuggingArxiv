# 大型语言模型中的可控文本生成：综述

发布时间：2024年08月22日

`LLM应用` `文本生成`

> Controllable Text Generation for Large Language Models: A Survey

# 摘要

> 在NLP领域，LLMs的文本生成质量已获高度认可。但面对现实世界的复杂需求，LLMs需更进一步。不仅需避免误导或不当内容，还需满足个性化需求，如模仿特定风格或创作诗意文本。这促使可控文本生成（CTG）技术应运而生，确保文本在遵循安全、情感、主题一致性和语言风格等预设条件的同时，保持高度的实用性、流畅性和多样性。本文深入探讨了LLMs中CTG的最新进展，全面阐释其核心概念，并明确控制条件与文本质量的要求。我们将CTG任务细分为内容控制与属性控制两大类，并详述了包括模型重训练、微调、强化学习、提示工程、潜在空间操作及解码时干预等关键方法。我们逐一剖析这些方法的特性、优势与局限，为实现精准生成控制提供深刻见解。同时，我们回顾了CTG的评估方法，概述其在多领域的应用，并直面当前研究的挑战，如流畅性与实用性的下降。此外，我们呼吁未来研究更注重实际应用。本文旨在为NLP领域的研究者与开发者提供有力指导。相关参考资料与中文版已开放于https://github.com/IAAR-Shanghai/CTGSurvey。

> In Natural Language Processing (NLP), Large Language Models (LLMs) have demonstrated high text generation quality. However, in real-world applications, LLMs must meet increasingly complex requirements. Beyond avoiding misleading or inappropriate content, LLMs are also expected to cater to specific user needs, such as imitating particular writing styles or generating text with poetic richness. These varied demands have driven the development of Controllable Text Generation (CTG) techniques, which ensure that outputs adhere to predefined control conditions--such as safety, sentiment, thematic consistency, and linguistic style--while maintaining high standards of helpfulness, fluency, and diversity.
  This paper systematically reviews the latest advancements in CTG for LLMs, offering a comprehensive definition of its core concepts and clarifying the requirements for control conditions and text quality. We categorize CTG tasks into two primary types: content control and attribute control. The key methods are discussed, including model retraining, fine-tuning, reinforcement learning, prompt engineering, latent space manipulation, and decoding-time intervention. We analyze each method's characteristics, advantages, and limitations, providing nuanced insights for achieving generation control. Additionally, we review CTG evaluation methods, summarize its applications across domains, and address key challenges in current research, including reduced fluency and practicality. We also propose several appeals, such as placing greater emphasis on real-world applications in future research. This paper aims to offer valuable guidance to researchers and developers in the field. Our reference list and Chinese version are open-sourced at https://github.com/IAAR-Shanghai/CTGSurvey.

[Arxiv](https://arxiv.org/abs/2408.12599)