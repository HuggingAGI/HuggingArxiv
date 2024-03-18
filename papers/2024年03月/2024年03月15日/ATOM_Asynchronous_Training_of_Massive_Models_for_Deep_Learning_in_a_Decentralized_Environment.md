# [ATOM 技术专为去中心化环境中的深度学习设计，实现了大规模模型的异步训练，赋予其高效处理能力。](https://arxiv.org/abs/2403.10504)

发布时间：2024年03月15日

`Agent` `` `分布式系统`

> ATOM: Asynchronous Training of Massive Models for Deep Learning in a Decentralized Environment

> Transformer架构的到来有力推进了NLP模型的进步，使其在各种NLP任务中屡创佳绩。但受限于大规模GPU内存及高速互连等专业硬件的缺失，训练大型模型成为难题，导致许多用户难以尝试对大型语言模型（LLMs）进行预训练和微调。为此，本研究提出了一种名为\atom的强健分布式训练框架，它专为使用性价比高的硬件（如消费级GPU和以太网）在去中心化环境下异步训练超大规模模型而设计。不同于常规将子模型分散到各个GPU上的模型划分方式，\atom力求通过无缝模型切换，在单台主机上完整装载一个LLM，并在多台主机间并行训练多个模型拷贝，从而优化训练效率。通过静态分析技术，\atom精准识别最优模型划分策略，并巧妙地将模型执行与切换过程融为一体。\atom的核心优点有：有效规避了管道并行方法中存在的单一故障点问题；在网络环境不佳时，其表现优于紧耦合的管道并行方法，展现出卓越的性能和扩展能力。我们在不同的GPT-3模型配置下进行实验发现，在网络连接非最优的情况下，相较于当前最先进的去中心化管道并行方法，\atom能够使训练效率提升最高达$20 \times$。

> The advent of the Transformer architecture has propelled the growth of natural language processing (NLP) models, leading to remarkable achievements in numerous NLP tasks. Yet, the absence of specialized hardware like expansive GPU memory and high-speed interconnects poses challenges for training large-scale models. This makes it daunting for many users to experiment with pre-training and fine-tuning large language models (LLMs). In this study, we introduce \atom, a resilient distributed training framework designed for asynchronous training of vast models in a decentralized setting using cost-effective hardware, including consumer-grade GPUs and Ethernet. Unlike conventional model partitioning methods that distribute sub-models across GPUs, \atom aims to accommodate a complete LLM on one host (peer) through seamlessly model swapping and concurrently trains multiple copies across various peers to optimize training throughput. Through static analysis, \atom identifies the best model partitioning strategy and flawlessly merges model execution with swapping. Key benefits of \atom include: Avoiding the central point of failure found in pipeline parallelism methods. Demonstrating superior performance and scalability compared to closely-integrated pipeline parallelism in slower networks. Our experiments using different GPT-3 model configurations reveal that, in scenarios with suboptimal network connections, \atom can enhance training efficiency up to $20 \times$ when juxtaposed with the state-of-the-art decentralized pipeline parallelism approaches.

![ATOM 技术专为去中心化环境中的深度学习设计，实现了大规模模型的异步训练，赋予其高效处理能力。](../../../paper_images/2403.10504/x1.png)

![ATOM 技术专为去中心化环境中的深度学习设计，实现了大规模模型的异步训练，赋予其高效处理能力。](../../../paper_images/2403.10504/x2.png)

![ATOM 技术专为去中心化环境中的深度学习设计，实现了大规模模型的异步训练，赋予其高效处理能力。](../../../paper_images/2403.10504/x3.png)

![ATOM 技术专为去中心化环境中的深度学习设计，实现了大规模模型的异步训练，赋予其高效处理能力。](../../../paper_images/2403.10504/x4.png)

![ATOM 技术专为去中心化环境中的深度学习设计，实现了大规模模型的异步训练，赋予其高效处理能力。](../../../paper_images/2403.10504/x5.png)

![ATOM 技术专为去中心化环境中的深度学习设计，实现了大规模模型的异步训练，赋予其高效处理能力。](../../../paper_images/2403.10504/x6.png)

![ATOM 技术专为去中心化环境中的深度学习设计，实现了大规模模型的异步训练，赋予其高效处理能力。](../../../paper_images/2403.10504/x7.png)

![ATOM 技术专为去中心化环境中的深度学习设计，实现了大规模模型的异步训练，赋予其高效处理能力。](../../../paper_images/2403.10504/x8.png)

![ATOM 技术专为去中心化环境中的深度学习设计，实现了大规模模型的异步训练，赋予其高效处理能力。](../../../paper_images/2403.10504/x9.png)

![ATOM 技术专为去中心化环境中的深度学习设计，实现了大规模模型的异步训练，赋予其高效处理能力。](../../../paper_images/2403.10504/x10.png)

![ATOM 技术专为去中心化环境中的深度学习设计，实现了大规模模型的异步训练，赋予其高效处理能力。](../../../paper_images/2403.10504/x11.png)

![ATOM 技术专为去中心化环境中的深度学习设计，实现了大规模模型的异步训练，赋予其高效处理能力。](../../../paper_images/2403.10504/x12.png)

![ATOM 技术专为去中心化环境中的深度学习设计，实现了大规模模型的异步训练，赋予其高效处理能力。](../../../paper_images/2403.10504/x13.png)

![ATOM 技术专为去中心化环境中的深度学习设计，实现了大规模模型的异步训练，赋予其高效处理能力。](../../../paper_images/2403.10504/x14.png)

![ATOM 技术专为去中心化环境中的深度学习设计，实现了大规模模型的异步训练，赋予其高效处理能力。](../../../paper_images/2403.10504/x15.png)

![ATOM 技术专为去中心化环境中的深度学习设计，实现了大规模模型的异步训练，赋予其高效处理能力。](../../../paper_images/2403.10504/x16.png)

![ATOM 技术专为去中心化环境中的深度学习设计，实现了大规模模型的异步训练，赋予其高效处理能力。](../../../paper_images/2403.10504/x17.png)

![ATOM 技术专为去中心化环境中的深度学习设计，实现了大规模模型的异步训练，赋予其高效处理能力。](../../../paper_images/2403.10504/x18.png)

![ATOM 技术专为去中心化环境中的深度学习设计，实现了大规模模型的异步训练，赋予其高效处理能力。](../../../paper_images/2403.10504/x19.png)

![ATOM 技术专为去中心化环境中的深度学习设计，实现了大规模模型的异步训练，赋予其高效处理能力。](../../../paper_images/2403.10504/x20.png)

![ATOM 技术专为去中心化环境中的深度学习设计，实现了大规模模型的异步训练，赋予其高效处理能力。](../../../paper_images/2403.10504/x21.png)

![ATOM 技术专为去中心化环境中的深度学习设计，实现了大规模模型的异步训练，赋予其高效处理能力。](../../../paper_images/2403.10504/)

![ATOM 技术专为去中心化环境中的深度学习设计，实现了大规模模型的异步训练，赋予其高效处理能力。](../../../paper_images/2403.10504/x23.png)

![ATOM 技术专为去中心化环境中的深度学习设计，实现了大规模模型的异步训练，赋予其高效处理能力。](../../../paper_images/2403.10504/x24.png)

[Arxiv](https://arxiv.org/abs/2403.10504)