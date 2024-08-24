# 人类级预测的推理与工具

发布时间：2024年08月21日

`Agent` `预测分析` `人工智能`

> Reasoning and Tools for Human-Level Forecasting

# 摘要

> 在网络规模数据集上训练的语言模型 (LMs) 之所以成功，是因为它们能记忆大量训练数据，即便这些数据仅在少数示例中出现。这些能力在问答等任务中虽受欢迎，但也引发了对模型是否真正具备推理能力的质疑。在预测任务中，这一区别尤为突出，因为答案不在训练数据中，模型需进行逻辑推断。我们提出的 Reasoning and Tools for Forecasting (RTF) 框架，包含能够动态获取最新信息并进行数值模拟的 ReAct 代理。通过竞争性预测平台的提问，我们评估了模型，并发现其表现与人类预测相当，甚至更优。这表明，配备适当工具的 LMs 确实能像人类一样思考和适应，为现实决策提供宝贵见解。

> Language models (LMs) trained on web-scale datasets are largely successful due to their ability to memorize large amounts of training data, even if only present in a few examples. These capabilities are often desirable in evaluation on tasks such as question answering but raise questions about whether these models can exhibit genuine reasoning or succeed only at mimicking patterns from the training data. This distinction is particularly salient in forecasting tasks, where the answer is not present in the training data, and the model must reason to make logical deductions. We present Reasoning and Tools for Forecasting (RTF), a framework of reasoning-and-acting (ReAct) agents that can dynamically retrieve updated information and run numerical simulation with equipped tools. We evaluate our model with questions from competitive forecasting platforms and demonstrate that our method is competitive with and can outperform human predictions. This suggests that LMs, with the right tools, can indeed think and adapt like humans, offering valuable insights for real-world decision-making.

[Arxiv](https://arxiv.org/abs/2408.12036)