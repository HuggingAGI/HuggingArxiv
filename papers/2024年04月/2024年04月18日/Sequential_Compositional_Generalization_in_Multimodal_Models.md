# 多模态模型中的顺序组合泛化

发布时间：2024年04月18日

`分类：RAG` `计算机视觉` `人工智能`

> Sequential Compositional Generalization in Multimodal Models

# 摘要

> 随着大规模多模态模型的兴起，生成建模和推理领域迎来了革命性的进步，为多样化的复杂任务带来了创新应用。但一个尚未充分探讨的关键问题是这些模型在更强大的泛化能力上的真实潜力。本研究通过分析 \textsc{CompAct} 数据集来探讨序列组合泛化，该数据集是在一个丰富的第一人称厨房活动视频背景下精心构建的，以感知为基础。数据集中的每个案例都结合了原始视频、自然声音和众包的分步描述。关键的是，我们的设计确保了各个概念在训练和评估集中的一致性分布，同时在评估集中呈现出新颖的组合。我们对多种单模态和多模态模型进行了深入评估。研究结果显示，双模态和三模态模型在性能上明显超越了仅文本的模型，这不仅凸显了多模态输入的重要性，也为未来研究指明了新的方向。

> The rise of large-scale multimodal models has paved the pathway for groundbreaking advances in generative modeling and reasoning, unlocking transformative applications in a variety of complex tasks. However, a pressing question that remains is their genuine capability for stronger forms of generalization, which has been largely underexplored in the multimodal setting. Our study aims to address this by examining sequential compositional generalization using \textsc{CompAct} (\underline{Comp}ositional \underline{Act}ivities)\footnote{Project Page: \url{http://cyberiada.github.io/CompAct}}, a carefully constructed, perceptually grounded dataset set within a rich backdrop of egocentric kitchen activity videos. Each instance in our dataset is represented with a combination of raw video footage, naturally occurring sound, and crowd-sourced step-by-step descriptions. More importantly, our setup ensures that the individual concepts are consistently distributed across training and evaluation sets, while their compositions are novel in the evaluation set. We conduct a comprehensive assessment of several unimodal and multimodal models. Our findings reveal that bi-modal and tri-modal models exhibit a clear edge over their text-only counterparts. This highlights the importance of multimodality while charting a trajectory for future research in this domain.

![多模态模型中的顺序组合泛化](../../../paper_images/2404.12013/x1.png)

![多模态模型中的顺序组合泛化](../../../paper_images/2404.12013/x2.png)

![多模态模型中的顺序组合泛化](../../../paper_images/2404.12013/x3.png)

![多模态模型中的顺序组合泛化](../../../paper_images/2404.12013/x4.png)

![多模态模型中的顺序组合泛化](../../../paper_images/2404.12013/x5.png)

![多模态模型中的顺序组合泛化](../../../paper_images/2404.12013/x6.png)

![多模态模型中的顺序组合泛化](../../../paper_images/2404.12013/x7.png)

![多模态模型中的顺序组合泛化](../../../paper_images/2404.12013/x8.png)

![多模态模型中的顺序组合泛化](../../../paper_images/2404.12013/x9.png)

![多模态模型中的顺序组合泛化](../../../paper_images/2404.12013/audio-rinse.png)

![多模态模型中的顺序组合泛化](../../../paper_images/2404.12013/vision-fridge.png)

[Arxiv](https://arxiv.org/abs/2404.12013)