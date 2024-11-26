# 关于生成语言模型的人类校准式自动化测试与验证

发布时间：2024年11月25日

`RAG`

> Human-Calibrated Automated Testing and Validation of Generative Language Models

# 摘要

> 本文引入了一个针对生成式语言模型（GLMs）进行评估与验证的全面框架，重点聚焦于在诸如银行等高风险领域所部署的检索增强生成（RAG）系统。由于存在开放式输出和主观质量评估，GLM的评估颇具挑战。借助RAG系统生成响应基于预定义文档集合这一结构化特性，我们提出了人类校准的自动化测试（HCAT）框架。HCAT整合了：a）运用分层抽样的自动化测试生成；b）基于嵌入的指标，用于对功能、风险和安全属性进行可解释的评估；c）通过概率校准和保形预测使机器生成的评估与人类判断相契合的两阶段校准方法。
  另外，该框架涵盖了鲁棒性测试，用于评估模型在对抗性、分布外和各种输入条件下的表现，以及通过边际和双变量分析进行有针对性的弱点识别，以精准定位有待改进的特定区域。这种经人类校准的多层评估框架为GLM评估提供了可扩展、透明且可解释的途径，为在准确性、透明度和法规合规性至关重要的应用中部署GLM提供了实用且可靠的解决方案。

> This paper introduces a comprehensive framework for the evaluation and validation of generative language models (GLMs), with a focus on Retrieval-Augmented Generation (RAG) systems deployed in high-stakes domains such as banking. GLM evaluation is challenging due to open-ended outputs and subjective quality assessments. Leveraging the structured nature of RAG systems, where generated responses are grounded in a predefined document collection, we propose the Human-Calibrated Automated Testing (HCAT) framework. HCAT integrates a) automated test generation using stratified sampling, b) embedding-based metrics for explainable assessment of functionality, risk and safety attributes, and c) a two-stage calibration approach that aligns machine-generated evaluations with human judgments through probability calibration and conformal prediction.
  In addition, the framework includes robustness testing to evaluate model performance against adversarial, out-of-distribution, and varied input conditions, as well as targeted weakness identification using marginal and bivariate analysis to pinpoint specific areas for improvement. This human-calibrated, multi-layered evaluation framework offers a scalable, transparent, and interpretable approach to GLM assessment, providing a practical and reliable solution for deploying GLMs in applications where accuracy, transparency, and regulatory compliance are paramount.

[Arxiv](https://arxiv.org/abs/2411.16391)