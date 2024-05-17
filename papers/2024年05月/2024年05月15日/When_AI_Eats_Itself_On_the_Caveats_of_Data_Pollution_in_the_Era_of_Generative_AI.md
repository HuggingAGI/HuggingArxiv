# AI自噬之忧：生成式AI时代的数据污染警示

发布时间：2024年05月15日

`LLM应用

这篇论文主要讨论了生成式AI技术中合成数据的使用问题，以及它对生成式AI系统性能和伦理的影响。它探讨了合成数据与真实数据整合的挑战，以及如何平衡两者的使用以确保生成式AI系统的最佳效果。这些问题与大型语言模型（LLM）的应用紧密相关，特别是在处理多模态信息融合时。因此，这篇论文属于LLM应用类别，因为它关注的是LLM在实际应用中遇到的具体问题和挑战，以及如何解决这些问题以促进技术的可持续发展。` `人工智能` `数据管理`

> When AI Eats Itself: On the Caveats of Data Pollution in the Era of Generative AI

# 摘要

> 生成式AI技术和大型模型正在创造出逼真的图像、文本、语音和音乐作品。然而，这些先进的生成模型需要庞大的高质量数据集，这往往意味着高昂的训练成本。为了节省开支，许多开发者选择使用模型自身生成的数据进行训练，但这并不总是能提升性能。因此，我们需要在真实数据和合成数据之间找到平衡，以确保最佳效果。当前，真实数据与合成数据的整合正逐渐失控。网络上无节制的合成数据传播污染了传统网络爬虫收集的数据集，混入了未标记的合成数据。这可能导致生成式AI系统过度依赖自身生成的数据，引发性能和伦理上的担忧。我们应该如何应对生成式AI无辨别地自我消耗的风险？我们能采取哪些措施来减轻这些潜在的负面影响？科学文献中对于合成数据在生成式AI中的影响，尤其是在多模态信息融合方面的研究尚显不足。本综述旨在填补这一空白，探讨盲目整合合成数据对生成式AI在图像和文本模态上的训练可能带来的后果，并提出减轻这些影响的策略。我们的目标是全面理解合成数据的作用，提倡平衡的使用方法，并探索促进生成式AI技术在大型模型时代可持续发展的实践。

> Generative artificial intelligence (AI) technologies and large models are producing realistic outputs across various domains, such as images, text, speech, and music. Creating these advanced generative models requires significant resources, particularly large and high-quality datasets. To minimize training expenses, many algorithm developers use data created by the models themselves as a cost-effective training solution. However, not all synthetic data effectively improve model performance, necessitating a strategic balance in the use of real versus synthetic data to optimize outcomes.
  Currently, the previously well-controlled integration of real and synthetic data is becoming uncontrollable. The widespread and unregulated dissemination of synthetic data online leads to the contamination of datasets traditionally compiled through web scraping, now mixed with unlabeled synthetic data. This trend portends a future where generative AI systems may increasingly rely blindly on consuming self-generated data, raising concerns about model performance and ethical issues. What will happen if generative AI continuously consumes itself without discernment? What measures can we take to mitigate the potential adverse effects?
  There is a significant gap in the scientific literature regarding the impact of synthetic data use in generative AI, particularly in terms of the fusion of multimodal information. To address this research gap, this review investigates the consequences of integrating synthetic data blindly on training generative AI on both image and text modalities and explores strategies to mitigate these effects. The goal is to offer a comprehensive view of synthetic data's role, advocating for a balanced approach to its use and exploring practices that promote the sustainable development of generative AI technologies in the era of large models.

[Arxiv](https://arxiv.org/abs/2405.09597)