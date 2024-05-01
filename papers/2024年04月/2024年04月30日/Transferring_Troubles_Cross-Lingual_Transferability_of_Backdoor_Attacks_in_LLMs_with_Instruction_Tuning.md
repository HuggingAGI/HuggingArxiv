# 在经过指令调整的大型语言模型（LLMs）中，后门攻击的跨语言转移性面临挑战。

发布时间：2024年04月30日

`LLM应用` `网络安全` `人工智能`

> Transferring Troubles: Cross-Lingual Transferability of Backdoor Attacks in LLMs with Instruction Tuning

# 摘要

> 后门攻击对英语主导的大型语言模型（LLMs）的影响已受到广泛关注，这类攻击在训练时嵌入恶意代码，并在特定触发条件下激活以产生恶意输出。然而，其对多语言模型的冲击尚未得到充分研究。本研究聚焦于多语言LLMs的跨语言后门攻击，特别是探讨在一个或两个语言中篡改指令调整数据如何影响其他未受影响语言的输出。尽管方法简单，但我们的实证分析发现，该方法在mT5、BLOOM和GPT-3.5-turbo等模型中效果显著，攻击成功率极高，多语言环境下超过95%。更令人担忧的是，大型模型对跨语言后门攻击的敏感性增强，这一现象也出现在主要基于英语数据预训练的LLMs中，如Llama2、Llama3和Gemma。此外，实验显示，即使经过改写，触发器依然有效，后门机制在25种语言的跨语言响应场景中表现出色，平均攻击成功率达到50%。本研究旨在揭示当前多语言LLMs的安全隐患，强调了采取针对性安全措施的迫切性。

> The implications of backdoor attacks on English-centric large language models (LLMs) have been widely examined - such attacks can be achieved by embedding malicious behaviors during training and activated under specific conditions that trigger malicious outputs. However, the impact of backdoor attacks on multilingual models remains under-explored. Our research focuses on cross-lingual backdoor attacks against multilingual LLMs, particularly investigating how poisoning the instruction-tuning data in one or two languages can affect the outputs in languages whose instruction-tuning data was not poisoned. Despite its simplicity, our empirical analysis reveals that our method exhibits remarkable efficacy in models like mT5, BLOOM, and GPT-3.5-turbo, with high attack success rates, surpassing 95% in several languages across various scenarios. Alarmingly, our findings also indicate that larger models show increased susceptibility to transferable cross-lingual backdoor attacks, which also applies to LLMs predominantly pre-trained on English data, such as Llama2, Llama3, and Gemma. Moreover, our experiments show that triggers can still work even after paraphrasing, and the backdoor mechanism proves highly effective in cross-lingual response settings across 25 languages, achieving an average attack success rate of 50%. Our study aims to highlight the vulnerabilities and significant security risks present in current multilingual LLMs, underscoring the emergent need for targeted security measures.

[Arxiv](https://arxiv.org/abs/2404.19597)