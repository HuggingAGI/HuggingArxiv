# 《反击 AI 黑客：将提示注入作为抵御 LLM 驱动的网络攻击之策》

发布时间：2024年10月28日

`LLM应用` `网络安全` `防御策略`

> Hacking Back the AI-Hacker: Prompt Injection as a Defense Against LLM-driven Cyberattacks

# 摘要

> 大型语言模型（LLMs）愈发被用于实现网络攻击的自动化，让复杂的攻击手段更易获取和推广。对此，我们提出了一种全新的防御策略，专门应对由LLM驱动的网络攻击。我们推出了Mantis这一防御框架，它利用LLM对对抗性输入的脆弱性来破坏恶意操作。一旦检测到自动化网络攻击，Mantis会在系统响应中植入精心设计的输入，致使攻击者的LLM破坏自身操作（被动防御），甚至危及攻击者的机器（主动防御）。通过部署有意设置的易受攻击的诱饵服务来吸引攻击者，并对攻击者的LLM使用动态提示注入，Mantis能够自主反击攻击者。在我们的实验中，Mantis在抵御自动化的LLM驱动攻击时，有效性始终超过95%。为推动进一步的研究与合作，Mantis已作为开源工具提供：https://github.com/pasquini-dario/project_mantis

> Large language models (LLMs) are increasingly being harnessed to automate cyberattacks, making sophisticated exploits more accessible and scalable. In response, we propose a new defense strategy tailored to counter LLM-driven cyberattacks. We introduce Mantis, a defensive framework that exploits LLMs' susceptibility to adversarial inputs to undermine malicious operations. Upon detecting an automated cyberattack, Mantis plants carefully crafted inputs into system responses, leading the attacker's LLM to disrupt their own operations (passive defense) or even compromise the attacker's machine (active defense). By deploying purposefully vulnerable decoy services to attract the attacker and using dynamic prompt injections for the attacker's LLM, Mantis can autonomously hack back the attacker. In our experiments, Mantis consistently achieved over 95% effectiveness against automated LLM-driven attacks. To foster further research and collaboration, Mantis is available as an open-source tool: https://github.com/pasquini-dario/project_mantis

[Arxiv](https://arxiv.org/abs/2410.20911)