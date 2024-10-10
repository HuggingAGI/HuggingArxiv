# 小心提问：揭秘文本到可视化模型的后门攻击

发布时间：2024年10月09日

`LLM应用` `数据可视化` `网络安全`

> Mind Your Questions Towards Backdoor Attacks on Text-to-Visualization Models

# 摘要

> 在大数据时代，文本到可视化 (text-to-vis) 模型已成为用户通过自然语言查询 (NLQs) 生成数据可视化并做出决策的重要工具。然而，这些模型的安全漏洞却鲜为人知。为此，我们推出了 VisPoison 框架，专门用于系统地识别这些漏洞。VisPoison 通过两种触发器激活三种后门攻击，可能导致数据泄露、误导性可视化或服务中断。主动攻击利用罕见词触发器获取机密数据，而被动攻击则无意中由用户触发，导致可视化错误或服务中断。实验表明，VisPoison 对当前模型的攻击成功率超过 90%，凸显了其安全问题。尽管我们探讨了两种防御机制，但现有对策仍显不足，迫切需要更强大的安全解决方案。

> Text-to-visualization (text-to-vis) models have become valuable tools in the era of big data, enabling users to generate data visualizations and make informed decisions through natural language queries (NLQs). Despite their widespread application, the security vulnerabilities of these models have been largely overlooked. To address this gap, we propose VisPoison, a novel framework designed to identify these vulnerabilities of current text-to-vis models systematically. VisPoison introduces two types of triggers that activate three distinct backdoor attacks, potentially leading to data exposure, misleading visualizations, or denial-of-service (DoS) incidents. The framework features both proactive and passive attack mechanisms: proactive attacks leverage rare-word triggers to access confidential data, while passive attacks, triggered unintentionally by users, exploit a first-word trigger method, causing errors or DoS events in visualizations. Through extensive experiments on both trainable and in-context learning (ICL)-based text-to-vis models, \textit{VisPoison} achieves attack success rates of over 90\%, highlighting the security problem of current text-to-vis models. Additionally, we explore two types of defense mechanisms against these attacks, but the results show that existing countermeasures are insufficient, underscoring the pressing need for more robust security solutions in text-to-vis systems.

[Arxiv](https://arxiv.org/abs/2410.06782)