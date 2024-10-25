# BATON：通过动态重新分批来提高大型语言模型的批量推理效率

发布时间：2024年10月24日

`LLM应用` `网络服务` `推理方案`

> BATON: Enhancing Batch-wise Inference Efficiency for Large Language Models via Dynamic Re-batching

# 摘要

> 大型语言模型（LLM）的先进能力激发了各种交互式网络服务或应用程序的发展，例如 ChatGPT，它为用户提供查询推理服务。与传统的 DNN 模型不同，LLM 的推理对于不同的查询需要不同的前向计算迭代，这给现有的运行至完成的批量式推理带来了效率挑战。因此，一些方法通过复制 LLM 的所有非线性层将批量式推理细化到迭代级别。然而，这种方法不仅增加了资源使用，而且由于新添加查询的预填充，还为批次引入了空闲计算。因此，我们提出了 BATON，一种通过动态调整处理批次的高效批量式 LLM 推理方案，它可以实现近乎零的空闲计算，而不会产生额外的资源消耗。为此，BATON 1）对新插入查询和处理批次的推理中涉及的向量进行整形以对齐维度，并基于向量整形生成新的注意力掩码以确保推理的正确性，这使得查询插入无需消耗额外资源；2）通过利用预填充和解码分离机制将新查询的预填充键和值嵌入到处理批次的 KV_Cache 中，消除新查询的预填充过程为批次引入的空闲计算。实验结果表明，与最先进的解决方案 Orca 相比，BATON 将查询处理效率提高了多达 1.75 倍。

> The advanced capabilities of Large Language Models (LLMs) have inspired the development of various interactive web services or applications, such as ChatGPT, which offer query inference services for users. Unlike traditional DNN model, the inference of LLM entails different iterations of forward computation for different queries, which result in efficiency challenges for existing run-to-completion batch-wise inference. Hence, some methods refine batch-wise inference to iteration-level by duplicating all nonlinear layers of LLM. However, this approach not only increases resource usage but also introduces idle computations to the batch due to the prefilling of newly added queries. Therefore, we propose BATON, an efficient batch-wise LLM inference scheme by dynamically adjusting processing batch, which can achieve near-zero idle computations without incurring additional resource consumption. To do so, BATON 1) shapes the vectors involved in the inference of the newly inserted query and processing batch to align dimensions and generates a new attention mask based on vector shaping to ensure inference correctness, which enables query inserting without consuming additional resource; 2) embeds prefilled Keys and Values of the new query into the KV_Cache of the processing batch by leveraging the prefilling and decoding separation mechanism, eliminating idle computations to the batch introduced by the prefilling process of the new query. Experimental results show that compared to the state-of-the-art solution Orca, BATON improves query processing by up to 1.75 times.

[Arxiv](https://arxiv.org/abs/2410.18701)