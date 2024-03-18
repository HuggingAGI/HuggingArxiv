# [本研究探讨如何巧妙利用上下文提示，将知识有效地融入大型语言模型中。]

发布时间：2024年03月03日

`LLM应用`

> Infusing Knowledge into Large Language Models with Contextual Prompts

> 知识注入作为一种提升大型语言模型在特定领域NLP任务上的表现力的有效途径，无需从零开始大规模预训练，更具潜力。以往增强LLM的方法常常需要借助已有知识图谱提供的额外预训练或知识提示，但这种方法在很多场景下并不现实。相反，直接从相关的文档中提取并注入知识更为普适，不仅减少了对结构化知识图谱的依赖，还能有效服务于那些鲜少出现在任何知识图谱中的实体。因此，我们提出一种源自输入文本上下文的、简洁且易于推广的知识注入策略。实验证明，通过检验微调后的LLM，该方法确实行之有效。

> Knowledge infusion is a promising method for enhancing Large Language Models for domain-specific NLP tasks rather than pre-training models over large data from scratch. These augmented LLMs typically depend on additional pre-training or knowledge prompts from an existing knowledge graph, which is impractical in many applications. In contrast, knowledge infusion directly from relevant documents is more generalisable and alleviates the need for structured knowledge graphs while also being useful for entities that are usually not found in any knowledge graph. With this motivation, we propose a simple yet generalisable approach for knowledge infusion by generating prompts from the context in the input text. Our experiments show the effectiveness of our approach which we evaluate by probing the fine-tuned LLMs.

[Arxiv](https://arxiv.org/abs/2403.01481)