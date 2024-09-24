# PathSeeker：借助强化学习越狱技术，深入挖掘 LLM 的安全隐患

发布时间：2024年09月21日

`LLM应用` `网络安全` `人工智能`

> PathSeeker: Exploring LLM Security Vulnerabilities with a Reinforcement Learning-Based Jailbreak Approach

# 摘要

> 近年来，大型语言模型（LLM）的广泛应用引发了对其安全性的担忧。传统越狱攻击依赖于模型内部细节，或在探索模型不安全行为时受限，通用性不足。本文提出PathSeeker，一种受“逃离安全迷宫”启发的黑盒越狱方法。我们视每个LLM为独特的“安全迷宫”，攻击者通过反馈和经验寻找出口，破坏其安全防御。利用多智能体强化学习，小模型协作指导主LLM进行变异操作，逐步修改输入以诱导有害响应。手动测试中，目标模型响应词汇逐渐丰富，最终产生有害内容。基于此，引入奖励机制，利用响应词汇扩展削弱安全约束。在13个商业和开源LLM测试中，PathSeeker优于五种先进攻击技术，尤其在GPT-4o-mini、Claude-3.5和GLM-4-air等高安全对齐模型中表现突出。本研究旨在提升对LLM安全漏洞的理解，并推动更强防御措施的发展。

> In recent years, Large Language Models (LLMs) have gained widespread use, accompanied by increasing concerns over their security. Traditional jailbreak attacks rely on internal model details or have limitations when exploring the unsafe behavior of the victim model, limiting their generalizability. In this paper, we introduce PathSeeker, a novel black-box jailbreak method inspired by the concept of escaping a security maze. This work is inspired by the game of rats escaping a maze. We think that each LLM has its unique "security maze", and attackers attempt to find the exit learning from the received feedback and their accumulated experience to compromise the target LLM's security defences. Our approach leverages multi-agent reinforcement learning, where smaller models collaborate to guide the main LLM in performing mutation operations to achieve the attack objectives. By progressively modifying inputs based on the model's feedback, our system induces richer, harmful responses. During our manual attempts to perform jailbreak attacks, we found that the vocabulary of the response of the target model gradually became richer and eventually produced harmful responses. Based on the observation, we also introduce a reward mechanism that exploits the expansion of vocabulary richness in LLM responses to weaken security constraints. Our method outperforms five state-of-the-art attack techniques when tested across 13 commercial and open-source LLMs, achieving high attack success rates, especially in strongly aligned commercial models like GPT-4o-mini, Claude-3.5, and GLM-4-air with strong safety alignment. This study aims to improve the understanding of LLM security vulnerabilities and we hope that this sturdy can contribute to the development of more robust defenses.

[Arxiv](https://arxiv.org/abs/2409.14177)