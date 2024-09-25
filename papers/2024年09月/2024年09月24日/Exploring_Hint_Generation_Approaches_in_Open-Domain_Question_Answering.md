# 探究开放领域问答中的提示生成策略

发布时间：2024年09月24日

`LLM应用` `问答系统`

> Exploring Hint Generation Approaches in Open-Domain Question Answering

# 摘要

> 自动问答系统依赖上下文信息提供准确答案，通常通过检索或生成方式准备上下文。本文介绍了一种名为 HINTQA 的新方法，利用自动提示生成技术，让 LLM 生成潜在答案的提示而非相关上下文。我们在 TriviaQA、NaturalQuestions 和 Web Questions 三个数据集上评估，发现提示的数量和顺序显著影响性能。结果显示，HINTQA 优于传统检索和生成方法，提示比检索和生成的上下文更能提升答案准确性。

> Automatic Question Answering (QA) systems rely on contextual information to provide accurate answers. Commonly, contexts are prepared through either retrieval-based or generation-based methods. The former involves retrieving relevant documents from a corpus like Wikipedia, whereas the latter uses generative models such as Large Language Models (LLMs) to generate the context. In this paper, we introduce a novel context preparation approach called HINTQA, which employs Automatic Hint Generation (HG) techniques. Unlike traditional methods, HINTQA prompts LLMs to produce hints about potential answers for the question rather than generating relevant context. We evaluate our approach across three QA datasets including TriviaQA, NaturalQuestions, and Web Questions, examining how the number and order of hints impact performance. Our findings show that the HINTQA surpasses both retrieval-based and generation-based approaches. We demonstrate that hints enhance the accuracy of answers more than retrieved and generated contexts.

[Arxiv](https://arxiv.org/abs/2409.16096)