# AgentPoison：利用毒化记忆或知识库手段，对 LLM 代理进行红队挑战

发布时间：2024年07月17日

`Agent` `网络安全` `人工智能`

> AgentPoison: Red-teaming LLM Agents via Poisoning Memory or Knowledge Bases

# 摘要

> LLM代理因其强大的推理和互动能力在多领域表现出色。然而，依赖未经核实的知识库引发安全疑虑。为此，我们首创AgentPoison攻击，通过毒化代理的记忆库植入后门，实现高概率的恶意行为激活，同时保持正常指令的性能。AgentPoison无需额外训练，触发器设计巧妙，实验证实其对多种代理的高效攻击能力，平均成功率超80%，对正常功能影响微乎其微。

> LLM agents have demonstrated remarkable performance across various applications, primarily due to their advanced capabilities in reasoning, utilizing external knowledge and tools, calling APIs, and executing actions to interact with environments. Current agents typically utilize a memory module or a retrieval-augmented generation (RAG) mechanism, retrieving past knowledge and instances with similar embeddings from knowledge bases to inform task planning and execution. However, the reliance on unverified knowledge bases raises significant concerns about their safety and trustworthiness. To uncover such vulnerabilities, we propose a novel red teaming approach AgentPoison, the first backdoor attack targeting generic and RAG-based LLM agents by poisoning their long-term memory or RAG knowledge base. In particular, we form the trigger generation process as a constrained optimization to optimize backdoor triggers by mapping the triggered instances to a unique embedding space, so as to ensure that whenever a user instruction contains the optimized backdoor trigger, the malicious demonstrations are retrieved from the poisoned memory or knowledge base with high probability. In the meantime, benign instructions without the trigger will still maintain normal performance. Unlike conventional backdoor attacks, AgentPoison requires no additional model training or fine-tuning, and the optimized backdoor trigger exhibits superior transferability, in-context coherence, and stealthiness. Extensive experiments demonstrate AgentPoison's effectiveness in attacking three types of real-world LLM agents: RAG-based autonomous driving agent, knowledge-intensive QA agent, and healthcare EHRAgent. On each agent, AgentPoison achieves an average attack success rate higher than 80% with minimal impact on benign performance (less than 1%) with a poison rate less than 0.1%.

![AgentPoison：利用毒化记忆或知识库手段，对 LLM 代理进行红队挑战](../../../paper_images/2407.12784/x1.png)

![AgentPoison：利用毒化记忆或知识库手段，对 LLM 代理进行红队挑战](../../../paper_images/2407.12784/x2.png)

![AgentPoison：利用毒化记忆或知识库手段，对 LLM 代理进行红队挑战](../../../paper_images/2407.12784/x3.png)

![AgentPoison：利用毒化记忆或知识库手段，对 LLM 代理进行红队挑战](../../../paper_images/2407.12784/x4.png)

![AgentPoison：利用毒化记忆或知识库手段，对 LLM 代理进行红队挑战](../../../paper_images/2407.12784/x5.png)

![AgentPoison：利用毒化记忆或知识库手段，对 LLM 代理进行红队挑战](../../../paper_images/2407.12784/x6.png)

![AgentPoison：利用毒化记忆或知识库手段，对 LLM 代理进行红队挑战](../../../paper_images/2407.12784/x7.png)

![AgentPoison：利用毒化记忆或知识库手段，对 LLM 代理进行红队挑战](../../../paper_images/2407.12784/x8.png)

![AgentPoison：利用毒化记忆或知识库手段，对 LLM 代理进行红队挑战](../../../paper_images/2407.12784/x9.png)

![AgentPoison：利用毒化记忆或知识库手段，对 LLM 代理进行红队挑战](../../../paper_images/2407.12784/x10.png)

![AgentPoison：利用毒化记忆或知识库手段，对 LLM 代理进行红队挑战](../../../paper_images/2407.12784/x11.png)

![AgentPoison：利用毒化记忆或知识库手段，对 LLM 代理进行红队挑战](../../../paper_images/2407.12784/x12.png)

![AgentPoison：利用毒化记忆或知识库手段，对 LLM 代理进行红队挑战](../../../paper_images/2407.12784/x13.png)

[Arxiv](https://arxiv.org/abs/2407.12784)