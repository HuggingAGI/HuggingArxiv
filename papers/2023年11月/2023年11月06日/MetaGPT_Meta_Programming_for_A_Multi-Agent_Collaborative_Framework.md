# MetaGPT：多代理协作框架的元编程之光在人工智能的星辰大海中，MetaGPT如同一颗璀璨的星辰，以其独特的元编程技术，为多代理协作框架注入了新的活力。它不仅仅是一个编程工具，更是一个智慧的交汇点，让不同的代理能够协同工作，共同编织出复杂而精妙的解决方案。MetaGPT的出现，预示着智能系统合作的新纪元，它将引领我们探索更加广阔的智能协作领域。

发布时间：2023年11月06日

`Agent

这篇论文介绍了一种名为MetaGPT的元编程框架，它旨在通过多代理协作来提高自动问题解决的效率和准确性。MetaGPT通过模拟人类工作流程，将任务分解为子任务，并分配给不同的代理，以促进协同工作。这种方法特别适用于复杂任务，因为它减少了由于幻觉连锁导致的逻辑不一致问题。论文中提到的MetaGPT在协作软件工程中的应用，以及它如何优化工作流程和提高解决方案的连贯性，表明这是一个关于代理系统的应用研究。因此，它属于Agent分类。` `软件工程` `多代理系统`

> MetaGPT: Meta Programming for A Multi-Agent Collaborative Framework

# 摘要

> 基于大型语言模型的代理社会在自动问题解决领域取得了显著进步，但面对复杂任务时，由于幻觉连锁导致的逻辑不一致，解决方案变得复杂。为此，我们推出了MetaGPT，一种创新的元编程框架，它将人类工作流程的高效性融入到多代理协作中。MetaGPT通过将标准化操作程序编码为提示序列，优化了工作流程，使得具备人类领域专业知识的代理能够验证中间结果，减少错误。采用装配线模式，MetaGPT为不同代理分配特定角色，将复杂任务分解为多个子任务，促进多代理协同工作。在协作软件工程的测试中，MetaGPT展现出了比以往基于聊天的多代理系统更为连贯的解决方案。欲了解更多信息，请访问我们的GitHub项目页面：https://github.com/geekan/MetaGPT。

> Remarkable progress has been made on automated problem solving through societies of agents based on large language models (LLMs). Existing LLM-based multi-agent systems can already solve simple dialogue tasks. Solutions to more complex tasks, however, are complicated through logic inconsistencies due to cascading hallucinations caused by naively chaining LLMs. Here we introduce MetaGPT, an innovative meta-programming framework incorporating efficient human workflows into LLM-based multi-agent collaborations. MetaGPT encodes Standardized Operating Procedures (SOPs) into prompt sequences for more streamlined workflows, thus allowing agents with human-like domain expertise to verify intermediate results and reduce errors. MetaGPT utilizes an assembly line paradigm to assign diverse roles to various agents, efficiently breaking down complex tasks into subtasks involving many agents working together. On collaborative software engineering benchmarks, MetaGPT generates more coherent solutions than previous chat-based multi-agent systems. Our project can be found at https://github.com/geekan/MetaGPT

[Arxiv](https://arxiv.org/abs/2308.00352)