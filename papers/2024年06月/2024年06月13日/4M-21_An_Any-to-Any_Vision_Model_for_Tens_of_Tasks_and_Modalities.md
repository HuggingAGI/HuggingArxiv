# 4M-21：一款全能视觉模型，轻松应对数十种任务与模态的挑战

发布时间：2024年06月13日

`RAG

理由：这篇论文主要探讨了如何通过联合训练大规模多模态数据集和文本语料库来扩展多模态和多任务基础模型的能力。它涉及了多种模态的处理和离散标记化，以及如何通过这种方式增强模型的即开即用能力。这与RAG（Retrieval-Augmented Generation）模型的概念相符，即通过结合检索和生成来提升模型的性能和适应性。因此，这篇论文更适合归类于RAG。` `多模态学习` `人工智能`

> 4M-21: An Any-to-Any Vision Model for Tens of Tasks and Modalities

# 摘要

> 尽管像4M或UnifiedIO这样的多模态和多任务基础模型前景看好，但它们的即开即用能力受限于其训练的模态和任务数量，通常较为有限。本研究通过训练一个单一模型在数十种高度多样化的模态上，并结合大规模多模态数据集和文本语料库进行联合训练，显著扩展了这些模型的能力。我们涵盖了多种语义和几何模态，利用了如DINOv2和ImageBind等尖端模型的特征图，以及专家模型如SAM和4DHumans的伪标签，并引入了一系列新模态，如图像元数据或调色板，以创新方式与模型互动和指导生成。关键在于对各种模态进行离散标记化，无论是图像、神经网络特征、向量、结构化数据还是文本形式的数据。这一进展不仅增强了多模态模型的即开即用能力，还展示了单个模型能解决至少三倍于现有模型的任务/模态，且性能不受影响。这为更精细、可控的多模态生成开辟了道路，并使我们能够探索将多样数据和目标训练的模型整合成统一模型的可能性。我们已成功训练出一个拥有三十亿参数的模型，使用多种模态和数据集，相关模型和训练代码已在4m.epfl.ch上开源。

> Current multimodal and multitask foundation models like 4M or UnifiedIO show promising results, but in practice their out-of-the-box abilities to accept diverse inputs and perform diverse tasks are limited by the (usually rather small) number of modalities and tasks they are trained on. In this paper, we expand upon the capabilities of them by training a single model on tens of highly diverse modalities and by performing co-training on large-scale multimodal datasets and text corpora. This includes training on several semantic and geometric modalities, feature maps from recent state of the art models like DINOv2 and ImageBind, pseudo labels of specialist models like SAM and 4DHumans, and a range of new modalities that allow for novel ways to interact with the model and steer the generation, for example image metadata or color palettes. A crucial step in this process is performing discrete tokenization on various modalities, whether they are image-like, neural network feature maps, vectors, structured data like instance segmentation or human poses, or data that can be represented as text. Through this, we expand on the out-of-the-box capabilities of multimodal models and specifically show the possibility of training one model to solve at least 3x more tasks/modalities than existing ones and doing so without a loss in performance. This enables more fine-grained and controllable multimodal generation capabilities and allows us to study the distillation of models trained on diverse data and objectives into a unified model. We successfully scale the training to a three billion parameter model using tens of modalities and different datasets. The resulting models and training code are open sourced at 4m.epfl.ch.

![4M-21：一款全能视觉模型，轻松应对数十种任务与模态的挑战](../../../paper_images/2406.09406/x2.png)

![4M-21：一款全能视觉模型，轻松应对数十种任务与模态的挑战](../../../paper_images/2406.09406/x3.png)

![4M-21：一款全能视觉模型，轻松应对数十种任务与模态的挑战](../../../paper_images/2406.09406/x4.png)

![4M-21：一款全能视觉模型，轻松应对数十种任务与模态的挑战](../../../paper_images/2406.09406/x5.png)

![4M-21：一款全能视觉模型，轻松应对数十种任务与模态的挑战](../../../paper_images/2406.09406/x6.png)

![4M-21：一款全能视觉模型，轻松应对数十种任务与模态的挑战](../../../paper_images/2406.09406/x7.png)

![4M-21：一款全能视觉模型，轻松应对数十种任务与模态的挑战](../../../paper_images/2406.09406/x8.png)

![4M-21：一款全能视觉模型，轻松应对数十种任务与模态的挑战](../../../paper_images/2406.09406/x9.png)

![4M-21：一款全能视觉模型，轻松应对数十种任务与模态的挑战](../../../paper_images/2406.09406/x10.png)

![4M-21：一款全能视觉模型，轻松应对数十种任务与模态的挑战](../../../paper_images/2406.09406/x11.png)

![4M-21：一款全能视觉模型，轻松应对数十种任务与模态的挑战](../../../paper_images/2406.09406/x12.png)

![4M-21：一款全能视觉模型，轻松应对数十种任务与模态的挑战](../../../paper_images/2406.09406/x13.png)

![4M-21：一款全能视觉模型，轻松应对数十种任务与模态的挑战](../../../paper_images/2406.09406/x14.png)

![4M-21：一款全能视觉模型，轻松应对数十种任务与模态的挑战](../../../paper_images/2406.09406/x15.png)

[Arxiv](https://arxiv.org/abs/2406.09406)