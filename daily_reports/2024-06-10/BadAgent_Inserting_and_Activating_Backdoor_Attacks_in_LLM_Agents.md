# BadAgent：潜入LLM代理的后门攻击激活术
发布时间：2024年06月05日

`Agent应用`
> BadAgent: Inserting and Activating Backdoor Attacks in LLM Agents
>
> 随着大型语言模型（LLMs）的兴起，基于LLM的智能代理应运而生，它们利用用户定义的工具提供个性化服务。目前，构建这些代理的先进技术是使用预训练的LLMs，并针对特定任务数据进行微调。然而，我们发现这些方法极易受到我们提出的名为BadAgent的回溯攻击的影响，这种攻击通过在含有后门的数据上微调模型来植入后门。在实际应用中，攻击者只需在输入中加入特定触发器，便能操控这些代理执行恶意操作。令人震惊的是，即使模型经过可信数据的微调，我们的攻击手段依然极为有效。尽管回溯攻击在自然语言处理领域已有广泛研究，但据我们所知，我们可能是首个将其应用于LLM代理的研究，这些代理因能访问外部工具而更具威胁性。我们的研究揭示了使用不可信LLMs或数据构建智能代理的潜在风险。相关代码已公开于https://github.com/DPamK/BadAgent。
>
> https://arxiv.org/abs/2406.03007


<hr />

- 论文原文: [https://arxiv.org/abs/2406.03007](https://arxiv.org/abs/2406.03007)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886