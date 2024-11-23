# 《大声追梦：基于发展合理数据训练视觉语言模型的自合成之法》

发布时间：2024年10月29日

`LLM应用` `人工智能` `多模态模型`

> Dreaming Out Loud: A Self-Synthesis Approach For Training Vision-Language Models With Developmentally Plausible Data

# 摘要

> 虽说当下的大型语言模型在生成类人文本时能力出众，但训练时却需要海量数据。在此，我们从人类认知发展中获得启发，于有限数据条件下训练模型。具体来讲，我们给出了一种自合成方法，它历经四个阶段：第一阶段构建基础语言能力，在小语料库上从零开始训练模型。第二阶段将语言与视觉环境相联系，把模型和视觉编码器结合，从有标签的图像生成描述性标题。在“自合成”的第三阶段，模型为未标注的图像生成标题，然后用这些标题与合成文本及之前的真实文本混合，进一步训练语言部分。这一阶段意在扩充模型的语言储备，就像人类为新经历进行自我标注一样。最后，第四阶段通过在特定任务（如视觉问答和推理）上训练模型来培养高级认知技能。我们的方法为使用发展上合理数量的数据训练多模态模型提供了概念验证。

> While today's large language models exhibit impressive abilities in generating human-like text, they require massive amounts of data during training. We here take inspiration from human cognitive development to train models in limited data conditions. Specifically we present a self-synthesis approach that iterates through four phases: Phase 1 sets up fundamental language abilities, training the model from scratch on a small corpus. Language is then associated with the visual environment in phase 2, integrating the model with a vision encoder to generate descriptive captions from labeled images. In the "self-synthesis" phase 3, the model generates captions for unlabeled images, that it then uses to further train its language component with a mix of synthetic, and previous real-world text. This phase is meant to expand the model's linguistic repertoire, similar to humans self-annotating new experiences. Finally, phase 4 develops advanced cognitive skills, by training the model on specific tasks such as visual question answering and reasoning. Our approach offers a proof of concept for training a multimodal model using a developmentally plausible amount of data.

[Arxiv](https://arxiv.org/abs/2411.00828)