# Transformer 层如同画家

发布时间：2024年07月12日

`LLM理论` `人工智能` `计算机科学`

> Transformer Layers as Painters

# 摘要

> 尽管transformer在大型语言模型中广泛应用，但其内部机制仍是个谜。我们旨在深入探究在预训练transformer中移除或重组信息的影响，这不仅能优化现有模型的使用，还能通过架构创新带来新变体。我们的实证研究发现，预训练transformer的底层和顶层与中间层存在差异，而中间层却展现出惊人的一致性。此外，我们发现某些问题类型对层跳过、非顺序运行或并行处理具有鲁棒性。这些观察暗示，即使是冻结的预训练模型，也能通过层跳过或并行处理，优雅地平衡准确性与延迟。

> Despite their nearly universal adoption for large language models, the internal workings of transformers are not well understood. We aim to better understand the impact of removing or reorganizing information throughout the layers of a pretrained transformer. Such an understanding could both yield better usage of existing models as well as to make architectural improvements to produce new variants. We present a series of empirical studies on frozen models that show that the lower and final layers of pretrained transformers differ from middle layers, but that middle layers have a surprising amount of uniformity. We further show that some classes of problems have robustness to skipping layers, running the layers in an order different from how they were trained, or running the layers in parallel. Our observations suggest that even frozen pretrained models may gracefully trade accuracy for latency by skipping layers or running layers in parallel.

![Transformer 层如同画家](../../../paper_images/2407.09298/x1.png)

![Transformer 层如同画家](../../../paper_images/2407.09298/x2.png)

![Transformer 层如同画家](../../../paper_images/2407.09298/x3.png)

![Transformer 层如同画家](../../../paper_images/2407.09298/x4.png)

![Transformer 层如同画家](../../../paper_images/2407.09298/x5.png)

![Transformer 层如同画家](../../../paper_images/2407.09298/x6.png)

![Transformer 层如同画家](../../../paper_images/2407.09298/x7.png)

![Transformer 层如同画家](../../../paper_images/2407.09298/x8.png)

![Transformer 层如同画家](../../../paper_images/2407.09298/x9.png)

![Transformer 层如同画家](../../../paper_images/2407.09298/x10.png)

![Transformer 层如同画家](../../../paper_images/2407.09298/x11.png)

![Transformer 层如同画家](../../../paper_images/2407.09298/x12.png)

![Transformer 层如同画家](../../../paper_images/2407.09298/x13.png)

![Transformer 层如同画家](../../../paper_images/2407.09298/x14.png)

![Transformer 层如同画家](../../../paper_images/2407.09298/x15.png)

![Transformer 层如同画家](../../../paper_images/2407.09298/x16.png)

![Transformer 层如同画家](../../../paper_images/2407.09298/x17.png)

![Transformer 层如同画家](../../../paper_images/2407.09298/x18.png)

![Transformer 层如同画家](../../../paper_images/2407.09298/x19.png)

![Transformer 层如同画家](../../../paper_images/2407.09298/x20.png)

![Transformer 层如同画家](../../../paper_images/2407.09298/x21.png)

![Transformer 层如同画家](../../../paper_images/2407.09298/x22.png)

![Transformer 层如同画家](../../../paper_images/2407.09298/x23.png)

![Transformer 层如同画家](../../../paper_images/2407.09298/x24.png)

![Transformer 层如同画家](../../../paper_images/2407.09298/x25.png)

![Transformer 层如同画家](../../../paper_images/2407.09298/x26.png)

![Transformer 层如同画家](../../../paper_images/2407.09298/x27.png)

![Transformer 层如同画家](../../../paper_images/2407.09298/x28.png)

![Transformer 层如同画家](../../../paper_images/2407.09298/x29.png)

![Transformer 层如同画家](../../../paper_images/2407.09298/x30.png)

![Transformer 层如同画家](../../../paper_images/2407.09298/x31.png)

![Transformer 层如同画家](../../../paper_images/2407.09298/x32.png)

![Transformer 层如同画家](../../../paper_images/2407.09298/x33.png)

[Arxiv](https://arxiv.org/abs/2407.09298)