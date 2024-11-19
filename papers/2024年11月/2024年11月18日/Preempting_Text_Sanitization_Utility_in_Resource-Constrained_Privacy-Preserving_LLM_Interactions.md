# 在资源受限的隐私保护 LLM 交互中抢先运用文本清理实用程序

发布时间：2024年11月18日

`LLM应用` `隐私保护` `在线服务`

> Preempting Text Sanitization Utility in Resource-Constrained Privacy-Preserving LLM Interactions

# 摘要

> 个人在工作和生活中与在线大型语言模型（LLMs）的交互日益频繁。这些交互引发了隐私问题，毕竟LLMs通常由第三方托管，他们能够收集用户及其所属公司的各类敏感信息。文献中已提出文本净化技术，可在将用户提示发送给LLM前对其进行净化处理。然而，净化会影响LLM执行的下游任务，其程度往往会给用户带来无法接受的结果。这可不只是小麻烦，因为LLM服务按使用次数收费，还会浪费大量计算资源，显然会造成金钱损失。我们提出一种架构，借助用户端的小型语言模型（SLM），在将提示发送给LLM之前预估净化的影响，从而避免资源损失。
  我们对该架构的评估揭示了基于差分隐私的文本净化存在的重大问题，希望能引起社区关注以作进一步探究。

> Individuals have been increasingly interacting with online Large Language Models (LLMs), both in their work and personal lives. These interactions raise privacy issues as the LLMs are typically hosted by third-parties who can gather a variety of sensitive information about users and their companies. Text Sanitization techniques have been proposed in the literature and can be used to sanitize user prompts before sending them to the LLM. However, sanitization has an impact on the downstream task performed by the LLM, and often to such an extent that it leads to unacceptable results for the user. This is not just a minor annoyance, with clear monetary consequences as LLM services charge on a per use basis as well as great amount of computing resources wasted. We propose an architecture leveraging a Small Language Model (SLM) at the user-side to help estimate the impact of sanitization on a prompt before it is sent to the LLM, thus preventing resource losses.
  Our evaluation of this architecture revealed a significant problem with text sanitization based on Differential Privacy, on which we want to draw the attention of the community for further investigation.

[Arxiv](https://arxiv.org/abs/2411.11521)