# [ROME 研究深入探索大型语言模型中，通过分析文本、概率分布以及隐藏状态揭示其内在的记忆机制。](https://arxiv.org/abs/2403.00510)

发布时间：2024年03月01日

`LLM理论`

> ROME: Memorization Insights from Text, Probability and Hidden State in Large Language Models

> 对大型语言模型的记忆特性进行深入研究至关重要。以往研究通过设立衡量标准、分析数据重复、模型规模、提示长度等影响因素，并对比模型输出与训练数据集以评测记忆能力。但面对海量训练数据及其耗时的预处理过程，我们创新性地提出了 ROME 方法，在无需直接访问训练数据的前提下探索记忆现象。此方法的核心是通过对比记忆与非记忆样本间的差异揭示模型记忆行为。具体实施时，模型先将样本划分为记忆与非记忆两类，再从文本内容、概率分布以及隐藏状态等多个维度比较两组样本的特点。实验结果显示，在词长、词性、词频、平均值及方差等方面，两类样本间存在着显著差异。

> Probing the memorization of large language models holds significant importance. Previous works have established metrics for quantifying memorization, explored various influencing factors, such as data duplication, model size, and prompt length, and evaluated memorization by comparing model outputs with training corpora. However, the training corpora are of enormous scale and its pre-processing is time-consuming. To explore memorization without accessing training data, we propose a novel approach, named ROME, wherein memorization is explored by comparing disparities across memorized and non-memorized. Specifically, models firstly categorize the selected samples into memorized and non-memorized groups, and then comparing the demonstrations in the two groups from the insights of text, probability, and hidden state. Experimental findings show the disparities in factors including word length, part-of-speech, word frequency, mean and variance, just to name a few.