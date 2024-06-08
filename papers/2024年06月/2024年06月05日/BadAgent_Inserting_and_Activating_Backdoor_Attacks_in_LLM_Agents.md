# BadAgent：潜伏于LLM代理中的后门攻击激活术

发布时间：2024年06月05日

`Agent

这篇论文主要讨论了基于大型语言模型（LLMs）的智能代理在受到后门攻击时的脆弱性。论文中提到的“BadAgent”后门攻击是通过在含有后门的数据上微调LLMs来植入后门，这直接关联到智能代理的安全性和操作性。因此，这篇论文的内容与智能代理（Agent）的构建和安全性紧密相关，而不是关于LLM的理论研究、RAG（Retrieval-Augmented Generation）技术，或者LLM的一般应用。因此，将其分类为Agent是最合适的。` `智能代理` `网络安全`

> BadAgent: Inserting and Activating Backdoor Attacks in LLM Agents

# 摘要

> 随着大型语言模型（LLMs）的兴起，基于LLM的智能代理应运而生，它们配备了一系列用户定制工具，提供个性化服务。目前，构建这些智能代理的先进技术是利用已训练的LLMs，并针对特定任务数据进行微调。然而，我们发现这些方法极易受到我们提出的名为BadAgent的后门攻击的影响，这种攻击通过在含有后门的数据上微调LLMs来植入后门。在实际应用中，攻击者只需在输入或环境中触发特定信号，便能操控这些智能代理执行恶意操作。令人震惊的是，即使经过可信数据的微调，我们的攻击手段依然异常坚固。尽管后门攻击在自然语言处理领域已有广泛研究，但据我们所知，我们可能是首次将其应用于LLM代理，这些代理因能访问外部工具而更具威胁性。我们的研究揭示了基于不可信LLMs或数据构建智能代理的潜在风险。相关代码已公开于https://github.com/DPamK/BadAgent。

> With the prosperity of large language models (LLMs), powerful LLM-based intelligent agents have been developed to provide customized services with a set of user-defined tools. State-of-the-art methods for constructing LLM agents adopt trained LLMs and further fine-tune them on data for the agent task. However, we show that such methods are vulnerable to our proposed backdoor attacks named BadAgent on various agent tasks, where a backdoor can be embedded by fine-tuning on the backdoor data. At test time, the attacker can manipulate the deployed LLM agents to execute harmful operations by showing the trigger in the agent input or environment. To our surprise, our proposed attack methods are extremely robust even after fine-tuning on trustworthy data. Though backdoor attacks have been studied extensively in natural language processing, to the best of our knowledge, we could be the first to study them on LLM agents that are more dangerous due to the permission to use external tools. Our work demonstrates the clear risk of constructing LLM agents based on untrusted LLMs or data. Our code is public at https://github.com/DPamK/BadAgent

[Arxiv](https://arxiv.org/abs/2406.03007)