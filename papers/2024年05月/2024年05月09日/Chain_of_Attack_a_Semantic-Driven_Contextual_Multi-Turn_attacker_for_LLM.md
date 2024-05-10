# 语义驱动攻击链：针对大型语言模型的多轮上下文攻击策略在

发布时间：2024年05月09日

`Agent

这篇论文探讨了大型语言模型（LLMs）在多轮对话中的安全性和道德风险，并提出了一种新的攻击策略——CoA（攻击链）方法。这种方法专注于利用上下文反馈和语义关联来动态调整攻击策略，以诱导LLMs产生不合理或有害的内容。研究的重点在于揭示LLMs的弱点，并为攻防提供新的视角和工具，这与Agent领域的研究相符，因为Agent通常指的是能够自主行动和决策的实体，而在这篇论文中，CoA方法可以被视为一种攻击Agent，它针对LLMs进行策略性的攻击。因此，这篇论文更适合归类于Agent分类。` `对话系统` `网络安全`

> Chain of Attack: a Semantic-Driven Contextual Multi-Turn attacker for LLM

# 摘要

> 大型语言模型（LLMs）在对话系统等自然语言处理任务中表现卓越，但同时也潜藏着安全和道德风险。特别是在多轮对话中，LLMs易受上下文引导，可能产生有害或有偏见的回应。本文创新性地提出了CoA（攻击链）方法，这是一种基于语义的上下文多轮攻击策略，能够根据对话中的上下文反馈和语义关联动态调整攻击策略，诱导LLMs产生不合理或有害内容。我们对CoA在多个LLMs和数据集上的效果进行了评估，结果显示CoA能有效揭示LLMs的弱点，并优于现有攻击手段。我们的研究为LLMs的攻防提供了新视角和工具，对提升对话系统的安全性和伦理标准具有重要意义。

> Large language models (LLMs) have achieved remarkable performance in various natural language processing tasks, especially in dialogue systems. However, LLM may also pose security and moral threats, especially in multi round conversations where large models are more easily guided by contextual content, resulting in harmful or biased responses. In this paper, we present a novel method to attack LLMs in multi-turn dialogues, called CoA (Chain of Attack). CoA is a semantic-driven contextual multi-turn attack method that adaptively adjusts the attack policy through contextual feedback and semantic relevance during multi-turn of dialogue with a large model, resulting in the model producing unreasonable or harmful content. We evaluate CoA on different LLMs and datasets, and show that it can effectively expose the vulnerabilities of LLMs, and outperform existing attack methods. Our work provides a new perspective and tool for attacking and defending LLMs, and contributes to the security and ethical assessment of dialogue systems.

[Arxiv](https://arxiv.org/abs/2405.05610)