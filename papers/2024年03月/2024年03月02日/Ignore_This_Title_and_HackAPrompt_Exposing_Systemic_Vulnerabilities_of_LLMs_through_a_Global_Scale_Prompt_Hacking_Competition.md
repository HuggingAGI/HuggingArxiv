# 无视标题，破解提示大赛：全球竞赛揭示LLMs的系统性漏洞

发布时间：2024年03月02日

`Agent

理由：这篇论文主要关注的是大型语言模型（LLMs）在实际应用中遇到的安全问题，特别是提示注入和越狱（提示攻击）。论文通过举办全球提示攻击竞赛，收集了大量的对抗性提示数据，并对其进行了分类。这种研究更偏向于探讨如何通过外部干预（即Agent的行为）来影响LLMs的行为，而不是深入探讨LLMs的理论基础或其内部结构。因此，将其归类为Agent更为合适。` `人工智能`

> Ignore This Title and HackAPrompt: Exposing Systemic Vulnerabilities of LLMs through a Global Scale Prompt Hacking Competition

# 摘要

> 大型语言模型（LLMs）如聊天机器人和写作助手，在与用户直接互动的环境中部署，却易受提示注入和越狱（合称提示攻击）的威胁，模型因此可能被诱导执行恶意指令，背离初衷。尽管提示攻击被视为重大安全风险，相关的大规模研究和资源却寥寥无几。为此，我们举办了一场全球提示攻击竞赛，开放自由形式的攻击方式，并收集了超过60万条针对顶尖LLMs的对抗性提示。我们的数据集证实了LLMs确实易受提示攻击影响，并提供了一个详尽的对抗性提示类型分类体系。

> Large Language Models (LLMs) are deployed in interactive contexts with direct user engagement, such as chatbots and writing assistants. These deployments are vulnerable to prompt injection and jailbreaking (collectively, prompt hacking), in which models are manipulated to ignore their original instructions and follow potentially malicious ones. Although widely acknowledged as a significant security threat, there is a dearth of large-scale resources and quantitative studies on prompt hacking. To address this lacuna, we launch a global prompt hacking competition, which allows for free-form human input attacks. We elicit 600K+ adversarial prompts against three state-of-the-art LLMs. We describe the dataset, which empirically verifies that current LLMs can indeed be manipulated via prompt hacking. We also present a comprehensive taxonomical ontology of the types of adversarial prompts.

[Arxiv](https://arxiv.org/abs/2311.16119)