# 利用 LLM 多代理系统实现高效且精准的图推理

发布时间：2024年10月07日

`Agent` `图计算` `人工智能`

> Scalable and Accurate Graph Reasoning with LLM-based Multi-Agents

# 摘要

> 近期研究尝试利用大型语言模型 (LLM) 解决复杂图推理任务，但由于图结构复杂及 LLM 处理长文本的局限，现有方法在小型图和简单任务上准确性仍不尽人意。为此，我们推出 GraphAgent-Reasoner，一个无需微调的框架，通过多代理协作策略实现精确图推理。借鉴分布式图计算理论，我们将图问题分解为节点级小任务，分配给多个代理协同解决，大幅降低单个 LLM 处理的信息量和复杂性，提升推理准确性。只需增加代理数量，GraphAgent-Reasoner 便能高效扩展，适应包含上千节点的大型图。在 GraphInstruct 数据集上，该框架在多项式时间图推理任务中表现近乎完美，显著超越现有最佳模型，包括闭源和开源微调版本。此外，它还能处理网页重要性分析等实际图推理应用。

> Recent research has explored the use of Large Language Models (LLMs) for tackling complex graph reasoning tasks. However, due to the intricacies of graph structures and the inherent limitations of LLMs in handling long text, current approaches often fail to deliver satisfactory accuracy, even on small-scale graphs and simple tasks. To address these challenges, we introduce GraphAgent-Reasoner, a fine-tuning-free framework that utilizes a multi-agent collaboration strategy for explicit and precise graph reasoning. Inspired by distributed graph computation theory, our framework decomposes graph problems into smaller, node-centric tasks that are distributed among multiple agents. The agents collaborate to solve the overall problem, significantly reducing the amount of information and complexity handled by a single LLM, thus enhancing the accuracy of graph reasoning. By simply increasing the number of agents, GraphAgent-Reasoner can efficiently scale to accommodate larger graphs with over 1,000 nodes. Evaluated on the GraphInstruct dataset, our framework demonstrates near-perfect accuracy on polynomial-time graph reasoning tasks, significantly outperforming the best available models, both closed-source and fine-tuned open-source variants. Our framework also demonstrates the capability to handle real-world graph reasoning applications such as webpage importance analysis.

[Arxiv](https://arxiv.org/abs/2410.05130)