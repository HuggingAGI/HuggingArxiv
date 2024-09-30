# 利用大型语言模型预测公众舆论事件热度的研究

发布时间：2024年09月27日

`LLM应用` `舆论分析` `人工智能`

> Research on Predicting Public Opinion Event Heat Levels Based on Large Language Models

# 摘要

> 近年来，大型语言模型如 GPT-4o 等在语言任务中表现出色，超越了人类水平。这激发了研究人员在舆论分析领域的探索。本研究提出了一种基于大型语言模型的舆论事件热度预测方法。首先，我们对 2022 年 7 月至 2023 年 12 月间收集的 62,836 条中文热点事件进行了预处理和分类。接着，根据在线传播热度指数，使用 MiniBatchKMeans 算法将事件自动聚类为四个热度等级。随后，我们从每个等级中随机选取 250 个事件，共 1,000 个事件，构建评估数据集。在评估中，我们测试了不同大型语言模型在有无参考案例情况下的预测准确性。结果显示，GPT-4o 和 DeepseekV2 在有参考案例时表现最佳，分别达到 41.4% 和 41.5% 的准确率。尽管总体准确率较低，但低热度事件的预测准确率较高，分别为 73.6% 和 70.4%。此外，预测准确率随热度等级升高而下降，这与实际数据分布不均有关。这表明，随着数据集的增强，大型语言模型在舆论事件热度预测方面具有巨大的研究潜力。

> In recent years, with the rapid development of large language models, serval models such as GPT-4o have demonstrated extraordinary capabilities, surpassing human performance in various language tasks. As a result, many researchers have begun exploring their potential applications in the field of public opinion analysis. This study proposes a novel large-language-models-based method for public opinion event heat level prediction. First, we preprocessed and classified 62,836 Chinese hot event data collected between July 2022 and December 2023. Then, based on each event's online dissemination heat index, we used the MiniBatchKMeans algorithm to automatically cluster the events and categorize them into four heat levels (ranging from low heat to very high heat). Next, we randomly selected 250 events from each heat level, totalling 1,000 events, to build the evaluation dataset. During the evaluation process, we employed various large language models to assess their accuracy in predicting event heat levels in two scenarios: without reference cases and with similar case references. The results showed that GPT-4o and DeepseekV2 performed the best in the latter case, achieving prediction accuracies of 41.4% and 41.5%, respectively. Although the overall prediction accuracy remains relatively low, it is worth noting that for low-heat (Level 1) events, the prediction accuracies of these two models reached 73.6% and 70.4%, respectively. Additionally, the prediction accuracy showed a downward trend from Level 1 to Level 4, which correlates with the uneven distribution of data across the heat levels in the actual dataset. This suggests that with the more robust dataset, public opinion event heat level prediction based on large language models will have significant research potential for the future.

[Arxiv](https://arxiv.org/abs/2409.18548)