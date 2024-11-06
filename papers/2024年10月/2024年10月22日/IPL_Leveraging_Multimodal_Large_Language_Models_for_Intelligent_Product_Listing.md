# IPL：利用多模态大型语言模型实现智能产品列表

发布时间：2024年10月22日

`LLM应用` `电子商务` `C2C 平台`

> IPL: Leveraging Multimodal Large Language Models for Intelligent Product Listing

# 摘要

> 摘要：与专业的企业对消费者（B2C）电子商务平台（例如亚马逊）不同，消费者对消费者（C2C）平台（例如 Facebook 市场）主要针对通常在电子商务方面缺乏足够经验的个人卖家。个人卖家经常难以编写适当的销售产品描述。随着多模态大型语言模型（MLLM）的最新进展，我们试图将这种最先进的生成式人工智能技术集成到产品列表流程中。为此，我们开发了 IPL，这是一种智能产品列表工具，专门用于使用各种产品属性（如类别、品牌、颜色、状况等）生成描述。IPL 允许用户仅通过上传销售产品的照片来编写产品描述。更重要的是，它可以模仿我们的 C2C 平台闲鱼的内容风格。这是通过在 MLLM 上采用特定领域的指令调整和采用多模态检索增强生成（RAG）过程来实现的。全面的实证评估表明，IPL 的基础模型在特定领域任务中显著优于基础模型，同时产生的幻觉更少。IPL 已成功部署在我们的生产系统中，72％的用户根据生成的内容发布了他们的产品列表，并且这些产品列表的质量得分比没有人工智能协助的产品列表高 5.6％。

> Unlike professional Business-to-Consumer (B2C) e-commerce platforms (e.g., Amazon), Consumer-to-Consumer (C2C) platforms (e.g., Facebook marketplace) are mainly targeting individual sellers who usually lack sufficient experience in e-commerce. Individual sellers often struggle to compose proper descriptions for selling products. With the recent advancement of Multimodal Large Language Models (MLLMs), we attempt to integrate such state-of-the-art generative AI technologies into the product listing process. To this end, we develop IPL, an Intelligent Product Listing tool tailored to generate descriptions using various product attributes such as category, brand, color, condition, etc. IPL enables users to compose product descriptions by merely uploading photos of the selling product. More importantly, it can imitate the content style of our C2C platform Xianyu. This is achieved by employing domain-specific instruction tuning on MLLMs and adopting the multi-modal Retrieval-Augmented Generation (RAG) process. A comprehensive empirical evaluation demonstrates that the underlying model of IPL significantly outperforms the base model in domain-specific tasks while producing less hallucination. IPL has been successfully deployed in our production system, where 72% of users have their published product listings based on the generated content, and those product listings are shown to have a quality score 5.6% higher than those without AI assistance.

[Arxiv](https://arxiv.org/abs/2410.16977)