# 大型语言模型（LLM）能如何精准地反映我们的语言？本文通过ECHO评估了AI聊天机器人在角色扮演方面的能力。

发布时间：2024年04月22日

`分类：LLM应用` `角色扮演` `人工智能`

> How Well Can LLMs Echo Us? Evaluating AI Chatbots' Role-Play Ability with ECHO

# 摘要

> 大型语言模型（LLMs）在角色扮演领域的应用正成为研究的新宠。但目前的研究多聚焦于模仿知名公众或虚构人物，而忽略了对普通个体模拟的可能性。这种偏颇限制了数字克隆人和电子游戏中非玩家角色的发展。为了填补这一空白，我们提出了ECHO，一个受图灵测试启发的评估体系。该体系通过目标个体的熟人来辨别人类与机器生成的回复。特别之处在于，ECHO专注于模拟普通人群，而非历史或虚构人物，为图灵测试的应用提供了新的视角。我们利用ECHO对三款角色扮演型LLMs进行了评估，包括基础模型GPT-3.5和GPT-4，以及OpenAI提供的在线GPTs应用。评估结果显示，GPT-4在欺骗人类评委方面更为有效，且GPTs的成功率达到了48.3%。此外，我们还探讨了LLMs是否能够区分人类与机器生成的文本。尽管GPT-4能够察觉差异，但它无法准确判断文本的来源。我们的代码和复现角色扮演LLMs的成果已在 https://github.com/CUHK-ARISE/ECHO 上公开。

> The role-play ability of Large Language Models (LLMs) has emerged as a popular research direction. However, existing studies focus on imitating well-known public figures or fictional characters, overlooking the potential for simulating ordinary individuals. Such an oversight limits the potential for advancements in digital human clones and non-player characters in video games. To bridge this gap, we introduce ECHO, an evaluative framework inspired by the Turing test. This framework engages the acquaintances of the target individuals to distinguish between human and machine-generated responses. Notably, our framework focuses on emulating average individuals rather than historical or fictional figures, presenting a unique advantage to apply the Turing Test. We evaluated three role-playing LLMs using ECHO, with GPT-3.5 and GPT-4 serving as foundational models, alongside the online application GPTs from OpenAI. Our results demonstrate that GPT-4 more effectively deceives human evaluators, and GPTs achieves a leading success rate of 48.3%. Furthermore, we investigated whether LLMs could discern between human-generated and machine-generated texts. While GPT-4 can identify differences, it could not determine which texts were human-produced. Our code and results of reproducing the role-playing LLMs are made publicly available via https://github.com/CUHK-ARISE/ECHO.

![大型语言模型（LLM）能如何精准地反映我们的语言？本文通过ECHO评估了AI聊天机器人在角色扮演方面的能力。](../../../paper_images/2404.13957/x1.png)

[Arxiv](https://arxiv.org/abs/2404.13957)