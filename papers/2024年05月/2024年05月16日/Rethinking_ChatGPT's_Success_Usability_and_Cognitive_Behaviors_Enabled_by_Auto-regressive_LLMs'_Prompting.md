# 反思 ChatGPT 的成功：自回归 LLM 提示技术如何激发可用性与认知行为

发布时间：2024年05月16日

`LLM理论

这篇论文主要探讨了大型语言模型（LLMs），特别是自回归LLMs（AR-LLMs）的提示范式，以及它们在模态结构、任务可定制性、透明度和复杂性等方面的表现。文章深入分析了LLMs在特定任务通道中的应用，并探讨了自由形式文本与口头上下文如何影响LLMs的认知行为，以及这些模型如何模仿人类语言表达。此外，论文还基于认知行为理论，展望了LLMs在自主代理及多代理系统中的应用潜力。这些内容主要涉及LLMs的理论分析和认知行为研究，因此归类为LLM理论。` `人工智能` `认知科学`

> Rethinking ChatGPT's Success: Usability and Cognitive Behaviors Enabled by Auto-regressive LLMs' Prompting

# 摘要

> 过去十年见证了大型语言模型（LLMs）训练与部署策略的多样化发展，其中自回归LLMs（AR-LLMs）的提示范式极大地推动了AI领域的进步。本文强调了自由形式模态（输入输出形式）与口头自由形式上下文在用户导向通道（模态转换方法）中的关键作用。我们深入分析了两种LLMs及六个特定任务通道在部署中的模态结构，并从用户视角出发，运用任务可定制性、透明度与复杂性等指标，凸显了AR-LLMs提示范式的优越性。同时，我们探讨了自由形式文本与口头上下文如何激发LLMs的多样认知行为，模拟人类语言表达。文章还详述了四种典型认知行为，展示了AR-LLMs如何通过自由形式模态与通道，成功模仿人类行为。最后，基于认知行为理论，我们展望了LLMs在自主代理及多代理系统中部署的优化潜力。

> Over the last decade, a wide range of training and deployment strategies for Large Language Models (LLMs) have emerged. Among these, the prompting paradigms of Auto-regressive LLMs (AR-LLMs) have catalyzed a significant surge in Artificial Intelligence (AI). This paper aims to emphasize the significance of utilizing free-form modalities (forms of input and output) and verbal free-form contexts as user-directed channels (methods for transforming modalities) for downstream deployment. Specifically, we analyze the structure of modalities within both two types of LLMs and six task-specific channels during deployment. From the perspective of users, our analysis introduces and applies the analytical metrics of task customizability, transparency, and complexity to gauge their usability, highlighting the superior nature of AR-LLMs' prompting paradigms. Moreover, we examine the stimulation of diverse cognitive behaviors in LLMs through the adoption of free-form text and verbal contexts, mirroring human linguistic expressions of such behaviors. We then detail four common cognitive behaviors to underscore how AR-LLMs' prompting successfully imitate human-like behaviors using this free-form modality and channel. Lastly, the potential for improving LLM deployment, both as autonomous agents and within multi-agent systems, is identified via cognitive behavior concepts and principles.

[Arxiv](https://arxiv.org/abs/2405.10474)