# 针对目标导向型客户服务聊天机器人的管道架构，进行机器学习模型的实验评估。

发布时间：2024年09月27日

`LLM应用` `客户服务` `人工智能`

> Experimental Evaluation of Machine Learning Models for Goal-oriented Customer Service Chatbot with Pipeline Architecture

# 摘要

> 将机器学习融入客户服务聊天机器人，能提升其理解与回应用户的能力，从而优化服务质量。然而，这种技术可能让某些用户感觉不自然，影响体验。因此，对每个组件的 ML 模型进行细致评估至关重要，尽管功能差异可能导致比较失衡。本文提出了一种针对目标导向聊天机器人的定制评估方法，聚焦于自然语言理解、对话管理和自然语言生成三大核心组件。我们强调个体评估，以找出最佳 ML 模型。具体而言，我们优化了超参数，并评估了 NLU（BERT 和 LSTM）、DM（DQN 和 DDQN）和 NLG（GPT-2 和 DialoGPT）的模型。结果表明，BERT 在意图检测上表现优异，而 LSTM 在槽填充上更胜一筹。DDQN 在减少回合、提高奖励和成功率方面优于 DQN。GPT-2 在 BLEU、METEOR 和 ROUGE 指标上超越了 DialoGPT。这些发现为未来聊天机器人的开发与优化提供了基准，揭示了模型性能与最佳超参数的关键信息。

> Integrating machine learning (ML) into customer service chatbots enhances their ability to understand and respond to user queries, ultimately improving service performance. However, they may appear artificial to some users and affecting customer experience. Hence, meticulous evaluation of ML models for each pipeline component is crucial for optimizing performance, though differences in functionalities can lead to unfair comparisons. In this paper, we present a tailored experimental evaluation approach for goal-oriented customer service chatbots with pipeline architecture, focusing on three key components: Natural Language Understanding (NLU), dialogue management (DM), and Natural Language Generation (NLG). Our methodology emphasizes individual assessment to determine optimal ML models. Specifically, we focus on optimizing hyperparameters and evaluating candidate models for NLU (utilizing BERT and LSTM), DM (employing DQN and DDQN), and NLG (leveraging GPT-2 and DialoGPT). The results show that for the NLU component, BERT excelled in intent detection whereas LSTM was superior for slot filling. For the DM component, the DDQN model outperformed DQN by achieving fewer turns, higher rewards, as well as greater success rates. For NLG, the large language model GPT-2 surpassed DialoGPT in BLEU, METEOR, and ROUGE metrics. These findings aim to provide a benchmark for future research in developing and optimizing customer service chatbots, offering valuable insights into model performance and optimal hyperparameters.

[Arxiv](https://arxiv.org/abs/2409.18568)