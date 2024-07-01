# Web2Code：一款大规模的网页转代码数据集与评估框架，专为多模态大型语言模型设计。

发布时间：2024年06月28日

`LLM应用` `网页开发` `自动化`

> Web2Code: A Large-scale Webpage-to-Code Dataset and Evaluation Framework for Multimodal LLMs

# 摘要

> 摘要：多模态大型语言模型（MLLMs）在跨图像、视频和音频等多种任务中表现卓越。然而，它们在理解网页截图和生成HTML代码方面却表现不佳。为此，我们提出Web2Code，包含一个大规模网页到代码数据集和评估框架，旨在提升MLLMs在这两方面的能力。我们利用预训练LLMs增强现有数据集并生成多样网页图像，输入为网页图像和指令，输出为HTML代码，并加入网页内容的自然语言QA对以深化理解。我们还开发了评估框架来测试MLLMs在这两方面的能力。实验证明，我们的数据集不仅提升了我们提出的任务性能，也在一般视觉领域表现更佳。我们期待这项工作能推动适用于网页内容生成和自动化的通用MLLMs的发展。相关数据和代码将在指定链接提供。

> 
Abstract:Multimodal large language models (MLLMs) have shown impressive success across modalities such as image, video, and audio in a variety of understanding and generation tasks. However, current MLLMs are surprisingly poor at understanding webpage screenshots and generating their corresponding HTML code. To address this problem, we propose Web2Code, a benchmark consisting of a new large-scale webpage-to-code dataset for instruction tuning and an evaluation framework for the webpage understanding and HTML code translation abilities of MLLMs. For dataset construction, we leverage pretrained LLMs to enhance existing webpage-to-code datasets as well as generate a diverse pool of new webpages rendered into images. Specifically, the inputs are webpage images and instructions, while the responses are the webpage's HTML code. We further include diverse natural language QA pairs about the webpage content in the responses to enable a more comprehensive understanding of the web content. To evaluate model performance in these tasks, we develop an evaluation framework for testing MLLMs' abilities in webpage understanding and web-to-code generation. Extensive experiments show that our proposed dataset is beneficial not only to our proposed tasks but also in the general visual domain, while previous datasets result in worse performance. We hope our work will contribute to the development of general MLLMs suitable for web-based content generation and task automation. Our data and code will be available at this https URL.
    

![Web2Code：一款大规模的网页转代码数据集与评估框架，专为多模态大型语言模型设计。](../../../paper_images/2406.20098/x1.png)

![Web2Code：一款大规模的网页转代码数据集与评估框架，专为多模态大型语言模型设计。](../../../paper_images/2406.20098/x2.png)

![Web2Code：一款大规模的网页转代码数据集与评估框架，专为多模态大型语言模型设计。](../../../paper_images/2406.20098/x3.png)

![Web2Code：一款大规模的网页转代码数据集与评估框架，专为多模态大型语言模型设计。](../../../paper_images/2406.20098/cloud.png)

![Web2Code：一款大规模的网页转代码数据集与评估框架，专为多模态大型语言模型设计。](../../../paper_images/2406.20098/x4.png)

![Web2Code：一款大规模的网页转代码数据集与评估框架，专为多模态大型语言模型设计。](../../../paper_images/2406.20098/x5.png)

![Web2Code：一款大规模的网页转代码数据集与评估框架，专为多模态大型语言模型设计。](../../../paper_images/2406.20098/ori.png)

![Web2Code：一款大规模的网页转代码数据集与评估框架，专为多模态大型语言模型设计。](../../../paper_images/2406.20098/vicuna.png)

![Web2Code：一款大规模的网页转代码数据集与评估框架，专为多模态大型语言模型设计。](../../../paper_images/2406.20098/crystalchat.png)

![Web2Code：一款大规模的网页转代码数据集与评估框架，专为多模态大型语言模型设计。](../../../paper_images/2406.20098/ori.png)

![Web2Code：一款大规模的网页转代码数据集与评估框架，专为多模态大型语言模型设计。](../../../paper_images/2406.20098/ori_code_img.png)

![Web2Code：一款大规模的网页转代码数据集与评估框架，专为多模态大型语言模型设计。](../../../paper_images/2406.20098/ours.png)

![Web2Code：一款大规模的网页转代码数据集与评估框架，专为多模态大型语言模型设计。](../../../paper_images/2406.20098/x6.png)

![Web2Code：一款大规模的网页转代码数据集与评估框架，专为多模态大型语言模型设计。](../../../paper_images/2406.20098/x7.png)

![Web2Code：一款大规模的网页转代码数据集与评估框架，专为多模态大型语言模型设计。](../../../paper_images/2406.20098/x8.png)

![Web2Code：一款大规模的网页转代码数据集与评估框架，专为多模态大型语言模型设计。](../../../paper_images/2406.20098/x9.png)

![Web2Code：一款大规模的网页转代码数据集与评估框架，专为多模态大型语言模型设计。](../../../paper_images/2406.20098/x10.png)

![Web2Code：一款大规模的网页转代码数据集与评估框架，专为多模态大型语言模型设计。](../../../paper_images/2406.20098/x11.png)

![Web2Code：一款大规模的网页转代码数据集与评估框架，专为多模态大型语言模型设计。](../../../paper_images/2406.20098/x12.png)

![Web2Code：一款大规模的网页转代码数据集与评估框架，专为多模态大型语言模型设计。](../../../paper_images/2406.20098/x13.png)

![Web2Code：一款大规模的网页转代码数据集与评估框架，专为多模态大型语言模型设计。](../../../paper_images/2406.20098/junbo.png)

![Web2Code：一款大规模的网页转代码数据集与评估框架，专为多模态大型语言模型设计。](../../../paper_images/2406.20098/pix2code.png)

![Web2Code：一款大规模的网页转代码数据集与评估框架，专为多模态大型语言模型设计。](../../../paper_images/2406.20098/WebSight.png)

![Web2Code：一款大规模的网页转代码数据集与评估框架，专为多模态大型语言模型设计。](../../../paper_images/2406.20098/QA.png)

![Web2Code：一款大规模的网页转代码数据集与评估框架，专为多模态大型语言模型设计。](../../../paper_images/2406.20098/WebSRC.png)

![Web2Code：一款大规模的网页转代码数据集与评估框架，专为多模态大型语言模型设计。](../../../paper_images/2406.20098/Modern_webpages.png)

![Web2Code：一款大规模的网页转代码数据集与评估框架，专为多模态大型语言模型设计。](../../../paper_images/2406.20098/Bootstrap_webpage.png)

[Arxiv](https://arxiv.org//pdf/2406.20098)