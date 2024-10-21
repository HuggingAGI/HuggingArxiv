# ChartifyText：利用 LLM 技术，自动将包含数据的文本转化为图表。

发布时间：2024年10月18日

`LLM应用` `数据可视化`

> ChartifyText: Automated Chart Generation from Data-Involved Texts via LLM

# 摘要

> 在科学研究、经济、公共卫生和新闻等领域，涉及数值的文本文档应用广泛。然而，读者往往难以快速解读这些数据丰富的文本并获得深刻见解。为此，我们研发了ChartifyText，一种利用大型语言模型（如GPT-4）自动将复杂数据文本转化为直观图表的全自动方法。该方法包含两个核心模块：表格数据推理和表达性图表生成。前者通过系统提示工程，明确考虑数据范围、不确定性、缺失值及主观情感，指导LLM推断表格数据；后者则通过直观视觉编码和简洁文本，增强标准图表以准确传达数据和见解。通过案例研究、专家访谈和用户实验，我们验证了ChartifyText在帮助读者高效理解数据文本方面的实用性和有效性。

> Text documents with numerical values involved are widely used in various applications such as scientific research, economy, public health and journalism. However, it is difficult for readers to quickly interpret such data-involved texts and gain deep insights. To fill this research gap, this work aims to automatically generate charts to accurately convey the underlying data and ideas to readers, which is essentially a challenging task. The challenges originate from text ambiguities, intrinsic sparsity and uncertainty of data in text documents, and subjective sentiment differences. Specifically, we propose ChartifyText, a novel fully-automated approach that leverages Large Language Models (LLMs) to convert complex data-involved texts to expressive charts. It consists of two major modules: tabular data inference and expressive chart generation. The tabular data inference module employs systematic prompt engineering to guide the LLM (e.g., GPT-4) to infer table data, where data ranges, uncertainties, missing data values and corresponding subjective sentiments are explicitly considered. The expressive chart generation module augments standard charts with intuitive visual encodings and concise texts to accurately convey the underlying data and insights. We extensively evaluate the effectiveness of ChartifyText on real-world data-involved text documents through case studies, in-depth interviews with three visualization experts, and a carefully-designed user study with 15 participants. The results demonstrate the usefulness and effectiveness of ChartifyText in helping readers efficiently and effectively make sense of data-involved texts.

[Arxiv](https://arxiv.org/abs/2410.14331)