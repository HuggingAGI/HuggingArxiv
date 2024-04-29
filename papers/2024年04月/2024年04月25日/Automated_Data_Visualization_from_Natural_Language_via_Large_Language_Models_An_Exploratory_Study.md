# 本研究探索了利用大型语言模型将自然语言自动转换为数据可视化的过程。

发布时间：2024年04月25日

`LLM应用` `数据可视化`

> Automated Data Visualization from Natural Language via Large Language Models: An Exploratory Study

# 摘要

> 自然语言到可视化（NL2Vis）任务致力于将自然语言描述转换成可视化的表格数据，以便用户能从海量数据中洞察信息。尽管基于深度学习的多种方法已应运而生，但在将未见数据库或跨多表的数据可视化时，仍面临挑战。本文借鉴大型语言模型（LLMs）的卓越生成能力，通过实证研究来评估其在创建可视化方面的能力，并探讨使用上下文学习提示来提升任务效果的可能性。我们首先研究了如何将结构化表格数据转化为连续文本提示，以便输入LLMs，并分析了哪些表格内容对NL2Vis最为关键。研究结果显示，将表格数据转化为程序文本是有效的，同时在构建提示时考虑表格结构是必要的。我们还对比了两种LLMs：经过微调的模型（如T5-Small）和仅限推理的模型（如GPT-3.5），并与现有最先进方法进行了比较。实验结果显示，LLMs在性能上超越了基线，尤其是仅限推理模型在上下文学习中通过少量示例的引导，有时甚至能超越微调模型。最后，我们深入分析了LLMs在NL2Vis中的不足，并提出了通过链式思考、角色扮演和代码解释等策略来迭代优化结果。实验结果证明了迭代更新策略的有效性，并为未来的研究开辟了新的可能性。

> The Natural Language to Visualization (NL2Vis) task aims to transform natural-language descriptions into visual representations for a grounded table, enabling users to gain insights from vast amounts of data. Recently, many deep learning-based approaches have been developed for NL2Vis. Despite the considerable efforts made by these approaches, challenges persist in visualizing data sourced from unseen databases or spanning multiple tables. Taking inspiration from the remarkable generation capabilities of Large Language Models (LLMs), this paper conducts an empirical study to evaluate their potential in generating visualizations, and explore the effectiveness of in-context learning prompts for enhancing this task. In particular, we first explore the ways of transforming structured tabular data into sequential text prompts, as to feed them into LLMs and analyze which table content contributes most to the NL2Vis. Our findings suggest that transforming structured tabular data into programs is effective, and it is essential to consider the table schema when formulating prompts. Furthermore, we evaluate two types of LLMs: finetuned models (e.g., T5-Small) and inference-only models (e.g., GPT-3.5), against state-of-the-art methods, using the NL2Vis benchmarks (i.e., nvBench). The experimental results reveal that LLMs outperform baselines, with inference-only models consistently exhibiting performance improvements, at times even surpassing fine-tuned models when provided with certain few-shot demonstrations through in-context learning. Finally, we analyze when the LLMs fail in NL2Vis, and propose to iteratively update the results using strategies such as chain-of-thought, role-playing, and code-interpreter. The experimental results confirm the efficacy of iterative updates and hold great potential for future study.

![本研究探索了利用大型语言模型将自然语言自动转换为数据可视化的过程。](../../../paper_images/2404.17136/x1.png)

![本研究探索了利用大型语言模型将自然语言自动转换为数据可视化的过程。](../../../paper_images/2404.17136/x2.png)

![本研究探索了利用大型语言模型将自然语言自动转换为数据可视化的过程。](../../../paper_images/2404.17136/x3.png)

![本研究探索了利用大型语言模型将自然语言自动转换为数据可视化的过程。](../../../paper_images/2404.17136/x4.png)

![本研究探索了利用大型语言模型将自然语言自动转换为数据可视化的过程。](../../../paper_images/2404.17136/x5.png)

![本研究探索了利用大型语言模型将自然语言自动转换为数据可视化的过程。](../../../paper_images/2404.17136/x6.png)

![本研究探索了利用大型语言模型将自然语言自动转换为数据可视化的过程。](../../../paper_images/2404.17136/x7.png)

![本研究探索了利用大型语言模型将自然语言自动转换为数据可视化的过程。](../../../paper_images/2404.17136/x8.png)

![本研究探索了利用大型语言模型将自然语言自动转换为数据可视化的过程。](../../../paper_images/2404.17136/x9.png)

![本研究探索了利用大型语言模型将自然语言自动转换为数据可视化的过程。](../../../paper_images/2404.17136/x10.png)

![本研究探索了利用大型语言模型将自然语言自动转换为数据可视化的过程。](../../../paper_images/2404.17136/x11.png)

![本研究探索了利用大型语言模型将自然语言自动转换为数据可视化的过程。](../../../paper_images/2404.17136/x12.png)

![本研究探索了利用大型语言模型将自然语言自动转换为数据可视化的过程。](../../../paper_images/2404.17136/x13.png)

![本研究探索了利用大型语言模型将自然语言自动转换为数据可视化的过程。](../../../paper_images/2404.17136/x14.png)

![本研究探索了利用大型语言模型将自然语言自动转换为数据可视化的过程。](../../../paper_images/2404.17136/x15.png)

![本研究探索了利用大型语言模型将自然语言自动转换为数据可视化的过程。](../../../paper_images/2404.17136/x16.png)

![本研究探索了利用大型语言模型将自然语言自动转换为数据可视化的过程。](../../../paper_images/2404.17136/x17.png)

![本研究探索了利用大型语言模型将自然语言自动转换为数据可视化的过程。](../../../paper_images/2404.17136/x18.png)

![本研究探索了利用大型语言模型将自然语言自动转换为数据可视化的过程。](../../../paper_images/2404.17136/x19.png)

![本研究探索了利用大型语言模型将自然语言自动转换为数据可视化的过程。](../../../paper_images/2404.17136/x20.png)

![本研究探索了利用大型语言模型将自然语言自动转换为数据可视化的过程。](../../../paper_images/2404.17136/x21.png)

[Arxiv](https://arxiv.org/abs/2404.17136)