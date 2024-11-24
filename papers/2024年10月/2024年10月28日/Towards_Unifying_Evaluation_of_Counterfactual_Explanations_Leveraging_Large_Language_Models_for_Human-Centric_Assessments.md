# 朝着反事实解释的统一评估迈进：借助大型语言模型开展以人为本的评估

发布时间：2024年10月28日

`LLM应用` `机器学习` `人工智能`

> Towards Unifying Evaluation of Counterfactual Explanations: Leveraging Large Language Models for Human-Centric Assessments

# 摘要

> 随着机器学习模型不断演进，要保持透明度，就需要更多以人为本的可解释人工智能技术。反事实解释源自人类的推理，能确定获得给定输出所需的最小输入变化，所以对支持决策极为关键。然而，这些解释的评估往往缺乏用户研究的依据，而且较为分散，现有的指标无法完全体现人类视角。为应对这一挑战，我们构建了一套多样的 30 个反事实场景，并从 206 位受访者处收集了 8 项评估指标的评分。接着，我们对不同的大型语言模型（LLM）进行微调，以预测这些指标下的平均或个人人类判断。我们的方法让 LLM 在零样本评估中的准确率高达 63%，在对所有指标进行微调后（超过 3 类预测）达到 85%。预测人类评分的微调模型在评估不同反事实解释框架时，具备更出色的可比性和可扩展性。

> As machine learning models evolve, maintaining transparency demands more human-centric explainable AI techniques. Counterfactual explanations, with roots in human reasoning, identify the minimal input changes needed to obtain a given output and, hence, are crucial for supporting decision-making. Despite their importance, the evaluation of these explanations often lacks grounding in user studies and remains fragmented, with existing metrics not fully capturing human perspectives. To address this challenge, we developed a diverse set of 30 counterfactual scenarios and collected ratings across 8 evaluation metrics from 206 respondents. Subsequently, we fine-tuned different Large Language Models (LLMs) to predict average or individual human judgment across these metrics. Our methodology allowed LLMs to achieve an accuracy of up to 63% in zero-shot evaluations and 85% (over a 3-classes prediction) with fine-tuning across all metrics. The fine-tuned models predicting human ratings offer better comparability and scalability in evaluating different counterfactual explanation frameworks.

[Arxiv](https://arxiv.org/abs/2410.21131)