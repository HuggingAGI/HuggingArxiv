# 我的模型怎么了？通过语义数据切片识别系统性问题

发布时间：2024年09月13日

`LLM应用` `机器学习` `数据分析`

> What Is Wrong with My Model? Identifying Systematic Problems with Semantic Data Slicing

# 摘要

> 机器学习模型虽会出错，但找出背后的系统性问题却非易事。从业者通过错误分析、测试、审计和红队测试等手段，试图找出模型可能的缺陷。为验证这些假设，他们采用数据切片技术。然而，传统方法受限于现有特征和程序化切片功能。为此，我们推出了 SemSlicer 框架，支持语义数据切片，无需依赖现有特征即可识别语义一致的切片。SemSlicer 借助大型语言模型，根据用户定义的标准注释数据集并生成切片。实验表明，SemSlicer 不仅成本低廉、切片准确，还能灵活调整设计维度，有效识别表现不佳的切片，助力从业者发现反映系统性问题的关键数据。

> Machine learning models make mistakes, yet sometimes it is difficult to identify the systematic problems behind the mistakes. Practitioners engage in various activities, including error analysis, testing, auditing, and red-teaming, to form hypotheses of what can go (or has gone) wrong with their models. To validate these hypotheses, practitioners employ data slicing to identify relevant examples. However, traditional data slicing is limited by available features and programmatic slicing functions. In this work, we propose SemSlicer, a framework that supports semantic data slicing, which identifies a semantically coherent slice, without the need for existing features. SemSlicer uses Large Language Models to annotate datasets and generate slices from any user-defined slicing criteria. We show that SemSlicer generates accurate slices with low cost, allows flexible trade-offs between different design dimensions, reliably identifies under-performing data slices, and helps practitioners identify useful data slices that reflect systematic problems.

[Arxiv](https://arxiv.org/abs/2409.09261)