# 生成式大型语言模型与病友在解读普通患者实验室检测结果时答案质量的比较：一项评估研究

发布时间：2024年01月23日

`LLM应用` `人工智能`

> Quality of Answers of Generative Large Language Models vs Peer Patients for Interpreting Lab Test Results for Lay Patients: Evaluation Study

# 摘要

> 实验室报告常常令人费解，但大型语言模型（LLMs）如 ChatGPT 为患者提供了一个获取答案的新途径。本研究旨在探讨利用 LLMs 为患者提出的实验室检测相关问题生成精准、有用且安全回答的可行性，并指出可通过增强策略减轻的潜在问题。我们从 Yahoo! Answers 搜集了实验室检测相关问题和答案，精选出 53 对问答对进行分析。利用 LangChain 框架及 ChatGPT 网络接口，我们从 GPT-4、Meta LLaMA 2、MedAlpaca 和 ORCA_mini 四款 LLMs 中为这 53 个问题生成了回答。我们首先采用标准的 QA 相似度评估指标，如 ROUGE、BLEU、METEOR、BERTScore，来评估答案之间的相似度。同时，我们还运用基于 LLM 的评估工具，判断目标模型在相关性、准确性、有用性和安全性方面是否优于基线模型。最终，我们邀请医学专家对七个选定问题的答复进行了人工评审，同样从四个维度进行评估。结果显示，无论是在胜率还是医学专家的评审中，GPT-4 的答复在相关性、准确性、有用性和安全性四个方面均优于其他 LLMs 和人类答复。尽管如此，LLMs 的答复有时仍缺乏对医疗背景的解释，存在错误陈述和缺少参考文献。与其他三款 LLMs 和人类回答相比，GPT-4 的答复更为精确、有益、贴切且安全。然而，GPT-4 的答复也存在不准确和缺乏个性化的情况。我们提出了多种提升 LLMs 答复质量的方法。

> Lab results are often confusing and hard to understand. Large language models (LLMs) such as ChatGPT have opened a promising avenue for patients to get their questions answered. We aim to assess the feasibility of using LLMs to generate relevant, accurate, helpful, and unharmful responses to lab test-related questions asked by patients and to identify potential issues that can be mitigated with augmentation approaches. We first collected lab test results related question and answer data from Yahoo! Answers and selected 53 QA pairs for this study. Using the LangChain framework and ChatGPT web portal, we generated responses to the 53 questions from four LLMs including GPT-4, Meta LLaMA 2, MedAlpaca, and ORCA_mini. We first assessed the similarity of their answers using standard QA similarity-based evaluation metrics including ROUGE, BLEU, METEOR, BERTScore. We also utilized an LLM-based evaluator to judge whether a target model has higher quality in terms of relevance, correctness, helpfulness, and safety than the baseline model. Finally, we performed a manual evaluation with medical experts for all the responses to seven selected questions on the same four aspects. The results of Win Rate and medical expert evaluation both showed that GPT-4's responses achieved better scores than all the other LLM responses and human responses on all four aspects (relevance, correctness, helpfulness, and safety). However, LLM responses occasionally also suffer from a lack of interpretation in one's medical context, incorrect statements, and lack of references. We find that compared to other three LLMs and human answer from the Q&A website, GPT-4's responses are more accurate, helpful, relevant, and safer. However, there are cases which GPT-4 responses are inaccurate and not individualized. We identified a number of ways to improve the quality of LLM responses.

[Arxiv](https://arxiv.org/abs/2402.01693)