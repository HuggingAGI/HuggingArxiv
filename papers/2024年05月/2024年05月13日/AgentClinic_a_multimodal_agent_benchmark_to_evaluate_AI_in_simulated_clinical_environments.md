# AgentClinic：多模态代理基准，专为评估AI在模拟临床环境中的表现而设计。

发布时间：2024年05月13日

`Agent

这篇论文介绍了一个名为AgentClinic的多模态评估平台，它允许大型语言模型（LLMs）在模拟的临床环境中扮演医生的角色，通过对话和数据收集来进行病情诊断。这个平台特别强调了在实际互动决策过程中的应用，而不仅仅是静态的问答评估。AgentClinic的设计和评估方法表明，它是一个用于评估和改进AI代理在复杂决策环境中表现的工具，特别是在医疗领域。因此，这篇论文更符合Agent分类，因为它关注的是AI代理在特定应用场景（如医疗诊断）中的行为和性能评估。` `人工智能评估`

> AgentClinic: a multimodal agent benchmark to evaluate AI in simulated clinical environments

# 摘要

> 诊断与治疗患者是一个复杂且连续的决策过程，医生需获取信息并据此行动。AI和LLMs的进步是临床护理的福音，但现有评估多依赖静态问答，未能模拟实际的互动决策。为此，我们推出了AgentClinic，一个多模态评估平台，让LLMs在模拟临床环境中扮演医生角色，通过对话和数据收集揭示病情。我们提供了两个环境：AgentClinic-NEJM结合图像与对话，而AgentClinic-MedQA仅含对话。我们模拟了偏见，发现这不仅降低了诊断准确性，还影响了患者的合作意愿和信心。在评估顶级LLMs时，我们注意到在传统基准上表现优异的模型在AgentClinic中却表现不佳。我们发现，患者代理使用的LLM对性能有显著影响，且互动的次数需适度，过多或过少都会影响诊断准确性。所有相关代码和数据均已公开，网址为https://AgentClinic.github.io。

> Diagnosing and managing a patient is a complex, sequential decision making process that requires physicians to obtain information -- such as which tests to perform -- and to act upon it. Recent advances in artificial intelligence (AI) and large language models (LLMs) promise to profoundly impact clinical care. However, current evaluation schemes overrely on static medical question-answering benchmarks, falling short on interactive decision-making that is required in real-life clinical work. Here, we present AgentClinic: a multimodal benchmark to evaluate LLMs in their ability to operate as agents in simulated clinical environments. In our benchmark, the doctor agent must uncover the patient's diagnosis through dialogue and active data collection. We present two open benchmarks: a multimodal image and dialogue environment, AgentClinic-NEJM, and a dialogue-only environment, AgentClinic-MedQA. We embed cognitive and implicit biases both in patient and doctor agents to emulate realistic interactions between biased agents. We find that introducing bias leads to large reductions in diagnostic accuracy of the doctor agents, as well as reduced compliance, confidence, and follow-up consultation willingness in patient agents. Evaluating a suite of state-of-the-art LLMs, we find that several models that excel in benchmarks like MedQA are performing poorly in AgentClinic-MedQA. We find that the LLM used in the patient agent is an important factor for performance in the AgentClinic benchmark. We show that both having limited interactions as well as too many interaction reduces diagnostic accuracy in doctor agents. The code and data for this work is publicly available at https://AgentClinic.github.io.

[Arxiv](https://arxiv.org/abs/2405.07960)