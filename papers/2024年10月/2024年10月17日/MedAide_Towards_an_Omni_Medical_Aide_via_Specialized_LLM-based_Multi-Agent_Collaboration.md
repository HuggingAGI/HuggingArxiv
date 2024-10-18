# MedAide：借助基于 LLM 的专门化多代理协作，迈向全方位医疗助手

发布时间：2024年10月17日

`Agent` `人工智能`

> MedAide: Towards an Omni Medical Aide via Specialized LLM-based Multi-Agent Collaboration

# 摘要

> 在医疗领域，LLM 驱动的交互系统虽有潜力，但常因缺乏个性化推荐和诊断分析而陷入困境。为此，我们推出了 MedAide，一个基于 LLM 的全方位医疗多代理协作框架。MedAide 通过检索增强生成重写查询，精准理解医疗意图，并利用上下文编码器生成意图原型嵌入，通过相似性匹配识别细粒度意图。根据意图相关性，各代理协同工作，提供综合决策分析。实验结果显示，MedAide 不仅超越了现有 LLM，还显著提升了医疗专业知识和战略推理能力。

> Large Language Model (LLM)-driven interactive systems currently show potential promise in healthcare domains. Despite their remarkable capabilities, LLMs typically lack personalized recommendations and diagnosis analysis in sophisticated medical applications, causing hallucinations and performance bottlenecks. To address these challenges, this paper proposes MedAide, an LLM-based omni medical multi-agent collaboration framework for specialized healthcare services. Specifically, MedAide first performs query rewriting through retrieval-augmented generation to accomplish accurate medical intent understanding. Immediately, we devise a contextual encoder to obtain intent prototype embeddings, which are used to recognize fine-grained intents by similarity matching. According to the intent relevance, the activated agents collaborate effectively to provide integrated decision analysis. Extensive experiments are conducted on four medical benchmarks with composite intents. Experimental results from automated metrics and expert doctor evaluations show that MedAide outperforms current LLMs and improves their medical proficiency and strategic reasoning.

[Arxiv](https://arxiv.org/abs/2410.12532)