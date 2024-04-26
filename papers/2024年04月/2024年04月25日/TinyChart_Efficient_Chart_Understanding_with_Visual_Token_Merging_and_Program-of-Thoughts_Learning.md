# TinyChart：采用视觉令牌融合与思维程序学习方法，实现图表理解的高效性。

发布时间：2024年04月25日

`LLM应用` `数据可视化` `人工智能`

> TinyChart: Efficient Chart Understanding with Visual Token Merging and Program-of-Thoughts Learning

# 摘要

> 图表在阐释和展示复杂数据关系方面发挥着关键作用。近期，多模态大型语言模型（MLLMs）在各类图表理解任务上展现了非凡的潜力。但是，这些模型因参数众多和计算需求高而难以在资源受限的环境下应用。本文介绍了TinyChart，一个仅含3B参数的高效MLLM，专为图表理解而设计。TinyChart成功应对了两个主要挑战：首先，采用思维程序（PoT）学习策略，减轻了数值计算学习的负担，训练模型生成用于数值运算的Python程序；其次，通过视觉令牌合并模块，减少了视觉变换器处理高分辨率图像时产生的冗长视觉特征序列，该模块能够逐步合并高度相似的视觉令牌。广泛的实验证明，3B参数的TinyChart在ChartQA、Chart-to-Text、Chart-to-Table、OpenCQA和ChartX等多个图表理解基准测试中达到了最佳性能。它不仅超越了拥有至多13B参数的多个图表理解MLLM，如ChartLlama和ChartAst，还在ChartQA上超越了封闭源的通用MLLM GPT-4V。此外，由于模型规模更小和视觉编码更高效，TinyChart在推理过程中展现出更高的吞吐量和卓越效率。我们的代码和模型已在https://github.com/X-PLUG/mPLUG-DocOwl/tree/main/TinyChart上发布。

> Charts are important for presenting and explaining complex data relationships. Recently, multimodal large language models (MLLMs) have shown remarkable capabilities in various chart understanding tasks. However, the sheer size of these models in terms of parameters and computational requirements limits their use in resource-constrained environments. In this paper, we present TinyChart, an efficient MLLM for chart understanding with only 3B parameters. TinyChart overcomes two key challenges in efficient chart understanding: (1) reduce the burden of learning numerical computations through a Program-of-Thoughts (PoT) learning strategy, which trains the model to generate Python programs for numerical calculations, and (2) reduce lengthy vision feature sequences produced by the vision transformer for high-resolution images through a Vision Token Merging module, which gradually merges most similar vision tokens. Extensive experiments demonstrate that our 3B TinyChart achieves SOTA performance on a variety of chart understanding benchmarks including ChartQA, Chart-to-Text, Chart-to-Table, OpenCQA, and ChartX. It outperforms several chart understanding MLLM with up to 13B parameters such as ChartLlama and ChartAst, and close-sourced general-purpose MLLM GPT-4V on ChartQA. It also demonstrates its superior efficiency with higher throughput during inference due to a smaller model scale and more efficient vision encoding. Our code and model are available at https://github.com/X-PLUG/mPLUG-DocOwl/tree/main/TinyChart.

![TinyChart：采用视觉令牌融合与思维程序学习方法，实现图表理解的高效性。](../../../paper_images/2404.16635/x1.png)

![TinyChart：采用视觉令牌融合与思维程序学习方法，实现图表理解的高效性。](../../../paper_images/2404.16635/x2.png)

![TinyChart：采用视觉令牌融合与思维程序学习方法，实现图表理解的高效性。](../../../paper_images/2404.16635/x3.png)

![TinyChart：采用视觉令牌融合与思维程序学习方法，实现图表理解的高效性。](../../../paper_images/2404.16635/x4.png)

![TinyChart：采用视觉令牌融合与思维程序学习方法，实现图表理解的高效性。](../../../paper_images/2404.16635/x5.png)

![TinyChart：采用视觉令牌融合与思维程序学习方法，实现图表理解的高效性。](../../../paper_images/2404.16635/x6.png)

![TinyChart：采用视觉令牌融合与思维程序学习方法，实现图表理解的高效性。](../../../paper_images/2404.16635/x7.png)

![TinyChart：采用视觉令牌融合与思维程序学习方法，实现图表理解的高效性。](../../../paper_images/2404.16635/x8.png)

![TinyChart：采用视觉令牌融合与思维程序学习方法，实现图表理解的高效性。](../../../paper_images/2404.16635/x9.png)

![TinyChart：采用视觉令牌融合与思维程序学习方法，实现图表理解的高效性。](../../../paper_images/2404.16635/x10.png)

![TinyChart：采用视觉令牌融合与思维程序学习方法，实现图表理解的高效性。](../../../paper_images/2404.16635/x11.png)

[Arxiv](https://arxiv.org/abs/2404.16635)