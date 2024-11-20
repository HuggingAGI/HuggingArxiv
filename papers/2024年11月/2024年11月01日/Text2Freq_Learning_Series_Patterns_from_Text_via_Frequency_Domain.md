# Text2Freq: 借由频域从文本中学习序列模式

发布时间：2024年11月01日

`其他` `时间序列预测`

> Text2Freq: Learning Series Patterns from Text via Frequency Domain

# 摘要

> 传统的时间序列预测模型主要依赖历史数值来预测未来结果。尽管这些模型成果斐然，但它们常常忽视其他模式中丰富的可用信息，比如特殊事件的文本描述，这些能为未来的动态提供关键洞见。然而，相较于其他跨模态工作，在时间序列预测中共同融入文本的研究还相对较少。另外，时间序列数据与文本信息之间的模态差异给多模态学习带来了挑战。为应对此任务，我们提出了 Text2Freq，这是一个通过频域整合文本和时间序列数据的跨模态模型。具体而言，我们的方法将文本信息与时间序列数据的低频成分对齐，在这两种模态之间建立起更有效且可解释的对应关系。我们在真实世界股票价格和合成文本的配对数据集上所做的实验表明，Text2Freq 达到了最先进的性能，其适应性架构为该领域的未来研究注入了动力。

> Traditional time series forecasting models mainly rely on historical numeric values to predict future outcomes.While these models have shown promising results, they often overlook the rich information available in other modalities, such as textual descriptions of special events, which can provide crucial insights into future dynamics.However, research that jointly incorporates text in time series forecasting remains relatively underexplored compared to other cross-modality work. Additionally, the modality gap between time series data and textual information poses a challenge for multimodal learning. To address this task, we propose Text2Freq, a cross-modality model that integrates text and time series data via the frequency domain. Specifically, our approach aligns textual information to the low-frequency components of time series data, establishing more effective and interpretable alignments between these two modalities. Our experiments on paired datasets of real-world stock prices and synthetic texts show that Text2Freq achieves state-of-the-art performance, with its adaptable architecture encouraging future research in this field.

[Arxiv](https://arxiv.org/abs/2411.00929)