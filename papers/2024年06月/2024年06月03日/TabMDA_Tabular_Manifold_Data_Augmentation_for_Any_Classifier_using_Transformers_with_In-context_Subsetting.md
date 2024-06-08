# TabMDA：利用Transformer的上下文子集技术，为任意分类器提供表格流形数据增强方案

发布时间：2024年06月03日

`LLM应用

理由：这篇论文介绍了一种名为TabMDA的技术，它利用预训练的上下文模型（如TabPFN）来增强表格数据，从而提升机器学习模型在表格数据上的性能。这种方法涉及到使用预训练模型来改进数据处理和模型训练，属于在特定应用场景（即表格数据处理）中利用大型语言模型（LLM）的技术。因此，它符合LLM应用的分类。` `数据增强` `机器学习`

> TabMDA: Tabular Manifold Data Augmentation for Any Classifier using Transformers with In-context Subsetting

# 摘要

> 表格数据在众多关键领域中广泛存在，但其获取量往往有限，导致机器学习模型在此类数据上的表现不尽人意。尽管数据增强在视觉和语言任务中常能提升性能，但面对表格数据时，由于输入空间缺乏明显对称性，其效果通常不佳。为此，我们创新性地提出了TabMDA，一种针对表格数据的流形数据增强技术。TabMDA借助预训练的上下文模型（如TabPFN），将数据映射至流形空间，并通过在不同上下文中多次编码数据，实现标签不变的转换，从而探索并扩展了底层模型的流形，有效扩充了训练集。作为一种无需额外训练的方法，TabMDA可广泛应用于各类分类器。我们在五个标准分类器上进行了测试，并在多个表格数据集上见证了其显著的性能提升。实验结果清晰地展示了TabMDA如何巧妙地利用预训练上下文模型的信息，为下游分类器注入活力，显著提升其性能。

> Tabular data is prevalent in many critical domains, yet it is often challenging to acquire in large quantities. This scarcity usually results in poor performance of machine learning models on such data. Data augmentation, a common strategy for performance improvement in vision and language tasks, typically underperforms for tabular data due to the lack of explicit symmetries in the input space. To overcome this challenge, we introduce TabMDA, a novel method for manifold data augmentation on tabular data. This method utilises a pre-trained in-context model, such as TabPFN, to map the data into a manifold space. TabMDA performs label-invariant transformations by encoding the data multiple times with varied contexts. This process explores the manifold of the underlying in-context models, thereby enlarging the training dataset. TabMDA is a training-free method, making it applicable to any classifier. We evaluate TabMDA on five standard classifiers and observe significant performance improvements across various tabular datasets. Our results demonstrate that TabMDA provides an effective way to leverage information from pre-trained in-context models to enhance the performance of downstream classifiers.

![TabMDA：利用Transformer的上下文子集技术，为任意分类器提供表格流形数据增强方案](../../../paper_images/2406.01805/x1.png)

![TabMDA：利用Transformer的上下文子集技术，为任意分类器提供表格流形数据增强方案](../../../paper_images/2406.01805/x2.png)

![TabMDA：利用Transformer的上下文子集技术，为任意分类器提供表格流形数据增强方案](../../../paper_images/2406.01805/x3.png)

![TabMDA：利用Transformer的上下文子集技术，为任意分类器提供表格流形数据增强方案](../../../paper_images/2406.01805/x4.png)

![TabMDA：利用Transformer的上下文子集技术，为任意分类器提供表格流形数据增强方案](../../../paper_images/2406.01805/x5.png)

![TabMDA：利用Transformer的上下文子集技术，为任意分类器提供表格流形数据增强方案](../../../paper_images/2406.01805/x6.png)

![TabMDA：利用Transformer的上下文子集技术，为任意分类器提供表格流形数据增强方案](../../../paper_images/2406.01805/x7.png)

![TabMDA：利用Transformer的上下文子集技术，为任意分类器提供表格流形数据增强方案](../../../paper_images/2406.01805/x8.png)

[Arxiv](https://arxiv.org/abs/2406.01805)