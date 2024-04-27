# 文本内容如何作用于多模态情境学习（ICL）的信息检索？

发布时间：2024年04月19日

`分类：LLM应用` `人工智能` `机器学习`

> How Does the Textual Information Affect the Retrieval of Multimodal In-Context Learning?

# 摘要

> 随着多模态大型语言模型（MLLMs）参数规模的扩大，它们在上下文学习方面展现出显著的潜力，尤其是在不更新预训练参数的情况下提升任务执行能力。然而，这种提升高度依赖于恰当的上下文示例选择，目前这一选择过程存在偏差，倾向于视觉数据而忽略了文本信息。此外，对于优化上下文示例选择至关重要的MLLMs监督检索器领域，尚未得到充分研究。本研究深入探讨了文本信息在多模态上下文中对无监督选择上下文示例的影响，发现检索器性能对所采用的模态极为敏感。为此，我们提出了一种创新的监督MLLM-检索器MSIER，利用神经网络挑选能够提升多模态上下文学习效率的示例。这一方法通过在三项不同任务上的广泛测试得到了验证。同时，我们还研究了模态对我们监督检索方法训练的影响，并识别了推动模型成功的关键因素。这项研究为未来的技术进步奠定了基础，展示了通过策略性地使用多模态数据，MLLMs的上下文学习能力有望得到进一步提升。

> The increase in parameter size of multimodal large language models (MLLMs) introduces significant capabilities, particularly in-context learning, where MLLMs enhance task performance without updating pre-trained parameters. This effectiveness, however, hinges on the appropriate selection of in-context examples, a process that is currently biased towards visual data, overlooking textual information. Furthermore, the area of supervised retrievers for MLLMs, crucial for optimal in-context example selection, continues to be uninvestigated. Our study offers an in-depth evaluation of the impact of textual information on the unsupervised selection of in-context examples in multimodal contexts, uncovering a notable sensitivity of retriever performance to the employed modalities. Responding to this, we introduce a novel supervised MLLM-retriever MSIER that employs a neural network to select examples that enhance multimodal in-context learning efficiency. This approach is validated through extensive testing across three distinct tasks, demonstrating the method's effectiveness. Additionally, we investigate the influence of modalities on our supervised retrieval method's training and pinpoint factors contributing to our model's success. This exploration paves the way for future advancements, highlighting the potential for refined in-context learning in MLLMs through the strategic use of multimodal data.

![文本内容如何作用于多模态情境学习（ICL）的信息检索？](../../../paper_images/2404.12866/x1.png)

![文本内容如何作用于多模态情境学习（ICL）的信息检索？](../../../paper_images/2404.12866/x2.png)

![文本内容如何作用于多模态情境学习（ICL）的信息检索？](../../../paper_images/2404.12866/x3.png)

![文本内容如何作用于多模态情境学习（ICL）的信息检索？](../../../paper_images/2404.12866/x4.png)

![文本内容如何作用于多模态情境学习（ICL）的信息检索？](../../../paper_images/2404.12866/x5.png)

![文本内容如何作用于多模态情境学习（ICL）的信息检索？](../../../paper_images/2404.12866/x6.png)

[Arxiv](https://arxiv.org/abs/2404.12866)