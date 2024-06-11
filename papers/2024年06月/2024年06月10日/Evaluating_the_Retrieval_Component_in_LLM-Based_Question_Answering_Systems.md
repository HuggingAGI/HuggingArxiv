# 探究大型语言模型问答系统中检索组件的效能评估

发布时间：2024年06月10日

`RAG

理由：这篇论文主要关注的是基于RAG（Retrieval-Augmented Generation）模型的问答系统中的检索器评估问题。它提出了一种新的评估框架，旨在更准确地评估检索器在聊天机器人中的表现，这与RAG模型的应用紧密相关。虽然论文涉及了LLM（大型语言模型）的应用，但其核心贡献在于改进RAG模型中的检索器评估，因此更适合归类为RAG。` `聊天机器人` `问答系统`

> Evaluating the Retrieval Component in LLM-Based Question Answering Systems

# 摘要

> 基于LLMs的问答系统（QA）依赖检索组件获取特定领域信息，以避免生成错误或幻觉的回答。尽管检索器评估源自信息检索早期研究，但在LLM聊天机器人中的应用仍具挑战。本研究提出了一种简明的基线，用于评估基于RAG的聊天机器人中的检索器。研究显示，该评估框架更准确地描绘了检索器的表现，并与QA系统的整体性能更为契合。传统评估指标如精确度、召回率和F1分数可能不足以全面评估LLMs，因为即便检索不完美，LLMs仍能给出准确回答。我们的方法则考虑了LLMs的优势，能够排除无关上下文，并识别回答中的潜在错误和幻觉。

> Question answering systems (QA) utilizing Large Language Models (LLMs) heavily depend on the retrieval component to provide them with domain-specific information and reduce the risk of generating inaccurate responses or hallucinations. Although the evaluation of retrievers dates back to the early research in Information Retrieval, assessing their performance within LLM-based chatbots remains a challenge.
  This study proposes a straightforward baseline for evaluating retrievers in Retrieval-Augmented Generation (RAG)-based chatbots. Our findings demonstrate that this evaluation framework provides a better image of how the retriever performs and is more aligned with the overall performance of the QA system. Although conventional metrics such as precision, recall, and F1 score may not fully capture LLMs' capabilities - as they can yield accurate responses despite imperfect retrievers - our method considers LLMs' strengths to ignore irrelevant contexts, as well as potential errors and hallucinations in their responses.

[Arxiv](https://arxiv.org/abs/2406.06458)