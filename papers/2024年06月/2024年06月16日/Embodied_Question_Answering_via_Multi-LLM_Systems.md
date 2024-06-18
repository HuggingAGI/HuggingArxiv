# 多LLM系统下的具身问答探索

发布时间：2024年06月16日

`Agent

这篇论文主要关注的是在Embodied Question Answering (EQA) 问题中使用多代理框架来提高答案的准确性和效率。研究中使用了基于大型语言模型 (LLM) 的多个代理，并通过训练一个中央答案模型 (CAM) 来整合这些代理的回答，从而生成更稳健的答案。这种方法涉及到了代理的设计和应用，因此属于Agent分类。虽然论文中使用了LLM，但主要焦点是代理的应用和优化，而不是LLM的理论或应用开发，因此不适合归类为LLM应用或LLM理论。此外，论文中并未提及与RAG（Retrieval-Augmented Generation）相关的技术或方法，因此也不属于RAG分类。` `家庭自动化` `智能助手`

> Embodied Question Answering via Multi-LLM Systems

# 摘要

> Embodied Question Answering (EQA) 问题中，代理需探索环境以解答用户疑问。现有研究多聚焦于单一代理，探索过程既耗时又昂贵。本研究创新地采用多代理框架，利用多个基于大型语言模型 (LLM) 的代理独立应对家庭环境相关查询。我们训练了一个中央答案模型 (CAM)，通过整合各代理的回答，生成更为稳健的答案。与传统的集成 LLM 聚合方法（如投票或辩论）相比，CAM 使 EQA 准确性提升了 50%，且无需代理间通信，降低了成本。我们进一步通过非线性和线性算法对 CAM 进行优化，并通过排列特征重要性 (PFI) 分析，揭示了 CAM 对各独立代理及查询上下文的依赖程度。

> Embodied Question Answering (EQA) is an important problem, which involves an agent exploring the environment to answer user queries. In the existing literature, EQA has exclusively been studied in single-agent scenarios, where exploration can be time-consuming and costly. In this work, we consider EQA in a multi-agent framework involving multiple large language models (LLM) based agents independently answering queries about a household environment. To generate one answer for each query, we use the individual responses to train a Central Answer Model (CAM) that aggregates responses for a robust answer. Using CAM, we observe a $50\%$ higher EQA accuracy when compared against aggregation methods for ensemble LLM, such as voting schemes and debates. CAM does not require any form of agent communication, alleviating it from the associated costs. We ablate CAM with various nonlinear (neural network, random forest, decision tree, XGBoost) and linear (logistic regression classifier, SVM) algorithms. Finally, we present a feature importance analysis for CAM via permutation feature importance (PFI), quantifying CAMs reliance on each independent agent and query context.

![多LLM系统下的具身问答探索](../../../paper_images/2406.10918/answer_network3.png)

![多LLM系统下的具身问答探索](../../../paper_images/2406.10918/pipelinefinal.png)

![多LLM系统下的具身问答探索](../../../paper_images/2406.10918/acc_comp_2envs.png)

![多LLM系统下的具身问答探索](../../../paper_images/2406.10918/acc_comp_80_20.png)

![多LLM系统下的具身问答探索](../../../paper_images/2406.10918/lgx_acc_comp.png)

[Arxiv](https://arxiv.org/abs/2406.10918)