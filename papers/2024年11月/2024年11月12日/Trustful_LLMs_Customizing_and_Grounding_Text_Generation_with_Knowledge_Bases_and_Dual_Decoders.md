# 可信的大型语言模型：使用知识库和双解码器定制和扎根文本生成

发布时间：2024年11月12日

`RAG` `语言模型` `内容生成`

> Trustful LLMs: Customizing and Grounding Text Generation with Knowledge Bases and Dual Decoders

# 摘要

> 虽然人们对大型语言模型的内容生成技能印象深刻，但像 ChatGPT 这样的大型语言模型的使用受到内容的领域基础的限制。生成内容的正确性和基础需要基于经过验证的上下文，例如来自检索增强生成（RAG）的结果。在将大型语言模型适应自定义领域时，一个重要的问题是生成的响应往往不完整，或者添加的内容未经核实，甚至可能是幻觉。先前关于幻觉检测的研究集中在评估指标上，这些指标不容易适应动态领域，并且可能容易受到像越狱这样的攻击。在这项工作中，我们提出 1）一种利用 RAG 上下文中的知识三元组来纠正幻觉的后处理算法，以及 2）一个融合 RAG 上下文以指导生成过程的双解码器模型。

> Although people are impressed by the content generation skills of large language models, the use of LLMs, such as ChatGPT, is limited by the domain grounding of the content. The correctness and groundedness of the generated content need to be based on a verified context, such as results from Retrieval-Augmented Generation (RAG). One important issue when adapting LLMs to a customized domain is that the generated responses are often incomplete, or the additions are not verified and may even be hallucinated. Prior studies on hallucination detection have focused on evaluation metrics, which are not easily adaptable to dynamic domains and can be vulnerable to attacks like jail-breaking. In this work, we propose 1) a post-processing algorithm that leverages knowledge triplets in RAG context to correct hallucinations and 2) a dual-decoder model that fuses RAG context to guide the generation process.

[Arxiv](https://arxiv.org/abs/2411.07870)