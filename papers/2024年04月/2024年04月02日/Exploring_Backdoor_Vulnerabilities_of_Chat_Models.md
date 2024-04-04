# 深入研究聊天机器人的安全漏洞

发布时间：2024年04月02日

`LLM应用` `聊天机器人` `网络安全`

> Exploring Backdoor Vulnerabilities of Chat Models

# 摘要

> 最新研究揭示，大型语言模型（LLMs）面临着后门攻击的安全风险。这种后门攻击下，模型在正常情形下运作正常，但一旦遇到特定的触发信号，便会展现出恶意行为。目前的研究多集中于针对指令调整过的LLMs，却忽略了一个实际场景：LLMs在多轮对话数据上经过微调，变身为聊天机器人。鉴于聊天机器人在现实世界的应用广泛，其安全性问题亟需关注。遗憾的是，我们发现，多轮交互的灵活性反而让触发器设计更加多变，增加了聊天机器人面对后门攻击的脆弱性。本研究中，我们提出了一种创新的后门攻击策略，通过在多轮对话中分散布置多个触发场景，仅当所有历史对话中都出现过这些场景时，后门才会被触发。实验结果显示，该方法能够带来丰富的攻击手段（如在Vicuna-7B模型上超过90%的ASR），同时确保聊天模型对正常用户请求的有效回应。值得注意的是，这种后门难以通过下游的重新对齐来消除，这进一步凸显了对聊天模型安全性问题持续研究和关注的必要性。注意：本文可能包含不当内容。

> Recent researches have shown that Large Language Models (LLMs) are susceptible to a security threat known as Backdoor Attack. The backdoored model will behave well in normal cases but exhibit malicious behaviours on inputs inserted with a specific backdoor trigger. Current backdoor studies on LLMs predominantly focus on instruction-tuned LLMs, while neglecting another realistic scenario where LLMs are fine-tuned on multi-turn conversational data to be chat models. Chat models are extensively adopted across various real-world scenarios, thus the security of chat models deserves increasing attention. Unfortunately, we point out that the flexible multi-turn interaction format instead increases the flexibility of trigger designs and amplifies the vulnerability of chat models to backdoor attacks. In this work, we reveal and achieve a novel backdoor attacking method on chat models by distributing multiple trigger scenarios across user inputs in different rounds, and making the backdoor be triggered only when all trigger scenarios have appeared in the historical conversations. Experimental results demonstrate that our method can achieve high attack success rates (e.g., over 90% ASR on Vicuna-7B) while successfully maintaining the normal capabilities of chat models on providing helpful responses to benign user requests. Also, the backdoor can not be easily removed by the downstream re-alignment, highlighting the importance of continued research and attention to the security concerns of chat models. Warning: This paper may contain toxic content.

![深入研究聊天机器人的安全漏洞](../../../paper_images/2404.02406/x1.png)

![深入研究聊天机器人的安全漏洞](../../../paper_images/2404.02406/x2.png)

![深入研究聊天机器人的安全漏洞](../../../paper_images/2404.02406/x3.png)

![深入研究聊天机器人的安全漏洞](../../../paper_images/2404.02406/x4.png)

![深入研究聊天机器人的安全漏洞](../../../paper_images/2404.02406/x5.png)

[Arxiv](https://arxiv.org/abs/2404.02406)