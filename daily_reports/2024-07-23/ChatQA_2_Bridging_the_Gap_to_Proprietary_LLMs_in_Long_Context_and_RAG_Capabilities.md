# ChatQA 2：跨越长上下文与RAG能力，连接专有LLM的桥梁
发布时间：2024年07月19日

`RAG`
> ChatQA 2: Bridging the Gap to Proprietary LLMs in Long Context and RAG Capabilities
>
> 我们推出的 ChatQA 2 模型，基于 Llama3，旨在提升开放访问 LLM 在长上下文理解和检索增强生成（RAG）方面的能力，使其与顶尖专有模型如 GPT-4-Turbo 相媲美。通过扩展 Llama3-70B-base 的上下文窗口至 128K 令牌，并实施三阶段指令调优，我们显著提升了模型处理大量信息的能力。实验显示，Llama3-ChatQA-2-70B 在长上下文理解任务上与 GPT-4-Turbo-2024-0409 不相上下，并在 RAG 测试中表现更佳。此外，我们发现先进的长上下文检索技术能有效解决 RAG 中的上下文碎片问题，进一步提升性能。我们还深入比较了 RAG 与长上下文解决方案的优劣，使用的是当前最先进的长上下文 LLM。
>
> https://arxiv.org/abs/2407.14482

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.14482/llama3_long_128k_370.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2407.14482](https://arxiv.org/abs/2407.14482)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 加入社群，公众号回复LLM
- 最新论文订阅体验：公众号号菜单回复1