# 大型语言模型是否有先见之明？使用每日新闻作为神谕进行持续评估

发布时间：2024年11月12日

`LLM应用` `语言模型` `事件预测`

> Are LLMs Prescient? A Continuous Evaluation using Daily News as the Oracle

# 摘要

> 许多现有的大型语言模型（LLM）评估基准由于新模型和训练数据的出现很快就过时了。这些基准在评估 LLM 性能如何随时间变化方面也存在不足，因为它们由没有时间维度的静态问题组成。为了解决这些限制，我们建议使用未来事件预测作为一种连续评估方法来评估 LLM 的时间泛化和预测能力。我们的基准 Daily Oracle 从每日新闻中自动生成问答（QA）对，挑战 LLM 预测“未来”事件结果。我们的发现表明，随着预训练数据过时，LLM 性能会随着时间的推移而下降。虽然检索增强生成（RAG）有可能提高预测准确性，但性能下降模式仍然存在，突出了持续模型更新的必要性。

> Many existing evaluation benchmarks for Large Language Models (LLMs) quickly become outdated due to the emergence of new models and training data. These benchmarks also fall short in assessing how LLM performance changes over time, as they consist of static questions without a temporal dimension. To address these limitations, we propose using future event prediction as a continuous evaluation method to assess LLMs' temporal generalization and forecasting abilities. Our benchmark, Daily Oracle, automatically generates question-answer (QA) pairs from daily news, challenging LLMs to predict "future" event outcomes. Our findings reveal that as pre-training data becomes outdated, LLM performance degrades over time. While Retrieval Augmented Generation (RAG) has the potential to enhance prediction accuracy, the performance degradation pattern persists, highlighting the need for continuous model updates.

[Arxiv](https://arxiv.org/abs/2411.08324)