# LLMs能够以少量示例，在上下文中高效学习低资源语言。

发布时间：2024年03月25日

`LLM应用` `低资源语言`

> LLMs Are Few-Shot In-Context Low-Resource Language Learners

# 摘要

> ICL技术使得LLMs只需借助少量上下文信息就能处理低资源语言中的多样化任务，从而有力地拉近了高资源与低资源语言间的鸿沟。遗憾的是，目前对该领域研究主要集中于像法语、西班牙语等相对高资源的语言上，而针对真正低资源语言的ICL探索却寥寥无几。在这项研究中，我们深入探讨了ICL及其跨语言变体X-ICL在25种低资源语言以及7种相对高资源语言中的应用效果。我们不仅验证了LLMs在低资源语言环境下运用ICL的有效性，还揭示了上下文标签对齐方法的局限性，并提出了一种更优的解决方案——查询对齐。同时，我们从多个角度深入剖析了ICL在处理低资源语言时的特点。研究发现，通过在目标语言中弥合语言差异，并在目标低资源语言与其所对应的模型擅长的高资源语言间实现语义对接，少量示例的上下文信息能够通过语义相关的内容显著提升LLMs对低资源语言的理解水平。这项工作强调了深化ICL研究，尤其是针对低资源语言研究的重要性。

> In-context learning (ICL) empowers large language models (LLMs) to perform diverse tasks in underrepresented languages using only short in-context information, offering a crucial avenue for narrowing the gap between high-resource and low-resource languages. Nonetheless, there is only a handful of works explored ICL for low-resource languages with most of them focusing on relatively high-resource languages, such as French and Spanish. In this work, we extensively study ICL and its cross-lingual variation (X-ICL) on 25 low-resource and 7 relatively higher-resource languages. Our study not only assesses the effectiveness of ICL with LLMs in low-resource languages but also identifies the shortcomings of in-context label alignment, and introduces a more effective alternative: query alignment. Moreover, we provide valuable insights into various facets of ICL for low-resource languages. Our study concludes the significance of few-shot in-context information on enhancing the low-resource understanding quality of LLMs through semantically relevant information by closing the language gap in the target language and aligning the semantics between the targeted low-resource and the high-resource language that the model is proficient in. Our work highlights the importance of advancing ICL research, particularly for low-resource languages.

[Arxiv](https://arxiv.org/abs/2403.16512)