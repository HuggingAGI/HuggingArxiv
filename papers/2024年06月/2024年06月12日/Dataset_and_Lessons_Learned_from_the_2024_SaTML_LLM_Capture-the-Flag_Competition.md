# 2024年SaTML LLM夺旗竞赛：数据集与经验总结

发布时间：2024年06月12日

`Agent

理由：这篇论文描述了一个针对大型语言模型（LLM）系统的安全挑战，并通过举办一场夺旗赛来探索和测试防御策略。这种类型的研究通常涉及开发和评估能够执行特定任务（如防御或攻击）的智能代理或系统。因此，它更符合Agent分类，因为这里讨论的是如何通过智能代理来保护或攻击LLM系统，而不是直接关于LLM的理论研究或应用开发。` `网络安全` `人工智能安全`

> Dataset and Lessons Learned from the 2024 SaTML LLM Capture-the-Flag Competition

# 摘要

> 大型语言模型系统易受恶意消息的威胁，这些消息企图篡改系统指令或泄露敏感数据。为此，我们在IEEE SaTML 2024上举办了一场夺旗赛，其中“旗帜”是LLM系统提示中的一个秘密字符串。比赛分为两阶段：首阶段，各队研发防御策略以保护秘密不被泄露；次阶段，则需破解其他队伍的防御以获取秘密。比赛揭示了防御措施屡遭突破的现实，凸显了构建有效防御的挑战及对LLM系统保护研究的迫切需求。为推动此领域研究，我们整理了超过137,000条多轮攻击的聊天记录，并开放了研究平台。

> Large language model systems face important security risks from maliciously crafted messages that aim to overwrite the system's original instructions or leak private data. To study this problem, we organized a capture-the-flag competition at IEEE SaTML 2024, where the flag is a secret string in the LLM system prompt. The competition was organized in two phases. In the first phase, teams developed defenses to prevent the model from leaking the secret. During the second phase, teams were challenged to extract the secrets hidden for defenses proposed by the other teams. This report summarizes the main insights from the competition. Notably, we found that all defenses were bypassed at least once, highlighting the difficulty of designing a successful defense and the necessity for additional research to protect LLM systems. To foster future research in this direction, we compiled a dataset with over 137k multi-turn attack chats and open-sourced the platform.

![2024年SaTML LLM夺旗竞赛：数据集与经验总结](../../../paper_images/2406.07954/x1.png)

![2024年SaTML LLM夺旗竞赛：数据集与经验总结](../../../paper_images/2406.07954/x2.png)

![2024年SaTML LLM夺旗竞赛：数据集与经验总结](../../../paper_images/2406.07954/x4.png)

![2024年SaTML LLM夺旗竞赛：数据集与经验总结](../../../paper_images/2406.07954/x5.png)

[Arxiv](https://arxiv.org/abs/2406.07954)