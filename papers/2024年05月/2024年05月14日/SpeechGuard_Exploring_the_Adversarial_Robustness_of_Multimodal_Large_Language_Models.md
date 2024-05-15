# 语音卫士：揭秘多模态大型语言模型在对抗攻击下的坚固防线

发布时间：2024年05月14日

`Agent

这篇论文主要探讨了集成语音和大语言模型（SLMs）的安全性和鲁棒性问题，特别是在对抗性攻击和越狱攻击方面的脆弱性。它不仅分析了这些模型的安全挑战，还设计了算法来生成对抗性示例，并提出了相应的防御措施。这与Agent分类相符，因为Agent通常指的是能够自主执行任务、做出决策并与其他系统或环境交互的智能实体。在这种情况下，SLMs可以被视为Agent，因为它们能够处理语音指令并生成文本响应，同时需要具备一定的安全性和鲁棒性来应对潜在的攻击。论文中的研究重点在于提高这些Agent的安全性和对抗攻击的能力，因此归类为Agent。` `语音识别` `对话系统`

> SpeechGuard: Exploring the Adversarial Robustness of Multimodal Large Language Models

# 摘要

> 集成语音和大语言模型（SLMs）近期因其能够遵循语音指令并生成相关文本响应而备受瞩目。然而，这些模型的安全性和鲁棒性仍是一个谜。本研究深入探讨了SLMs在对抗性攻击和越狱攻击面前的脆弱性，并设计了无需人工干预的算法，在白盒和黑盒攻击场景中生成对抗性示例以越狱SLMs。同时，我们提出对策以抵御此类攻击。我们的模型在包含语音指令的对话数据上训练，在口语问答任务上取得了顶尖成绩，安全性和有用性指标均超过80%。尽管有安全措施，实验表明SLMs在对抗性扰动和转移攻击面前仍显脆弱，平均攻击成功率分别为90%和10%，这些攻击针对的是涵盖12种有害类别的有害问题数据集。不过，我们的对策显著降低了攻击成功率。

> Integrated Speech and Large Language Models (SLMs) that can follow speech instructions and generate relevant text responses have gained popularity lately. However, the safety and robustness of these models remains largely unclear. In this work, we investigate the potential vulnerabilities of such instruction-following speech-language models to adversarial attacks and jailbreaking. Specifically, we design algorithms that can generate adversarial examples to jailbreak SLMs in both white-box and black-box attack settings without human involvement. Additionally, we propose countermeasures to thwart such jailbreaking attacks. Our models, trained on dialog data with speech instructions, achieve state-of-the-art performance on spoken question-answering task, scoring over 80% on both safety and helpfulness metrics. Despite safety guardrails, experiments on jailbreaking demonstrate the vulnerability of SLMs to adversarial perturbations and transfer attacks, with average attack success rates of 90% and 10% respectively when evaluated on a dataset of carefully designed harmful questions spanning 12 different toxic categories. However, we demonstrate that our proposed countermeasures reduce the attack success significantly.

[Arxiv](https://arxiv.org/abs/2405.08317)