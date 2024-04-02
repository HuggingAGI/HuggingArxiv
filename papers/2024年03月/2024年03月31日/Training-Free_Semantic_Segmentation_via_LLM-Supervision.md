# 借助大型语言模型的指导，我们可以实现无需额外训练的语义分割技术。

发布时间：2024年03月31日

`LLM应用` `语义分割`

> Training-Free Semantic Segmentation via LLM-Supervision

# 摘要

> 近期开放词汇模型如CLIP的发展，通过自然语言实现类别特定嵌入，显著提升了零样本分类和分割的能力。但研究多集中于通过提示设计、学习或少量标注数据微调来提升模型精度，忽略了优化类别描述符的重要性。本研究提出了一种新颖的文本监督语义分割方法，利用大型语言模型（如GPT-3）指导，无需额外训练即可生成详细的子类集合，精准刻画各类别。接着，我们运用高级文本监督语义分割模型，以生成的子类作为目标标签，实现符合各子类特性的定制化分割效果。我们还设计了一个整合方案，融合不同子类描述的分割图，以更全面展现测试图像的多面性。经过三大标准基准的全面测试，我们的方法在性能上显著超越了传统方法。

> Recent advancements in open vocabulary models, like CLIP, have notably advanced zero-shot classification and segmentation by utilizing natural language for class-specific embeddings. However, most research has focused on improving model accuracy through prompt engineering, prompt learning, or fine-tuning with limited labeled data, thereby overlooking the importance of refining the class descriptors. This paper introduces a new approach to text-supervised semantic segmentation using supervision by a large language model (LLM) that does not require extra training. Our method starts from an LLM, like GPT-3, to generate a detailed set of subclasses for more accurate class representation. We then employ an advanced text-supervised semantic segmentation model to apply the generated subclasses as target labels, resulting in diverse segmentation results tailored to each subclass's unique characteristics. Additionally, we propose an assembly that merges the segmentation maps from the various subclass descriptors to ensure a more comprehensive representation of the different aspects in the test images. Through comprehensive experiments on three standard benchmarks, our method outperforms traditional text-supervised semantic segmentation methods by a marked margin.

![借助大型语言模型的指导，我们可以实现无需额外训练的语义分割技术。](../../../paper_images/2404.00701/x1.png)

![借助大型语言模型的指导，我们可以实现无需额外训练的语义分割技术。](../../../paper_images/2404.00701/x2.png)

![借助大型语言模型的指导，我们可以实现无需额外训练的语义分割技术。](../../../paper_images/2404.00701/x3.png)

![借助大型语言模型的指导，我们可以实现无需额外训练的语义分割技术。](../../../paper_images/2404.00701/x4.png)

![借助大型语言模型的指导，我们可以实现无需额外训练的语义分割技术。](../../../paper_images/2404.00701/x5.png)

![借助大型语言模型的指导，我们可以实现无需额外训练的语义分割技术。](../../../paper_images/2404.00701/x6.png)

![借助大型语言模型的指导，我们可以实现无需额外训练的语义分割技术。](../../../paper_images/2404.00701/x7.png)

![借助大型语言模型的指导，我们可以实现无需额外训练的语义分割技术。](../../../paper_images/2404.00701/x8.png)

![借助大型语言模型的指导，我们可以实现无需额外训练的语义分割技术。](../../../paper_images/2404.00701/x9.png)

![借助大型语言模型的指导，我们可以实现无需额外训练的语义分割技术。](../../../paper_images/2404.00701/x10.png)

![借助大型语言模型的指导，我们可以实现无需额外训练的语义分割技术。](../../../paper_images/2404.00701/x11.png)

![借助大型语言模型的指导，我们可以实现无需额外训练的语义分割技术。](../../../paper_images/2404.00701/x12.png)

![借助大型语言模型的指导，我们可以实现无需额外训练的语义分割技术。](../../../paper_images/2404.00701/x13.png)

![借助大型语言模型的指导，我们可以实现无需额外训练的语义分割技术。](../../../paper_images/2404.00701/x14.png)

![借助大型语言模型的指导，我们可以实现无需额外训练的语义分割技术。](../../../paper_images/2404.00701/x15.png)

![借助大型语言模型的指导，我们可以实现无需额外训练的语义分割技术。](../../../paper_images/2404.00701/x16.png)

![借助大型语言模型的指导，我们可以实现无需额外训练的语义分割技术。](../../../paper_images/2404.00701/x17.png)

![借助大型语言模型的指导，我们可以实现无需额外训练的语义分割技术。](../../../paper_images/2404.00701/x18.png)

![借助大型语言模型的指导，我们可以实现无需额外训练的语义分割技术。](../../../paper_images/2404.00701/x19.png)

![借助大型语言模型的指导，我们可以实现无需额外训练的语义分割技术。](../../../paper_images/2404.00701/x20.png)

![借助大型语言模型的指导，我们可以实现无需额外训练的语义分割技术。](../../../paper_images/2404.00701/x21.png)

![借助大型语言模型的指导，我们可以实现无需额外训练的语义分割技术。](../../../paper_images/2404.00701/x22.png)

![借助大型语言模型的指导，我们可以实现无需额外训练的语义分割技术。](../../../paper_images/2404.00701/x23.png)

![借助大型语言模型的指导，我们可以实现无需额外训练的语义分割技术。](../../../paper_images/2404.00701/x24.png)

![借助大型语言模型的指导，我们可以实现无需额外训练的语义分割技术。](../../../paper_images/2404.00701/x25.png)

![借助大型语言模型的指导，我们可以实现无需额外训练的语义分割技术。](../../../paper_images/2404.00701/x26.png)

![借助大型语言模型的指导，我们可以实现无需额外训练的语义分割技术。](../../../paper_images/2404.00701/x27.png)

![借助大型语言模型的指导，我们可以实现无需额外训练的语义分割技术。](../../../paper_images/2404.00701/x28.png)

![借助大型语言模型的指导，我们可以实现无需额外训练的语义分割技术。](../../../paper_images/2404.00701/x29.png)

[Arxiv](https://arxiv.org/abs/2404.00701)