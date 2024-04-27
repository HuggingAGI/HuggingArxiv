# SEED-Bench-2-Plus：以文本丰富的视觉理解为基准，评估多模态大型语言模型的性能。

发布时间：2024年04月25日

`LLM应用` `视觉识别`

> SEED-Bench-2-Plus: Benchmarking Multimodal Large Language Models with Text-Rich Visual Comprehension

# 摘要

> 掌握富含文本的视觉内容对于实际应用多模态大型语言模型（MLLMs）至关重要，因为现实世界中充满了嵌入大量文本的图像场景。尽管新型MLLMs的多功能性令人瞩目，提升了我们的期待，但其在处理文本密集场景的能力尚未得到全面客观的评估。本文提出了SEED-Bench-2-Plus，一个专为评估MLLMs文本密集视觉理解能力而设计的基准测试。该测试包含2300道多项选择题，覆盖图表、地图和网络三大类别，每类均广泛覆盖现实世界中的文本密集场景。这些类别因其复杂性和多样性，有效模拟了真实世界的文本密集环境。我们还对34个主要的MLLMs进行了深入评估，包括GPT-4V、Gemini-Pro-Vision和Claude-3-Opus，突出了MLLMs在文本密集视觉理解方面的当前限制。我们期望本研究能为现有的MLLM基准测试增添价值，提供深刻的见解，并激发MLLMs文本密集视觉理解领域的进一步研究。相关数据集和评估代码可在 https://github.com/AILab-CVC/SEED-Bench 获取。

> Comprehending text-rich visual content is paramount for the practical application of Multimodal Large Language Models (MLLMs), since text-rich scenarios are ubiquitous in the real world, which are characterized by the presence of extensive texts embedded within images. Recently, the advent of MLLMs with impressive versatility has raised the bar for what we can expect from MLLMs. However, their proficiency in text-rich scenarios has yet to be comprehensively and objectively assessed, since current MLLM benchmarks primarily focus on evaluating general visual comprehension. In this work, we introduce SEED-Bench-2-Plus, a benchmark specifically designed for evaluating \textbf{text-rich visual comprehension} of MLLMs. Our benchmark comprises 2.3K multiple-choice questions with precise human annotations, spanning three broad categories: Charts, Maps, and Webs, each of which covers a wide spectrum of text-rich scenarios in the real world. These categories, due to their inherent complexity and diversity, effectively simulate real-world text-rich environments. We further conduct a thorough evaluation involving 34 prominent MLLMs (including GPT-4V, Gemini-Pro-Vision and Claude-3-Opus) and emphasize the current limitations of MLLMs in text-rich visual comprehension. We hope that our work can serve as a valuable addition to existing MLLM benchmarks, providing insightful observations and inspiring further research in the area of text-rich visual comprehension with MLLMs. The dataset and evaluation code can be accessed at https://github.com/AILab-CVC/SEED-Bench.

[Arxiv](https://arxiv.org/abs/2404.16790)