# 基于Llama的CI/CD问答聊天机器人开发：爱立信实践案例
发布时间：2024年08月17日


> Developing a Llama-Based Chatbot for CI/CD Question Answering: A Case Study at Ericsson
>
> 本文分享了我们在爱立信开发基于Llama的CI/CD问答聊天机器人的经验。该机器人采用RAG模型，专门针对爱立信的CI/CD文档特性，以提升回答的准确性和相关性。实证评估显示，结合BM25和嵌入检索器的集成检索器性能最佳。在与72个CI/CD问题和答案的基准对比中，我们的聊天机器人配置在61.11%的问题上提供了完全正确的答案，26.39%的问题上提供了部分正确的答案，12.50%的问题上提供了错误的答案。通过错误分析，我们探讨了不准确的原因，并提出了改进建议。此外，我们还总结了经验教训，并指出了未来提升聊天机器人准确性的方向。
>
> https://arxiv.org/abs/2408.09277

**点击公众号菜单加入大语言模型论文讨论**
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2408.09277](https://arxiv.org/abs/2408.09277)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)