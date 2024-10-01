# 大语言模型上，影响函数还管用吗？

发布时间：2024年09月30日

`LLM理论` `机器学习`

> Do Influence Functions Work on Large Language Models?

# 摘要

> 影响力函数旨在量化单个训练数据点对模型预测的影响。尽管在传统机器学习模型中已有广泛研究，但在大语言模型 (LLM) 中的应用仍有限。我们进行了一项系统研究，探讨影响力函数在 LLM 中的有效性。结果显示，在多个任务中，影响力函数表现不佳。原因包括：LLM 规模导致的近似误差、微调中的收敛不确定性，以及模型参数变化与 LLM 行为变化的不相关性。因此，我们建议寻找替代方法来识别有影响力的样本。为支持未来研究，我们的代码已在 https://github.com/plumprc/Failures-of-Influence-Functions-in-LLMs 上公开。

> Influence functions aim to quantify the impact of individual training data points on a model's predictions. While extensive research has been conducted on influence functions in traditional machine learning models, their application to large language models (LLMs) has been limited. In this work, we conduct a systematic study to address a key question: do influence functions work on LLMs? Specifically, we evaluate influence functions across multiple tasks and find that they consistently perform poorly in most settings. Our further investigation reveals that their poor performance can be attributed to: (1) inevitable approximation errors when estimating the iHVP component due to the scale of LLMs, (2) uncertain convergence during fine-tuning, and, more fundamentally, (3) the definition itself, as changes in model parameters do not necessarily correlate with changes in LLM behavior. Our study thus suggests the need for alternative approaches for identifying influential samples. To support future work, our code is made available at https://github.com/plumprc/Failures-of-Influence-Functions-in-LLMs.

[Arxiv](https://arxiv.org/abs/2409.19998)