# SplitLLM：通过协作推理优化 LLM 的模型放置和吞吐量

发布时间：2024年10月14日

`LLM应用` `信息技术` `人工智能`

> SplitLLM: Collaborative Inference of LLMs for Model Placement and Throughput Optimization

# 摘要

> 近年来，大型语言模型（LLM）凭借其理解和生成类人文本的能力，已成为颠覆性创新，深刻影响着我们的日常生活。它们的功能涵盖自然语言理解、信息检索、翻译、聊天机器人、虚拟助手等多个领域。然而，LLM 的庞大参数数量和 Transformer 架构中自注意力机制的二次复杂度，使得推理过程资源密集，吞吐量受限，尤其是处理长序列时。为此，我们设计了一种服务器与客户端间的协作推理架构，旨在优化资源利用，提升吞吐量。通过动态规划算法，我们实现了计算任务在服务器与客户端间的最优分配，不仅减轻了服务器负担，还提升了整体效率。实验结果显示，该方法能有效减少服务器工作量约 1/3，并比传统贪婪方法提升 19% 的性能。这表明，在多样化 LLM 推理请求的环境中，我们的方案显著提升了服务器吞吐量。

> Large language models (LLMs) have been a disruptive innovation in recent years, and they play a crucial role in our daily lives due to their ability to understand and generate human-like text. Their capabilities include natural language understanding, information retrieval and search, translation, chatbots, virtual assistance, and many more. However, it is well known that LLMs are massive in terms of the number of parameters. Additionally, the self-attention mechanism in the underlying architecture of LLMs, Transformers, has quadratic complexity in terms of both computation and memory with respect to the input sequence length. For these reasons, LLM inference is resource-intensive, and thus, the throughput of LLM inference is limited, especially for the longer sequences. In this report, we design a collaborative inference architecture between a server and its clients to alleviate the throughput limit. In this design, we consider the available resources on both sides, i.e., the computation and communication costs. We develop a dynamic programming-based algorithm to optimally allocate computation between the server and the client device to increase the server throughput, while not violating the service level agreement (SLA). We show in the experiments that we are able to efficiently distribute the workload allowing for roughly 1/3 reduction in the server workload, while achieving 19 percent improvement over a greedy method. As a result, we are able to demonstrate that, in an environment with different types of LLM inference requests, the throughput of the server is improved.

[Arxiv](https://arxiv.org/abs/2410.10759)