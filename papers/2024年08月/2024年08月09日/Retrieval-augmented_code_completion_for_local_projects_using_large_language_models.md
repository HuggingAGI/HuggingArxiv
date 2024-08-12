# 利用大型语言模型为本地项目提供增强检索的代码补全功能

发布时间：2024年08月09日

`LLM应用` `软件开发` `人工智能`

> Retrieval-augmented code completion for local projects using large language models

# 摘要

> 随着 LLM 在软件开发领域的普及，隐私和计算需求成为商业解决方案中的难题。为此，我们探索了适用于本地执行和增强的 1.6 亿参数 LLM。通过在开源 Python 代码上训练 GPT-2 和 RETRO 模型，我们验证了基于向量嵌入检索的优势。进一步地，我们采用 In-context 检索增强生成技术，根据令牌的 Jaccard 相似性检索代码片段，提升了模型性能。实验表明，尽管方法简单，但在处理更大模型时，这种方法比 RETRO 架构更为有效。我们强调，在代码完成任务中，适当的令牌化是释放 LLM 潜力的关键。

> The use of large language models (LLMs) is becoming increasingly widespread among software developers. However, privacy and computational requirements are problematic with commercial solutions and the use of LLMs. In this work, we focus on using LLMs with around 160 million parameters that are suitable for local execution and augmentation with retrieval from local projects. We train two models based on the transformer architecture, the generative model GPT-2 and the retrieval-adapted RETRO model, on open-source Python files, and empirically evaluate and compare them, confirming the benefits of vector embedding based retrieval. Further, we improve our models' performance with In-context retrieval-augmented generation, which retrieves code snippets based on the Jaccard similarity of tokens. We evaluate In-context retrieval-augmented generation on larger models and conclude that, despite its simplicity, the approach is more suitable than using the RETRO architecture. We highlight the key role of proper tokenization in achieving the full potential of LLMs in code completion.

[Arxiv](https://arxiv.org/abs/2408.05026)