# 探索直截了当的对话式红队策略

发布时间：2024年09月07日

`LLM应用` `网络安全`

> Exploring Straightforward Conversational Red-Teaming

# 摘要

> LLM 在商业对话系统中的应用日益广泛，但同时也带来了安全和伦理风险。在多轮对话中，上下文的影响可能导致模型产生不希望的响应。本文探讨了现成 LLM 在红队测试中的有效性，比较了单轮和多轮对话策略。实验表明，现成模型能有效进行红队测试，甚至能根据过往经验调整策略，但随着模型对齐程度的提高，其有效性会降低。

> Large language models (LLMs) are increasingly used in business dialogue systems but they pose security and ethical risks. Multi-turn conversations, where context influences the model's behavior, can be exploited to produce undesired responses. In this paper, we examine the effectiveness of utilizing off-the-shelf LLMs in straightforward red-teaming approaches, where an attacker LLM aims to elicit undesired output from a target LLM, comparing both single-turn and conversational red-teaming tactics. Our experiments offer insights into various usage strategies that significantly affect their performance as red teamers. They suggest that off-the-shelf models can act as effective red teamers and even adjust their attack strategy based on past attempts, although their effectiveness decreases with greater alignment.

[Arxiv](https://arxiv.org/abs/2409.04822)