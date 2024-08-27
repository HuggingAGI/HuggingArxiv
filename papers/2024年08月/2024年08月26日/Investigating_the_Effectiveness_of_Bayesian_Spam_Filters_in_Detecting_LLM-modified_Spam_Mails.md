# 探究贝叶斯垃圾邮件过滤器对 LLM 修改型垃圾邮件的检测效能

发布时间：2024年08月26日

`LLM应用` `网络安全` `垃圾邮件过滤`

> Investigating the Effectiveness of Bayesian Spam Filters in Detecting LLM-modified Spam Mails

# 摘要

> 垃圾邮件和网络钓鱼在网络安全中依旧威胁巨大，几乎占安全事件的九成。随着攻击手段日益复杂，强化防御机制的需求愈发迫切。贝叶斯垃圾邮件过滤器，如广受欢迎的开源工具SpamAssassin，是抵御这些威胁的关键。然而，大型语言模型如ChatGPT的兴起，为网络安全带来了新挑战。这些模型不仅功能强大、易于获取，而且使用成本极低，这使得它们可能被用于制作能够绕过传统过滤器的复杂垃圾邮件。本研究聚焦于评估SpamAssassin对经LLM修改的邮件的防御能力。我们设计了一套测试流程，利用GPT-3.5 Turbo对垃圾邮件进行修改，并检验SpamAssassin的分类准确性。结果令人震惊，SpamAssassin竟将高达73.7%的修改后垃圾邮件误判为合法邮件，而相比之下，简单的字典替换攻击成功率仅为0.4%。这些数据揭示了LLM修改垃圾邮件的巨大威胁，尤其是其低成本（每封邮件仅0.17美分）。本文深入剖析了当前垃圾邮件过滤器的脆弱性，并强调了网络安全措施不断升级的紧迫性。

> Spam and phishing remain critical threats in cybersecurity, responsible for nearly 90% of security incidents. As these attacks grow in sophistication, the need for robust defensive mechanisms intensifies. Bayesian spam filters, like the widely adopted open-source SpamAssassin, are essential tools in this fight. However, the emergence of large language models (LLMs) such as ChatGPT presents new challenges. These models are not only powerful and accessible, but also inexpensive to use, raising concerns about their misuse in crafting sophisticated spam emails that evade traditional spam filters. This work aims to evaluate the robustness and effectiveness of SpamAssassin against LLM-modified email content. We developed a pipeline to test this vulnerability. Our pipeline modifies spam emails using GPT-3.5 Turbo and assesses SpamAssassin's ability to classify these modified emails correctly. The results show that SpamAssassin misclassified up to 73.7% of LLM-modified spam emails as legitimate. In contrast, a simpler dictionary-replacement attack showed a maximum success rate of only 0.4%. These findings highlight the significant threat posed by LLM-modified spam, especially given the cost-efficiency of such attacks (0.17 cents per email). This paper provides crucial insights into the vulnerabilities of current spam filters and the need for continuous improvement in cybersecurity measures.

[Arxiv](https://arxiv.org/abs/2408.14293)