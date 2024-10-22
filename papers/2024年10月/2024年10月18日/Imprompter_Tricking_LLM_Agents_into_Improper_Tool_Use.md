# Imprompter：诱导 LLM 代理误用工具

发布时间：2024年10月18日

`Agent` `网络安全` `人工智能`

> Imprompter: Tricking LLM Agents into Improper Tool Use

# 摘要

> 大型语言模型（LLM）代理融合了生成式机器学习与代码解释器、网络浏览、电子邮件等工具，代表了个人计算的新趋势。我们探讨了这些系统的安全基础，揭示了一种新型自动混淆对抗提示攻击，威胁用户资源的安全。通过提示优化技术，我们展示了如何自动生成此类攻击。实验证明，这些攻击不仅在理论模型中有效，还能影响实际生产中的代理系统。例如，我们成功实施了对 Mistral 的 LeChat 代理的信息泄露攻击，通过分析对话提取个人信息，并将其传输至攻击者服务器，成功率高达80%。这些攻击手段多样，涵盖文本和图像领域，对新兴代理系统如 Mistral 的 LeChat、ChatGLM 和 Meta 的 Llama 构成威胁。

> Large Language Model (LLM) Agents are an emerging computing paradigm that blends generative machine learning with tools such as code interpreters, web browsing, email, and more generally, external resources. These agent-based systems represent an emerging shift in personal computing. We contribute to the security foundations of agent-based systems and surface a new class of automatically computed obfuscated adversarial prompt attacks that violate the confidentiality and integrity of user resources connected to an LLM agent. We show how prompt optimization techniques can find such prompts automatically given the weights of a model. We demonstrate that such attacks transfer to production-level agents. For example, we show an information exfiltration attack on Mistral's LeChat agent that analyzes a user's conversation, picks out personally identifiable information, and formats it into a valid markdown command that results in leaking that data to the attacker's server. This attack shows a nearly 80% success rate in an end-to-end evaluation. We conduct a range of experiments to characterize the efficacy of these attacks and find that they reliably work on emerging agent-based systems like Mistral's LeChat, ChatGLM, and Meta's Llama. These attacks are multimodal, and we show variants in the text-only and image domains.

[Arxiv](https://arxiv.org/abs/2410.14923)