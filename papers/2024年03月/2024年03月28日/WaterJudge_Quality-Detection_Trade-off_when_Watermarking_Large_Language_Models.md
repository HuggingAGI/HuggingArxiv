# WaterJudge：为大型语言模型添加水印时，质量与检测之间的权衡。

发布时间：2024年03月28日

`LLM应用` `人工智能` `系统性能评估`

> WaterJudge: Quality-Detection Trade-off when Watermarking Large Language Models

# 摘要

> 为生成性AI系统（例如大型语言模型LLM）打上水印，因其在众多任务中展现出的卓越性能而备受关注。尽管现有技术已经能够通过微小且依赖上下文的词汇分布变化来实施和识别水印，但对于这些变化对生成文本质量的具体影响，研究尚显不足。在确保水印易于检测的同时，尽可能减少对系统性能的影响，对于选择合适的水印策略极为关键。本文提出了一个简洁的分析框架，通过对比评估和一个灵活的NLG评估体系，来衡量特定水印策略可能导致的质量下降。我们的框架能够直观地展示水印策略在质量与检测性之间的权衡，为找到一个既能保证质量又能实现高效检测的LLM水印平衡点提供了简便方法。我们将这一方法应用于两个摘要系统和一个翻译系统，实现了跨模型和跨任务的深入分析。

> Watermarking generative-AI systems, such as LLMs, has gained considerable interest, driven by their enhanced capabilities across a wide range of tasks. Although current approaches have demonstrated that small, context-dependent shifts in the word distributions can be used to apply and detect watermarks, there has been little work in analyzing the impact that these perturbations have on the quality of generated texts. Balancing high detectability with minimal performance degradation is crucial in terms of selecting the appropriate watermarking setting; therefore this paper proposes a simple analysis framework where comparative assessment, a flexible NLG evaluation framework, is used to assess the quality degradation caused by a particular watermark setting. We demonstrate that our framework provides easy visualization of the quality-detection trade-off of watermark settings, enabling a simple solution to find an LLM watermark operating point that provides a well-balanced performance. This approach is applied to two different summarization systems and a translation system, enabling cross-model analysis for a task, and cross-task analysis.

![WaterJudge：为大型语言模型添加水印时，质量与检测之间的权衡。](../../../paper_images/2403.19548/diagram_8.jpeg)

![WaterJudge：为大型语言模型添加水印时，质量与检测之间的权衡。](../../../paper_images/2403.19548/comparative.png)

![WaterJudge：为大型语言模型添加水印时，质量与检测之间的权衡。](../../../paper_images/2403.19548/x1.png)

![WaterJudge：为大型语言模型添加水印时，质量与检测之间的权衡。](../../../paper_images/2403.19548/x2.png)

![WaterJudge：为大型语言模型添加水印时，质量与检测之间的权衡。](../../../paper_images/2403.19548/x3.png)

![WaterJudge：为大型语言模型添加水印时，质量与检测之间的权衡。](../../../paper_images/2403.19548/x4.png)

![WaterJudge：为大型语言模型添加水印时，质量与检测之间的权衡。](../../../paper_images/2403.19548/x5.png)

![WaterJudge：为大型语言模型添加水印时，质量与检测之间的权衡。](../../../paper_images/2403.19548/x6.png)

![WaterJudge：为大型语言模型添加水印时，质量与检测之间的权衡。](../../../paper_images/2403.19548/x7.png)

![WaterJudge：为大型语言模型添加水印时，质量与检测之间的权衡。](../../../paper_images/2403.19548/x8.png)

![WaterJudge：为大型语言模型添加水印时，质量与检测之间的权衡。](../../../paper_images/2403.19548/x9.png)

![WaterJudge：为大型语言模型添加水印时，质量与检测之间的权衡。](../../../paper_images/2403.19548/x10.png)

![WaterJudge：为大型语言模型添加水印时，质量与检测之间的权衡。](../../../paper_images/2403.19548/x11.png)

![WaterJudge：为大型语言模型添加水印时，质量与检测之间的权衡。](../../../paper_images/2403.19548/x12.png)

![WaterJudge：为大型语言模型添加水印时，质量与检测之间的权衡。](../../../paper_images/2403.19548/x13.png)

![WaterJudge：为大型语言模型添加水印时，质量与检测之间的权衡。](../../../paper_images/2403.19548/x14.png)

![WaterJudge：为大型语言模型添加水印时，质量与检测之间的权衡。](../../../paper_images/2403.19548/x15.png)

![WaterJudge：为大型语言模型添加水印时，质量与检测之间的权衡。](../../../paper_images/2403.19548/x16.png)

![WaterJudge：为大型语言模型添加水印时，质量与检测之间的权衡。](../../../paper_images/2403.19548/x17.png)

![WaterJudge：为大型语言模型添加水印时，质量与检测之间的权衡。](../../../paper_images/2403.19548/x18.png)

![WaterJudge：为大型语言模型添加水印时，质量与检测之间的权衡。](../../../paper_images/2403.19548/x19.png)

![WaterJudge：为大型语言模型添加水印时，质量与检测之间的权衡。](../../../paper_images/2403.19548/x20.png)

![WaterJudge：为大型语言模型添加水印时，质量与检测之间的权衡。](../../../paper_images/2403.19548/x21.png)

[Arxiv](https://arxiv.org/abs/2403.19548)