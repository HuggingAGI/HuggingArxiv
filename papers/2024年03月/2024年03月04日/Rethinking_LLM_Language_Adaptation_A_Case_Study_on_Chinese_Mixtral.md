# 对LLM的语言适应性进行再思考——以“Chinese Mixtral”为例的深度探究

发布时间：2024年03月04日

`LLM应用`

> Rethinking LLM Language Adaptation: A Case Study on Chinese Mixtral

> Mixtral——作为一款采用稀疏专家混合结构且表现突出的语言模型，凭借其独特的设计和卓越性能吸引了广泛关注。在此背景下，基于 Mixtral-8x7B-v0.1，本研究提出了强化了中文能力的 Chinese-Mixtral 和 Chinese-Mixtral-Instruct，它们经过深度预训练及指令精调优化。实验结果证实，这两种模型在保留原有英文处理能力的基础上，有效提高了中文理解与生成的表现力。同时，我们针对大型语言模型在进行语言适应时面临的若干核心问题进行了探讨，例如扩充特定语言词汇表的必要性以及选择何种初始化模型（基础模型对比指令模型），并结合实际数据和深入分析给出解答。为了直观展示各个专家层对下游任务的重要程度，我们还提供了可视化的结果展示。所有相关资源已开放至 \url{https://github.com/ymcui/Chinese-Mixtral}，供公众获取。

> Mixtral, a representative sparse mixture of experts (SMoE) language model, has received significant attention due to its unique model design and superior performance. Based on Mixtral-8x7B-v0.1, in this paper, we propose Chinese-Mixtral and Chinese-Mixtral-Instruct with improved Chinese language abilities by adopting further pre-training and instruction fine-tuning. Experimental results show that our Chinese-Mixtral and Chinese-Mixtral-Instruct successfully improve Chinese understanding and generation performance while retaining the original English abilities. Then, we discuss several key questions when performing language adaptation on large language models, including the necessity of extending the language-specific vocabulary and the choice of the initialization model (foundation model v.s. instruction model), by providing empirical results and analysis. We also present the visualizations of each expert to examine their importance on downstream tasks. Our resources are publicly available through \url{https://github.com/ymcui/Chinese-Mixtral}.

[Arxiv](https://arxiv.org/abs/2403.01851)