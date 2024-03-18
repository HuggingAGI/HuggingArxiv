# Chronos项目致力于探索和掌握时间序列背后的“语言”，揭示其内在规律与模式。

发布时间：2024年03月12日

`Agent`

> Chronos: Learning the Language of Time Series

> 现在介绍 Chronos——一个简单且实用的框架，用于预训练概率性时间序列模型。Chronos 将时序数据通过缩放、量化转为固定词库中的令牌，并运用交叉熵损失在这些编码后的时间序列上训练各种基于变压器的语言模型架构。我们在大量公开数据集以及借助高斯过程生成的合成数据集来增强泛化能力的基础上，对 T5 系列（参数规模从20M至710M不等）进行了 Chronos 模型的预训练。在囊括42个数据集、比较了经典局部模型及深度学习方法的综合基准测试中，Chronos 模型展现出两大优势：(a) 对于训练语料库所含数据集，其性能显著优于其他方法；(b) 针对全新数据集的零样本表现与专门为此训练的方法相比，不仅可比甚至还更胜一筹。这一研究证明 Chronos 模型能有效利用多样领域的时间序列数据提升对未见预测任务的零样本精确度，从而推动预训练模型成为大大简化预测流程的可行工具。

> We introduce Chronos, a simple yet effective framework for pretrained probabilistic time series models. Chronos tokenizes time series values using scaling and quantization into a fixed vocabulary and trains existing transformer-based language model architectures on these tokenized time series via the cross-entropy loss. We pretrained Chronos models based on the T5 family (ranging from 20M to 710M parameters) on a large collection of publicly available datasets, complemented by a synthetic dataset that we generated via Gaussian processes to improve generalization. In a comprehensive benchmark consisting of 42 datasets, and comprising both classical local models and deep learning methods, we show that Chronos models: (a) significantly outperform other methods on datasets that were part of the training corpus; and (b) have comparable and occasionally superior zero-shot performance on new datasets, relative to methods that were trained specifically on them. Our results demonstrate that Chronos models can leverage time series data from diverse domains to improve zero-shot accuracy on unseen forecasting tasks, positioning pretrained models as a viable tool to greatly simplify forecasting pipelines.

![Chronos项目致力于探索和掌握时间序列背后的“语言”，揭示其内在规律与模式。](../../../paper_images/2403.07815/x1.png)

![Chronos项目致力于探索和掌握时间序列背后的“语言”，揭示其内在规律与模式。](../../../paper_images/2403.07815/x2.png)

![Chronos项目致力于探索和掌握时间序列背后的“语言”，揭示其内在规律与模式。](../../../paper_images/2403.07815/x3.png)

![Chronos项目致力于探索和掌握时间序列背后的“语言”，揭示其内在规律与模式。](../../../paper_images/2403.07815/x4.png)

![Chronos项目致力于探索和掌握时间序列背后的“语言”，揭示其内在规律与模式。](../../../paper_images/2403.07815/x5.png)

![Chronos项目致力于探索和掌握时间序列背后的“语言”，揭示其内在规律与模式。](../../../paper_images/2403.07815/x6.png)

![Chronos项目致力于探索和掌握时间序列背后的“语言”，揭示其内在规律与模式。](../../../paper_images/2403.07815/x7.png)

![Chronos项目致力于探索和掌握时间序列背后的“语言”，揭示其内在规律与模式。](../../../paper_images/2403.07815/x8.png)

![Chronos项目致力于探索和掌握时间序列背后的“语言”，揭示其内在规律与模式。](../../../paper_images/2403.07815/x9.png)

![Chronos项目致力于探索和掌握时间序列背后的“语言”，揭示其内在规律与模式。](../../../paper_images/2403.07815/x10.png)

![Chronos项目致力于探索和掌握时间序列背后的“语言”，揭示其内在规律与模式。](../../../paper_images/2403.07815/x11.png)

![Chronos项目致力于探索和掌握时间序列背后的“语言”，揭示其内在规律与模式。](../../../paper_images/2403.07815/x12.png)

![Chronos项目致力于探索和掌握时间序列背后的“语言”，揭示其内在规律与模式。](../../../paper_images/2403.07815/x13.png)

![Chronos项目致力于探索和掌握时间序列背后的“语言”，揭示其内在规律与模式。](../../../paper_images/2403.07815/x14.png)

![Chronos项目致力于探索和掌握时间序列背后的“语言”，揭示其内在规律与模式。](../../../paper_images/2403.07815/x15.png)

![Chronos项目致力于探索和掌握时间序列背后的“语言”，揭示其内在规律与模式。](../../../paper_images/2403.07815/x16.png)

![Chronos项目致力于探索和掌握时间序列背后的“语言”，揭示其内在规律与模式。](../../../paper_images/2403.07815/x17.png)

![Chronos项目致力于探索和掌握时间序列背后的“语言”，揭示其内在规律与模式。](../../../paper_images/2403.07815/x18.png)

![Chronos项目致力于探索和掌握时间序列背后的“语言”，揭示其内在规律与模式。](../../../paper_images/2403.07815/x19.png)

![Chronos项目致力于探索和掌握时间序列背后的“语言”，揭示其内在规律与模式。](../../../paper_images/2403.07815/x20.png)

![Chronos项目致力于探索和掌握时间序列背后的“语言”，揭示其内在规律与模式。](../../../paper_images/2403.07815/x21.png)

![Chronos项目致力于探索和掌握时间序列背后的“语言”，揭示其内在规律与模式。](../../../paper_images/2403.07815/x22.png)

![Chronos项目致力于探索和掌握时间序列背后的“语言”，揭示其内在规律与模式。](../../../paper_images/2403.07815/x23.png)

![Chronos项目致力于探索和掌握时间序列背后的“语言”，揭示其内在规律与模式。](../../../paper_images/2403.07815/x24.png)

![Chronos项目致力于探索和掌握时间序列背后的“语言”，揭示其内在规律与模式。](../../../paper_images/2403.07815/x25.png)

![Chronos项目致力于探索和掌握时间序列背后的“语言”，揭示其内在规律与模式。](../../../paper_images/2403.07815/x26.png)

![Chronos项目致力于探索和掌握时间序列背后的“语言”，揭示其内在规律与模式。](../../../paper_images/2403.07815/x27.png)

![Chronos项目致力于探索和掌握时间序列背后的“语言”，揭示其内在规律与模式。](../../../paper_images/2403.07815/x28.png)

![Chronos项目致力于探索和掌握时间序列背后的“语言”，揭示其内在规律与模式。](../../../paper_images/2403.07815/x29.png)

![Chronos项目致力于探索和掌握时间序列背后的“语言”，揭示其内在规律与模式。](../../../paper_images/2403.07815/x30.png)

![Chronos项目致力于探索和掌握时间序列背后的“语言”，揭示其内在规律与模式。](../../../paper_images/2403.07815/x31.png)

![Chronos项目致力于探索和掌握时间序列背后的“语言”，揭示其内在规律与模式。](../../../paper_images/2403.07815/x32.png)

![Chronos项目致力于探索和掌握时间序列背后的“语言”，揭示其内在规律与模式。](../../../paper_images/2403.07815/x33.png)

![Chronos项目致力于探索和掌握时间序列背后的“语言”，揭示其内在规律与模式。](../../../paper_images/2403.07815/x34.png)

![Chronos项目致力于探索和掌握时间序列背后的“语言”，揭示其内在规律与模式。](../../../paper_images/2403.07815/x35.png)

![Chronos项目致力于探索和掌握时间序列背后的“语言”，揭示其内在规律与模式。](../../../paper_images/2403.07815/x36.png)

![Chronos项目致力于探索和掌握时间序列背后的“语言”，揭示其内在规律与模式。](../../../paper_images/2403.07815/x37.png)

![Chronos项目致力于探索和掌握时间序列背后的“语言”，揭示其内在规律与模式。](../../../paper_images/2403.07815/x38.png)

[Arxiv](https://arxiv.org/abs/2403.07815)