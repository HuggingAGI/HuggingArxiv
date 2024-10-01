# CLLMate：一款专为天气与气候事件预测设计的多模态大型语言模型

发布时间：2024年09月27日

`LLM应用` `环境科学`

> CLLMate: A Multimodal LLM for Weather and Climate Events Forecasting

# 摘要

> 预测天气和气候事件对于应对环境挑战至关重要。传统研究多聚焦于封闭事件的数值预测，而忽视了开放事件的直接预测。为此，我们提出了天气和气候事件预测（WCEF）任务，结合气象数据和文本信息，预测潜在的天气和气候变化。然而，多模态数据对齐和监督数据集的缺乏使得这一任务充满挑战。为此，我们设计了一个框架，利用大型语言模型（LLM）将历史气象数据与过去的天气和气候事件对齐，并通过分析41,000多篇环境新闻文章构建知识图谱。随后，我们将这些事件与气象数据映射，创建了LLM在WCEF任务上调整的最大和最独特的监督数据集。最终，我们推出了CLLMate（气候LLM），一个多模态LLM，用于预测天气和气候事件。实验结果显示，CLLMate不仅超越了基线模型，还优于其他多模态LLM，展示了LLM在天气和气候事件预测中的巨大潜力，并为WCEF任务的研究开辟了新的前景。

> Forecasting weather and climate events is crucial for making appropriate measures to mitigate environmental hazards and minimize associated losses. Previous research on environmental forecasting focuses on predicting numerical meteorological variables related to closed-set events rather than forecasting open-set events directly, which limits the comprehensiveness of event forecasting. We propose Weather and Climate Event Forecasting (WCEF), a new task that leverages meteorological raster data and textual event data to predict potential weather and climate events. However, due to difficulties in aligning multimodal data and the lack of sufficient supervised datasets, this task is challenging to accomplish. Therefore, we first propose a framework to align historical meteorological data with past weather and climate events using the large language model (LLM). In this framework, we construct a knowledge graph by using LLM to extract information about weather and climate events from a corpus of over 41k highly environment-focused news articles. Subsequently, we mapped these events with meteorological raster data, creating a supervised dataset, which is the largest and most novel for LLM tuning on the WCEF task. Finally, we introduced our aligned models, CLLMate (LLM for climate), a multimodal LLM to forecast weather and climate events using meteorological raster data. In evaluating CLLMate, we conducted extensive experiments. The results indicate that CLLMate surpasses both the baselines and other multimodal LLMs, showcasing the potential of utilizing LLM to align weather and climate events with meteorological data and highlighting the promising future for research on the WCEF task.

[Arxiv](https://arxiv.org/abs/2409.19058)