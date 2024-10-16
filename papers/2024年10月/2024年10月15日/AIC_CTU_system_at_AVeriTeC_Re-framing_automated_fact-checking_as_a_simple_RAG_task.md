# AVeriTeC 的 AIC CTU 系统：将自动事实核查简化为一个简单的 RAG 任务

发布时间：2024年10月15日

`RAG` `事实核查` `人工智能`

> AIC CTU system at AVeriTeC: Re-framing automated fact-checking as a simple RAG task

# 摘要

> 本文介绍了我们在 AVeriTeC 共享任务中获得第 3 名的方案，该方案利用 Retrieval-Augmented Generation (RAG) 技术，结合大型语言模型的预测能力，解决在野外检索证据进行事实核查的难题。我们公开了代码库，详细阐述了检索器和证据与标签生成器两大模块，并解释了 MMR 重排序和 Likert 量表置信度估计等特色功能。通过在 AVeriTeC 开发和测试集上的评估，我们选择了 GPT-4o 作为最佳模型，同时 Llama 3.1 70B 作为开源备选。实证错误分析显示，预测错误常与数据噪声或事实核查的模糊性相关，这为未来的研究与数据增强提供了方向。

> This paper describes our $3^{rd}$ place submission in the AVeriTeC shared task in which we attempted to address the challenge of fact-checking with evidence retrieved in the wild using a simple scheme of Retrieval-Augmented Generation (RAG) designed for the task, leveraging the predictive power of Large Language Models. We release our codebase and explain its two modules - the Retriever and the Evidence & Label generator - in detail, justifying their features such as MMR-reranking and Likert-scale confidence estimation. We evaluate our solution on AVeriTeC dev and test set and interpret the results, picking the GPT-4o as the most appropriate model for our pipeline at the time of our publication, with Llama 3.1 70B being a promising open-source alternative. We perform an empirical error analysis to see that faults in our predictions often coincide with noise in the data or ambiguous fact-checks, provoking further research and data augmentation.

[Arxiv](https://arxiv.org/abs/2410.11446)