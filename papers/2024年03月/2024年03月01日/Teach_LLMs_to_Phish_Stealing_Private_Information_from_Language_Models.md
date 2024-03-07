# [让 LLM 学会“垂钓”隐私：探究如何从语言模型中获取敏感信息](https://arxiv.org/abs/2403.00871)

发布时间：2024年03月01日

`LLM安全`

> Teach LLMs to Phish: Stealing Private Information from Language Models

> 大型语言模型在处理私人数据训练时，存在潜在的隐私风险，可能记忆并泄露敏感信息。为此，我们创新性地提出了名为“神经网络钓鱼”的新型实际数据窃取攻击手法。该攻击能针对性地从基于用户数据训练的模型中抽取诸如信用卡号等敏感或个人身份信息，成功率达到10%乃至50%。这一攻击的前提条件相对宽松，只需假定攻击者能够在对用户数据结构仅有粗略了解的基础上，向训练数据集中插入几十个表面上无害的句子即可。

> When large language models are trained on private data, it can be a significant privacy risk for them to memorize and regurgitate sensitive information. In this work, we propose a new practical data extraction attack that we call "neural phishing". This attack enables an adversary to target and extract sensitive or personally identifiable information (PII), e.g., credit card numbers, from a model trained on user data with upwards of 10% attack success rates, at times, as high as 50%. Our attack assumes only that an adversary can insert as few as 10s of benign-appearing sentences into the training dataset using only vague priors on the structure of the user data.