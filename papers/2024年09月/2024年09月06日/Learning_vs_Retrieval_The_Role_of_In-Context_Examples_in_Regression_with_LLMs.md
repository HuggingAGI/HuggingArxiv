# 学习与检索：LLM 回归任务中上下文示例的角色

发布时间：2024年09月06日

`LLM理论` `人工智能` `机器学习`

> Learning vs Retrieval: The Role of In-Context Examples in Regression with LLMs

# 摘要

> 生成式 LLM 具备 in-context 学习能力，但其背后的机制仍待深入研究。实验结果显示，模型如何利用 ICL 并不总是一致。为此，我们提出一个评估 ICL 机制的框架，认为其结合了内部知识检索与从示例中学习，尤其关注回归任务。我们首先验证 LLM 在实际数据集上的回归能力，随后设计实验，探究 LLM 在检索内部知识与学习示例间的平衡。这一过程介于两极之间。我们详细分析了不同因素（如任务先验知识、示例信息类型与丰富度）对机制触发的影响。通过三个 LLM 和多个数据集的验证，我们证实了研究的有效性。研究结果还指导了如何设计提示，以最大化 in-context 示例的元学习效果，并根据具体问题优化知识检索。

> Generative Large Language Models (LLMs) are capable of being in-context learners. However, the underlying mechanism of in-context learning (ICL) is still a major research question, and experimental research results about how models exploit ICL are not always consistent. In this work, we propose a framework for evaluating in-context learning mechanisms, which we claim are a combination of retrieving internal knowledge and learning from in-context examples by focusing on regression tasks. First, we show that LLMs can perform regression on real-world datasets and then design experiments to measure the extent to which the LLM retrieves its internal knowledge versus learning from in-context examples. We argue that this process lies on a spectrum between these two extremes. We provide an in-depth analysis of the degrees to which these mechanisms are triggered depending on various factors, such as prior knowledge about the tasks and the type and richness of the information provided by the in-context examples. We employ three LLMs and utilize multiple datasets to corroborate the robustness of our findings. Our results shed light on how to engineer prompts to leverage meta-learning from in-context examples and foster knowledge retrieval depending on the problem being addressed.

[Arxiv](https://arxiv.org/abs/2409.04318)