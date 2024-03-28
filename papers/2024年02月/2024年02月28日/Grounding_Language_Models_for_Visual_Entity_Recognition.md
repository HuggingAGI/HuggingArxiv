# 为视觉实体识别而进行的语言模型接地技术，旨在探究如何使语言模型更好地理解和利用视觉信息，从而提升识别图像中特定实体的能力。

发布时间：2024年02月28日

`Agent`

> Grounding Language Models for Visual Entity Recognition

# 摘要

> 我们创新性地提出了AutoVER——一种基于自回归机制的视觉实体识别模型，它通过融合检索增强约束生成技术，成功扩展了多模态大语言模型的功能边界。AutoVER不仅擅长处理需结合视觉信息进行推理的查询任务，还有效解决了跨领域实体识别的难题。此模型独辟蹊径，在无需借助外部检索器的前提下，采用对比学习策略，高效地区分海量标签空间中的相似实体。在实际应用时，利用检索得到的候选答案列表，能直观地引导语言生成过程，排除无效解码路径，从而显著提升了性能。在最新的Oven-Wiki基准测试中，AutoVER在各种数据集分割上的表现均有大幅提升，其中“已见过实体”分割的准确率从32.7%跃升至61.5%，并在处理未见过的数据和复杂查询任务时，成绩同样实现了显著的两位数增长。

> We introduce AutoVER, an Autoregressive model for Visual Entity Recognition. Our model extends an autoregressive Multi-modal Large Language Model by employing retrieval augmented constrained generation. It mitigates low performance on out-of-domain entities while excelling in queries that require visually-situated reasoning. Our method learns to distinguish similar entities within a vast label space by contrastively training on hard negative pairs in parallel with a sequence-to-sequence objective without an external retriever. During inference, a list of retrieved candidate answers explicitly guides language generation by removing invalid decoding paths. The proposed method achieves significant improvements across different dataset splits in the recently proposed Oven-Wiki benchmark. Accuracy on the Entity seen split rises from 32.7% to 61.5%. It also demonstrates superior performance on the unseen and query splits by a substantial double-digit margin.

[Arxiv](https://arxiv.org/abs/2402.18695)