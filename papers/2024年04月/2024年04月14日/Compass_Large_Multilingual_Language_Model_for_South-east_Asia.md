# 指南针：为东南亚地区量身打造的大型多语言语言模型

发布时间：2024年04月14日

`LLM应用` `分类：东南亚语言处理` `多语言模型`

> Compass: Large Multilingual Language Model for South-east Asia

# 摘要

> 大型语言模型在英语、汉语等资源丰富的语言中表现卓越，但在东南亚地区，尤其是印尼语这类资源匮乏的语言中，效果大打折扣。面对这一挑战，我们推出了 CompassLLM，这款针对东南亚语言定制的多语言模型，旨在满足 Shopee 的发展需求。我们采取了分阶段预训练和课程学习的策略，逐步聚焦低资源语言，并创建了一个多语言指导库，通过监督学习微调，打造出 CompassLLM-SFT 模型。进一步采用直接偏好优化原则，形成了 CompassLLM-DPO 模型。初步评估显示，我们的模型在各项评估任务中均超越了现有基准模型，特别是在东南亚语言，如印尼语方面，展现出卓越的性能。

> Large language models have exhibited significant proficiency in languages endowed with extensive linguistic resources, such as English and Chinese. Nevertheless, their effectiveness notably diminishes when applied to languages characterized by limited linguistic resources, particularly within the Southeast Asian linguistic landscape, such as Indonesian. The scarcity of linguistic resources for these languages presents challenges associated with inadequate training, restricted vocabulary coverage, and challenging evaluation processes. In response to these exigencies, we have introduced CompassLLM, a large multilingual model specifically tailored for Southeast Asian languages, with the primary aim of supporting the developmental requirements of Shopee. Our methodology encompasses several key strategies. To progressively enhance multilingual proficiencies, we implemented a multi-stage pre-training strategy integrated with curriculum learning, gradually intensifying the focus on low-resource languages. Concurrently, to better accommodate low-resource human instructions, we curated and generated a repository of high-quality multilingual human instructions, culminating the CompassLLM-SFT model through supervised instruction fine-tuning. Finally, to reinforce the model's alignment with human preference behaviors, we have embraced the principle of Direct Preference Optimization (DPO) to obtain CompassLLM-DPO model. Preliminary evaluation of the CompassLLM model yields promising results, with our model surpassing benchmark models like Vicuna-7b-v1.5, Sealion, Falcon and SeaLLM, across diverse evaluation tasks, as verified through both automated and human-driven assessments. Notably, our model exhibits its superior performance in South-east Asia languages, such as Indonesian language.

![指南针：为东南亚地区量身打造的大型多语言语言模型](../../../paper_images/2404.09220/x1.png)

![指南针：为东南亚地区量身打造的大型多语言语言模型](../../../paper_images/2404.09220/x2.png)

![指南针：为东南亚地区量身打造的大型多语言语言模型](../../../paper_images/2404.09220/x3.png)

![指南针：为东南亚地区量身打造的大型多语言语言模型](../../../paper_images/2404.09220/x4.png)

![指南针：为东南亚地区量身打造的大型多语言语言模型](../../../paper_images/2404.09220/x5.png)

![指南针：为东南亚地区量身打造的大型多语言语言模型](../../../paper_images/2404.09220/x6.png)

![指南针：为东南亚地区量身打造的大型多语言语言模型](../../../paper_images/2404.09220/x7.png)

![指南针：为东南亚地区量身打造的大型多语言语言模型](../../../paper_images/2404.09220/x8.png)

![指南针：为东南亚地区量身打造的大型多语言语言模型](../../../paper_images/2404.09220/x9.png)

![指南针：为东南亚地区量身打造的大型多语言语言模型](../../../paper_images/2404.09220/x10.png)

![指南针：为东南亚地区量身打造的大型多语言语言模型](../../../paper_images/2404.09220/x11.png)

![指南针：为东南亚地区量身打造的大型多语言语言模型](../../../paper_images/2404.09220/x12.png)

![指南针：为东南亚地区量身打造的大型多语言语言模型](../../../paper_images/2404.09220/safety_pipeline.png)

![指南针：为东南亚地区量身打造的大型多语言语言模型](../../../paper_images/2404.09220/x13.png)

![指南针：为东南亚地区量身打造的大型多语言语言模型](../../../paper_images/2404.09220/x14.png)

![指南针：为东南亚地区量身打造的大型多语言语言模型](../../../paper_images/2404.09220/x15.png)

![指南针：为东南亚地区量身打造的大型多语言语言模型](../../../paper_images/2404.09220/x16.png)

![指南针：为东南亚地区量身打造的大型多语言语言模型](../../../paper_images/2404.09220/x17.png)

![指南针：为东南亚地区量身打造的大型多语言语言模型](../../../paper_images/2404.09220/x18.png)

![指南针：为东南亚地区量身打造的大型多语言语言模型](../../../paper_images/2404.09220/x19.png)

![指南针：为东南亚地区量身打造的大型多语言语言模型](../../../paper_images/2404.09220/x20.png)

![指南针：为东南亚地区量身打造的大型多语言语言模型](../../../paper_images/2404.09220/x21.png)

![指南针：为东南亚地区量身打造的大型多语言语言模型](../../../paper_images/2404.09220/x22.png)

![指南针：为东南亚地区量身打造的大型多语言语言模型](../../../paper_images/2404.09220/x23.png)

![指南针：为东南亚地区量身打造的大型多语言语言模型](../../../paper_images/2404.09220/x24.png)

![指南针：为东南亚地区量身打造的大型多语言语言模型](../../../paper_images/2404.09220/x25.png)

![指南针：为东南亚地区量身打造的大型多语言语言模型](../../../paper_images/2404.09220/x26.png)

![指南针：为东南亚地区量身打造的大型多语言语言模型](../../../paper_images/2404.09220/x27.png)

![指南针：为东南亚地区量身打造的大型多语言语言模型](../../../paper_images/2404.09220/x28.png)

![指南针：为东南亚地区量身打造的大型多语言语言模型](../../../paper_images/2404.09220/x29.png)

![指南针：为东南亚地区量身打造的大型多语言语言模型](../../../paper_images/2404.09220/x30.png)

![指南针：为东南亚地区量身打造的大型多语言语言模型](../../../paper_images/2404.09220/x31.png)

![指南针：为东南亚地区量身打造的大型多语言语言模型](../../../paper_images/2404.09220/x32.png)

![指南针：为东南亚地区量身打造的大型多语言语言模型](../../../paper_images/2404.09220/x33.png)

![指南针：为东南亚地区量身打造的大型多语言语言模型](../../../paper_images/2404.09220/x34.png)

[Arxiv](https://arxiv.org/abs/2404.09220)