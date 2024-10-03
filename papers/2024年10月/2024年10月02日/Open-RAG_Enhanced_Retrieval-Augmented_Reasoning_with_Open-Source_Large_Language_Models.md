# Open-RAG：利用开源大型语言模型提升检索增强推理能力

发布时间：2024年10月02日

`RAG` `人工智能`

> Open-RAG: Enhanced Retrieval-Augmented Reasoning with Open-Source Large Language Models

# 摘要

> RAG 虽然提升了 LLM 的事实准确性，但在使用开源 LLM 时，其推理能力仍显不足。为此，我们推出了 Open-RAG 框架，通过开源 LLM 增强 RAG 的推理能力。Open-RAG 将任意 LLM 转化为高效的稀疏 MoE 模型，能处理复杂推理任务，并训练模型识别看似相关但误导的干扰因素。它动态选择专家，整合外部知识，生成更精准、更贴切的回答。我们还提出了混合自适应检索方法，平衡性能与速度。实验显示，基于 Llama2-7B 的 Open-RAG 在知识密集型任务中超越了 ChatGPT 等顶尖模型。代码和模型已在 https://openragmoe.github.io/ 开源。

> Retrieval-Augmented Generation (RAG) has been shown to enhance the factual accuracy of Large Language Models (LLMs), but existing methods often suffer from limited reasoning capabilities in effectively using the retrieved evidence, particularly when using open-source LLMs. To mitigate this gap, we introduce a novel framework, Open-RAG, designed to enhance reasoning capabilities in RAG with open-source LLMs. Our framework transforms an arbitrary dense LLM into a parameter-efficient sparse mixture of experts (MoE) model capable of handling complex reasoning tasks, including both single- and multi-hop queries. Open-RAG uniquely trains the model to navigate challenging distractors that appear relevant but are misleading. As a result, Open-RAG leverages latent learning, dynamically selecting relevant experts and integrating external knowledge effectively for more accurate and contextually relevant responses. In addition, we propose a hybrid adaptive retrieval method to determine retrieval necessity and balance the trade-off between performance gain and inference speed. Experimental results show that the Llama2-7B-based Open-RAG outperforms state-of-the-art LLMs and RAG models such as ChatGPT, Self-RAG, and Command R+ in various knowledge-intensive tasks. We open-source our code and models at https://openragmoe.github.io/

[Arxiv](https://arxiv.org/abs/2410.01782)