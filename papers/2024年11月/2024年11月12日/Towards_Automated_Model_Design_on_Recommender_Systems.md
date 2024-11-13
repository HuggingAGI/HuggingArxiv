# 关于推荐系统的自动化模型设计

发布时间：2024年11月12日

`其他` `推荐系统`

> Towards Automated Model Design on Recommender Systems

# 摘要

> 深度学习模型的日益普及为开发基于人工智能的推荐系统创造了新的机会。使用深度神经网络设计推荐系统需要精心的架构设计，进一步的优化需要在联合优化模型架构和硬件方面进行大量的协同设计工作。设计自动化，如自动机器学习（AutoML），对于充分挖掘推荐模型设计的潜力是必要的，包括模型选择和模型 - 硬件协同设计策略。我们引入了一种利用权重共享来探索丰富的解决方案空间的新范式。我们的范式创建了一个大型的超网来搜索最优架构和协同设计策略，以应对推荐领域中数据的多模态和异质性的挑战。从模型的角度来看，超网包括各种运算符、密集连接和维度搜索选项。从协同设计的角度来看，它包含了多种内存处理（PIM）配置，以生成硬件高效的模型。我们的解决方案空间的规模、异质性和复杂性带来了一些挑战，我们通过提出各种用于训练和评估超网的技术来解决这些挑战。我们精心制作的模型在三个点击率（CTR）预测基准上显示出了有希望的结果，在仅关注架构搜索时，其性能优于手动设计和 AutoML 制作的模型，并达到了最先进的性能。从协同设计的角度来看，我们在推荐模型中实现了 2 倍的 FLOPs 效率、1.8 倍的能源效率和 1.5 倍的性能提升。

> The increasing popularity of deep learning models has created new opportunities for developing AI-based recommender systems. Designing recommender systems using deep neural networks requires careful architecture design, and further optimization demands extensive co-design efforts on jointly optimizing model architecture and hardware. Design automation, such as Automated Machine Learning (AutoML), is necessary to fully exploit the potential of recommender model design, including model choices and model-hardware co-design strategies. We introduce a novel paradigm that utilizes weight sharing to explore abundant solution spaces. Our paradigm creates a large supernet to search for optimal architectures and co-design strategies to address the challenges of data multi-modality and heterogeneity in the recommendation domain. From a model perspective, the supernet includes a variety of operators, dense connectivity, and dimension search options. From a co-design perspective, it encompasses versatile Processing-In-Memory (PIM) configurations to produce hardware-efficient models. Our solution space's scale, heterogeneity, and complexity pose several challenges, which we address by proposing various techniques for training and evaluating the supernet. Our crafted models show promising results on three Click-Through Rates (CTR) prediction benchmarks, outperforming both manually designed and AutoML-crafted models with state-of-the-art performance when focusing solely on architecture search. From a co-design perspective, we achieve 2x FLOPs efficiency, 1.8x energy efficiency, and 1.5x performance improvements in recommender models.

[Arxiv](https://arxiv.org/abs/2411.07569)