# Parrot：借助语义变量，高效支持基于大型语言模型的应用服务
发布时间：2024年05月30日

`Agent应用`
> Parrot: Efficient Serving of LLM-based Applications with Semantic Variable
>
> 随着大型语言模型（LLMs）的兴起，基于LLM的应用程序（AI代理或副驾驶）应运而生，这是一种融合了LLM与传统软件优势的新型软件范式。这些应用程序能够通过多个LLM请求构建复杂的工作流程，以完成任务。然而，受限于公共LLM服务提供的简化请求级API，它们无法保留关键的应用级信息。这导致公共LLM服务只能孤立地优化单个请求，从而影响了LLM应用的整体性能。本论文推出的Parrot系统，专注于提升基于LLM的应用程序的端到端体验。Parrot引入了语义变量（Semantic Variable），这一创新抽象使得应用级知识能够被公共LLM服务所利用。语义变量在请求提示中标记输入输出变量，并在多个LLM请求间建立数据流，为LLM应用的编程提供了一种直观方法。通过向公共LLM服务开放语义变量，可以进行数据流分析，揭示请求间的内在联系，从而为LLM应用的整体性能优化开辟新途径。实验证明，Parrot能为LLM应用的实际场景带来显著的性能提升。
>
> https://arxiv.org/abs/2405.19888

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19888/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19888/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19888/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19888/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19888/multiagent.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19888/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19888/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19888/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19888/x8.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19888/x9.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19888/x10.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19888/x11.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19888/x12.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19888/x13.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19888/x14.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19888/x15.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19888/x16.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19888/x17.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19888/x18.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19888/x19.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19888/x20.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19888/x21.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19888/x22.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19888/x23.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19888/x24.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19888/x25.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19888/x26.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19888/x27.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19888/x28.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2405.19888](https://arxiv.org/abs/2405.19888)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886