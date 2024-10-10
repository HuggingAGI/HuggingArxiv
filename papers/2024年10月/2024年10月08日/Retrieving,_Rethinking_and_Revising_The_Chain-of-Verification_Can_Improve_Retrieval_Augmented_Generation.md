# 通过检索、重新思考和修订的验证链，能够显著提升检索增强生成的质量。

发布时间：2024年10月08日

`RAG` `人工智能`

> Retrieving, Rethinking and Revising: The Chain-of-Verification Can Improve Retrieval Augmented Generation

# 摘要

> 最新的检索增强生成 (RAG) 技术试图通过整合外部知识来提升大型语言模型 (LLM) 的性能。然而，这种方法存在两大难题：一是原始查询可能无法精准检索，导致上下文知识错误；二是语言模型因知识边界限制，容易生成与外部参考不符的答案。为此，我们提出了链式验证 (CoV-RAG)，旨在提升外部检索的准确性和内部生成的连贯性。具体而言，我们在 RAG 中嵌入验证模块，进行评分、判断和重写。对于外部检索错误，CoV-RAG 通过修订查询获取新知识；对于内部生成错误，我们通过思维链 (CoT) 推理在训练中统一 QA 和验证任务。我们的实验结果显示，CoV-RAG 在不同 LLM 骨干下，均能显著超越现有最先进基线，展现出强大的适应性和有效性。

> Recent Retrieval Augmented Generation (RAG) aims to enhance Large Language Models (LLMs) by incorporating extensive knowledge retrieved from external sources. However, such approach encounters some challenges: Firstly, the original queries may not be suitable for precise retrieval, resulting in erroneous contextual knowledge; Secondly, the language model can easily generate inconsistent answer with external references due to their knowledge boundary limitation. To address these issues, we propose the chain-of-verification (CoV-RAG) to enhance the external retrieval correctness and internal generation consistency. Specifically, we integrate the verification module into the RAG, engaging in scoring, judgment, and rewriting. To correct external retrieval errors, CoV-RAG retrieves new knowledge using a revised query. To correct internal generation errors, we unify QA and verification tasks with a Chain-of-Thought (CoT) reasoning during training. Our comprehensive experiments across various LLMs demonstrate the effectiveness and adaptability compared with other strong baselines. Especially, our CoV-RAG can significantly surpass the state-of-the-art baselines using different LLM backbones.

[Arxiv](https://arxiv.org/abs/2410.05801)