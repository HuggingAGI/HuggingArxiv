# 数据污染，我们能忽视多少？

发布时间：2024年10月04日

`LLM理论` `机器学习` `数据安全`

> How much can we forget about Data Contamination?

# 摘要

> 基准数据泄露到训练数据中已成为评估 LLM 能力的一大难题。我们通过实验和理论分析，挑战了小规模污染使基准评估无效的普遍观点。首先，我们量化了基准过拟合的程度，考虑了模型参数、示例重复次数和训练令牌数量三个维度。结果显示，轻微污染确实会导致过拟合，但如果训练数据量超过 Chinchilla 定律的五倍，即使是多次污染也能被遗忘。接着，我们提出了一个基于累积权重衰减的遗忘理论，为遗忘过去数据所需的梯度步数设定了界限。实验表明，遗忘速度比理论预测更快。综上所述，我们的研究显示，在实际训练中，适量的污染最终会被遗忘。

> The leakage of benchmark data into the training data has emerged as a significant challenge for evaluating the capabilities of large language models (LLMs). In this work, we use experimental evidence and theoretical estimates to challenge the common assumption that small-scale contamination renders benchmark evaluations invalid. First, we experimentally quantify the magnitude of benchmark overfitting based on scaling along three dimensions: The number of model parameters (up to 1.6B), the number of times an example is seen (up to 144), and the number of training tokens (up to 40B). We find that if model and data follow the Chinchilla scaling laws, minor contamination indeed leads to overfitting. At the same time, even 144 times of contamination can be forgotten if the training data is scaled beyond five times Chinchilla, a regime characteristic of many modern LLMs. We then derive a simple theory of example forgetting via cumulative weight decay. It allows us to bound the number of gradient steps required to forget past data for any training run where we know the hyperparameters of AdamW. This indicates that many LLMs, including Llama 3, have forgotten the data seen at the beginning of training. Experimentally, we demonstrate that forgetting occurs faster than what is predicted by our bounds. Taken together, our results suggest that moderate amounts of contamination can be forgotten at the end of realistically scaled training runs.

[Arxiv](https://arxiv.org/abs/2410.03249)