# 借助大型语言模型，提升实时疫情预测的准确性：以COVID-19为例的深入分析

发布时间：2024年04月10日

`LLM应用` `公共卫生` `疾病预测`

> Advancing Real-time Pandemic Forecasting Using Large Language Models: A COVID-19 Case Study

# 摘要

> 预测疾病爆发的短期传播一直是个大难题，因为涉及的因素错综复杂。这些因素包括流行病学数据、病毒特性、人口统计和公共政策等，它们通过多模态变量相互关联。传统预测模型在处理这些复杂数据和转化为可靠结果方面表现不佳，这影响了它们为公共卫生决策者提供有效信息的能力。我们提出了PandemicLLM，一个创新的多模态大型语言模型框架，将疾病传播的实时预测转化为文本推理问题，能够整合传统模型难以处理的实时、复杂和非数值信息。通过独特的AI-人类协作提示设计和时间序列表示学习，PandemicLLM能够编码多模态数据。在COVID-19大流行中应用该模型，训练其利用公共卫生政策文本、基因组监控和流行病学时间序列数据，覆盖美国所有州的测试显示，PandemicLLM是一个高效的预测工具，能够及时捕捉病毒变种的影响并提供准确预测。这项研究展示了如何利用LLMs和表示学习来提升大流行预测，证明了人工智能创新在未来加强公共卫生危机管理中的潜力。

> Forecasting the short-term spread of an ongoing disease outbreak is a formidable challenge due to the complexity of contributing factors, some of which can be characterized through interlinked, multi-modality variables such as epidemiological time series data, viral biology, population demographics, and the intersection of public policy and human behavior. Existing forecasting model frameworks struggle with the multifaceted nature of relevant data and robust results translation, which hinders their performances and the provision of actionable insights for public health decision-makers. Our work introduces PandemicLLM, a novel framework with multi-modal Large Language Models (LLMs) that reformulates real-time forecasting of disease spread as a text reasoning problem, with the ability to incorporate real-time, complex, non-numerical information that previously unattainable in traditional forecasting models. This approach, through a unique AI-human cooperative prompt design and time series representation learning, encodes multi-modal data for LLMs. The model is applied to the COVID-19 pandemic, and trained to utilize textual public health policies, genomic surveillance, spatial, and epidemiological time series data, and is subsequently tested across all 50 states of the U.S. Empirically, PandemicLLM is shown to be a high-performing pandemic forecasting framework that effectively captures the impact of emerging variants and can provide timely and accurate predictions. The proposed PandemicLLM opens avenues for incorporating various pandemic-related data in heterogeneous formats and exhibits performance benefits over existing models. This study illuminates the potential of adapting LLMs and representation learning to enhance pandemic forecasting, illustrating how AI innovations can strengthen pandemic responses and crisis management in the future.

![借助大型语言模型，提升实时疫情预测的准确性：以COVID-19为例的深入分析](../../../paper_images/2404.06962/x1.png)

![借助大型语言模型，提升实时疫情预测的准确性：以COVID-19为例的深入分析](../../../paper_images/2404.06962/x2.png)

![借助大型语言模型，提升实时疫情预测的准确性：以COVID-19为例的深入分析](../../../paper_images/2404.06962/pandemicllm_predictions.png)

![借助大型语言模型，提升实时疫情预测的准确性：以COVID-19为例的深入分析](../../../paper_images/2404.06962/PandemicLLM_7b_1_week_WMSE.png)

![借助大型语言模型，提升实时疫情预测的准确性：以COVID-19为例的深入分析](../../../paper_images/2404.06962/PandemicLLM_7b_3_week_WMSE.png)

![借助大型语言模型，提升实时疫情预测的准确性：以COVID-19为例的深入分析](../../../paper_images/2404.06962/PandemicLLM_13b_1_week_WMSE.png)

![借助大型语言模型，提升实时疫情预测的准确性：以COVID-19为例的深入分析](../../../paper_images/2404.06962/PandemicLLM_13b_3_week_WMSE.png)

![借助大型语言模型，提升实时疫情预测的准确性：以COVID-19为例的深入分析](../../../paper_images/2404.06962/WMSE_1-Week_no_variant.png)

![借助大型语言模型，提升实时疫情预测的准确性：以COVID-19为例的深入分析](../../../paper_images/2404.06962/WMSE_3-Week_no_variant.png)

![借助大型语言模型，提升实时疫情预测的准确性：以COVID-19为例的深入分析](../../../paper_images/2404.06962/1-week.png)

![借助大型语言模型，提升实时疫情预测的准确性：以COVID-19为例的深入分析](../../../paper_images/2404.06962/3-week.png)

![借助大型语言模型，提升实时疫情预测的准确性：以COVID-19为例的深入分析](../../../paper_images/2404.06962/cm_7b_1-week.png)

![借助大型语言模型，提升实时疫情预测的准确性：以COVID-19为例的深入分析](../../../paper_images/2404.06962/cm_7b_3-week.png)

![借助大型语言模型，提升实时疫情预测的准确性：以COVID-19为例的深入分析](../../../paper_images/2404.06962/cm_13b_1-week.png)

![借助大型语言模型，提升实时疫情预测的准确性：以COVID-19为例的深入分析](../../../paper_images/2404.06962/cm_13b_3-week.png)

![借助大型语言模型，提升实时疫情预测的准确性：以COVID-19为例的深入分析](../../../paper_images/2404.06962/x3.png)

![借助大型语言模型，提升实时疫情预测的准确性：以COVID-19为例的深入分析](../../../paper_images/2404.06962/wmse_3w_variant.png)

![借助大型语言模型，提升实时疫情预测的准确性：以COVID-19为例的深入分析](../../../paper_images/2404.06962/confidence_vairant_3w.png)

![借助大型语言模型，提升实时疫情预测的准确性：以COVID-19为例的深入分析](../../../paper_images/2404.06962/x4.png)

![借助大型语言模型，提升实时疫情预测的准确性：以COVID-19为例的深入分析](../../../paper_images/2404.06962/x5.png)

![借助大型语言模型，提升实时疫情预测的准确性：以COVID-19为例的深入分析](../../../paper_images/2404.06962/ts_map_testing_set.png)

![借助大型语言模型，提升实时疫情预测的准确性：以COVID-19为例的深入分析](../../../paper_images/2404.06962/x6.png)

![借助大型语言模型，提升实时疫情预测的准确性：以COVID-19为例的深入分析](../../../paper_images/2404.06962/x7.png)

[Arxiv](https://arxiv.org/abs/2404.06962)