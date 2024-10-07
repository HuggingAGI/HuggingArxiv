# 自然语言处理中的不确定性探究

发布时间：2024年10月04日

`LLM理论` `人工智能`

> On Uncertainty In Natural Language Processing

# 摘要

> 过去十年，深度学习催生了众多强大系统，广泛应用于各行各业。在自然语言处理领域，大型语言模型的突破性进展，使其在用户应用中日益普及。为充分发挥其优势并规避潜在风险，量化模型预测的可靠性及开发中的不确定性至关重要。本论文从语言学、统计学和神经学视角，探讨了自然语言处理中不确定性的特征，并研究了通过实验设计减少和量化不确定性的方法。我们还通过理论与实证分析，探究了归纳偏差对文本分类任务的影响，进一步深化了对建模中不确定性量化的理解。实验涵盖丹麦语、英语和芬兰语三种语言，并采用了多种不确定性量化方法。此外，我们提出了一种基于非可交换保形预测的校准采样方法，用于自然语言生成，能更精准地覆盖实际延续。最后，我们开发了一种利用辅助预测器量化大型黑箱语言模型置信度的方法，仅依赖目标模型的输入与输出文本进行预测。

> The last decade in deep learning has brought on increasingly capable systems that are deployed on a wide variety of applications. In natural language processing, the field has been transformed by a number of breakthroughs including large language models, which are used in increasingly many user-facing applications. In order to reap the benefits of this technology and reduce potential harms, it is important to quantify the reliability of model predictions and the uncertainties that shroud their development.
  This thesis studies how uncertainty in natural language processing can be characterized from a linguistic, statistical and neural perspective, and how it can be reduced and quantified through the design of the experimental pipeline. We further explore uncertainty quantification in modeling by theoretically and empirically investigating the effect of inductive model biases in text classification tasks. The corresponding experiments include data for three different languages (Danish, English and Finnish) and tasks as well as a large set of different uncertainty quantification approaches. Additionally, we propose a method for calibrated sampling in natural language generation based on non-exchangeable conformal prediction, which provides tighter token sets with better coverage of the actual continuation. Lastly, we develop an approach to quantify confidence in large black-box language models using auxiliary predictors, where the confidence is predicted from the input to and generated output text of the target model alone.

[Arxiv](https://arxiv.org/abs/2410.03446)