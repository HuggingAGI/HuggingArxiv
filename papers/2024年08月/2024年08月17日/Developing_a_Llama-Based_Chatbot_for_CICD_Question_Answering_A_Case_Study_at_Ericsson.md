# 基于Llama的CI/CD问答聊天机器人开发：爱立信实践案例

发布时间：2024年08月17日

`RAG` `软件开发` `通信技术`

> Developing a Llama-Based Chatbot for CI/CD Question Answering: A Case Study at Ericsson

# 摘要

> 本文分享了我们在爱立信开发基于Llama的CI/CD问答聊天机器人的经验。该机器人采用RAG模型，专门针对爱立信的CI/CD文档特性，以提升回答的准确性和相关性。实证评估显示，结合BM25和嵌入检索器的集成检索器性能最佳。在与72个CI/CD问题和答案的基准对比中，我们的聊天机器人配置在61.11%的问题上提供了完全正确的答案，26.39%的问题上提供了部分正确的答案，12.50%的问题上提供了错误的答案。通过错误分析，我们探讨了不准确的原因，并提出了改进建议。此外，我们还总结了经验教训，并指出了未来提升聊天机器人准确性的方向。

> This paper presents our experience developing a Llama-based chatbot for question answering about continuous integration and continuous delivery (CI/CD) at Ericsson, a multinational telecommunications company. Our chatbot is designed to handle the specificities of CI/CD documents at Ericsson, employing a retrieval-augmented generation (RAG) model to enhance accuracy and relevance. Our empirical evaluation of the chatbot on industrial CI/CD-related questions indicates that an ensemble retriever, combining BM25 and embedding retrievers, yields the best performance. When evaluated against a ground truth of 72 CI/CD questions and answers at Ericsson, our most accurate chatbot configuration provides fully correct answers for 61.11% of the questions, partially correct answers for 26.39%, and incorrect answers for 12.50%. Through an error analysis of the partially correct and incorrect answers, we discuss the underlying causes of inaccuracies and provide insights for further refinement. We also reflect on lessons learned and suggest future directions for further improving our chatbot's accuracy.

[Arxiv](https://arxiv.org/abs/2408.09277)