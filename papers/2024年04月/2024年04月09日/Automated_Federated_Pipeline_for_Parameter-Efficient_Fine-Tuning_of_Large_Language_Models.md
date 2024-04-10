# 本文介绍了一种自动化联邦管道技术，旨在实现大型语言模型微调过程中的参数高效利用。

发布时间：2024年04月09日

`LLM应用` `联邦学习` `大数据处理`

> Automated Federated Pipeline for Parameter-Efficient Fine-Tuning of Large Language Models

# 摘要

> 近期，智能生成内容（AIGC）特别是大型语言模型（LLMs）的发展迎来了爆发式增长。但面对众多具体任务，我们仍需利用私有数据对LLMs进行精细调校。尽管联邦学习为保护隐私的LLM调校提供了一条光明大道，但LLM庞大的体量和对计算、通讯资源的高需求，使得这一方法在实际应用中面临挑战。尤其现实中边缘服务器的计算和网络资源参差不齐，更增加了调校LLM的难度。为应对这些问题，我们设计并推出了一个名为FedPipe的自动化联邦流程，它能够在不增加推理延迟的前提下，以最低的训练成本完成LLM的微调。FedPipe通过评估各个权重对LLM训练的影响，确定出需要调整的关键参数。接着，为这些参数设计低秩适配器，并在边缘服务器上进行本地化训练，随后整合各服务器的适配器以全局优化LLM。最终，根据边缘服务器的内存要求，对LLM的参数进行适当量化，以减少内存占用。大量实验证明，FedPipe不仅提升了模型训练的效率，而且在准确性上超越了现有的顶尖标准。

> Recently, there has been a surge in the development of advanced intelligent generative content (AIGC), especially large language models (LLMs). However, for many downstream tasks, it is necessary to fine-tune LLMs using private data. While federated learning offers a promising privacy-preserving solution to LLM fine-tuning, the substantial size of an LLM, combined with high computational and communication demands, makes it hard to apply to downstream tasks. More importantly, private edge servers often possess varying computing and network resources in real-world scenarios, introducing additional complexities to LLM fine-tuning. To tackle these problems, we design and implement an automated federated pipeline, named FedPipe, to fine-tune LLMs with minimal training cost but without adding any inference latency. FedPipe firstly identifies the weights to be fine-tuned based on their contributions to the LLM training. It then configures a low-rank adapter for each selected weight to train local low-rank adapters on an edge server, and aggregate local adapters of all edge servers to fine-tune the whole LLM. Finally, it appropriately quantizes the parameters of LLM to reduce memory space according to the requirements of edge servers. Extensive experiments demonstrate that FedPipe expedites the model training and achieves higher accuracy than state-of-the-art benchmarks.

![本文介绍了一种自动化联邦管道技术，旨在实现大型语言模型微调过程中的参数高效利用。](../../../paper_images/2404.06448/x1.png)

![本文介绍了一种自动化联邦管道技术，旨在实现大型语言模型微调过程中的参数高效利用。](../../../paper_images/2404.06448/x2.png)

![本文介绍了一种自动化联邦管道技术，旨在实现大型语言模型微调过程中的参数高效利用。](../../../paper_images/2404.06448/x3.png)

![本文介绍了一种自动化联邦管道技术，旨在实现大型语言模型微调过程中的参数高效利用。](../../../paper_images/2404.06448/x4.png)

![本文介绍了一种自动化联邦管道技术，旨在实现大型语言模型微调过程中的参数高效利用。](../../../paper_images/2404.06448/x5.png)

![本文介绍了一种自动化联邦管道技术，旨在实现大型语言模型微调过程中的参数高效利用。](../../../paper_images/2404.06448/x6.png)

![本文介绍了一种自动化联邦管道技术，旨在实现大型语言模型微调过程中的参数高效利用。](../../../paper_images/2404.06448/x7.png)

![本文介绍了一种自动化联邦管道技术，旨在实现大型语言模型微调过程中的参数高效利用。](../../../paper_images/2404.06448/x8.png)

![本文介绍了一种自动化联邦管道技术，旨在实现大型语言模型微调过程中的参数高效利用。](../../../paper_images/2404.06448/x9.png)

![本文介绍了一种自动化联邦管道技术，旨在实现大型语言模型微调过程中的参数高效利用。](../../../paper_images/2404.06448/x10.png)

![本文介绍了一种自动化联邦管道技术，旨在实现大型语言模型微调过程中的参数高效利用。](../../../paper_images/2404.06448/x11.png)

![本文介绍了一种自动化联邦管道技术，旨在实现大型语言模型微调过程中的参数高效利用。](../../../paper_images/2404.06448/x12.png)

![本文介绍了一种自动化联邦管道技术，旨在实现大型语言模型微调过程中的参数高效利用。](../../../paper_images/2404.06448/x13.png)

![本文介绍了一种自动化联邦管道技术，旨在实现大型语言模型微调过程中的参数高效利用。](../../../paper_images/2404.06448/x14.png)

![本文介绍了一种自动化联邦管道技术，旨在实现大型语言模型微调过程中的参数高效利用。](../../../paper_images/2404.06448/x15.png)

![本文介绍了一种自动化联邦管道技术，旨在实现大型语言模型微调过程中的参数高效利用。](../../../paper_images/2404.06448/x16.png)

![本文介绍了一种自动化联邦管道技术，旨在实现大型语言模型微调过程中的参数高效利用。](../../../paper_images/2404.06448/x17.png)

![本文介绍了一种自动化联邦管道技术，旨在实现大型语言模型微调过程中的参数高效利用。](../../../paper_images/2404.06448/x18.png)

![本文介绍了一种自动化联邦管道技术，旨在实现大型语言模型微调过程中的参数高效利用。](../../../paper_images/2404.06448/x19.png)

![本文介绍了一种自动化联邦管道技术，旨在实现大型语言模型微调过程中的参数高效利用。](../../../paper_images/2404.06448/x20.png)

![本文介绍了一种自动化联邦管道技术，旨在实现大型语言模型微调过程中的参数高效利用。](../../../paper_images/2404.06448/x21.png)

![本文介绍了一种自动化联邦管道技术，旨在实现大型语言模型微调过程中的参数高效利用。](../../../paper_images/2404.06448/x22.png)

![本文介绍了一种自动化联邦管道技术，旨在实现大型语言模型微调过程中的参数高效利用。](../../../paper_images/2404.06448/x23.png)

![本文介绍了一种自动化联邦管道技术，旨在实现大型语言模型微调过程中的参数高效利用。](../../../paper_images/2404.06448/x24.png)

![本文介绍了一种自动化联邦管道技术，旨在实现大型语言模型微调过程中的参数高效利用。](../../../paper_images/2404.06448/x25.png)

![本文介绍了一种自动化联邦管道技术，旨在实现大型语言模型微调过程中的参数高效利用。](../../../paper_images/2404.06448/x26.png)

![本文介绍了一种自动化联邦管道技术，旨在实现大型语言模型微调过程中的参数高效利用。](../../../paper_images/2404.06448/x27.png)

![本文介绍了一种自动化联邦管道技术，旨在实现大型语言模型微调过程中的参数高效利用。](../../../paper_images/2404.06448/x28.png)

![本文介绍了一种自动化联邦管道技术，旨在实现大型语言模型微调过程中的参数高效利用。](../../../paper_images/2404.06448/x29.png)

[Arxiv](https://arxiv.org/abs/2404.06448)