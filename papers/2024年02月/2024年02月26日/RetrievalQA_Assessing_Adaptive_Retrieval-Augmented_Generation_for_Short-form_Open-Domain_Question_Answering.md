# [RetrievalQA 项目旨在测评适应性检索增强技术在短篇开放领域问答任务上的表现。这项研究关注于利用检索技术提升生成式模型解答问题的能力，在开放式问题回答场景下，探索检索增强生成的有效性和适用性。](https://arxiv.org/abs/2402.16457)

发布时间：2024年02月26日

`ARAG`

> RetrievalQA: Assessing Adaptive Retrieval-Augmented Generation for Short-form Open-Domain Question Answering

> ARAG技术旨在智能判断针对不同查询是否需要检索，从而提升信息获取的相关性和效率，但以往研究对此类方法的评估并不充分。为此，本研究构建了一个名为RetrievalQA的基准评测，它包含1,271道涵盖新颖及长尾知识的短问题，其中的问题答案超出了LLMs的知识范围，必须借助外部信息源解答。这样的设计使RetrievalQA成为了检验现有ARAG方法的理想平台。通过分析发现，依赖阈值调节的校准方法存在局限性，而常规的提示方式无法有效引导LLMs作出精准的检索判断。因此，我们根据这些发现创新性地提出了时间感知自适应检索策略（TA-ARE），这一简洁高效的方法能够在不经过校准或额外训练的情况下辅助LLMs判断何时进行检索操作。相关的数据集和代码将公开在GitHub仓库<https://github.com/hyintell/RetrievalQA>中。

> Adaptive retrieval-augmented generation (ARAG) aims to dynamically determine the necessity of retrieval for queries instead of retrieving indiscriminately to enhance the efficiency and relevance of the sourced information. However, previous works largely overlook the evaluation of ARAG approaches, leading to their effectiveness being understudied. This work presents a benchmark, RetrievalQA, comprising 1,271 short-form questions covering new world and long-tail knowledge. The knowledge necessary to answer the questions is absent from LLMs; therefore, external information must be retrieved to answer correctly. This makes RetrievalQA a suitable testbed to evaluate existing ARAG methods. We observe that calibration-based methods heavily rely on threshold tuning, while vanilla prompting is inadequate for guiding LLMs to make reliable retrieval decisions. Based on our findings, we propose Time-Aware Adaptive Retrieval (TA-ARE), a simple yet effective method that helps LLMs assess the necessity of retrieval without calibration or additional training. The dataset and code will be available at \url{https://github.com/hyintell/RetrievalQA}

[Arxiv](https://arxiv.org/abs/2402.16457)