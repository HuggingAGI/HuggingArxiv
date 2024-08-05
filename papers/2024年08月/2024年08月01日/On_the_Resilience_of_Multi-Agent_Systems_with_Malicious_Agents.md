# 探讨恶意代理存在下的多代理系统韧性

发布时间：2024年08月01日

`Agent` `人工智能` `网络安全`

> On the Resilience of Multi-Agent Systems with Malicious Agents

# 摘要

> 由大型语言模型驱动的多智能体系统，通过专家智能体的协作，在多个领域展现出卓越能力。然而，单独部署时，系统可能面临恶意智能体的威胁，这些智能体生成难以察觉的错误结果。本文深入探讨了两个关键问题：在恶意智能体影响下，不同结构的多智能体系统的韧性表现；以及如何增强系统对恶意智能体的防御能力。我们通过AutoTransform和AutoInject方法模拟恶意智能体，并在代码生成、数学问题、翻译和文本评估等任务上进行了全面实验。实验结果显示，层级结构A$\rightarrow$(B$\leftrightarrow$C)的韧性最佳，性能仅下降$23.6\%$，远低于其他结构的$46.4\%$和$49.8\%$。此外，通过引入审查机制或挑战机制，我们证明了提升系统韧性的可行性。相关代码和数据已公开在https://github.com/CUHK-ARISE/MAS-Resilience。

> Multi-agent systems, powered by large language models, have shown great abilities across various tasks due to the collaboration of expert agents, each focusing on a specific domain. However, when agents are deployed separately, there is a risk that malicious users may introduce malicious agents who generate incorrect or irrelevant results that are too stealthy to be identified by other non-specialized agents. Therefore, this paper investigates two essential questions: (1) What is the resilience of various multi-agent system structures (e.g., A$\rightarrow$B$\rightarrow$C, A$\leftrightarrow$B$\leftrightarrow$C) under malicious agents, on different downstream tasks? (2) How can we increase system resilience to defend against malicious agents? To simulate malicious agents, we devise two methods, AutoTransform and AutoInject, to transform any agent into a malicious one while preserving its functional integrity. We run comprehensive experiments on four downstream multi-agent systems tasks, namely code generation, math problems, translation, and text evaluation. Results suggest that the "hierarchical" multi-agent structure, i.e., A$\rightarrow$(B$\leftrightarrow$C), exhibits superior resilience with the lowest performance drop of $23.6\%$, compared to $46.4\%$ and $49.8\%$ of other two structures. Additionally, we show the promise of improving multi-agent system resilience by demonstrating that two defense methods, introducing an additional agent to review and correct messages or mechanisms for each agent to challenge others' outputs, can enhance system resilience. Our code and data are available at https://github.com/CUHK-ARISE/MAS-Resilience.

![探讨恶意代理存在下的多代理系统韧性](../../../paper_images/2408.00989/x1.png)

![探讨恶意代理存在下的多代理系统韧性](../../../paper_images/2408.00989/x2.png)

![探讨恶意代理存在下的多代理系统韧性](../../../paper_images/2408.00989/x3.png)

![探讨恶意代理存在下的多代理系统韧性](../../../paper_images/2408.00989/x4.png)

![探讨恶意代理存在下的多代理系统韧性](../../../paper_images/2408.00989/x5.png)

![探讨恶意代理存在下的多代理系统韧性](../../../paper_images/2408.00989/x6.png)

![探讨恶意代理存在下的多代理系统韧性](../../../paper_images/2408.00989/x7.png)

![探讨恶意代理存在下的多代理系统韧性](../../../paper_images/2408.00989/x8.png)

![探讨恶意代理存在下的多代理系统韧性](../../../paper_images/2408.00989/x9.png)

![探讨恶意代理存在下的多代理系统韧性](../../../paper_images/2408.00989/x10.png)

![探讨恶意代理存在下的多代理系统韧性](../../../paper_images/2408.00989/x11.png)

![探讨恶意代理存在下的多代理系统韧性](../../../paper_images/2408.00989/x12.png)

[Arxiv](https://arxiv.org/abs/2408.00989)