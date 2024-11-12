# 将人类的解释纳入以进行稳健的仇恨言论检测

发布时间：2024年11月09日

`LLM应用` `语言模型` `仇恨言论检测`

> Incorporating Human Explanations for Robust Hate Speech Detection

# 摘要

> 鉴于大型 Transformer 语言模型（LM）的黑箱性质和复杂性，对通用性和鲁棒性的担忧对诸如仇恨言论（HS）检测等领域产生了伦理影响。使用内容丰富的社会偏见框架数据集，其中包含人工注释的刻板印象、意图和目标群体，我们开发了一个三阶段分析来评估 LMs 是否忠实地评估仇恨言论。首先，我们观察到需要对基于上下文的刻板印象意图进行建模，以捕捉隐含的语义。接下来，我们设计了一个新任务，刻板印象意图蕴含（SIE），它鼓励模型在上下文中理解刻板印象的存在。最后，通过消融测试和用户研究，我们发现 SIE 目标提高了内容理解，但在对隐含意图建模方面仍然存在挑战。

> Given the black-box nature and complexity of large transformer language models (LM), concerns about generalizability and robustness present ethical implications for domains such as hate speech (HS) detection. Using the content rich Social Bias Frames dataset, containing human-annotated stereotypes, intent, and targeted groups, we develop a three stage analysis to evaluate if LMs faithfully assess hate speech. First, we observe the need for modeling contextually grounded stereotype intents to capture implicit semantic meaning. Next, we design a new task, Stereotype Intent Entailment (SIE), which encourages a model to contextually understand stereotype presence. Finally, through ablation tests and user studies, we find a SIE objective improves content understanding, but challenges remain in modeling implicit intent.

[Arxiv](https://arxiv.org/abs/2411.06213)