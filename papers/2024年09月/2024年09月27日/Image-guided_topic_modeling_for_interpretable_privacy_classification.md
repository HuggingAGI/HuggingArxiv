# 图像引导的主题建模助力隐私分类的可解释性

发布时间：2024年09月27日

`LLM应用` `隐私保护` `图像处理`

> Image-guided topic modeling for interpretable privacy classification

# 摘要

> 预测图像中的私人信息并解释其含义，是一项复杂且依赖上下文的任务，即使对大型语言模型也颇具挑战。为帮助理解隐私决策，我们提出基于自然语言内容描述符来预测图像隐私。这些描述符与反映人们感知图像内容的隐私评分相关联。我们采用创新的图像引导主题建模（ITM）方法生成描述符，该方法通过多模态对齐，融合视觉语言模型中的视觉与文本信息。利用ITM生成的描述符，我们训练了一个可解释的隐私预测器Priv$\times$ITM。实验表明，Priv$\times$ITM在准确性上超越了现有的可解释方法5个百分点，与当前最先进的非可解释模型表现相当。

> Predicting and explaining the private information contained in an image in human-understandable terms is a complex and contextual task. This task is challenging even for large language models. To facilitate the understanding of privacy decisions, we propose to predict image privacy based on a set of natural language content descriptors. These content descriptors are associated with privacy scores that reflect how people perceive image content. We generate descriptors with our novel Image-guided Topic Modeling (ITM) approach. ITM leverages, via multimodality alignment, both vision information and image textual descriptions from a vision language model. We use the ITM-generated descriptors to learn a privacy predictor, Priv$\times$ITM, whose decisions are interpretable by design. Our Priv$\times$ITM classifier outperforms the reference interpretable method by 5 percentage points in accuracy and performs comparably to the current non-interpretable state-of-the-art model.

[Arxiv](https://arxiv.org/abs/2409.18674)