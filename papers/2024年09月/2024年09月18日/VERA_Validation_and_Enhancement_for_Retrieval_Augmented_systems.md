# VERA：检索增强系统的验证与提升

发布时间：2024年09月18日

`RAG` `信息检索`

> VERA: Validation and Enhancement for Retrieval Augmented systems

# 摘要

> 大型语言模型 (LLM) 虽然能力出众，但常因依赖内置知识而产生不准确答案。检索增强生成 (RAG) 通过引入外部信息检索系统，为查询提供额外上下文，以减少特定情境下的不准确性。然而，准确性问题依旧存在，模型可能依赖无关文档或错误推断。为提升 RAG 框架中检索系统与 LLM 的性能，我们提出 \textbf{VERA} (\textbf{V}alidation and \textbf{E}nhancement for \textbf{R}etrieval \textbf{A}ugmented systems)，该系统旨在：1) 在生成响应前评估并增强检索上下文，2) 评估并优化 LLM 生成的响应，确保精确无误。VERA 采用评估兼增强的 LLM，首先判断是否需外部检索，评估检索内容的相关性与冗余，并优化以剔除非必要信息。生成响应后，VERA 将其分解为原子陈述，评估其与查询的相关性，确保符合上下文。实验显示，VERA 不仅提升小规模开源模型性能，对大规模最先进模型亦有显著效果。这些改进凸显 VERA 在生成准确相关响应方面的潜力，推动检索增强语言建模的最新进展。VERA 结合多重评估与优化步骤，有效减少幻觉，优化检索与响应过程，成为信息生成中追求高准确性与可靠性的应用之宝贵工具。

> Large language models (LLMs) exhibit remarkable capabilities but often produce inaccurate responses, as they rely solely on their embedded knowledge. Retrieval-Augmented Generation (RAG) enhances LLMs by incorporating an external information retrieval system, supplying additional context along with the query to mitigate inaccuracies for a particular context. However, accuracy issues still remain, as the model may rely on irrelevant documents or extrapolate incorrectly from its training knowledge. To assess and improve the performance of both the retrieval system and the LLM in a RAG framework, we propose \textbf{VERA} (\textbf{V}alidation and \textbf{E}nhancement for \textbf{R}etrieval \textbf{A}ugmented systems), a system designed to: 1) Evaluate and enhance the retrieved context before response generation, and 2) Evaluate and refine the LLM-generated response to ensure precision and minimize errors. VERA employs an evaluator-cum-enhancer LLM that first checks if external retrieval is necessary, evaluates the relevance and redundancy of the retrieved context, and refines it to eliminate non-essential information. Post-response generation, VERA splits the response into atomic statements, assesses their relevance to the query, and ensures adherence to the context. Our experiments demonstrate VERA's remarkable efficacy not only in improving the performance of smaller open-source models, but also larger state-of-the art models. These enhancements underscore VERA's potential to produce accurate and relevant responses, advancing the state-of-the-art in retrieval-augmented language modeling. VERA's robust methodology, combining multiple evaluation and refinement steps, effectively mitigates hallucinations and improves retrieval and response processes, making it a valuable tool for applications demanding high accuracy and reliability in information generation. .

[Arxiv](https://arxiv.org/abs/2409.15364)