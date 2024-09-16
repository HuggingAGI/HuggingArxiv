# Eir：泰国医学领域的大型语言模型

发布时间：2024年09月13日

`LLM应用` `人工智能`

> Eir: Thai Medical Large Language Models

# 摘要

> 我们推出了 Eir Thai Medical LLM，一个拥有 80 亿参数的大型语言模型，专为提升泰语医疗任务的准确性而设计。该模型致力于为医疗专业人员和患者提供清晰易懂的答案，从而优化诊断和治疗流程。为确保模型符合护理标准并提供公正答案，我们进行了人类评估。为保障数据安全，模型部署在医院内部网络，确保高安全性和快速处理。内部 API 连接通过加密和严格认证措施保护，防止数据泄露和未授权访问。我们在 MedQA、MedMCQA、PubMedQA 和 MMLU 医疗子集四个基准上评估了多个 80 亿参数的开源大型语言模型，并基于最佳基线开发了 Eir Thai Medical LLM。我们采用了零-shot、少-shot、链式思维推理和集成/自一致性投票等多种提问策略进行评估。结果显示，我们的模型比商业泰语大型语言模型表现高出 10% 以上。此外，我们还针对泰语临床使用开发了增强模型测试，涵盖 18 个临床任务，模型表现超过 GPT-4o 11% 以上。

> We present Eir Thai Medical LLM, a large language model with 8 billion parameters, specifically designed to enhance the accuracy of handling medical tasks in the Thai language. This model focuses on providing clear and easy-to-understand answers for both healthcare professionals and patients, thereby improving the efficiency of diagnosis and treatment processes. Human evaluation was conducted to ensure that the model adheres to care standards and provides unbiased answers.
  To prioritize data security, the model is deployed within the hospital's internal network, ensuring both high security and faster processing speeds. The internal API connection is secured with encryption and strict authentication measures to prevent data leaks and unauthorized access.
  We evaluated several open-source large language models with 8 billion parameters on four medical benchmarks: MedQA, MedMCQA, PubMedQA, and the medical subset of MMLU. The best-performing baselines were used to develop Eir Thai Medical LLM. Our evaluation employed multiple questioning strategies, including zero-shot, few-shot, chain-of-thought reasoning, and ensemble/self-consistency voting methods. Our model outperformed commercially available Thai-language large language models by more than 10%. In addition, we developed enhanced model testing tailored for clinical use in Thai across 18 clinical tasks, where our model exceeded GPT-4o performance by more than 11%

[Arxiv](https://arxiv.org/abs/2409.08523)