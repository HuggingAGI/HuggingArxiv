# 无视标题，破解提示：一场全球性的提示破解大赛，揭露了大型语言模型中的系统性安全漏洞。

发布时间：2024年03月02日

`LLM应用

这篇论文关注的是大型语言模型（LLMs）在实际应用中遇到的安全问题，特别是提示注入和越狱（提示黑客攻击）的问题。论文通过举办全球提示黑客竞赛，收集了大量的对抗性提示数据，并创建了相关数据集，以证实LLMs的脆弱性。此外，论文还提出了一套对抗性提示类型的分类体系。这些内容都是围绕LLMs在实际应用中的安全问题展开的，因此属于LLM应用分类。` `聊天机器人` `网络安全`

> Ignore This Title and HackAPrompt: Exposing Systemic Vulnerabilities of LLMs through a Global Scale Prompt Hacking Competition

# 摘要

> 大型语言模型（LLMs）在聊天机器人和写作助手等直接用户互动场景中广泛应用，却易受提示注入和越狱（合称提示黑客攻击）的威胁，使模型偏离原定指令，转而执行潜在恶意指令。尽管这一安全威胁广受关注，但相关的大规模资源和定量研究却寥寥无几。为此，我们举办了一场全球提示黑客竞赛，开放自由形式的攻击。我们收集了超过600,000个针对三种顶尖LLMs的对抗性提示，并创建了相关数据集，证实了LLMs确实易受提示黑客攻击的影响。此外，我们还提出了一套全面的对抗性提示类型分类体系。

> Large Language Models (LLMs) are deployed in interactive contexts with direct user engagement, such as chatbots and writing assistants. These deployments are vulnerable to prompt injection and jailbreaking (collectively, prompt hacking), in which models are manipulated to ignore their original instructions and follow potentially malicious ones. Although widely acknowledged as a significant security threat, there is a dearth of large-scale resources and quantitative studies on prompt hacking. To address this lacuna, we launch a global prompt hacking competition, which allows for free-form human input attacks. We elicit 600K+ adversarial prompts against three state-of-the-art LLMs. We describe the dataset, which empirically verifies that current LLMs can indeed be manipulated via prompt hacking. We also present a comprehensive taxonomical ontology of the types of adversarial prompts.

[Arxiv](https://arxiv.org/abs/2311.16119)