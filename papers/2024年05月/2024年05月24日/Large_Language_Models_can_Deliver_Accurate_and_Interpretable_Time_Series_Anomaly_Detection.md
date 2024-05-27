# 大型语言模型在时间序列异常检测方面展现出准确性与可解释性。

发布时间：2024年05月24日

`LLM应用

这篇论文摘要描述了一种名为LLMAD的新方法，该方法利用大型语言模型（LLMs）进行时间序列异常检测（TSAD）。这种方法通过检索相似的时间序列片段来提高异常检测的准确性，并增强了可解释性。LLMAD采用了AnoCoT方法，模拟专家决策逻辑，从多角度解释检测结果，以帮助用户做出决策。实验结果表明，LLMAD在性能上与顶尖的深度学习技术相当，同时提供了卓越的解释性。这是首次尝试直接将LLMs应用于TSAD领域。因此，这篇论文应归类为LLM应用。` `时间序列分析` `异常检测`

> Large Language Models can Deliver Accurate and Interpretable Time Series Anomaly Detection

# 摘要

> 时间序列异常检测（TSAD）通过识别异常模式，确保系统稳定并迅速响应，对各行业至关重要。传统模型依赖深度学习，需大量数据且缺乏透明度。为此，我们创新提出LLMAD，一种利用大型语言模型（LLMs）的新方法，它通过检索相似时间序列片段，不仅提高了异常检测的准确性，还增强了可解释性。LLMAD采用AnoCoT方法，模拟专家决策逻辑，从多角度解释检测结果，助力用户决策。实验证明，LLMAD在性能上媲美顶尖深度学习技术，同时提供卓越的解释性。这是首次尝试直接应用LLMs于TSAD领域。

> Time series anomaly detection (TSAD) plays a crucial role in various industries by identifying atypical patterns that deviate from standard trends, thereby maintaining system integrity and enabling prompt response measures. Traditional TSAD models, which often rely on deep learning, require extensive training data and operate as black boxes, lacking interpretability for detected anomalies. To address these challenges, we propose LLMAD, a novel TSAD method that employs Large Language Models (LLMs) to deliver accurate and interpretable TSAD results. LLMAD innovatively applies LLMs for in-context anomaly detection by retrieving both positive and negative similar time series segments, significantly enhancing LLMs' effectiveness. Furthermore, LLMAD employs the Anomaly Detection Chain-of-Thought (AnoCoT) approach to mimic expert logic for its decision-making process. This method further enhances its performance and enables LLMAD to provide explanations for their detections through versatile perspectives, which are particularly important for user decision-making. Experiments on three datasets indicate that our LLMAD achieves detection performance comparable to state-of-the-art deep learning methods while offering remarkable interpretability for detections. To the best of our knowledge, this is the first work that directly employs LLMs for TSAD.

![大型语言模型在时间序列异常检测方面展现出准确性与可解释性。](../../../paper_images/2405.15370/x1.png)

![大型语言模型在时间序列异常检测方面展现出准确性与可解释性。](../../../paper_images/2405.15370/x2.png)

![大型语言模型在时间序列异常检测方面展现出准确性与可解释性。](../../../paper_images/2405.15370/x3.png)

![大型语言模型在时间序列异常检测方面展现出准确性与可解释性。](../../../paper_images/2405.15370/x4.png)

![大型语言模型在时间序列异常检测方面展现出准确性与可解释性。](../../../paper_images/2405.15370/x5.png)

![大型语言模型在时间序列异常检测方面展现出准确性与可解释性。](../../../paper_images/2405.15370/x6.png)

![大型语言模型在时间序列异常检测方面展现出准确性与可解释性。](../../../paper_images/2405.15370/x7.png)

![大型语言模型在时间序列异常检测方面展现出准确性与可解释性。](../../../paper_images/2405.15370/x8.png)

![大型语言模型在时间序列异常检测方面展现出准确性与可解释性。](../../../paper_images/2405.15370/x9.png)

[Arxiv](https://arxiv.org/abs/2405.15370)