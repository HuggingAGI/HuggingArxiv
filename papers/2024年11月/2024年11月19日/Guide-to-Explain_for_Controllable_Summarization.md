# 《可控摘要的指南阐释》

发布时间：2024年11月19日

`LLM应用` `摘要生成`

> Guide-to-Explain for Controllable Summarization

# 摘要

> 近来，大型语言模型（LLMs）在抽象摘要任务里表现出色。但利用 LLMs 进行可控摘要的探索还不够深入，这限制了其生成符合特定用户偏好摘要的能力。在本文中，我们率先探究了 LLMs 对各类属性的把控能力，结果表明，相较于语言属性，它们在诸如长度和抽取性等数字属性方面面临更多挑战。为应对此难题，我们提出了用于可控摘要的引导解释框架（GTE）。我们的 GTE 框架能让模型识别初稿中不对齐的属性，并引导其解释先前输出中的错误。基于这种反思，模型生成了调整得当的摘要。所以，通过让模型反思自身的不对齐之处，我们生成满足所需属性的摘要所需的迭代次数，比其他单纯使用 LLMs 的迭代方法少很多。

> Recently, large language models (LLMs) have demonstrated remarkable performance in abstractive summarization tasks. However, controllable summarization with LLMs remains underexplored, limiting their ability to generate summaries that align with specific user preferences. In this paper, we first investigate the capability of LLMs to control diverse attributes, revealing that they encounter greater challenges with numerical attributes, such as length and extractiveness, compared to linguistic attributes. To address this challenge, we propose a guide-to-explain framework (GTE) for controllable summarization. Our GTE framework enables the model to identify misaligned attributes in the initial draft and guides it in explaining errors in the previous output. Based on this reflection, the model generates a well-adjusted summary. As a result, by allowing the model to reflect on its misalignment, we generate summaries that satisfy the desired attributes in surprisingly fewer iterations than other iterative methods solely using LLMs.

[Arxiv](https://arxiv.org/abs/2411.12460)