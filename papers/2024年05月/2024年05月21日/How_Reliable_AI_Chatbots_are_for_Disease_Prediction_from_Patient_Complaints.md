# 人工智能聊天机器人在从患者投诉中预测疾病方面的可靠性如何？

发布时间：2024年05月21日

`LLM应用

这篇论文主要探讨了大型语言模型（LLMs）在医疗领域的应用，特别是在急诊中使用AI聊天机器人进行疾病预测的能力。研究聚焦于GPT 4.0、Claude 3 Opus和Gemini Ultra 1.0等模型，并通过实验评估了它们在疾病预测方面的性能。虽然研究结果显示这些模型在特定条件下表现出色，但强调了它们在关键医疗决策中的局限性，并提出了需要进一步的研究和改进。因此，这篇论文属于LLM应用类别，因为它关注的是LLMs在实际医疗场景中的应用和效果评估。`

> How Reliable AI Chatbots are for Disease Prediction from Patient Complaints?

# 摘要

> AI聊天机器人借助LLMs在医疗领域崭露头角，旨在自动化患者互动并辅助临床决策。本研究聚焦于GPT 4.0、Claude 3 Opus和Gemini Ultra 1.0，探讨它们在急诊中根据患者投诉预测疾病的可靠性。通过少量样本学习技术，我们评估了这些聊天机器人的疾病预测能力，并与微调后的BERT模型进行了比较。结果表明，GPT 4.0在数据增多时准确率高，Gemini Ultra 1.0在样本较少时表现出色，Claude 3 Opus则保持稳定。相比之下，BERT的表现不及这些聊天机器人，显示出因数据有限而受限。尽管聊天机器人的准确性各有千秋，但它们均不足以支撑关键医疗决策，凸显了严格验证和人类监督的必要性。研究强调，AI聊天机器人虽有潜力，但应作为人类专家的补充，而非替代，以确保患者安全。未来需进一步研究与改进，以提升AI在医疗应用中疾病预测的可靠性。

> Artificial Intelligence (AI) chatbots leveraging Large Language Models (LLMs) are gaining traction in healthcare for their potential to automate patient interactions and aid clinical decision-making. This study examines the reliability of AI chatbots, specifically GPT 4.0, Claude 3 Opus, and Gemini Ultra 1.0, in predicting diseases from patient complaints in the emergency department. The methodology includes few-shot learning techniques to evaluate the chatbots' effectiveness in disease prediction. We also fine-tune the transformer-based model BERT and compare its performance with the AI chatbots. Results suggest that GPT 4.0 achieves high accuracy with increased few-shot data, while Gemini Ultra 1.0 performs well with fewer examples, and Claude 3 Opus maintains consistent performance. BERT's performance, however, is lower than all the chatbots, indicating limitations due to limited labeled data. Despite the chatbots' varying accuracy, none of them are sufficiently reliable for critical medical decision-making, underscoring the need for rigorous validation and human oversight. This study reflects that while AI chatbots have potential in healthcare, they should complement, not replace, human expertise to ensure patient safety. Further refinement and research are needed to improve AI-based healthcare applications' reliability for disease prediction.

[Arxiv](https://arxiv.org/abs/2405.13219)