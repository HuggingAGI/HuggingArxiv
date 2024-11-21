# 针对 LLM 目标劫持的伪对话注入

发布时间：2024年10月31日

`LLM应用` `语言模型` `网络安全`

> Pseudo-Conversation Injection for LLM Goal Hijacking

# 摘要

> 目标劫持是针对大型语言模型（LLMs）的一种对抗性攻击，其目的在于操控模型生成特定的、预先设定好的输出，全然不顾用户的初始输入。在目标劫持里，攻击者通常会在用户的提示后面添加精心设计的恶意后缀，迫使模型无视用户的原始输入，生成目标响应。在本文中，我们引入了一种名为伪对话注入的新型目标劫持攻击方法，它利用了LLMs在对话情境中角色识别的弱点。具体而言，我们通过伪造LLM对用户初始提示的回应，接着加上恶意新任务的提示来构建后缀。这使得模型将初始提示和伪造的回应视作已完成的对话，进而执行新的伪造提示。基于此方法，我们提出了三种伪对话构建策略：有针对性伪对话、通用伪对话和稳健伪对话。这些策略旨在不同场景下实现有效的目标劫持。我们在ChatGPT和Qwen这两个主流LLM平台上开展的实验表明，我们所提出的方法在攻击有效性方面显著优于现有的方法。

> Goal hijacking is a type of adversarial attack on Large Language Models (LLMs) where the objective is to manipulate the model into producing a specific, predetermined output, regardless of the user's original input. In goal hijacking, an attacker typically appends a carefully crafted malicious suffix to the user's prompt, which coerces the model into ignoring the user's original input and generating the target response. In this paper, we introduce a novel goal hijacking attack method called Pseudo-Conversation Injection, which leverages the weaknesses of LLMs in role identification within conversation contexts. Specifically, we construct the suffix by fabricating responses from the LLM to the user's initial prompt, followed by a prompt for a malicious new task. This leads the model to perceive the initial prompt and fabricated response as a completed conversation, thereby executing the new, falsified prompt. Following this approach, we propose three Pseudo-Conversation construction strategies: Targeted Pseudo-Conversation, Universal Pseudo-Conversation, and Robust Pseudo-Conversation. These strategies are designed to achieve effective goal hijacking across various scenarios. Our experiments, conducted on two mainstream LLM platforms including ChatGPT and Qwen, demonstrate that our proposed method significantly outperforms existing approaches in terms of attack effectiveness.

[Arxiv](https://arxiv.org/abs/2410.23678)