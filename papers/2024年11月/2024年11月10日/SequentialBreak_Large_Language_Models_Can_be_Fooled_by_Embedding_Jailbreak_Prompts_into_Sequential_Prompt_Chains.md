# SequentialBreak：大型语言模型可能会被嵌入越狱提示到顺序提示链中所愚弄。

发布时间：2024年11月10日

`LLM应用` `语言模型` `安全防御`

> SequentialBreak: Large Language Models Can be Fooled by Embedding Jailbreak Prompts into Sequential Prompt Chains

# 摘要

> 随着大型语言模型（LLMs）在各种应用中的集成度不断提高，它们被误用的可能性也在增加，引发了重大的安全担忧。众多越狱攻击已被提出以评估 LLMs 的安全防御。当前的越狱攻击主要依靠场景伪装、提示混淆、提示优化和提示迭代优化来隐藏恶意提示。特别是，单个查询中的顺序提示链可以使 LLMs 专注于某些提示而忽略其他提示，有利于上下文操纵。本文介绍了 SequentialBreak，一种利用此漏洞的新型越狱攻击。我们讨论了几种场景，不限于像题库、对话完成和游戏环境这样的例子，其中有害提示嵌入在良性提示中，可以诱使 LLMs 生成有害响应。这些场景的不同叙述结构表明，SequentialBreak 足够灵活，能够适应所讨论之外的各种提示格式。大量实验表明，SequentialBreak 仅使用单个查询就实现了相对于现有开源和闭源模型基线的攻击成功率的大幅提升。通过我们的研究，我们强调迫切需要更强大和有弹性的保障措施来增强 LLM 安全性并防止潜在的误用。与此研究相关的所有结果文件和网站都可在这个 GitHub 存储库中找到：https://anonymous.4open.science/r/JailBreakAttack-4F3B/。

> As the integration of the Large Language Models (LLMs) into various applications increases, so does their susceptibility to misuse, raising significant security concerns. Numerous jailbreak attacks have been proposed to assess the security defense of LLMs. Current jailbreak attacks mainly rely on scenario camouflage, prompt obfuscation, prompt optimization, and prompt iterative optimization to conceal malicious prompts. In particular, sequential prompt chains in a single query can lead LLMs to focus on certain prompts while ignoring others, facilitating context manipulation. This paper introduces SequentialBreak, a novel jailbreak attack that exploits this vulnerability. We discuss several scenarios, not limited to examples like Question Bank, Dialog Completion, and Game Environment, where the harmful prompt is embedded within benign ones that can fool LLMs into generating harmful responses. The distinct narrative structures of these scenarios show that SequentialBreak is flexible enough to adapt to various prompt formats beyond those discussed. Extensive experiments demonstrate that SequentialBreak uses only a single query to achieve a substantial gain of attack success rate over existing baselines against both open-source and closed-source models. Through our research, we highlight the urgent need for more robust and resilient safeguards to enhance LLM security and prevent potential misuse. All the result files and website associated with this research are available in this GitHub repository: https://anonymous.4open.science/r/JailBreakAttack-4F3B/.

[Arxiv](https://arxiv.org/abs/2411.06426)