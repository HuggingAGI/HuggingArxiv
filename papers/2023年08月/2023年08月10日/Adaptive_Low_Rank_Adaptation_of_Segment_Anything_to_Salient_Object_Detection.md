# 本文介绍了一种自适应低秩调整技术，旨在将“任何片段”模型适配到显著目标检测任务中，以提升检测性能。

发布时间：2023年08月10日

`分类：RAG` `人工智能` `图像处理`

> Adaptive Low Rank Adaptation of Segment Anything to Salient Object Detection

# 摘要

> 诸如 OpenAI 的 GPT-3、GPT-4，Meta 的 LLaMA，以及 Google 的 PaLM2 等基础模型，引领了人工智能领域的革新。特别值得一提的是 Segment Anything Model (SAM) 的引入，它在经过 10 亿个遮罩和 1100 万张图像的训练后，展现出了分割现实世界物体的非凡能力。尽管 SAM 在常规物体分割任务上表现优异，但它在识别关键物体方面存在不足，影响了其在该领域的性能。为了解决这一问题，我们引入了 Segment Salient Object Model (SSOM)，这是一种创新的解决方案，它通过深度学习中的低秩结构，对 SAM 进行自适应微调，以提高显著物体检测的准确性。在五个颇具挑战性的 RGB 基准数据集上的全面评估显示，SSOM 在性能上超越了现有的顶尖技术。

> Foundation models, such as OpenAI's GPT-3 and GPT-4, Meta's LLaMA, and Google's PaLM2, have revolutionized the field of artificial intelligence. A notable paradigm shift has been the advent of the Segment Anything Model (SAM), which has exhibited a remarkable capability to segment real-world objects, trained on 1 billion masks and 11 million images. Although SAM excels in general object segmentation, it lacks the intrinsic ability to detect salient objects, resulting in suboptimal performance in this domain. To address this challenge, we present the Segment Salient Object Model (SSOM), an innovative approach that adaptively fine-tunes SAM for salient object detection by harnessing the low-rank structure inherent in deep learning. Comprehensive qualitative and quantitative evaluations across five challenging RGB benchmark datasets demonstrate the superior performance of our approach, surpassing state-of-the-art methods.

[Arxiv](https://arxiv.org/abs/2308.05426)