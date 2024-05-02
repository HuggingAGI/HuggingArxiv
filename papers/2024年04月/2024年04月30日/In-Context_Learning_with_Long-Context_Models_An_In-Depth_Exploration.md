# 深入探索长文本上下文模型中的上下文内学习

发布时间：2024年04月30日

`LLM理论` `机器学习` `人工智能`

> In-Context Learning with Long-Context Models: An In-Depth Exploration

# 摘要

> 随着模型能够处理的上下文长度增加，能够在上下文中展示的示例数量逐渐逼近整个训练集的规模。我们在不同数据集和模型上探究了在这种极端规模下的上下文内学习（ICL）的表现。研究发现，在拥有广泛标签空间的众多数据集中，性能随着数百至数千个示例的增加而持续提升。这一现象与示例检索和微调的效果形成鲜明对比：示例检索在较短上下文长度时效果显著，但随着示例数量增加，其增益逐渐减少；而微调虽然对数据的需求超过ICL，但在引入更多数据后，有时能超越长上下文ICL的表现。我们利用ICL的这一设置，深入研究了上下文内学习和长上下文模型的多个特性。我们发现，长上下文ICL对随机输入顺序的干扰更为不敏感，同标签示例的集中可能对性能产生负面影响，而我们观察到的性能提升并非源自于同时编码多个示例的累积效应。综上所述，尽管长上下文ICL的效果出人意料地好，但其主要优势更多来自于对类似示例的回顾，而非对任务本身的学习。

> As model context lengths continue to increase, the number of demonstrations that can be provided in-context approaches the size of entire training datasets. We study the behavior of in-context learning (ICL) at this extreme scale on multiple datasets and models. We show that, for many datasets with large label spaces, performance continues to increase with hundreds or thousands of demonstrations. We contrast this with example retrieval and finetuning: example retrieval shows excellent performance at low context lengths but has diminished gains with more demonstrations; finetuning is more data hungry than ICL but can sometimes exceed long-context ICL performance with additional data. We use this ICL setting as a testbed to study several properties of both in-context learning and long-context models. We show that long-context ICL is less sensitive to random input shuffling than short-context ICL, that grouping of same-label examples can negatively impact performance, and that the performance boosts we see do not arise from cumulative gain from encoding many examples together. We conclude that although long-context ICL can be surprisingly effective, most of this gain comes from attending back to similar examples rather than task learning.

![深入探索长文本上下文模型中的上下文内学习](../../../paper_images/2405.00200/x1.png)

![深入探索长文本上下文模型中的上下文内学习](../../../paper_images/2405.00200/x2.png)

![深入探索长文本上下文模型中的上下文内学习](../../../paper_images/2405.00200/x3.png)

![深入探索长文本上下文模型中的上下文内学习](../../../paper_images/2405.00200/x4.png)

![深入探索长文本上下文模型中的上下文内学习](../../../paper_images/2405.00200/x5.png)

![深入探索长文本上下文模型中的上下文内学习](../../../paper_images/2405.00200/x6.png)

![深入探索长文本上下文模型中的上下文内学习](../../../paper_images/2405.00200/x7.png)

![深入探索长文本上下文模型中的上下文内学习](../../../paper_images/2405.00200/x8.png)

![深入探索长文本上下文模型中的上下文内学习](../../../paper_images/2405.00200/x9.png)

![深入探索长文本上下文模型中的上下文内学习](../../../paper_images/2405.00200/x10.png)

![深入探索长文本上下文模型中的上下文内学习](../../../paper_images/2405.00200/x11.png)

![深入探索长文本上下文模型中的上下文内学习](../../../paper_images/2405.00200/x12.png)

![深入探索长文本上下文模型中的上下文内学习](../../../paper_images/2405.00200/x13.png)

![深入探索长文本上下文模型中的上下文内学习](../../../paper_images/2405.00200/x14.png)

![深入探索长文本上下文模型中的上下文内学习](../../../paper_images/2405.00200/x15.png)

![深入探索长文本上下文模型中的上下文内学习](../../../paper_images/2405.00200/x16.png)

![深入探索长文本上下文模型中的上下文内学习](../../../paper_images/2405.00200/x17.png)

![深入探索长文本上下文模型中的上下文内学习](../../../paper_images/2405.00200/x18.png)

![深入探索长文本上下文模型中的上下文内学习](../../../paper_images/2405.00200/x19.png)

![深入探索长文本上下文模型中的上下文内学习](../../../paper_images/2405.00200/x20.png)

![深入探索长文本上下文模型中的上下文内学习](../../../paper_images/2405.00200/x21.png)

![深入探索长文本上下文模型中的上下文内学习](../../../paper_images/2405.00200/x22.png)

![深入探索长文本上下文模型中的上下文内学习](../../../paper_images/2405.00200/x23.png)

![深入探索长文本上下文模型中的上下文内学习](../../../paper_images/2405.00200/x24.png)

![深入探索长文本上下文模型中的上下文内学习](../../../paper_images/2405.00200/x25.png)

![深入探索长文本上下文模型中的上下文内学习](../../../paper_images/2405.00200/x26.png)

![深入探索长文本上下文模型中的上下文内学习](../../../paper_images/2405.00200/x27.png)

![深入探索长文本上下文模型中的上下文内学习](../../../paper_images/2405.00200/x28.png)

![深入探索长文本上下文模型中的上下文内学习](../../../paper_images/2405.00200/x29.png)

![深入探索长文本上下文模型中的上下文内学习](../../../paper_images/2405.00200/x30.png)

![深入探索长文本上下文模型中的上下文内学习](../../../paper_images/2405.00200/x31.png)

![深入探索长文本上下文模型中的上下文内学习](../../../paper_images/2405.00200/x32.png)

![深入探索长文本上下文模型中的上下文内学习](../../../paper_images/2405.00200/x33.png)

![深入探索长文本上下文模型中的上下文内学习](../../../paper_images/2405.00200/x34.png)

![深入探索长文本上下文模型中的上下文内学习](../../../paper_images/2405.00200/x35.png)

[Arxiv](https://arxiv.org/abs/2405.00200)