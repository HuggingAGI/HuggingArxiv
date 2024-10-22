# Mini-InternVL：一款灵活转移的多模态模型，仅用5%的参数就能实现90%的性能。

发布时间：2024年10月21日

`LLM应用` `自动驾驶` `医学影像`

> Mini-InternVL: A Flexible-Transfer Pocket Multimodal Model with 5% Parameters and 90% Performance

# 摘要

> 多模态大型语言模型（MLLMs）在视觉与语言任务中表现出色，但庞大的模型规模和高昂的计算成本限制了其在消费级GPU和边缘设备上的应用。为此，我们推出了Mini-InternVL，一系列参数仅为1B至4B的MLLMs，却能以5%的参数达到90%的性能。这一显著提升使得模型在实际应用中更加便捷。我们还开发了统一的适应框架，使Mini-InternVL在自动驾驶、医学影像和遥感等下游任务中表现卓越。我们相信，这项研究将为高效MLLMs的发展提供宝贵资源。代码已公开，详见https://github.com/OpenGVLab/InternVL。

> Multimodal large language models (MLLMs) have demonstrated impressive performance in vision-language tasks across a broad spectrum of domains. However, the large model scale and associated high computational costs pose significant challenges for training and deploying MLLMs on consumer-grade GPUs or edge devices, thereby hindering their widespread application. In this work, we introduce Mini-InternVL, a series of MLLMs with parameters ranging from 1B to 4B, which achieves 90% of the performance with only 5% of the parameters. This significant improvement in efficiency and effectiveness makes our models more accessible and applicable in various real-world scenarios. To further promote the adoption of our models, we develop a unified adaptation framework for Mini-InternVL, which enables our models to transfer and outperform specialized models in downstream tasks, including autonomous driving, medical images, and remote sensing. We believe that our study can provide valuable insights and resources to advance the development of efficient and effective MLLMs. Code is available at https://github.com/OpenGVLab/InternVL.

[Arxiv](https://arxiv.org/abs/2410.16261)