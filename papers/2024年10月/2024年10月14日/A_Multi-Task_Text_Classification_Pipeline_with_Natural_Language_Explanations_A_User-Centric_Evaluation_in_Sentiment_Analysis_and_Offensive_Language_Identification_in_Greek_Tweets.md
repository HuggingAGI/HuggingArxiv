# 多任务文本分类管道，结合自然语言解释，专注于希腊推文中的情感分析与冒犯性语言识别，以用户为中心进行评估。

发布时间：2024年10月14日

`LLM应用` `社交媒体`

> A Multi-Task Text Classification Pipeline with Natural Language Explanations: A User-Centric Evaluation in Sentiment Analysis and Offensive Language Identification in Greek Tweets

# 摘要

> 可解释性近年来备受瞩目。现有技术多以规则或特征重要性形式呈现解释，虽信息丰富，但非专业用户理解难度较大。因此，自然语言解释因其易懂性和展示性而更受青睐。本研究提出了一种用于文本分类的新型管道，能提供自然语言的预测与解释。该管道包含文本分类器和解释生成器两部分。只要提供真实理由，任何文本分类任务均可采用此管道。我们以希腊推文中的情感分析和冒犯性语言识别为实验重点，利用希腊大型语言模型获取解释。通过基于三种指标的用户研究，实验在两个数据集上均取得良好效果。

> Interpretability is a topic that has been in the spotlight for the past few years. Most existing interpretability techniques produce interpretations in the form of rules or feature importance. These interpretations, while informative, may be harder to understand for non-expert users and therefore, cannot always be considered as adequate explanations. To that end, explanations in natural language are often preferred, as they are easier to comprehend and also more presentable to end-users. This work introduces an early concept for a novel pipeline that can be used in text classification tasks, offering predictions and explanations in natural language. It comprises of two models: a classifier for labelling the text and an explanation generator which provides the explanation. The proposed pipeline can be adopted by any text classification task, given that ground truth rationales are available to train the explanation generator. Our experiments are centred around the tasks of sentiment analysis and offensive language identification in Greek tweets, using a Greek Large Language Model (LLM) to obtain the necessary explanations that can act as rationales. The experimental evaluation was performed through a user study based on three different metrics and achieved promising results for both datasets.

[Arxiv](https://arxiv.org/abs/2410.10290)