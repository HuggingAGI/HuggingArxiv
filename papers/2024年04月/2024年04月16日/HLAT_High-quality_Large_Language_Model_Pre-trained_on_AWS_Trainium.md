# HLAT：依托 AWS Trainium 打造的高品质大型语言模型

发布时间：2024年04月16日

`LLM应用` `云计算` `机器学习加速器`

> HLAT: High-quality Large Language Model Pre-trained on AWS Trainium

# 摘要

> 要让大型语言模型（LLMs）在具体任务上表现出色，需历经数万亿令牌的预训练洗礼。这一过程不仅依赖众多高性能计算资源，还需稳定的分布式训练架构来提升训练效率。随着AI/ML应用的激增，传统昂贵的加速器如GPU日渐供不应求，因此迫切需要开发可伸缩且经济高效的新型专业加速器。AWS Trainium作为第二代机器学习加速器，专为深度学习模型训练而生。其配套的Amazon EC2 trn1实例，作为GPU实例的替代选择，适用于LLM训练。然而，鉴于其软件生态系统尚处于起步阶段，用trn1实例训练参数高达数十亿的LLMs并非易事。本文介绍了HLAT，一个70亿参数的解码器专用LLM，通过trn1实例在1.8万亿令牌上完成了预训练。HLAT的性能与在NVIDIA GPU和Google TPU上训练的LLaMA和OpenLLaMA等开源基线模型相媲美。我们还介绍了使用Neuron分布式训练库（NDTL）的最佳实践，这是为AWS Trainium量身打造的分布式训练工具，助力高效训练。我们的研究显示，搭载NDTL的AWS Trainium能够高效地预训练出性能卓越、成本可控的尖端LLM模型。

> Getting large language models (LLMs) to perform well on the downstream tasks requires pre-training over trillions of tokens. This typically demands a large number of powerful computational devices in addition to a stable distributed training framework to accelerate the training. The growing number of applications leveraging AI/ML had led to a scarcity of the expensive conventional accelerators (such as GPUs), which begs the need for the alternative specialized-accelerators that are scalable and cost-efficient. AWS Trainium is the second-generation machine learning accelerator that has been purposely built for training large deep learning models. Its corresponding instance, Amazon EC2 trn1, is an alternative to GPU instances for LLM training. However, training LLMs with billions of parameters on trn1 is challenging due to its relatively nascent software ecosystem. In this paper, we showcase HLAT: a 7 billion parameter decoder-only LLM pre-trained using trn1 instances over 1.8 trillion tokens. The performance of HLAT is benchmarked against popular open source baseline models including LLaMA and OpenLLaMA, which have been trained on NVIDIA GPUs and Google TPUs, respectively. On various evaluation tasks, we show that HLAT achieves model quality on par with the baselines. We also share the best practice of using the Neuron Distributed Training Library (NDTL), a customized distributed training library for AWS Trainium to achieve efficient training. Our work demonstrates that AWS Trainium powered by the NDTL is able to successfully pre-train state-of-the-art LLM models with high performance and cost-effectiveness.

![HLAT：依托 AWS Trainium 打造的高品质大型语言模型](../../../paper_images/2404.10630/x1.png)

![HLAT：依托 AWS Trainium 打造的高品质大型语言模型](../../../paper_images/2404.10630/x2.png)

![HLAT：依托 AWS Trainium 打造的高品质大型语言模型](../../../paper_images/2404.10630/x3.png)

![HLAT：依托 AWS Trainium 打造的高品质大型语言模型](../../../paper_images/2404.10630/x4.png)

![HLAT：依托 AWS Trainium 打造的高品质大型语言模型](../../../paper_images/2404.10630/x5.png)

![HLAT：依托 AWS Trainium 打造的高品质大型语言模型](../../../paper_images/2404.10630/x6.png)

![HLAT：依托 AWS Trainium 打造的高品质大型语言模型](../../../paper_images/2404.10630/x7.png)

![HLAT：依托 AWS Trainium 打造的高品质大型语言模型](../../../paper_images/2404.10630/x8.png)

![HLAT：依托 AWS Trainium 打造的高品质大型语言模型](../../../paper_images/2404.10630/x9.png)

![HLAT：依托 AWS Trainium 打造的高品质大型语言模型](../../../paper_images/2404.10630/x10.png)

![HLAT：依托 AWS Trainium 打造的高品质大型语言模型](../../../paper_images/2404.10630/x11.png)

![HLAT：依托 AWS Trainium 打造的高品质大型语言模型](../../../paper_images/2404.10630/x12.png)

![HLAT：依托 AWS Trainium 打造的高品质大型语言模型](../../../paper_images/2404.10630/x13.png)

![HLAT：依托 AWS Trainium 打造的高品质大型语言模型](../../../paper_images/2404.10630/x14.png)

![HLAT：依托 AWS Trainium 打造的高品质大型语言模型](../../../paper_images/2404.10630/x15.png)

![HLAT：依托 AWS Trainium 打造的高品质大型语言模型](../../../paper_images/2404.10630/x16.png)

![HLAT：依托 AWS Trainium 打造的高品质大型语言模型](../../../paper_images/2404.10630/x17.png)

![HLAT：依托 AWS Trainium 打造的高品质大型语言模型](../../../paper_images/2404.10630/x18.png)

![HLAT：依托 AWS Trainium 打造的高品质大型语言模型](../../../paper_images/2404.10630/x19.png)

![HLAT：依托 AWS Trainium 打造的高品质大型语言模型](../../../paper_images/2404.10630/x20.png)

![HLAT：依托 AWS Trainium 打造的高品质大型语言模型](../../../paper_images/2404.10630/x21.png)

![HLAT：依托 AWS Trainium 打造的高品质大型语言模型](../../../paper_images/2404.10630/x22.png)

![HLAT：依托 AWS Trainium 打造的高品质大型语言模型](../../../paper_images/2404.10630/x23.png)

![HLAT：依托 AWS Trainium 打造的高品质大型语言模型](../../../paper_images/2404.10630/x24.png)

[Arxiv](https://arxiv.org/abs/2404.10630)