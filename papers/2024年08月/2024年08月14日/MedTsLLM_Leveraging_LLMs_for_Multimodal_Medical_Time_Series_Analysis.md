# MedTsLLM：借助 LLM 之力，探索多模态医学时间序列的奥秘

发布时间：2024年08月14日

`LLM应用` `时间序列分析`

> MedTsLLM: Leveraging LLMs for Multimodal Medical Time Series Analysis

# 摘要

> 现实世界数据的复杂性与异质性为传统机器学习与信号处理带来了挑战。以医学为例，有效解析多样生理信号对患者监测与临床决策极为关键，却也充满挑战。我们推出的MedTsLLM框架，作为多模态大型语言模型，巧妙融合时间序列与文本上下文，针对生理信号进行语义分割、边界与异常检测，助力深入信号分析，为临床提供实用洞见。通过重编程层，我们使时间序列嵌入与预训练LLM空间对齐，充分利用原始数据与文本信息。面对医疗数据的多变量特性，我们创新处理多协变量方法，并定制包含患者特质的文本提示。MedTsLLM在心电图、呼吸波形等多领域超越前沿基准，标志着LLM在医学时间序列分析的重大进步，有望强化临床数据工具，提升患者福祉。

> The complexity and heterogeneity of data in many real-world applications pose significant challenges for traditional machine learning and signal processing techniques. For instance, in medicine, effective analysis of diverse physiological signals is crucial for patient monitoring and clinical decision-making and yet highly challenging. We introduce MedTsLLM, a general multimodal large language model (LLM) framework that effectively integrates time series data and rich contextual information in the form of text to analyze physiological signals, performing three tasks with clinical relevance: semantic segmentation, boundary detection, and anomaly detection in time series. These critical tasks enable deeper analysis of physiological signals and can provide actionable insights for clinicians. We utilize a reprogramming layer to align embeddings of time series patches with a pretrained LLM's embedding space and make effective use of raw time series, in conjunction with textual context. Given the multivariate nature of medical datasets, we develop methods to handle multiple covariates. We additionally tailor the text prompt to include patient-specific information. Our model outperforms state-of-the-art baselines, including deep learning models, other LLMs, and clinical methods across multiple medical domains, specifically electrocardiograms and respiratory waveforms. MedTsLLM presents a promising step towards harnessing the power of LLMs for medical time series analysis that can elevate data-driven tools for clinicians and improve patient outcomes.

[Arxiv](https://arxiv.org/abs/2408.07773)