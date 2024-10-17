# 通过模态对齐，重新探索大型语言模型在时间序列分析中的应用。

发布时间：2024年10月16日

`LLM应用` `时间序列分析` `网络应用`

> Revisited Large Language Model for Time Series Analysis through Modality Alignment

# 摘要

> 大型语言模型在传感器数据分析等关键网络应用中表现出色，但因其并非专为时间序列任务设计，简单的线性回归模型往往能在低复杂度下达到类似效果。我们通过大量实验评估了LLMs在时间序列任务（如预测、分类、插补和异常检测）中的应用效果，发现其在这些任务中优势甚微，甚至可能扭曲数据的时间结构。相比之下，简单模型在参数更少的情况下表现更优。我们还分析了现有重编程技术，发现它们未能有效对齐时间序列数据与语言，在嵌入空间中表现出伪对齐行为。研究结果表明，LLM在时间序列任务中的表现更多源于数据本身的特性，而非与语言模型架构的有效对齐。

> Large Language Models have demonstrated impressive performance in many pivotal web applications such as sensor data analysis. However, since LLMs are not designed for time series tasks, simpler models like linear regressions can often achieve comparable performance with far less complexity. In this study, we perform extensive experiments to assess the effectiveness of applying LLMs to key time series tasks, including forecasting, classification, imputation, and anomaly detection. We compare the performance of LLMs against simpler baseline models, such as single-layer linear models and randomly initialized LLMs. Our results reveal that LLMs offer minimal advantages for these core time series tasks and may even distort the temporal structure of the data. In contrast, simpler models consistently outperform LLMs while requiring far fewer parameters. Furthermore, we analyze existing reprogramming techniques and show, through data manifold analysis, that these methods fail to effectively align time series data with language and display pseudo-alignment behaviour in embedding space. Our findings suggest that the performance of LLM-based methods in time series tasks arises from the intrinsic characteristics and structure of time series data, rather than any meaningful alignment with the language model architecture.

[Arxiv](https://arxiv.org/abs/2410.12326)