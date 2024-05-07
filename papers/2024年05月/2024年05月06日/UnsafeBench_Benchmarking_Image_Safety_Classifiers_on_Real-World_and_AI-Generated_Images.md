# UnsafeBench 项目致力于对现实世界及 AI 创造的图像进行图像安全分类器的基准测试，旨在评估和提升图像安全分类技术的实际效能。

发布时间：2024年05月06日

`分类：LLM应用

这篇论文主要研究了图像安全分类器在识别和减少不安全图像（如暴力、仇恨言论等）传播中的作用，特别是在处理现实世界图像和AI生成图像时的性能。论文提出了一个评估图像安全分类器效能和鲁棒性的基准测试框架UnsafeBench，并构建了一个包含10,000张现实世界和AI生成图像的数据集。此外，论文还设计并实施了一个全面的图像审核工具PerspectiveVision，能够有效识别多种现实世界和AI生成的不安全图像类别。这些研究内容与LLM（大型语言模型）的应用密切相关，因此将这篇论文归类为LLM应用。` `图像识别` `网络安全`

> UnsafeBench: Benchmarking Image Safety Classifiers on Real-World and AI-Generated Images

# 摘要

> 图像安全分类器对于在线识别和减少不安全图像（如暴力、仇恨言论等）的传播至关重要。随着文本到图像模型的兴起以及对AI模型安全性的担忧增加，开发者越发依赖这些分类器来保护他们的模型。但是，这些分类器在处理现实世界图像和AI生成图像时的性能尚未明确。为填补这一研究空缺，本研究提出了UnsafeBench，这是一个评估图像安全分类器效能和鲁棒性的基准测试框架。我们首先构建了一个包含10,000张现实世界和AI生成图像的数据集，这些图像根据11个不安全类别（如色情、暴力、仇恨等）被标记为安全或不安全。接着，我们评估了五种主流图像安全分类器以及三种由通用视觉语言模型支持的分类器的有效性和鲁棒性。我们的评估发现，现有的分类器在应对多维度不安全图像问题上还不够全面和有效。此外，仅基于现实世界图像训练的分类器在处理AI生成图像时表现不佳。基于这些发现，我们设计并实施了一个全面的图像审核工具PerspectiveVision，它能够有效识别11种现实世界和AI生成的不安全图像类别。PerspectiveVision的最佳模型在六个评估数据集上达到了0.810的综合F1分数，与封闭源和高成本的最先进模型如GPT-4V相当。UnsafeBench和PerspectiveVision有助于研究社区更深入地理解在生成AI时代图像安全分类的领域。

> Image safety classifiers play an important role in identifying and mitigating the spread of unsafe images online (e.g., images including violence, hateful rhetoric, etc.). At the same time, with the advent of text-to-image models and increasing concerns about the safety of AI models, developers are increasingly relying on image safety classifiers to safeguard their models. Yet, the performance of current image safety classifiers remains unknown for real-world and AI-generated images. To bridge this research gap, in this work, we propose UnsafeBench, a benchmarking framework that evaluates the effectiveness and robustness of image safety classifiers. First, we curate a large dataset of 10K real-world and AI-generated images that are annotated as safe or unsafe based on a set of 11 unsafe categories of images (sexual, violent, hateful, etc.). Then, we evaluate the effectiveness and robustness of five popular image safety classifiers, as well as three classifiers that are powered by general-purpose visual language models. Our assessment indicates that existing image safety classifiers are not comprehensive and effective enough in mitigating the multifaceted problem of unsafe images. Also, we find that classifiers trained only on real-world images tend to have degraded performance when applied to AI-generated images. Motivated by these findings, we design and implement a comprehensive image moderation tool called PerspectiveVision, which effectively identifies 11 categories of real-world and AI-generated unsafe images. The best PerspectiveVision model achieves an overall F1-Score of 0.810 on six evaluation datasets, which is comparable with closed-source and expensive state-of-the-art models like GPT-4V. UnsafeBench and PerspectiveVision can aid the research community in better understanding the landscape of image safety classification in the era of generative AI.

[Arxiv](https://arxiv.org/abs/2405.03486)