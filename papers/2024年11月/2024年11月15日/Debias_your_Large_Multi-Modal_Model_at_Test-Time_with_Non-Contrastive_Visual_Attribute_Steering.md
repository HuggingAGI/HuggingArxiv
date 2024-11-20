# 在测试阶段，借助非对比视觉属性引导来对您的大型多模态模型进行去偏处理。

发布时间：2024年11月15日

`LLM应用` `多模态模型` `去偏框架`

> Debias your Large Multi-Modal Model at Test-Time with Non-Contrastive Visual Attribute Steering

# 摘要

> 大型多模态模型（LMMs）作为通用聊天机器人，能针对给定输入（比如图像）展开对话，能力令人瞩目。但它们的回答受训练数据集中社会偏见的影响，面对描绘不同人群的图像时，模型的响应会有不良差异。在本研究中，我们为 LMMs 提出了全新的去偏框架，能在文本生成时直接去除偏差表征，减少与受保护属性相关的输出，甚至从内部进行表征。我们的方法无需训练，给定一张图像和目标属性列表，仅需对图像本身进行一步梯度下降就能消除相应表征。实验表明，我们不仅能最大程度降低 LMMs 生成与受保护属性相关文本的倾向，还能改善情绪，甚至能用合成数据为消除提供信息，同时在 COCO 或 FACET 等真实数据上保留语言建模能力。此外，去偏后的 LMM 生成结果与基线有偏模型的准确性相似，这表明去偏效果的实现无需牺牲模型性能。

> Large Multi-Modal Models (LMMs) have demonstrated impressive capabilities as general-purpose chatbots that can engage in conversations about a provided input, such as an image. However, their responses are influenced by societal biases present in their training datasets, leading to undesirable differences in how the model responds when presented with images depicting people of different demographics. In this work, we propose a novel debiasing framework for LMMs that directly removes biased representations during text generation to decrease outputs related to protected attributes, or even representing them internally. Our proposed method is training-free; given a single image and a list of target attributes, we can ablate the corresponding representations with just one step of gradient descent on the image itself. Our experiments show that not only can we can minimize the propensity of LMMs to generate text related to protected attributes, but we can improve sentiment and even simply use synthetic data to inform the ablation while retaining language modeling capabilities on real data such as COCO or FACET. Furthermore, we find the resulting generations from a debiased LMM exhibit similar accuracy as a baseline biased model, showing that debiasing effects can be achieved without sacrificing model performance.

[Arxiv](https://arxiv.org/abs/2411.12590)