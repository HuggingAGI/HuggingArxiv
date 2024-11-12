# 多模态预测器：联合预测时间序列和文本数据

发布时间：2024年11月11日

`LLM应用` `医疗保健` `气候科学`

> Multi-Modal Forecaster: Jointly Predicting Time Series and Textual Data

# 摘要

> 当前的预测方法在很大程度上是单模态的，并且由于缺乏精心策划的多模态基准数据集，而忽略了经常伴随时间序列的丰富文本数据。在这项工作中，我们开发了 TimeText Corpus（TTC），这是一个经过精心策划、时间对齐的文本和时间多模态预测数据集。我们的数据集由与时间戳对齐的数字和文本序列组成，并且包括来自两个不同领域的数据：气候科学和医疗保健。我们的数据对可用的多模态数据集的稀缺选择做出了重大贡献。我们还提出了混合多模态预测器（Hybrid-MMF），这是一个多模态的 LLM，使用共享嵌入来联合预测文本和时间序列数据。然而，与我们的预期相反，在我们的实验中，我们的 Hybrid-MMF 模型没有优于现有的基线。这个负面结果突出了多模态预测中固有的挑战。我们的代码和数据可在 https://github.com/Rose-STL-Lab/Multimodal_ Forecasting 获得。

> Current forecasting approaches are largely unimodal and ignore the rich textual data that often accompany the time series due to lack of well-curated multimodal benchmark dataset. In this work, we develop TimeText Corpus (TTC), a carefully curated, time-aligned text and time dataset for multimodal forecasting. Our dataset is composed of sequences of numbers and text aligned to timestamps, and includes data from two different domains: climate science and healthcare. Our data is a significant contribution to the rare selection of available multimodal datasets. We also propose the Hybrid Multi-Modal Forecaster (Hybrid-MMF), a multimodal LLM that jointly forecasts both text and time series data using shared embeddings. However, contrary to our expectations, our Hybrid-MMF model does not outperform existing baselines in our experiments. This negative result highlights the challenges inherent in multimodal forecasting. Our code and data are available at https://github.com/Rose-STL-Lab/Multimodal_ Forecasting.

[Arxiv](https://arxiv.org/abs/2411.06735)