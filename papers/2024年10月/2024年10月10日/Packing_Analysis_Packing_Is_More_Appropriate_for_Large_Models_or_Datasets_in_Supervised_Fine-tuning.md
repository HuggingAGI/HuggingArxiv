# 打包分析：在监督微调中，大型模型或数据集更适合采用打包策略。

发布时间：2024年10月10日

`LLM理论` `人工智能` `数据处理`

> Packing Analysis: Packing Is More Appropriate for Large Models or Datasets in Supervised Fine-tuning

# 摘要

> 打包技术最初用于预训练阶段，通过组合不同训练序列以适应模型最大输入长度，从而最大化硬件资源效率。尽管在预训练中表现出色，但在监督微调（SFT）阶段，其效果仍需深入探讨：（1）打包能否在保持性能的同时提升训练效率，（2）适合打包微调的模型和数据集规模，以及（3）打包无关或相关样本是否会导致模型过度依赖或忽略上下文。本文通过对比填充与打包的SFT方法，涵盖了从69K到1.2M的数据集和8B到70B的模型，首次全面分析了打包的优缺点及其实施考量。分析范围包括知识、推理、编码等基准，以及GPT评估、时间效率等微调参数。此外，我们开源了微调和评估代码，并提供不同数据集上的微调检查点，以推动未来对打包技术的研究。代码链接：https://github.com/ShuheWang1998/Packing-Analysis?tab=readme-ov-file。

> Packing, initially utilized in the pre-training phase, is an optimization technique designed to maximize hardware resource efficiency by combining different training sequences to fit the model's maximum input length. Although it has demonstrated effectiveness during pre-training, there remains a lack of comprehensive analysis for the supervised fine-tuning (SFT) stage on the following points: (1) whether packing can effectively enhance training efficiency while maintaining performance, (2) the suitable size of the model and dataset for fine-tuning with the packing method, and (3) whether packing unrelated or related training samples might cause the model to either excessively disregard or over-rely on the context.
  In this paper, we perform extensive comparisons between SFT methods using padding and packing, covering SFT datasets ranging from 69K to 1.2M and models from 8B to 70B. This provides the first comprehensive analysis of the advantages and limitations of packing versus padding, as well as practical considerations for implementing packing in various training scenarios. Our analysis covers various benchmarks, including knowledge, reasoning, and coding, as well as GPT-based evaluations, time efficiency, and other fine-tuning parameters. We also open-source our code for fine-tuning and evaluation and provide checkpoints fine-tuned on datasets of different sizes, aiming to advance future research on packing methods. Code is available at: https://github.com/ShuheWang1998/Packing-Analysis?tab=readme-ov-file.

[Arxiv](https://arxiv.org/abs/2410.08081)