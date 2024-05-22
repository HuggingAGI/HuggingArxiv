# 大型基础模型在诊断应用中，数据集质量是否仍是心头之患？

发布时间：2024年05月21日

`LLM应用

这篇论文主要探讨了预训练的大型基础模型（LFM）在医学诊断任务中的应用，特别是在视网膜图像分析中的表现。论文通过实验研究了LFM对图像质量和数据集偏差的鲁棒性，并探讨了微调技术在减轻这些问题上的效果。这些内容主要关注于LLM在特定领域的应用，即医学诊断，因此属于LLM应用分类。` `计算机视觉`

> Is Dataset Quality Still a Concern in Diagnosis Using Large Foundation Model?

# 摘要

> 预训练的大型基础模型（LFM）在自然语言处理和计算机视觉等多个领域取得了显著进展，尤其在医学诊断任务中表现突出。通过利用大量未标记数据，我们开发了一种基于视觉变换器（VIT）和自监督学习框架的LFM，用于视网膜图像，并在多个数据集上展示了其在视网膜疾病诊断中的潜力。然而，深度学习模型一直受困于数据集质量问题，如图像质量和数据集偏差。为了探究这些问题对LFM的影响，我们在两个视网膜诊断任务中使用了质量不同的数据集进行研究。我们特别关注了以下问题：LFM是否对图像质量更鲁棒？是否受数据集偏差影响？微调技术能否减轻这些影响？研究结果表明，LFM相比传统卷积网络更能抵御数据集质量问题，包括图像质量和数据集偏差。此外，我们还发现微调技术是LFM缓解这些问题的有效手段。

> Recent advancements in pre-trained large foundation models (LFM) have yielded significant breakthroughs across various domains, including natural language processing and computer vision. These models have been particularly impactful in the domain of medical diagnostic tasks. With abundant unlabeled data, an LFM has been developed for fundus images using the Vision Transformer (VIT) and a self-supervised learning framework. This LFM has shown promising performance in fundus disease diagnosis across multiple datasets. On the other hand, deep learning models have long been challenged by dataset quality issues, such as image quality and dataset bias. To investigate the influence of data quality on LFM, we conducted explorations in two fundus diagnosis tasks using datasets of varying quality. Specifically, we explored the following questions: Is LFM more robust to image quality? Is LFM affected by dataset bias? Can fine-tuning techniques alleviate these effects? Our investigation found that LFM exhibits greater resilience to dataset quality issues, including image quality and dataset bias, compared to typical convolutional networks. Furthermore, we discovered that overall fine-tuning is an effective adapter for LFM to mitigate the impact of dataset quality issues.

[Arxiv](https://arxiv.org/abs/2405.12584)