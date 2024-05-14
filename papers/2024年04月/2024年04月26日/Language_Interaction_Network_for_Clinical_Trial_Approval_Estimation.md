# 临床试验批准预测的语言互动网络在这项研究中，我们提出了一种新颖的语言交互网络，旨在预测临床试验的批准情况。该网络通过分析临床试验申请中的语言交互模式，来评估其获得批准的可能性。我们的方法结合了自然语言处理和机器学习技术，以识别和量化申请文本中的关键因素，这些因素可能影响监管机构的决策过程。通过这种方式，我们希望能够为研究人员和临床试验申请者提供一个有价值的工具，帮助他们更好地理解和准备他们的申请材料，从而提高获得批准的机会。

发布时间：2024年04月26日

`LLM应用

这篇论文探讨了临床试验结果预测的问题，特别是针对生物制剂这一复杂治疗剂类别。它提出了一种名为语言交互网络（LINT）的新颖预测方法，该方法仅基于试验文本描述，并在生物干预试验中展示了良好的预测性能。虽然论文中没有直接提到大型语言模型（LLM），但考虑到LINT方法依赖于文本描述，并且其性能评估使用了ROC-AUC分数，这表明它可能涉及某种形式的语言模型或文本分析技术。因此，将这篇论文归类为“LLM应用”是合适的，因为它展示了语言模型在特定应用领域（即临床试验结果预测）的实际应用和效果。` `临床试验` `生物制剂`

> Language Interaction Network for Clinical Trial Approval Estimation

# 摘要

> 临床试验结果预测旨在评估试验成功达成目标的可能性，这通常依赖于机器学习模型，它们分析临床试验描述、药物分子特征和疾病条件等多种数据。准确预测对优化试验设计和投资决策至关重要。尽管以往研究多聚焦于小分子药物，但生物制剂——这一迅速增长的背景下治疗剂类别，因其缺乏传统药物的明确分子特性而日益受到关注。生物制剂的复杂性使得传统方法如图形神经网络的应用变得困难。为此，我们提出了语言交互网络（LINT），一种仅基于试验文本描述的新颖预测方法。经过三阶段临床试验的严格测试，LINT在生物干预试验中分别取得了0.770、0.740和0.748的ROC-AUC分数，展现了其在临床试验预测中的有效性。

> Clinical trial outcome prediction seeks to estimate the likelihood that a clinical trial will successfully reach its intended endpoint. This process predominantly involves the development of machine learning models that utilize a variety of data sources such as descriptions of the clinical trials, characteristics of the drug molecules, and specific disease conditions being targeted. Accurate predictions of trial outcomes are crucial for optimizing trial planning and prioritizing investments in a drug portfolio. While previous research has largely concentrated on small-molecule drugs, there is a growing need to focus on biologics-a rapidly expanding category of therapeutic agents that often lack the well-defined molecular properties associated with traditional drugs. Additionally, applying conventional methods like graph neural networks to biologics data proves challenging due to their complex nature. To address these challenges, we introduce the Language Interaction Network (LINT), a novel approach that predicts trial outcomes using only the free-text descriptions of the trials. We have rigorously tested the effectiveness of LINT across three phases of clinical trials, where it achieved ROC-AUC scores of 0.770, 0.740, and 0.748 for phases I, II, and III, respectively, specifically concerning trials involving biologic interventions.

[Arxiv](https://arxiv.org/abs/2405.06662)