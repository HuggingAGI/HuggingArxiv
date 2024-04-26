# 全面分类与基准测试：探究大型语言模型对时间序列特征的理解。

发布时间：2024年04月25日

`LLM应用` `时间序列分析` `自动报告生成`

> Evaluating Large Language Models on Time Series Feature Understanding: A Comprehensive Taxonomy and Benchmark

# 摘要

> 大型语言模型（LLMs）在自动进行时间序列分析与报告方面展现出巨大潜力，这对于医疗、金融、气候、能源等多个领域至关重要。本文提出了一套严格评估LLMs时间序列理解能力的框架，覆盖了单变量和多变量的时间序列。我们引入了一个全面的时间序列特征分类体系，它清晰地界定了时间序列数据的多种内在特性。基于这一分类体系，我们设计并构建了一个包含丰富特征的时间序列数据集，为测试LLMs的时间序列理解能力提供了坚实基础。实验结果揭示了当前最先进LLMs在时间序列理解上的强项与不足，指出了这些模型能够高效理解的特征以及它们的不足之处。同时，我们还发现了LLMs对于数据格式、查询点位置以及时间序列总长度等因素的敏感度。

> Large Language Models (LLMs) offer the potential for automatic time series analysis and reporting, which is a critical task across many domains, spanning healthcare, finance, climate, energy, and many more. In this paper, we propose a framework for rigorously evaluating the capabilities of LLMs on time series understanding, encompassing both univariate and multivariate forms. We introduce a comprehensive taxonomy of time series features, a critical framework that delineates various characteristics inherent in time series data. Leveraging this taxonomy, we have systematically designed and synthesized a diverse dataset of time series, embodying the different outlined features. This dataset acts as a solid foundation for assessing the proficiency of LLMs in comprehending time series. Our experiments shed light on the strengths and limitations of state-of-the-art LLMs in time series understanding, revealing which features these models readily comprehend effectively and where they falter. In addition, we uncover the sensitivity of LLMs to factors including the formatting of the data, the position of points queried within a series and the overall time series length.

[Arxiv](https://arxiv.org/abs/2404.16563)