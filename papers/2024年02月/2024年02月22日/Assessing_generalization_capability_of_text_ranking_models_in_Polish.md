# [本研究旨在深入探讨波兰语环境下文本排名模型的泛化性能，以期对其在不同场景下的适用性有更全面的理解和评价。]

发布时间：2024年02月22日

`RAG`

> Assessing generalization capability of text ranking models in Polish

> 随着RAG技术的日益普及，它正被广泛应用来整合内部知识库与大型语言模型。在常规RAG流程中，三个关键模型分别扮演着检索、重排序和生成的角色。本文聚焦波兰语环境下的重排序挑战，深入探讨了各类重排序器的性能表现，并将它们与市场上的检索模型进行了对比。基于包含41个多元化信息检索任务的波兰语基准测试，我们对市面现有模型及我们自主训练的模型进行了详尽评估。实验揭示，大部分模型在处理非目标领域的泛化时面临难题，但巧妙结合高效优化手段与大量训练数据，我们成功打造出体积紧凑且具有泛化能力的重排序器。其中最为出色的模型，在波兰语文本重排序任务上实现了新的突破，其性能甚至超越了拥有高达30倍参数量的现有模型。

> Retrieval-augmented generation (RAG) is becoming an increasingly popular technique for integrating internal knowledge bases with large language models. In a typical RAG pipeline, three models are used, responsible for the retrieval, reranking, and generation stages. In this article, we focus on the reranking problem for the Polish language, examining the performance of rerankers and comparing their results with available retrieval models. We conduct a comprehensive evaluation of existing models and those trained by us, utilizing a benchmark of 41 diverse information retrieval tasks for the Polish language. The results of our experiments show that most models struggle with out-of-domain generalization. However, a combination of effective optimization method and a large training dataset allows for building rerankers that are both compact in size and capable of generalization. The best of our models establishes a new state-of-the-art for reranking in the Polish language, outperforming existing models with up to 30 times more parameters.

[Arxiv](https://arxiv.org/abs/2402.14318)