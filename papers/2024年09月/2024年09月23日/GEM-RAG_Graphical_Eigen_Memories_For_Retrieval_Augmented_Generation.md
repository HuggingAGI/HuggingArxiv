# GEM-RAG：一种利用图形特征记忆进行检索增强生成的新方法

发布时间：2024年09月23日

`RAG` `人工智能` `问答系统`

> GEM-RAG: Graphical Eigen Memories For Retrieval Augmented Generation

# 摘要

> 记忆的形成、检索和推理能力是通用智能的基石，使实体能够学习、适应并拥有直觉洞察力。大型语言模型 (LLM) 在适当记忆或上下文的辅助下，已展现出推理和响应刺激的能力。然而，它们在记忆的编码、存储和检索方面仍显不足，这限制了它们作为 AI 代理的全部潜力，尤其是在特定领域的专业化方面。为此，检索增强生成 (RAG) 成为一个有前景的研究方向，旨在通过提供丰富的上下文信息来增强 LLM。在问答 (QA) 应用中，RAG 方法将文本分块嵌入，并利用文本嵌入检索最相关的块。受人类记忆机制的启发，我们提出改进标准 RAG 方法，通过生成和编码更高层次的信息，并根据其回答问题的效用对文本块进行标记。我们引入了图形特征记忆用于检索增强生成 (GEM-RAG)。GEM-RAG 通过 LLM 生成的“效用”问题标记文本块，基于文本和效用问题的相似性构建图结构，并利用图的特征分解生成高层次的摘要节点，捕捉文本的主要主题。我们在两个标准 QA 任务上，使用 UnifiedQA 和 GPT-3.5 Turbo 结合 SBERT 和 OpenAI 的文本编码器，评估了 GEM-RAG，结果表明 GEM-RAG 在这些任务上优于其他最先进的 RAG 方法。此外，我们还探讨了强大 RAG 系统的意义及未来发展方向。

> The ability to form, retrieve, and reason about memories in response to stimuli serves as the cornerstone for general intelligence - shaping entities capable of learning, adaptation, and intuitive insight. Large Language Models (LLMs) have proven their ability, given the proper memories or context, to reason and respond meaningfully to stimuli. However, they are still unable to optimally encode, store, and retrieve memories - the ability to do this would unlock their full ability to operate as AI agents, and to specialize to niche domains. To remedy this, one promising area of research is Retrieval Augmented Generation (RAG), which aims to augment LLMs by providing them with rich in-context examples and information. In question-answering (QA) applications, RAG methods embed the text of interest in chunks, and retrieve the most relevant chunks for a prompt using text embeddings. Motivated by human memory encoding and retrieval, we aim to improve over standard RAG methods by generating and encoding higher-level information and tagging the chunks by their utility to answer questions. We introduce Graphical Eigen Memories For Retrieval Augmented Generation (GEM-RAG). GEM-RAG works by tagging each chunk of text in a given text corpus with LLM generated ``utility'' questions, connecting chunks in a graph based on the similarity of both their text and utility questions, and then using the eigendecomposition of the memory graph to build higher level summary nodes that capture the main themes of the text. We evaluate GEM-RAG, using both UnifiedQA and GPT-3.5 Turbo as the LLMs, with SBERT, and OpenAI's text encoders on two standard QA tasks, showing that GEM-RAG outperforms other state-of-the-art RAG methods on these tasks. We also discuss the implications of having a robust RAG system and future directions.

[Arxiv](https://arxiv.org/abs/2409.15566)