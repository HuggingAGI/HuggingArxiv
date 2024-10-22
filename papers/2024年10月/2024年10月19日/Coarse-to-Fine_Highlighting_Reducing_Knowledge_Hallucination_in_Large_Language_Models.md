# 从粗到细的突出显示：减少大型语言模型中的知识幻觉

发布时间：2024年10月19日

`RAG` `人工智能`

> Coarse-to-Fine Highlighting: Reducing Knowledge Hallucination in Large Language Models

# 摘要

> 生成看似合理但错误的事实信息（即幻觉）引起了广泛研究兴趣。检索增强语言模型 (RALM) 通过提供最新知识来减少幻觉，但现有 RALM 在处理长上下文时可能加剧幻觉。为此，我们提出 COFT，一种从粗到细的高亮方法，专注于不同粒度级别的关键文本，避免在长上下文中迷失。COFT 包含召回器、评分器和选择器三个组件：召回器提取潜在关键实体，评分器衡量其重要性，选择器以动态阈值算法高亮关键段落、句子或单词。实验表明，COFT 在 F1 分数上领先 30%，并在阅读理解和问答等长篇任务中表现出色。

> Generation of plausible but incorrect factual information, often termed hallucination, has attracted significant research interest. Retrieval-augmented language model (RALM) -- which enhances models with up-to-date knowledge -- emerges as a promising method to reduce hallucination. However, existing RALMs may instead exacerbate hallucination when retrieving lengthy contexts. To address this challenge, we propose COFT, a novel \textbf{CO}arse-to-\textbf{F}ine highligh\textbf{T}ing method to focus on different granularity-level key texts, thereby avoiding getting lost in lengthy contexts. Specifically, COFT consists of three components: \textit{recaller}, \textit{scorer}, and \textit{selector}. First, \textit{recaller} applies a knowledge graph to extract potential key entities in a given context. Second, \textit{scorer} measures the importance of each entity by calculating its contextual weight. Finally, \textit{selector} selects high contextual weight entities with a dynamic threshold algorithm and highlights the corresponding paragraphs, sentences, or words in a coarse-to-fine manner. Extensive experiments on the knowledge hallucination benchmark demonstrate the effectiveness of COFT, leading to a superior performance over $30\%$ in the F1 score metric. Moreover, COFT also exhibits remarkable versatility across various long-form tasks, such as reading comprehension and question answering.

[Arxiv](https://arxiv.org/abs/2410.15116)