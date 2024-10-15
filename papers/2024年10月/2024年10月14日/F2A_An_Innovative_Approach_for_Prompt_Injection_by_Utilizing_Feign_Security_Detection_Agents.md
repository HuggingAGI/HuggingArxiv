# F2A：通过伪装安全检测代理实现提示注入的创新策略

发布时间：2024年10月14日

`Agent` `网络安全` `人工智能`

> F2A: An Innovative Approach for Prompt Injection by Utilizing Feign Security Detection Agents

# 摘要

> 随着 LLM 的迅猛发展，内容安全检测领域涌现了众多成熟应用。然而，我们发现 LLM 对安全检测代理过于信任，这一漏洞可能被黑客利用。为此，本文提出了 Feign Agent Attack (F2A) 攻击，通过伪造安全检测结果，绕过 LLM 的防御机制，获取有害内容并劫持对话。实验表明，F2A 能有效劫持 LLM，揭示了 LLM 盲目信任检测结果的根本原因。本文还提出了解决方案，强调 LLM 需批判性评估代理结果，以提升其可靠性和安全性，抵御 F2A 攻击。

> With the rapid development of Large Language Models (LLMs), numerous mature applications of LLMs have emerged in the field of content safety detection. However, we have found that LLMs exhibit blind trust in safety detection agents. The general LLMs can be compromised by hackers with this vulnerability. Hence, this paper proposed an attack named Feign Agent Attack (F2A).Through such malicious forgery methods, adding fake safety detection results into the prompt, the defense mechanism of LLMs can be bypassed, thereby obtaining harmful content and hijacking the normal conversation. Continually, a series of experiments were conducted. In these experiments, the hijacking capability of F2A on LLMs was analyzed and demonstrated, exploring the fundamental reasons why LLMs blindly trust safety detection results. The experiments involved various scenarios where fake safety detection results were injected into prompts, and the responses were closely monitored to understand the extent of the vulnerability. Also, this paper provided a reasonable solution to this attack, emphasizing that it is important for LLMs to critically evaluate the results of augmented agents to prevent the generating harmful content. By doing so, the reliability and security can be significantly improved, protecting the LLMs from F2A.

[Arxiv](https://arxiv.org/abs/2410.08776)