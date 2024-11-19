# QCG-Rerank：旅游领域中在检索增强型大型语言模型里采用查询扩展的块图重排序

发布时间：2024年11月04日

`RAG` `信息检索`

> QCG-Rerank: Chunks Graph Rerank with Query Expansion in Retrieval-Augmented LLMs for Tourism Domain

# 摘要

> 检索增强生成（RAG）借助整合信息检索技术，减轻了大型语言模型（LLMs）中的幻觉问题。然而，在旅游领域，鉴于查询通常简短，数据库内容又繁杂多样，现有的 RAG 在检索后可能会含有大量不相关或相互矛盾的信息内容。为应对此挑战，我们提出了 QCG-Rerank 模型。该模型先是进行初始检索获取候选块，接着通过提取关键信息来拓展原始查询以增强语义。而后，利用扩展后的查询和候选块计算相似度得分作为初始转移概率，并构建块图。紧接着，基于初始估计反复计算转移概率直至收敛。选取得分最高的块输入到 LLMs 中生成响应。我们在 Cultour、IIRC、StrategyQA、HotpotQA、SQuAD 和 MuSiQue 数据集上对该模型进行评估。实验结果表明，QCG-Rerank 方法有效且优越。

> Retrieval-Augmented Generation (RAG) mitigates the issue of hallucination in Large Language Models (LLMs) by integrating information retrieval techniques. However, in the tourism domain, since the query is usually brief and the content in the database is diverse, existing RAG may contain a significant amount of irrelevant or contradictory information contents after retrieval. To address this challenge, we propose the QCG-Rerank model. This model first performs an initial retrieval to obtain candidate chunks and then enhances semantics by extracting critical information to expand the original query. Next, we utilize the expanded query and candidate chunks to calculate similarity scores as the initial transition probability and construct the chunks graph. Subsequently, We iteratively compute the transition probabilities based on an initial estimate until convergence. The chunks with the highest score are selected and input into the LLMs to generate responses. We evaluate the model on Cultour, IIRC, StrategyQA, HotpotQA, SQuAD, and MuSiQue datasets. The experimental results demonstrate the effectiveness and superiority of the QCG-Rerank method.

[Arxiv](https://arxiv.org/abs/2411.08724)