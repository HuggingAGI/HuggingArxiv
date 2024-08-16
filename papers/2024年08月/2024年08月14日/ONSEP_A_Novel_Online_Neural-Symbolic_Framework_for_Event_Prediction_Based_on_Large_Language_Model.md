# ONSEP：一款基于大型语言模型的新颖在线神经-符号框架，专为事件预测设计

发布时间：2024年08月14日

`LLM应用` `事件预测` `知识图谱`

> ONSEP: A Novel Online Neural-Symbolic Framework for Event Prediction Based on Large Language Model

# 摘要

> 在事件预测领域，时间知识图谱预测（TKGF）技术至关重要。传统方法因测试时不利用经验且依赖单一短期历史而受限。本文提出的在线神经符号事件预测（ONSEP）框架，通过融合动态因果规则挖掘（DCRM）和双历史增强生成（DHAG），实现了创新。DCRM动态提取实时数据中的因果规则，快速适应新关系；DHAG则融合长短历史，采用双分支策略提升预测质量。该框架在多数据集上显著提升性能，Hit@k（k=1,3,10）大幅改进，强化了LLM的事件预测能力，无需大规模再训练。ONSEP不仅推动了TKGF技术进步，也展示了神经符号方法在动态数据环境中的适应潜力。

> In the realm of event prediction, temporal knowledge graph forecasting (TKGF) stands as a pivotal technique. Previous approaches face the challenges of not utilizing experience during testing and relying on a single short-term history, which limits adaptation to evolving data. In this paper, we introduce the Online Neural-Symbolic Event Prediction (ONSEP) framework, which innovates by integrating dynamic causal rule mining (DCRM) and dual history augmented generation (DHAG). DCRM dynamically constructs causal rules from real-time data, allowing for swift adaptation to new causal relationships. In parallel, DHAG merges short-term and long-term historical contexts, leveraging a bi-branch approach to enrich event prediction. Our framework demonstrates notable performance enhancements across diverse datasets, with significant Hit@k (k=1,3,10) improvements, showcasing its ability to augment large language models (LLMs) for event prediction without necessitating extensive retraining. The ONSEP framework not only advances the field of TKGF but also underscores the potential of neural-symbolic approaches in adapting to dynamic data environments.

[Arxiv](https://arxiv.org/abs/2408.07840)