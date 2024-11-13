# 评估文本和图像生成模型中空间关系的生成

发布时间：2024年11月12日

`LLM应用` `人工智能` `空间关系`

> Evaluating the Generation of Spatial Relations in Text and Image Generative Models

# 摘要

> 理解空间关系对于人类和人工智能来说都是一项至关重要的认知能力。虽然当前的研究主要集中在对文本到图像（T2I）模型的基准测试上，但我们提出了一个更全面的评估，包括	extit{两者}T2I 和大型语言模型（LLM）。由于空间关系是以视觉空间的方式自然理解的，我们开发了一种将 LLM 输出转换为图像的方法，从而使我们能够	extit{直观地}评估 T2I 模型和 LLM。我们检查了 8 个著名的生成模型（3 个 T2I 模型和 5 个 LLM）对一组 10 个常见介词的空间关系理解，并评估了自动评估方法的可行性。令人惊讶的是，我们发现尽管 T2I 模型具有令人印象深刻的一般图像生成能力，但它们的表现却不尽如人意。更令人惊讶的是，我们的结果表明，尽管 LLM 主要是基于文本数据进行训练的，但在生成空间关系方面，它们比 T2I 模型要准确得多。我们研究了模型失败的原因，并强调了可以填补的差距，以实现更符合空间规律的生成。

> Understanding spatial relations is a crucial cognitive ability for both humans and AI. While current research has predominantly focused on the benchmarking of text-to-image (T2I) models, we propose a more comprehensive evaluation that includes \textit{both} T2I and Large Language Models (LLMs). As spatial relations are naturally understood in a visuo-spatial manner, we develop an approach to convert LLM outputs into an image, thereby allowing us to evaluate both T2I models and LLMs \textit{visually}. We examined the spatial relation understanding of 8 prominent generative models (3 T2I models and 5 LLMs) on a set of 10 common prepositions, as well as assess the feasibility of automatic evaluation methods. Surprisingly, we found that T2I models only achieve subpar performance despite their impressive general image-generation abilities. Even more surprisingly, our results show that LLMs are significantly more accurate than T2I models in generating spatial relations, despite being primarily trained on textual data. We examined reasons for model failures and highlight gaps that can be filled to enable more spatially faithful generations.

[Arxiv](https://arxiv.org/abs/2411.07664)