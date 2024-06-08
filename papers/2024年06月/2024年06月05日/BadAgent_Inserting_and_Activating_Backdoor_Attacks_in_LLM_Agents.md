# BadAgent：潜入LLM代理的后门攻击激活术

发布时间：2024年06月05日

`Agent

理由：这篇论文主要讨论了基于大型语言模型（LLMs）的智能代理在受到特定攻击（名为BadAgent的回溯攻击）时的安全问题。这种攻击通过在含有后门的数据上微调模型来植入后门，从而影响代理的行为。论文的重点在于智能代理的安全性和攻击方法，这与Agent分类下的研究内容相符，即关注智能代理的设计、功能及其潜在的安全威胁。` `智能代理` `网络安全`

> BadAgent: Inserting and Activating Backdoor Attacks in LLM Agents

# 摘要

> 随着大型语言模型（LLMs）的兴起，基于LLM的智能代理应运而生，它们利用用户定义的工具提供个性化服务。目前，构建这些代理的先进技术是使用预训练的LLMs，并针对特定任务数据进行微调。然而，我们发现这些方法极易受到我们提出的名为BadAgent的回溯攻击的影响，这种攻击通过在含有后门的数据上微调模型来植入后门。在实际应用中，攻击者只需在输入中加入特定触发器，便能操控这些代理执行恶意操作。令人震惊的是，即使模型经过可信数据的微调，我们的攻击手段依然极为有效。尽管回溯攻击在自然语言处理领域已有广泛研究，但据我们所知，我们可能是首个将其应用于LLM代理的研究，这些代理因能访问外部工具而更具威胁性。我们的研究揭示了使用不可信LLMs或数据构建智能代理的潜在风险。相关代码已公开于https://github.com/DPamK/BadAgent。

> With the prosperity of large language models (LLMs), powerful LLM-based intelligent agents have been developed to provide customized services with a set of user-defined tools. State-of-the-art methods for constructing LLM agents adopt trained LLMs and further fine-tune them on data for the agent task. However, we show that such methods are vulnerable to our proposed backdoor attacks named BadAgent on various agent tasks, where a backdoor can be embedded by fine-tuning on the backdoor data. At test time, the attacker can manipulate the deployed LLM agents to execute harmful operations by showing the trigger in the agent input or environment. To our surprise, our proposed attack methods are extremely robust even after fine-tuning on trustworthy data. Though backdoor attacks have been studied extensively in natural language processing, to the best of our knowledge, we could be the first to study them on LLM agents that are more dangerous due to the permission to use external tools. Our work demonstrates the clear risk of constructing LLM agents based on untrusted LLMs or data. Our code is public at https://github.com/DPamK/BadAgent

[Arxiv](https://arxiv.org/abs/2406.03007)