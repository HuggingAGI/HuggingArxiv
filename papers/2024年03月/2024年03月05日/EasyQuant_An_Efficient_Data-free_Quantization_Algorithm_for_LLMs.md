# [EasyQuant：针对LLMs设计的高效无数据量化方案](https://arxiv.org/abs/2403.02775)

发布时间：2024年03月05日

`LLM应用`

> EasyQuant: An Efficient Data-free Quantization Algorithm for LLMs

> LLMs 在各种任务上展现出了远胜传统方法的优越性，但受限于高昂计算资源及大内存需求，实际应用时面临挑战。模型量化技术为此提供了一种有效的解决方案，它能够显著降低运行开销。然而，过去多数研究在量化LLMs时，采用有限训练样本校准模型，可能导致模型在应对未知场景和新任务时泛化性能受损。为此，本研究探索了一个核心问题：我们是否能设计出一种不依赖训练数据、保障LLMs泛化能力的量化方法呢？于是，我们创新提出了一种无需训练、完全独立于数据的权重量化算法——EasyQuant。经观察发现，权重中的异常值以及量化范围的选择是决定量化误差大小的关键因素。因此，EasyQuant选择保留少于1%的异常权重，并针对性优化量化范围以减少重建误差。令人惊喜的是，EasyQuant成功实现了与原模型旗鼓相当的表现，并且由于完全不依赖训练数据，量化后的LLMs泛化性能得以稳固保障。更为重要的是，EasyQuant支持并行处理，即便是参数规模超过1000亿的LLMs，也能够在短短几分钟内完成量化过程。目前，据我们了解，这是首次在数据独立环境下实现近乎无损量化效果的研究，并且我们的算法执行效率较依赖数据的方法提升了十倍以上。

> Large language models (LLMs) have proven to be very superior to conventional methods in various tasks. However, their expensive computations and high memory requirements are prohibitive for deployment. Model quantization is an effective method for reducing this overhead. The problem is that in most previous works, the quantized model was calibrated using few samples from the training data, which might affect the generalization of the quantized LLMs to unknown cases and tasks. Hence in this work, we explore an important question: Can we design a data-independent quantization method for LLMs to guarantee its generalization performance? In this work, we propose EasyQuant, a training-free and data-independent weight-only quantization algorithm for LLMs. Our observation indicates that two factors: outliers in the weight and quantization ranges, are essential for reducing the quantization error. Therefore, in EasyQuant, we leave the outliers (less than 1%) unchanged and optimize the quantization range to reduce the reconstruction error. With these methods, we surprisingly find that EasyQuant achieves comparable performance to the original model. Since EasyQuant does not depend on any training data, the generalization performance of quantized LLMs is safely guaranteed. Moreover, EasyQuant can be implemented in parallel so that the quantized model could be attained in a few minutes even for LLMs over 100B. To our best knowledge, we are the first work that achieves almost lossless quantization performance for LLMs under a data-independent setting and our algorithm runs over 10 times faster than the data-dependent methods.

[Arxiv](https://arxiv.org/abs/2403.02775)